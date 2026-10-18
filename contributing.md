# Contribution Guidelines

Thank you for considering contributing to Awesome Open Source Boilerplates! This document outlines the process and guidelines for contributing.

## Code of Conduct

By participating in this project, you agree to abide by our [Contributor Code of Conduct](code-of-conduct.md). Please read it before contributing.

## How to Contribute

1. Fork the repository
2. Create a new branch for your contribution
3. Make your changes
4. Submit a pull request

## Guidelines for Adding a New Boilerplate

Please ensure your submission meets **all** of these minimum requirements. Pull requests that don't will be closed.

- **Open Source**: The boilerplate must use an [OSI-approved license](https://opensource.org/licenses) (e.g. MIT, Apache-2.0, BSD, GPL). Source-available licenses such as Elastic License 2.0, BSL, SSPL or "free for non-commercial use" are not accepted.
- **SaaS starter**: It must be a runnable starter template for building a SaaS product, with authentication plus billing, multi-tenancy or teams. General-purpose boilerplates, UI component libraries, frameworks, SDKs and single packages are out of scope.
- **Not a teaser**: The core features must be part of the open source version. Free tiers of paid boilerplates are not accepted.
- **Maturity**: The repository must be at least 3 months old.
- **Active Maintenance**: The project must have been updated within the last 12 months.
- **Adoption**: The repository must have at least 50 GitHub stars.
- **Documentation**: Must have clear documentation and setup instructions.
- **Quality**: Should follow best practices and coding standards for its technology.
- **Uniqueness**: The project must not already be on the list.

## Where Entries Go

Each project is listed **exactly once**, in the section of its main framework or language (e.g. Next.js & React, Django). If no section fits, suggest a new one.

## Pull Request Format

When submitting a pull request, please:

- Use the following format for adding entries:
  ```markdown
  - [Project Name](link) - Brief description that explains what makes this boilerplate unique.
  ```
- Link directly to the repository or the project's homepage, without tracking, UTM or affiliate parameters
- Keep the description to one sentence that starts with a capital letter and ends with a period
- Describe the stack and features; skip marketing words such as "free", "best", "MIT-licensed" or "open source" (everything here is open source)
- Add the entry at the end of the relevant section
- Submit one project per pull request
- Disclose in the pull request description if you are the author or maintainer
- Check your spelling and grammar
- Remove any trailing whitespace

## New Categories

To suggest a new category:

1. Ensure it's relevant to boilerplates and starter templates
2. Add it in alphabetical order in the table of contents
3. Create the corresponding section with a suitable description

## Updating Your Pull Request

If the maintainers ask for changes, don't create a new pull request. Instead:

1. Make the required updates to your existing PR
2. Push your changes to the same branch
3. The PR will update automatically

Need help updating your PR? Check out [this guide on amending commits](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md).

## Quality Checks

Before submitting, verify that your contribution:

- [ ] Uses an OSI-approved open source license
- [ ] Is a runnable SaaS starter with authentication plus billing, multi-tenancy or teams
- [ ] Is at least 3 months old and was updated within the last 12 months
- [ ] Has at least 50 GitHub stars
- [ ] Includes a meaningful one-sentence description ending with a period
- [ ] Links without tracking parameters
- [ ] Is placed in exactly one, correct section
- [ ] Follows the established format
- [ ] Does not duplicate existing entries
- [ ] Passes `npx awesome-lint`

## Questions?

If you have questions about contributing, feel free to:

1. Open an issue
2. Start a discussion
3. Contact the maintainers

Thank you for helping make Awesome Open Source Boilerplates better! 🎉
