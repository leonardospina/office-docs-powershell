---
external help file: Microsoft.Exchange.TransportMailflow-Help.xml
online version: https://docs.microsoft.com/powershell/module/exchange/remove-fileplanpropertyreferenceid
applicable: Security & Compliance Center
title: Remove-FilePlanPropertyReferenceId
schema: 2.0.0
---

# Remove-FilePlanPropertyReferenceId

## SYNOPSIS
This cmdlet is available only in the Security & Compliance Center. For more information, see [Security & Compliance Center PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc-powershell).

Use the New-FilePlanPropertyReferenceId cmdlet to remove file plan property reference IDs.

For information about the parameter sets in the Syntax section below, see [Exchange cmdlet syntax](https://docs.microsoft.com/powershell/exchange/exchange-cmdlet-syntax).

## SYNTAX

```
Remove-FilePlanPropertyReferenceId [-Identity] <PolicyIdParameter>
 [-Confirm]
 [-ForceDeletion]
 [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
You need to be assigned permissions in the Security & Compliance Center before you can use this cmdlet. For more information, see [Permissions in Security & Compliance Center](https://go.microsoft.com/fwlink/p/?LinkId=511920).

## EXAMPLES

### Example 1
```powershell
Remove-FilePlanPropertyReferenceId -Identity "Contoso-0001"
```

This example removes the custom file plan property reference ID named Contoso-0001.

## PARAMETERS

### -Identity
The Identity parameter specifies the custom file plan property reference ID that you want to remove. You can use any value that uniquely identifies the reference ID. For example:

- Name
- Distinguished name (DN)
- Id

```yaml
Type: PolicyIdParameter
Parameter Sets: (All)
Aliases:
Applicable: Security & Compliance Center

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -Confirm
The Confirm switch specifies whether to show or hide the confirmation prompt. How this switch affects the cmdlet depends on if the cmdlet requires confirmation before proceeding.

- Destructive cmdlets (for example, Remove-\* cmdlets) have a built-in pause that forces you to acknowledge the command before proceeding. For these cmdlets, you can skip the confirmation prompt by using this exact syntax: -Confirm:$false.
- Most other cmdlets (for example, New-\* and Set-\* cmdlets) don't have a built-in pause. For these cmdlets, specifying the Confirm switch without a value introduces a pause that forces you acknowledge the command before proceeding.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ForceDeletion
The ForceDeletion switch forces the removal of the file plan property reference ID. You don't need to specify a value with this switch.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
The WhatIf switch doesn't work in Security & Compliance Center PowerShell.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/p/?LinkID=113216).

## INPUTS

###  

## OUTPUTS

###  

## NOTES

## RELATED LINKS