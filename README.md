# dependabot-sample

This repo demonstrates that [Dependabot](https://github.com/dependabot) does **not** detect or update vulnerable NuGet dependencies when using .NET 8 projects with [Central Package Management](https://learn.microsoft.com/en-us/nuget/consume-packages/Central-Package-Management) (`Directory.Packages.props`).

Vulnerable packages are declared centrally. Dependabot will not open PRs or alerts for them in this setup.
