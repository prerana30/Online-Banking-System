# BankingSystem

Welcome to the Bank System Project repository! This project aims to develop a compact yet efficient bank system, providing essential functionalities. Built using .NET, ASP.NET Core, and C#, this application delivers a robust platform for banking operations.

### Key Features:

- **User Onboarding:** Seamlessly onboard new users to the banking system.
- **KYC Verification:** Implement KYC (Know Your Customer) verification processes to ensure compliance and security.
- **Teller-Managed Deposits:** Enable tellers to manage deposits efficiently, ensuring smooth transaction processes.
- **ATM Withdrawals:** Facilitate ATM withdrawals for users, enhancing accessibility and convenience.

### Technologies Used:

| For Development | For Deployment  | Tools & Platforms  |
| :--------------:|:---------------:|:------------------:|
| C#              | AWS RDS 			  | Firebase (for test)  |
| .NET Core       | AWS S3 	        | Render (for test)    |
| ASP.NET Core    | AWS ECR   	    | Visual Studio      |
| PostgreSQL      | AWS ECS       	| GitHub, Trello     |             





## Getting Started:

### Prerequisites Installed
- [.NET8](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- [PostgreSQL](https://www.postgresql.org/download/)

### Clone & RUN Source Code
```
git clone git@github.com:ishwors/BankingSystem.git
```

<details>
<summary>
Make sure that you have following packages while running this project
</summary>
  
> AutoMapper" Version="13.0.1"  
> AWSSDK.S3" Version="3.7.307.1"  
> BCrypt.Net-Core" Version="1.6.0"  
> FirebaseStorage.net" Version="1.0.3"  
> Microsoft.AspNetCore.Authentication.JwtBearer" Version="8.0.3"  
> Microsoft.AspNetCore.Authorization" Version="8.0.3"  
> Microsoft.AspNetCore.Identity.EntityFrameworkCore" Version="8.0.3"  
> Microsoft.AspNetCore.JsonPatch" Version="8.0.3"  
> Microsoft.AspNetCore.Mvc.NewtonsoftJson" Version="8.0.3"  
> Microsoft.EntityFrameworkCore" Version="8.0.3"  
> Microsoft.EntityFrameworkCore.Design" Version="8.0.3"
> Microsoft.EntityFrameworkCore.Tools" Version="8.0.3"
> Microsoft.IdentityModel.Tokens" Version="7.4.1"  
> Npgsql.EntityFrameworkCore.PostgreSQL" Version="8.0.2"  
> Swashbuckle.AspNetCore" Version="6.4.0"
</details>

```
cd BankingSystem.API
```
```
dotnet build
```
```
dotnet run
```


OR
### RUN [**docker image**](https://hub.docker.com/repository/docker/ishwors/bankingsystem-repo/)

```
docker pull ishwors/bankingsystem-repo:latest
```
```
docker run -it -p 8080:8080 ishwors/bankingsystem-repo
```



