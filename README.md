# Semantic Filtering with Local Embeddings in Blazor Data Grid

Semantic search for medical records using AI embeddings Blazor Grid. This sample demonstrates how to implement intelligent, context-aware data filtering without relying on external AI services.

## Overview

This Blazor web application showcases how to build a semantic search experience for medical records using **local embeddings** and the **Blazor Grid** component. Rather than simple keyword matching, the search understands the meaning of query text and finds semantically similar medical information.

**Key Use Case**: A healthcare data portal where physicians and staff can search medical records using natural language queries (e.g., "respiratory issues" to find records with symptoms like "shortness of breath").

## Features

- **Semantic Search** — Find medical records based on meaning, not just keywords
- **Local Embeddings** — Run AI inference locally without external API calls
- **Responsive UI** — Built with Blazor components and Grid
- **Interactive Filtering** — Real-time data filtering with visual feedback
- **Bootstrap Styling** — Clean, modern interface with Bootstrap CSS

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/Semantic-Filtering-with-local-embeddings-in-Blazor-Data-Grid.git
cd Semantic-Filtering-with-local-embeddings-in-Blazor-Data-Grid
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

- [Blazor DataGrid Documentation](https://blazor.syncfusion.com/documentation/datagrid/getting-started-with-web-app)
- [Online DataGrid Embedding Demo](https://blazor.syncfusion.com/demos/datagrid/semantic-filtering?theme=fluent2)
- [Blazor Documentation](https://blazor.syncfusion.com/documentation/introduction)

