# Larry Murphy Website

Official website project for Larry Murphy.

The site is maintained in GitHub, deployed through Cloudflare Pages, and developed using a shared Git workflow across two computers.

## Project Status

The repository, deployment pipeline, and two-computer Git workflow are fully configured and operational.

Current focus:

- Establish professional project documentation
- Confirm and standardize the repository structure
- Continue website design and development
- Maintain a clear history of changes and upcoming work

See [PROJECT_STATUS.md](PROJECT_STATUS.md) for the current project snapshot and [TODO.md](TODO.md) for planned work.

## Live Site

- **Production site:** `TODO: Add Cloudflare Pages production URL`
- **GitHub repository:** `TODO: Add GitHub repository URL`

## Technology

The exact site stack should be documented here once the current repository files are reviewed.

Confirmed infrastructure:

- Git and GitHub for source control
- Cloudflare Pages for hosting and deployment
- Local development on two computers
- Markdown documentation stored with the source code

## Repository Structure

The repository should follow a clear, maintainable structure. Update this section after the source files are reviewed.

```text
/
├── README.md
├── PROJECT_STATUS.md
├── CHANGELOG.md
├── TODO.md
└── ... website source files
```

## Documentation

| File | Purpose |
|---|---|
| `README.md` | Main project overview and setup guide |
| `PROJECT_STATUS.md` | Current state, decisions, environment, and active work |
| `CHANGELOG.md` | Chronological record of meaningful changes |
| `TODO.md` | Prioritized development backlog |

## Development Workflow

This repository is used from two computers. The safest standard workflow is:

### Before starting work

```bash
git status
git pull --rebase
```

### After making changes

```bash
git status
git add .
git commit -m "Describe the completed change"
git push
```

### Important workflow rules

1. Pull before beginning work on either computer.
2. Avoid editing the same files on both computers before synchronizing.
3. Commit complete, understandable units of work.
4. Push finished commits so the other computer can retrieve them.
5. Confirm Cloudflare Pages deployment after pushing production changes.
6. Never commit passwords, API keys, tokens, or private configuration values.

## Local Development

Local setup instructions will be added after the repository structure and development commands are confirmed.

Expected documentation items:

- Required software
- Clone command
- Install command, if applicable
- Local development command
- Build command, if applicable
- Deployment behavior
- Environment-variable requirements

## Deployment

Cloudflare Pages is connected to the GitHub repository.

Expected deployment flow:

1. Changes are committed locally.
2. Commits are pushed to GitHub.
3. Cloudflare Pages detects the configured branch update.
4. Cloudflare builds and deploys the site.
5. The deployment is reviewed on the Cloudflare Pages dashboard and production URL.

Document the following once verified:

- Production branch
- Build command
- Build output directory
- Root directory
- Environment variables
- Custom domain configuration

## Contributing

This is currently a privately managed project. All changes should:

- Be tied to a clear task in `TODO.md`
- Use descriptive commit messages
- Update documentation when behavior or project structure changes
- Add an entry to `CHANGELOG.md` for meaningful completed work

## License

`TODO: Choose and document a license, or state that all rights are reserved.`
