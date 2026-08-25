# Contributing

Thanks for your interest in the Enterprise Retail Lakehouse Pipeline project.

## Contribution Guidelines

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Validate the project before committing.
5. Commit changes with a clear message.
6. Push the branch.
7. Open a Pull Request.

## Development Standards

Contributions should follow these practices:

- Preserve the Bronze, Silver, and Gold Medallion Architecture.
- Keep notebook naming and execution order consistent.
- Write readable and maintainable PySpark transformations.
- Maintain existing data quality and validation checks.
- Avoid unnecessary transformations and actions.
- Update documentation when pipeline behavior changes.
- Ensure GitHub Actions CI passes before submitting changes.

## Data Engineering Standards

When modifying the pipeline:

- Maintain schema consistency between pipeline layers.
- Preserve data lineage between Bronze, Silver, and Gold.
- Validate row counts and transformation results.
- Handle null values and duplicates appropriately.
- Keep business transformations clearly documented.
- Follow Delta Lake best practices where applicable.

## Security

Never commit:

- API keys
- Databricks access tokens
- Cloud credentials
- Database passwords
- `.env` files
- Private connection strings
- Production secrets

## Pull Requests

Pull Requests should include:

- A clear description of the change
- Reason for the change
- Pipeline components affected
- Validation performed
- Relevant screenshots if outputs change
