---
external help file: UMN-Google-help.xml
Module Name: UMN-Google
online version: 
schema: 2.0.0
---

# Get-GFilePermissions

## SYNOPSIS
Get Permissions on Google Drive File

## SYNTAX

```
Get-GFilePermissions [-accessToken] <String> [-fileID] <String>
```

## DESCRIPTION
Get Permission ID list on Google File

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
Get-GFilePermissions -fileID 'String of File ID'
```

## PARAMETERS

### -accessToken
OAuth Access Token for authorization.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -fileID
The fileID to query. 
This is returned when a new file is created.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

