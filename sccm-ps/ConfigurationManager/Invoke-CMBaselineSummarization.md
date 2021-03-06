<<<<<<< HEAD
---
title: Invoke-CMBaselineSummarization
titleSuffix: Configuration Manager
description: Updates configuration baseline data.
ms.date: 05/05/2019
ms.prod: configuration-manager
ms.technology: configmgr-other
ms.topic: conceptual
author: aczechowski
ms.author: aaroncz
manager: dougeby
=======
﻿---
external help file: AdminUI.PS.Sum.dll-Help.xml
ms.assetid: EC3D7A25-AFDB-40BE-88E5-3B6506920E8D
online version: https://go.microsoft.com/fwlink/?linkid=834101
schema: 2.0.0
>>>>>>> master
---

# Invoke-CMBaselineSummarization

## SYNOPSIS
Updates configuration baseline data.

## SYNTAX

```
Invoke-CMBaselineSummarization [-DisableWildcardHandling] [-ForceWildcardHandling] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
The **Invoke-CMBaselineSummarization** cmdlet updates data in configuration baselines in Microsoft System Center Configuration Manager with the latest data from the site database.
This action might take several minutes to complete.

You can use the [Set-CMBaselineSummarizationSchedule](Set-CMBaselineSummarizationSchedule.md) cmdlet to configure a schedule by which the data is updated with the latest information from the site database.

## EXAMPLES

> [!NOTE]
> Configuration Manager CmdLets must be run from the Configuration Manager site drive. For more information, see the [getting started documentation](https://docs.microsoft.com/powershell/sccm/overview).


### Example 1: Update configuration baseline data
```
PS XYZ:\>Invoke-CMBaselineSummarization
```

This command updates data in configuration baselines with the latest data from the site database.

## PARAMETERS

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisableWildcardHandling
DisableWildcardHandling treats wildcard characters as literal character values. Cannot be combined with **ForceWildcardHandling**.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ForceWildcardHandling
ForceWildcardHandling processes wildcard characters and may lead to unexpected behavior (not recommended). Cannot be combined with **DisableWildcardHandling**.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Set-CMBaselineSummarizationSchedule](Set-CMBaselineSummarizationSchedule.md)

[Get-CMBaselineSummarizationSchedule](Get-CMBaselineSummarizationSchedule.md)


