# Using This Template

## Quick Start

1. Click "Use this template" button on GitHub
2. Name your new repository
3. Clone locally:
   ```bash
   git clone https://github.com/YOUR-ORG/your-new-repo.git
   cd your-new-repo
   ```
4. Install dependencies:
   ```bash
   npm install
   ```
5. Run initialization:
   ```bash
   npm run init
   ```
6. Delete this file after initialization

## What's Included

### Structure
- 📁 Complete documentation directory structure
- 📝 Document templates for policies, procedures, and architecture
- 🎯 Example documents showing best practices
- 🔧 Configuration files for linting and validation

### Automation
- ✅ GitHub Actions for CI/CD
- 🔍 Markdown linting and formatting
- 📝 Spell checking
- 🔗 Link validation
- 📄 PDF generation capability

### Meta-Documentation
- Setup guide for maintaining the repository
- Docs-as-code strategy and philosophy
- Contributing guidelines
- Issue and PR templates

## Customization

The `npm run init` script will:
- Replace all `{{VARIABLE}}` placeholders with your values
- Personalize the repository for your organization
- Remove example content (optional)
- Set up your documentation structure

### Variables to Replace

| Variable | Description | Example |
|----------|-------------|---------|
| `{{COMPANY_NAME}}` | Your organization name | "Acme Corp" |
| `{{REPO_NAME}}` | Repository name | "acme-docs" |
| `{{GITHUB_ORG}}` | GitHub organization | "acme-corp" |
| `{{DOCS_EMAIL}}` | Documentation team email | "docs@acme.com" |
| `{{SLACK_CHANNEL}}` | Support Slack channel | "#docs-help" |

## Post-Initialization Steps

After running `npm run init`:

1. **Review and Commit**
   ```bash
   git add .
   git commit -m "Initialize documentation repository"
   git push origin main
   ```

2. **Configure GitHub**
   - Set up branch protection rules
   - Configure GitHub Pages (optional)
   - Add team members and permissions

3. **Start Documenting**
   - Remove example documents
   - Add your actual documentation
   - Customize templates as needed

## Directory Structure

```
.github/
├── DOCUMENTATION/      # Meta-docs about the repo
├── workflows/          # GitHub Actions
└── ISSUE_TEMPLATE/     # Issue templates

docs/
├── policies/          # Company policies
├── procedures/        # Operating procedures
├── architecture/      # Technical documentation
├── guides/            # How-to guides
├── references/        # API and references
└── templates/         # Document templates

scripts/               # Build and utility scripts
config/               # Tool configurations
```

## Available Commands

```bash
npm run lint        # Fix markdown issues
npm run spell       # Check spelling
npm run links       # Validate links
npm run validate    # Run all checks
npm run init        # Personalize template
```

## Getting Help

### Documentation
- [Setup Guide](.github/DOCUMENTATION/setup-guide.md)
- [Docs-as-Code Strategy](.github/DOCUMENTATION/docs-as-code-strategy.md)
- [Contributing Guide](CONTRIBUTING.md)

### Support
- Create an issue in this template repository
- Check the [Discussions](https://github.com/YOUR-ORG/docs-as-code-template/discussions) section

## License

This template is provided under the MIT License. You may choose any license for your derivative documentation repository.

---

*Remember to delete this file after successfully initializing your repository!*
