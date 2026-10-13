# How to Add the Syncfusion Blazor Split Button to a Blazor WebAssembly App

## Overview

This sample demonstrates how to add and configure the Syncfusion [Blazor Split Button](https://www.syncfusion.com/blazor-components/blazor-split-button) in a hosted Blazor WebAssembly application. It displays a Paste action with a custom icon and provides a drop-down menu containing related paste options. The sample also demonstrates horizontal menu-item presentation, disabled states, and opening-event handling.

## Key Features

- Displays the Syncfusion Blazor `SfSplitButton` component with Paste as its primary action.
- Adds a custom Paste icon and positions it to the left of the button text using `IconCss` and `IconPosition`.
- Defines related paste actions through `DropDownMenuItems` and presents the menu items horizontally using custom styling.
- Handles the `OnOpen` event to toggle the disabled state of the `Paste as Special` menu item.
- Configures the Split Button as disabled using the `Disabled` property.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to run the project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `AddingSplitButtonComponent.sln`

3. Restore the NuGet packages by rebuilding the solution.
4. Set the startup project to:

   `AddingSplitButtonComponent.Server`

5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Open the application URL displayed by Visual Studio after launch.
8. Verify that the Split Button displays the Paste action with its configured icon.

**Visual Studio Code**

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the server project directory:

```bash
cd Server
```

5. Restore the NuGet packages:

```bash
dotnet restore
```

6. Run the project:

```bash
dotnet run
```

7. Open the local URL displayed in the terminal after the application starts.
8. Verify that the Split Button displays the Paste action with its configured icon.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: [Blazor Split Button getting started documentation](https://blazor.syncfusion.com/documentation/split-button/getting-started)

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.

