# Contributing to Pelagornis

Thank you for your interest in contributing to Pelagornis! We welcome contributions of all kinds. Please read the following guidelines to ensure a smooth collaboration.

## Development

### Adding a Workflow

Before adding a new workflow, please open an issue to discuss it. We likely welcome it, but our release model with tags and Dependabot discourages workflows that update frequently.

### Modifying an Existing Workflow

Pull requests (PRs) are welcome!

Once the code has been pushed to a branch in this repository, you can modify your repository to test your feature branch. Example:

```yml
uses: Pelagornis/github-workflows/.github/workflows/example.yaml@my-feature-branch
```

Testing branches does not require a PR, but feel free to open a draft PR and @mention a reviewer if you'd like feedback. Ideally, PRs should link to at least one example of the modifications running.

## Releasing

To create a new release, use the GitHub UI at: [Pelagornis Releases](https://github.com/Pelagornis/github-workflows/releases/new)

### Versioning

Follow semantic versioning when creating tags:

- Major version bump: If the update requires users to modify their workflows, increment the major version and note the breaking change in the release notes.

- Minor version bump: If you add a new workflow or an opt-in feature, increment the minor version.

- Patch version bump: If you fix a bug or make a transparent change, increment the patch version.

- Leave the release title blank. If you'd like to add additional details, ensure the version number is included. Use the automatically generated changelog as a starting point and supplement it with any necessary details.

## Contribution Guidelines

### Code Style

Follow the [pelagornis styleguide](https://pelagornis.github.io/styleguide/).

Ensure all commits have meaningful messages.

### Submitting a PR

1. Fork the repository and create a feature branch.
2. Open a pull request with a clear description of your changes.
3. Ensure that all tests pass before requesting a review.
4. Add relevant documentation if necessary.

We appreciate your contributions and look forward to collaborating with you!
