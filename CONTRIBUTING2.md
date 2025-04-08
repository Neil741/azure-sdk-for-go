# Contributing to Azure SDK for Go

## Code Style
- Follow Go's standard formatting using `gofmt`.
- Use descriptive variable and function names that align with Azure SDK conventions.
- Avoid using global variables unless absolutely necessary.

## Testing Guidelines
- Write unit tests for all new features and bug fixes.
- Use `require` and `assert` from `testify` for test validations.
- Ensure tests are idempotent and can run in isolation.

## Azure Best Practices
- Always use Azure-specific tools and libraries when interacting with Azure services.
- For image generation, ensure the `azopenai.Client` is properly configured with the correct endpoint and model.
- Use `context.WithTimeout` to manage API call timeouts effectively.

## Commit Messages
- Use clear and concise commit messages.
- Prefix messages with the type of change, e.g., `feat:`, `fix:`, `test:`, `docs:`.

## Pull Requests
- Ensure your branch is up-to-date with the `main` branch before creating a pull request.
- Provide a detailed description of the changes in the pull request.
