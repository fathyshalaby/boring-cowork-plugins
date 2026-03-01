# Content Management & Localization
Manage documentation content lifecycle and localization:

### Content Lifecycle
1. **Plan**: Identify what docs are needed (new feature, API change, user feedback).
2. **Draft**: Write first draft following style guide and templates.
3. **Review**: Technical review (SME) + editorial review (tech writer).
4. **Publish**: Deploy via CI/CD to documentation site.
5. **Maintain**: Monitor analytics, update for product changes, respond to feedback.
6. **Archive/Retire**: Remove or archive docs for deprecated features.

### Localization (l10n)
- **Internationalization (i18n) first**: Separate translatable strings from code. Use i18n frameworks.
- **Translation management**: Use a TMS (Translation Management System) like Crowdin, Transifex, or Phrase.
- **Machine translation + human review**: MT (DeepL, Google Translate) for first pass, human review for quality.
- **Context for translators**: Provide screenshots, character limits, and notes for ambiguous terms.
- **Continuous localization**: Integrate translation into CI/CD — new strings automatically sent for translation.

### Analytics for Docs
| Metric | Indicates |
|--------|-----------|
| Page views | Content popularity |
| Time on page | Engagement (or confusion — check with bounce rate) |
| Search queries | What users are looking for |
| Search with no results | Content gaps |
| Feedback ratings (thumbs up/down) | Content quality |
| Support ticket deflection | Documentation effectiveness |
