---
title: formatters flavor in MegaLinter
description: formatters flavor is an optimized MegaLinter with only linters related to formatters projects
---
# formatters MegaLinter Flavor

![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-formatters/v7.6.0)
![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-formatters)

## Description

Contains only formatters

## Usage

- [GitHub Action](https://megalinter.io/7.6.0/installation/#github-action): **oxsecurity/megalinter/flavors/formatters@v7.6.0**
- Docker image: **oxsecurity/megalinter-formatters:v7.6.0**
- [mega-linter-runner](https://megalinter.io/7.6.0/mega-linter-runner/): `mega-linter-runner --flavor formatters`

## Embedded linters

### Languages

|                                                                               <!-- -->                                                                               | Language                                                                              | Linter                                                                                                                                                                                                                 |                                                                                                 Additional                                                                                                 |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------:|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|    <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/bash.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon -->    | [**BASH**](https://megalinter.io/7.6.0/descriptors/bash/)                             | [**shfmt**](https://megalinter.io/7.6.0/descriptors/bash_shfmt/)<br/>[_BASH_SHFMT_](https://megalinter.io/7.6.0/descriptors/bash_shfmt/)                                                                               |                    [![GitHub stars](https://img.shields.io/github/stars/mvdan/sh?cacheSeconds=3600)](https://github.com/mvdan/sh) ![formatter](https://shields.io/badge/-format-yellow)                    |
|   <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/csharp.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon -->   | [**C#** (CSHARP)](https://megalinter.io/7.6.0/descriptors/csharp/)                    | [**dotnet-format**](https://megalinter.io/7.6.0/descriptors/csharp_dotnet_format/)<br/>[_CSHARP_DOTNET_FORMAT_](https://megalinter.io/7.6.0/descriptors/csharp_dotnet_format/)                                         |               [![GitHub stars](https://img.shields.io/github/stars/dotnet/format?cacheSeconds=3600)](https://github.com/dotnet/format) ![formatter](https://shields.io/badge/-format-yellow)               |
|   <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/csharp.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon -->   | [**C#** (CSHARP)](https://megalinter.io/7.6.0/descriptors/csharp/)                    | [**csharpier**](https://megalinter.io/7.6.0/descriptors/csharp_csharpier/)<br/>[_CSHARP_CSHARPIER_](https://megalinter.io/7.6.0/descriptors/csharp_csharpier/)                                                         |             [![GitHub stars](https://img.shields.io/github/stars/belav/csharpier?cacheSeconds=3600)](https://github.com/belav/csharpier) ![formatter](https://shields.io/badge/-format-yellow)             |
| <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/javascript.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon --> | [**JAVASCRIPT**](https://megalinter.io/7.6.0/descriptors/javascript/)                 | [**prettier**](https://megalinter.io/7.6.0/descriptors/javascript_prettier/)<br/>[_JAVASCRIPT_PRETTIER_](https://megalinter.io/7.6.0/descriptors/javascript_prettier/)                                                 |           [![GitHub stars](https://img.shields.io/github/stars/prettier/prettier?cacheSeconds=3600)](https://github.com/prettier/prettier) ![formatter](https://shields.io/badge/-format-yellow)           |
| <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/powershell.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon --> | [**POWERSHELL**](https://megalinter.io/7.6.0/descriptors/powershell/)                 | [**powershell_formatter**](https://megalinter.io/7.6.0/descriptors/powershell_powershell_formatter/)<br/>[_POWERSHELL_POWERSHELL_FORMATTER_](https://megalinter.io/7.6.0/descriptors/powershell_powershell_formatter/) | [![GitHub stars](https://img.shields.io/github/stars/PowerShell/PSScriptAnalyzer?cacheSeconds=3600)](https://github.com/PowerShell/PSScriptAnalyzer) ![formatter](https://shields.io/badge/-format-yellow) |
|   <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/python.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon -->   | [**PYTHON**](https://megalinter.io/7.6.0/descriptors/python/)                         | [**black**](https://megalinter.io/7.6.0/descriptors/python_black/)<br/>[_PYTHON_BLACK_](https://megalinter.io/7.6.0/descriptors/python_black/)                                                                         |                   [![GitHub stars](https://img.shields.io/github/stars/psf/black?cacheSeconds=3600)](https://github.com/psf/black) ![formatter](https://shields.io/badge/-format-yellow)                   |
|   <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/python.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon -->   | [**PYTHON**](https://megalinter.io/7.6.0/descriptors/python/)                         | [**isort**](https://megalinter.io/7.6.0/descriptors/python_isort/)<br/>[_PYTHON_ISORT_](https://megalinter.io/7.6.0/descriptors/python_isort/)                                                                         |                 [![GitHub stars](https://img.shields.io/github/stars/PyCQA/isort?cacheSeconds=3600)](https://github.com/PyCQA/isort) ![formatter](https://shields.io/badge/-format-yellow)                 |
| <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/typescript.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon --> | [**TYPESCRIPT**](https://megalinter.io/7.6.0/descriptors/typescript/)                 | [**prettier**](https://megalinter.io/7.6.0/descriptors/typescript_prettier/)<br/>[_TYPESCRIPT_PRETTIER_](https://megalinter.io/7.6.0/descriptors/typescript_prettier/)                                                 |           [![GitHub stars](https://img.shields.io/github/stars/prettier/prettier?cacheSeconds=3600)](https://github.com/prettier/prettier) ![formatter](https://shields.io/badge/-format-yellow)           |
|  <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/vbdotnet.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon -->  | [**Visual Basic .NET** (VBDOTNET)](https://megalinter.io/7.6.0/descriptors/vbdotnet/) | [**dotnet-format**](https://megalinter.io/7.6.0/descriptors/vbdotnet_dotnet_format/)<br/>[_VBDOTNET_DOTNET_FORMAT_](https://megalinter.io/7.6.0/descriptors/vbdotnet_dotnet_format/)                                   |               [![GitHub stars](https://img.shields.io/github/stars/dotnet/format?cacheSeconds=3600)](https://github.com/dotnet/format) ![formatter](https://shields.io/badge/-format-yellow)               |

### Formats

|                                                                              <!-- -->                                                                              | Format                                                            | Linter                                                                                                                                                                                                                           |                                                                                                       Additional                                                                                                       |
|:------------------------------------------------------------------------------------------------------------------------------------------------------------------:|-------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|   <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/json.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon -->   | [**JSON**](https://megalinter.io/7.6.0/descriptors/json/)         | [**prettier**](https://megalinter.io/7.6.0/descriptors/json_prettier/)<br/>[_JSON_PRETTIER_](https://megalinter.io/7.6.0/descriptors/json_prettier/)                                                                             |                 [![GitHub stars](https://img.shields.io/github/stars/prettier/prettier?cacheSeconds=3600)](https://github.com/prettier/prettier) ![formatter](https://shields.io/badge/-format-yellow)                 |
| <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/markdown.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon --> | [**MARKDOWN**](https://megalinter.io/7.6.0/descriptors/markdown/) | [**markdownlint**](https://megalinter.io/7.6.0/descriptors/markdown_markdownlint/)<br/>[_MARKDOWN_MARKDOWNLINT_](https://megalinter.io/7.6.0/descriptors/markdown_markdownlint/)                                                 |           [![GitHub stars](https://img.shields.io/github/stars/DavidAnson/markdownlint?cacheSeconds=3600)](https://github.com/DavidAnson/markdownlint) ![formatter](https://shields.io/badge/-format-yellow)           |
| <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/markdown.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon --> | [**MARKDOWN**](https://megalinter.io/7.6.0/descriptors/markdown/) | [**markdown-table-formatter**](https://megalinter.io/7.6.0/descriptors/markdown_markdown_table_formatter/)<br/>[_MARKDOWN_MARKDOWN_TABLE_FORMATTER_](https://megalinter.io/7.6.0/descriptors/markdown_markdown_table_formatter/) | [![GitHub stars](https://img.shields.io/github/stars/nvuillam/markdown-table-formatter?cacheSeconds=3600)](https://github.com/nvuillam/markdown-table-formatter) ![formatter](https://shields.io/badge/-format-yellow) |
|   <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/rst.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon -->    | [**RST**](https://megalinter.io/7.6.0/descriptors/rst/)           | [**rstfmt**](https://megalinter.io/7.6.0/descriptors/rst_rstfmt/)<br/>[_RST_RSTFMT_](https://megalinter.io/7.6.0/descriptors/rst_rstfmt/)                                                                                        |                                                                                 ![formatter](https://shields.io/badge/-format-yellow)                                                                                  |
|   <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/yaml.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon -->   | [**YAML**](https://megalinter.io/7.6.0/descriptors/yaml/)         | [**prettier**](https://megalinter.io/7.6.0/descriptors/yaml_prettier/)<br/>[_YAML_PRETTIER_](https://megalinter.io/7.6.0/descriptors/yaml_prettier/)                                                                             |                 [![GitHub stars](https://img.shields.io/github/stars/prettier/prettier?cacheSeconds=3600)](https://github.com/prettier/prettier) ![formatter](https://shields.io/badge/-format-yellow)                 |

### Tooling formats

|                                                                              <!-- -->                                                                               | Tooling format                                                      | Linter                                                                                                                                                                                  |                                                                                         Additional                                                                                         |
|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------:|---------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/snakemake.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon --> | [**SNAKEMAKE**](https://megalinter.io/7.6.0/descriptors/snakemake/) | [**snakefmt**](https://megalinter.io/7.6.0/descriptors/snakemake_snakefmt/)<br/>[_SNAKEMAKE_SNAKEFMT_](https://megalinter.io/7.6.0/descriptors/snakemake_snakefmt/)                     |  [![GitHub stars](https://img.shields.io/github/stars/snakemake/snakefmt?cacheSeconds=3600)](https://github.com/snakemake/snakefmt) ![formatter](https://shields.io/badge/-format-yellow)  |
| <img src="https://github.com/oxsecurity/megalinter/raw/main/docs/assets/icons/terraform.ico" alt="" height="32px" class="megalinter-icon"></a> <!-- linter-icon --> | [**TERRAFORM**](https://megalinter.io/7.6.0/descriptors/terraform/) | [**terraform-fmt**](https://megalinter.io/7.6.0/descriptors/terraform_terraform_fmt/)<br/>[_TERRAFORM_TERRAFORM_FMT_](https://megalinter.io/7.6.0/descriptors/terraform_terraform_fmt/) | [![GitHub stars](https://img.shields.io/github/stars/hashicorp/terraform?cacheSeconds=3600)](https://github.com/hashicorp/terraform) ![formatter](https://shields.io/badge/-format-yellow) |

### Other

| <!-- --> | Code quality checker | Linter | Additional  |
| :---: | ----------------- | -------------- | :-----:  |
