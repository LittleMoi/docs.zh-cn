---
title: dotnet nuget list source 命令
description: dotnet nuget list source 命令列出 NuGet 配置文件中的所有现有源。
ms.date: 03/20/2020
ms.openlocfilehash: 8b14413949bd60ddeed977d19eec9bb99982da70
ms.sourcegitcommit: 927b7ea6b2ea5a440c8f23e3e66503152eb85591
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/16/2020
ms.locfileid: "81463542"
---
# <a name="dotnet-nuget-list-source"></a>dotnet nuget list source

**本文适用于：** ✔️ .NET Core 3.1.200 SDK 及更高版本

## <a name="name"></a>“属性”

`dotnet nuget list source` - 列出所有配置的 NuGet 源。

## <a name="synopsis"></a>摘要

```dotnetcli
dotnet nuget list source [--format [Detailed|Short]] [--configfile <FILE>]

dotnet nuget list source -h|--help
```

## <a name="description"></a>描述

`dotnet nuget list source` 命令列出 NuGet 配置文件中的所有现有源。

## <a name="options"></a>选项

- **`--configfile <FILE>`**

  NuGet 配置文件。 如果指定，则只使用此文件中的设置。 如果不指定，将使用当前目录中的配置文件的层次结构。 有关详细信息，请参阅[常见的 NuGet 配置](https://docs.microsoft.com/nuget/consume-packages/configuring-nuget-behavior)。

- **`--format [Detailed|Short]`**

  list 命令输出的格式为：`Detailed`（默认值）和 `Short`。

## <a name="examples"></a>示例

- 列出当前目录中的已配置源：

  ```dotnetcli
  dotnet nuget list source
  ```

## <a name="see-also"></a>请参阅

- [NuGet.config 文件中的包源部分](/nuget/reference/nuget-config-file#package-source-sections)

- [sources 命令 (nuget.exe)](/nuget/reference/cli-reference/cli-ref-sources)
