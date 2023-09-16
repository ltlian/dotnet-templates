# Basic .NET7 project template

A custom dotnet SDK template for initializing a basic .NET7 project structure with some common configurations.

See <https://learn.microsoft.com/en-us/dotnet/core/tools/custom-templates>

## Usage

### Installing the template

    dotnet new install <path-to-template>

### Initializing a project using the template

    dotnet new basic

For available options, see <https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-new>

### Uninstalling the template

    dotnet new uninstall <path-to-template>

For Windows systems, you may have to wrap the file path in quotes.

## Template features

- `.gitignore` file based on one found in the official [dotnet/sdk](https://github.com/dotnet/sdk/tree/main/template_feed/Microsoft.DotNet.Common.ItemTemplates/content/Gitignore) repository
- `.editorconfig` file based on one found in the official [dotnet/sdk](https://github.com/dotnet/sdk/tree/main/template_feed/Microsoft.DotNet.Common.ItemTemplates/content/EditorConfig) repository
- `.gitattribute` file based on one found in the official [dotnet/core](https://github.com/dotnet/core) repository
