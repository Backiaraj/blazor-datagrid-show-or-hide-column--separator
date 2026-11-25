# Blazor DataGrid - Show or Hide Column Separator

A Blazor application demonstrating how to hide or show the column separator (freeze line) in the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component when the `AllowFreezeLineMoving` feature is enabled.

## Overview

When the `AllowFreezeLineMoving` property is enabled in the Blazor DataGrid, a draggable frozen line separator is rendered on either the left or right side of the grid to allow users to freeze columns. This sample demonstrates how to hide these separator lines using CSS properties and class names.

By using simple CSS styling, you can easily control the visibility of the freeze line separators to match your application's UI requirements.

## Features

- **Column Freezing** - Interactive column freezing with draggable freeze line separators
- **CSS Customization** - Hide or show freeze line separators using CSS properties
- **Column Sorting** - Built-in sorting capability on all columns
- **Multiple Data Types** - Support for numeric, date, and string data types
- **Responsive Layout** - Dynamically responsive grid layout

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`ShowHideColumnSeparator.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd blazor-datagrid-show-or-hide-column--separator
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/frozen-column

**Online example**: https://blazor.syncfusion.com/demos/datagrid/show-or-hide-column?theme=fluent2