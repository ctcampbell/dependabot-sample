# dependabot-sample

This repo demonstrates that [Dependabot](https://github.com/dependabot) does now detect vulnerable NuGet dependencies when using .NET 8 projects with [Central Package Management](https://learn.microsoft.com/en-us/nuget/consume-packages/Central-Package-Management) (`Directory.Packages.props`). To enable use Automatic Dependency Submission in repository Advanced Security settings.

Vulnerable packages are declared centrally. Dependabot will open PRs and alerts for them in this setup.
