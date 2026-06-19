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
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-show-or-hide-column--separator.git
cd blazor-datagrid-show-or-hide-column--separator
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/column-chooser

**Online example**: https://blazor.syncfusion.com/demos/datagrid/show-or-hide-column?theme=fluent2