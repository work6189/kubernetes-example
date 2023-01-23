# base64 encoding IN window PowerShell
> [Convert]::ToBase64String([Text.Encoding]::UTF8.GetBytes('username'))  

# base64 decoding IN window PowerShell
> [Text.Encoding]::Utf8.GetString([Convert]::FromBase64String('dXNlcm5hbWU='))