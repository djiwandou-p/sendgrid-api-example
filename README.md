## SendGrid API Example 

simple example using C# 

result: 

<img width="822" height="142" alt="image" src="https://github.com/user-attachments/assets/8335e9c3-d33a-402b-883a-7edd3229c78e" />


### How to run this project

`dotnet add package SendGrid`

set env variable in Windows -> System or in PowerShell Admin
```
[System.Environment]::GetEnvironmentVariable("SENDGRID_API_KEY", "Machine")
[System.Environment]::GetEnvironmentVariable("SENDGRID_API_KEY", "User")
```

check env variable using PowerShell
`$env:SENDGRID_API_KEY`


`dotnet run`
