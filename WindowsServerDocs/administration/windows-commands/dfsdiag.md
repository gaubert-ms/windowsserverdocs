---
title: dfsdiag
description: Reference topic for dfsdiag, which provides diagnostic information for DFS Namespaces.
ms.prod: windows-server
ms.technology: manage-windows-commands
ms.topic: article
ms.assetid: c0891e67-0187-4f18-923d-5623e6127f90
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# dfsdiag

Provides diagnostic information for DFS Namespaces.

## Syntax

```
dfsdiag [ /TestDCs [/Domain:<Domain name>]| /TestSites </Machine:<server name>| /DFSPath:<namespace root or DFS folder> [/Recurse]> [/Full] | /TestDFSConfig /DFSRoot:<namespace> | /TestDFSIntegrity /DFSRoot:<DFS root path> [/Recurse] [/Full] | /TestReferral /DFSPath:<DFS path for getting referrals> [/Full] | /?] 

```

#### Parameters

|Parameter|Description|
|---------|-----------|
|[Dfsdiag TestDCs](dfsdiag-testdcs.md)|Checks domain controller configuration.|
|[Dfsdiag TestSites](dfsdiag-testsites.md)|Checks site associations.|
|[Dfsdiag TestDFSConfig](dfsdiag-testdfsconfig.md)|Checks DFS Namespace configuration.|
|[Dfsdiag TestDFSIntegrity](dfsdiag-testdfsintegrity.md)|Checks DFS Namespace integrity.|
|[Dfsdiag TestReferral](dfsdiag-testreferral.md)|Checks referral responses.|
|/?|Displays help at the command prompt.|

## Additional References

-   - [Command-Line Syntax Key](command-line-syntax-key.md)