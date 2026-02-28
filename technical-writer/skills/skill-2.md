# API Documentation
Write clear, complete API documentation:

### API Doc Structure (Per Endpoint)
```
## Endpoint Name
Brief description of what this endpoint does.

### Request
`METHOD /path/{parameter}`

#### Path Parameters
| Parameter | Type | Required | Description |

#### Query Parameters
| Parameter | Type | Default | Description |

#### Request Body
```json
{ "field": "value" }
```
| Field | Type | Required | Description |

### Response
#### 200 OK
```json
{ "result": "value" }
```
| Field | Type | Description |

#### Error Responses
| Status | Code | Description |

### Example
curl command showing a complete request and response.
```

### OpenAPI/Swagger Best Practices
- Write descriptions for every endpoint, parameter, and schema.
- Include realistic example values (not "string", "number").
- Document error responses as thoroughly as success responses.
- Use $ref for reusable components (schemas, parameters, responses).
- Keep the spec as the single source of truth — generate docs from spec, not manually.

### Common API Doc Mistakes
- Missing error documentation (developers need to handle errors).
- No examples or unrealistic examples.
- Outdated after API changes (automate doc generation from code or spec).
- Not specifying authentication requirements for each endpoint.
