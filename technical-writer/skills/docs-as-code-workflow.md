# Docs-as-Code Workflow
Implement a docs-as-code workflow for scalable documentation:

### Docs-as-Code Principles
- Documentation lives in the same repository as code (or a dedicated docs repo).
- Written in lightweight markup (Markdown, reStructuredText, AsciiDoc).
- Reviewed via pull requests — same workflow as code changes.
- Built and deployed via CI/CD (GitHub Actions, GitLab CI).
- Versioned alongside the product.

### Static Site Generators
| Tool | Language | Best For |
|------|---------|----------|
| Docusaurus | React | Product docs, versioning |
| MkDocs (Material) | Python | Clean, searchable docs |
| Sphinx | Python/RST | API docs, cross-references |
| Hugo | Go | Fast builds, large sites |
| GitBook | SaaS | Quick setup, collaboration |
| Astro Starlight | JS | Modern, fast, customizable |

### Automated Checks
- **Linting**: markdownlint, vale (style guide enforcement).
- **Link checking**: Broken link detection in CI pipeline.
- **Code sample testing**: Extract and test code samples automatically.
- **Spell checking**: cspell or similar in CI.
- **Screenshots**: Automated screenshot generation for UI docs (Playwright, Puppeteer).
