---
external help file: UMN-Google-help.xml
Module Name: UMN-Google
online version: 
schema: 2.0.0
---

# Remove-GFilePermissions

## SYNOPSIS
Remove Permissions on Google Drive File

## SYNTAX

```
Remove-GFilePermissions [-accessToken] <String> [-fileID] <String> [-permissionsID] <String>
```

## DESCRIPTION
Remove Permission ID list on Google File

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
Remove-GFilePermissions -fileID 'String of File ID' -accessToken $accessToken -permissionID 'ID of the permission'
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

### -permissionsID
The permission ID to be removed.
See Get-GFilePermissions

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES
A successfull removal returns no body data.

## RELATED LINKS

