﻿---
author: jpjofre
description: 
external help file: System.Management.Automation.dll-Help.xml
keywords: powershell, cmdlet
manager: carolz
ms.date: 2016-09-20
ms.prod: powershell
ms.technology: powershell
ms.topic: reference
online version: http://go.microsoft.com/fwlink/?LinkID=113362
schema: 2.0.0
title: Out-Default
---

# Out-Default
## SYNOPSIS
Sends the output to the default formatter and to the default output cmdlet.
## SYNTAX

```
Out-Default [-InputObject <PSObject>] [<CommonParameters>]
```

## DESCRIPTION
The **Out-Default** cmdlet sends output to the default formatter and the default output cmdlet.
This cmdlet has no effect on the formatting or output of Windows PowerShell commands.
It is a placeholder that lets you write your own **Out-Default** function or cmdlet.
## EXAMPLES

### 1:
```

```

## PARAMETERS

### -InputObject
Accepts input to the cmdlet.

```yaml
Type: PSObject
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).
## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Format-Custom](../Microsoft.PowerShell.Utility/Format-Custom.md)

[Format-List](../Microsoft.PowerShell.Utility/Format-List.md)

[Format-Table](../Microsoft.PowerShell.Utility/Format-Table.md)

[Format-Wide](../Microsoft.PowerShell.Utility/Format-Wide.md)

[about_Format.ps1.xml](About/about_Format.ps1xml.md)

