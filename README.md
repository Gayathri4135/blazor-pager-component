# Blazor Pager Component - Data Binding

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Pager](https://www.syncfusion.com/blazor-components/blazor-pager) component with a data-bound collection in a Blazor application. The implementation is designed to display records in pages rather than rendering the entire dataset at once, improving usability and scalability when working with larger collections.

The sample showcases a common paging workflow in which user interaction with pager navigation controls determines the subset of records presented to the user. It serves as a foundation for implementing efficient data browsing and on-demand loading scenarios in Blazor applications.

## Key Features

- Demonstrates Syncfusion Blazor Pager integration within a Blazor application.
- Shows how paging can be applied to a bound data source.
- Supports navigation between record sets through Pager UI controls.
- Illustrates an on-demand data presentation approach.
- Uses sample data stored within the project's `Data` folder.
- Includes a dedicated sample page hosted in `Pages/Index.razor`.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open `CreatingPagerComponent.sln`.
3. Restore all NuGet packages.
4. Build the solution.
5. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

4. Open the URL displayed in the terminal after the application starts.

## Project Structure

- `CreatingPagerComponent.sln` — Visual Studio solution file containing the sample projects.

- `Pages/Index.razor` — Main sample page demonstrating Pager-related functionality.


## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/pager/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.