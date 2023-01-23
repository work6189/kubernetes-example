# base64 encoding IN window PowerShell
> [Convert]::ToBase64String([Text.Encoding]::UTF8.GetBytes('username'))  

# base64 encoding IN Linux
> echo -n "username" | base64

# base64 decoding IN window PowerShell
> [Text.Encoding]::Utf8.GetString([Convert]::FromBase64String('dXNlcm5hbWU='))

# base64 decoding IN Linux
> echo -n "dXNlcm5hbWU=" | base64 --decode

# example kubernetes reference
https://www.youtube.com/watch?v=s_o8dwzRlu4&t=874s