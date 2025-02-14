---
content_git_url: https://github.com/Microsoft/Partner-Center-PowerShell/blob/master/docs/help/Get-PartnerIndirectReseller.md
external help file: Microsoft.Store.PartnerCenter.PowerShell.dll-Help.xml
Module Name: PartnerCenter
online version: https://docs.microsoft.com/powershell/module/partnercenter/Get-PartnerIndirectReseller
original_content_git_url: https://github.com/Microsoft/Partner-Center-PowerShell/blob/master/docs/help/Get-PartnerIndirectReseller.md
schema: 2.0.0
---

# Get-PartnerIndirectReseller

## SYNOPSIS
Gets a list of indirect resellers.

## SYNTAX

```
Get-PartnerIndirectReseller [-CustomerId <String>] [<CommonParameters>]
```

## DESCRIPTION
Gets a list of indirect resellers.

## EXAMPLES

### Example 1
```powershell
PS C:\> Get-PartnerIndirectReseller
```

Gets a list of indirect resellers.

## PARAMETERS

### -CustomerId
The identifier for the customer.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### Microsoft.Store.PartnerCenter.PowerShell.Models.Relationships.PSPartnerRelationship

## NOTES

## RELATED LINKS
