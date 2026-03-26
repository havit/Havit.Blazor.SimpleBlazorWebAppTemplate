# Havit.Blazor Simple Blazor Web App Template



## What's Included in This Template

* Based on the standard *Blazor Web App* template from the ASP.NET Core Blazor team with the following settings:
  * Framework: .NET 10.0
  * Authentication type: None
  * Configure for HTTPS: Enabled
  * Interactive render mode: Auto (Server and WebAssembly)
  * Interactivity location: Global
  * Include sample pages: Enabled
  * Do not use top-level statements: Disabled
  * Enlist in .NET Aspire orchestration: Disabled
* [Havit.Blazor Bootstrap](https://havit.blazor.eu) package is [installed](https://havit.blazor.eu/getting-started#installation) (with unnecessary sample files removed)
* `MainLayout` and `NavMenu` updated to use [`HxSidebar`](https://havit.blazor.eu/components/HxSidebar) for navigation
* [`HxMessenger`](https://havit.blazor.eu/components/HxMessenger) and [`HxMessageBox`](https://havit.blazor.eu/components/HxMessageBox) support added
* Sample pages (`Counter` and `Weather`) modified to use [Havit.Blazor](https://havit.blazor.eu) components



## Setting Up Your Solution

1. [Create a new GitHub repository using this template](https://github.com/new?template_name=Havit.Blazor.SimpleBlazorWebAppTemplate&template_owner=havit) (click the link or select *Use this template* from the upper-right corner of the repository homepage).
2. Clone the new repository to your local machine.
   Alternatively, you can download the template to your computer if you do not want to use GitHub to maintain your source code.
3. Run the `SetSolutionName.ps1` script (PowerShell) to rename the solution and projects.
   (You might need to adjust PowerShell execution policy to be able to run this script.)
4. Remove unnecessary files:
   * `SetSolutionName.ps1`
   * `LICENSE.txt` - This license applies to the template, not your project.
   * `README.md` - This file (the instructions) won't be needed.
   * (`Counter.razor` and `Weather.razor` - Sample files used for demonstration.)

You're all set!
