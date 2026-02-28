# intern-tech-writer-assessment

# Structure

`intern-tech-writer-assessment/`<br>
`│`<br>
`├── openapi.yaml`
`├── README.md`
`├── responses/`
`│   ├── login-success.json`
`│   ├── login-error.json`
`│   └── users-response.json`
`│`
`└── docs/`
`    └── user-api.md   (empty file)`

# 🟢 Task Instructions Given to Intern

---

## 📌 PART 1 — Improve OpenAPI File

You are required to improve the provided `openapi.yaml` file.

### ✅ You Must:

- **Improve endpoint summaries**
  - Make summaries clear, descriptive, and professional.
  - Avoid vague terms such as `login`, `get users`, or `ok`.

- **Add proper descriptions**
  - Add meaningful descriptions to:
    - The overall API (`info` section)
    - Each endpoint
    - Request bodies
    - Responses

- **Enhance the API Schema**
  Add the following where missing:

  - **Required fields**
    - Explicitly define required properties in request bodies.

  - **Example values**
    - Provide realistic example values for request fields.
    - Add example responses for success and error cases.

  - **Response schema**
    - Define structured response schemas for successful responses.
    - Include proper `type`, `properties`, and nested structure where applicable.

  - **Error response schema**
    - Define a consistent error response format.
    - Include fields such as:
      - `success`
      - `message`
      - `error_code`
      - `timestamp` (if applicable)

- **Add tags**
  - Group endpoints logically (e.g., `Authentication`, `Users`).
  - Ensure tags are meaningful and consistently applied.

- **Improve naming clarity**
  - Replace unclear terms like `ok`, `invalid`, etc.
  - Use consistent naming conventions for fields and descriptions.

- **Maintain valid YAML syntax**
  - Ensure proper indentation.
  - Avoid syntax errors.
  - Keep the file compliant with OpenAPI 3.0 standards.

---

## 📌 PART 2 — Write Proper Developer Documentation

Inside `docs/user-api.md`, you must create structured developer documentation.

### The document must include:

- **API Overview**
- **Authentication Explanation**

### For Each Endpoint, Include:

- **Method**
- **URL**
- **Description**
- **Request Body Table**
- **Sample Request**
- **Sample Response**
- **Error Codes Table**
- **cURL Example**

### Documentation Requirements:

- Must be written in clean, professional **Markdown**
- Proper headings and subheadings
- Correct table formatting
- Proper code blocks for JSON and cURL examples
- Clear and developer-friendly language

---

## 📌 PART 3 — Repository Discipline

You must demonstrate proper Git workflow and repository management.

### Requirements:

- Create meaningful commit messages, such as:
  - `improve openapi structure`
  - `add response schema`
  - `write user api documentation`

- Push your changes to GitHub.
- Share the repository link for review.

---

### 📌 Expected Outcome

Your submission should demonstrate:

- Technical understanding of OpenAPI and APIs  
- Ability to structure professional developer documentation  
- Clean Markdown formatting  
- Proper Git discipline and version control practices  
