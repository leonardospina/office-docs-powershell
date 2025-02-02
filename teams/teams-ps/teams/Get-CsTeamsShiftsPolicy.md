---
external help file: Microsoft.TeamsCmdlets.PowerShell.Custom.dll-Help.xml
Module Name: MicrosoftTeams
online version: https://docs.microsoft.com/powershell/module/teams/get-teamsshiftspolicy
schema: 2.0.0
---

# Get-CsTeamsShiftsPolicy

## SYNOPSIS

This cmdlet allows you to get properties of a TeamsShiftPolicy instance, including user's shift based presence and Teams off shift warning message-specific settings.

## SYNTAX

### Identity (Default)
```
Get-CsTeamsShiftsPolicy [[-Identity] <XdsIdentity>] [<CommonParameters>]
```

## DESCRIPTION
This cmdlet allows you to get properties of a TeamsShiftPolicy instance. Use this to get the policy name, user's shift based presence (EnableShiftPresence) and Teams off shift warning message-specific settings (ShiftNoticeMessageType, ShiftNoticeMessageCustom, ShiftNoticeFrequency, AccessGracePeriodMinutes).


## EXAMPLES

### Example 1
```powershell
PS C:\> Get-CsTeamsShiftsPolicy
```

Gets the properties of all instances of the TeamsShiftPolicy.

### Example 2
```powershell
PS C:\> Get-CsTeamsShiftsPolicy -Identity OffShiftAccessMessage1Always
```

Gets the properties of the OffShiftAccessMessage1Always instance of the TeamsShiftPolicy.

## PARAMETERS

### -Identity
Policy instance name. Optional.

```yaml
Type: XdsIdentity
Parameter Sets: Identity
Aliases:
Applicable: Microsoft Teams
Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).


## INPUTS

### None

## OUTPUTS

### System.Object
## NOTES

## RELATED LINKS

[Set-CsTeamsShiftsPolicy](Set-CsTeamsShiftsPolicy.md)

[New-CsTeamsShiftsPolicy](New-CsTeamsShiftsPolicy.md)

[Remove-CsTeamsShiftsPolicy](Remove-CsTeamsShiftsPolicy.md)

[Grant-CsTeamsShiftsPolicy](Grant-CsTeamsShiftsPolicy.md)
