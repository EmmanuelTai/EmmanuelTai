# Hi, I'm Emmanuel Tai-Ojuolape 👋

**Backend Developer** · .NET · ASP.NET Core · SQL Server · Lagos, Nigeria

I build secure, reliable backend systems in C# and ASP.NET Core. Right now I'm a Backend Developer at **[Xown Solutions](https://xownsolutions.com)**.

**Open to backend developer roles, remote or international.**

---

### What I've done

-  **Cut flight search time from 1–3+ minutes to about 8 seconds** in production on Patelo (85%+ faster)
-  Integrated multiple **third-party flight and hotel supplier APIs** into one booking flow
-  Built and debugged **payment flows** (GlobalPay at work, Paystack in my own projects), including reconciliation and webhook verification
-  Built **authentication and authorization** with JWT, Google OAuth and role-based access (SuperAdmin / Admin / Customer)
-  Refactored an inherited codebase and fixed **EF Core migration corruption**, so deployments are reliable again

---

### Tech stack

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_10-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

| Area | What I use |
|---|---|
| **Languages & frameworks** | C#, SQL, ASP.NET Core, Entity Framework Core |
| **Architecture** | Clean Architecture, Repository + Unit of Work, Dependency Injection, Middleware |
| **Security** | JWT, Google OAuth, role-based authorization, BCrypt, HMAC webhook verification |
| **Integrations** | Supplier APIs, GlobalPay, Paystack, SMTP email (MailKit) |
| **Data & performance** | SQL query optimization, indexing, transactions and concurrency, caching, async/await |
| **Tools** | Visual Studio, Git, GitHub, Postman, SQL Server |

---

### Featured project

####  [E-Commerce REST API](https://github.com/EmmanuelTai/ecommerce-api)
A backend for an online store: customers browse, add to cart, check out and pay with **Paystack**, and admins manage products, orders and customers.
**Tech:** .NET 10 · ASP.NET Core · EF Core · SQL Server · Paystack · MailKit

- **No overselling:** two buyers can't both get the last item. Stock is reduced with a conditional SQL update inside one transaction, and I tested it with simultaneous checkouts.
- **Secure payments:** Paystack webhooks are checked with an HMAC-SHA512 signature and confirmed with Paystack before an order is marked paid. Retries never double-process a payment.
- **Clean structure:** layered architecture with Repository + Unit of Work, JWT with Customer/Admin roles, one consistent error format, caching and transactional emails.

 Every design decision and its trade-off is written up in [`docs/DESIGN.md`](https://github.com/EmmanuelTai/ecommerce-api/blob/main/docs/DESIGN.md).

---

### What I'm learning next

- Automated testing for APIs (xUnit, integration tests)
- Docker and CI/CD with GitHub Actions
- Deploying .NET APIs to Azure

---

### Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emmanuel-tai-ojuolape-84a613198)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:emmanueltai000@gmail.com)
