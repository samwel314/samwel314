# Samuel Marzouk 👋

[![dotnet](https://img.shields.io/badge/.NET-10-512BD4?style=flat-square&logo=.net&logoColor=white)](https://dotnet.microsoft.com/)
[![github](https://img.shields.io/badge/GitHub-samwel314-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/samwel314)
[![linkedin](https://img.shields.io/badge/LinkedIn-Samwel_Marzouk-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samuel-marzouk-0a815821a/)
[![email](https://img.shields.io/badge/Email-samwelmarzouk3%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:samwelmarzouk3@gmail.com)

Junior Backend .NET Developer — ASP.NET Core | EF Core | Clean Architecture

---

Contents
- [About Me](#about-me)
- [Tech & Tools](#tech--tools)
- [Featured Projects](#featured-projects)
- [Example: Minimal API usage](#example-minimal-api-usage)
- [Contact](#contact)
- [Contributing & License](#contributing--license)

---

## About Me
I build secure, scalable, and maintainable backend APIs using Clean Architecture and modern .NET.  
I focus on clear separation of concerns, testability, and fine-grained access control (claims and resource-based authorization). I like sharing what I learn through short technical posts and examples.

Value highlights:
- Building APIs with security-first mindset (IDOR prevention, claims/resource auth)
- Designing maintainable systems using Clean Architecture
- Practical experience with EF Core, Dapper, and SQL Server
- Familiar with real-time features using SignalR

---

## Tech & Tools
- Language / Platform: C#, ASP.NET Core (.NET 10)
- API styles: Minimal APIs, RESTful APIs
- Data access: EF Core, Dapper, SQL Server
- Auth & Security: ASP.NET Identity, JWT, Claims-based & resource-based authorization
- Architecture: Clean Architecture, Separation of Concerns, Testable code
- Real-time: SignalR
- Other: Stripe integration (payments), Bootstrap (front-end for admin dashboards)

---

## Featured Projects

### 1) Invoice Management System
A multi-branch invoice platform for stores and clients.
- Purpose: Clients submit invoices; employees manage invoices for their branch.
- Key features:
  - Admin manages branches, users, employees
  - Branch-level access control — employees only see their branch data
  - Clients can track invoice status
- Tech: ASP.NET Core, EF Core, SQL Server, Identity
- Repo / Demo: (add link)

### 2) Book E-commerce System
Full-stack online bookstore for users and admins.
- Purpose: Sell books online with shopping and admin management
- Key features:
  - Admin dashboard for books and orders
  - Shopping cart and Stripe-powered checkout
  - Role-based access control
- Tech: ASP.NET Core MVC, EF Core, SQL Server, Bootstrap
- Repo / Demo: (add link)

### 3) Travel Linker Platform
Enterprise platform for hotels and transport companies.
- Purpose: Dashboard for companies to manage rooms, trips, schedules
- Key features:
  - Admin manages services, employees, schedules
  - Employees access only assigned entities
  - REST API backend for mobile/web clients
- Tech: ASP.NET Core, EF Core, JWT Authentication
- Repo / Demo: (add link)

### 4) ToDo List — Minimal API
Lightweight task management API built with Minimal APIs and Clean Architecture.
- Purpose: Personal tasks CRUD with authentication
- Key features:
  - Register, login, manage personal tasks
  - Minimal, testable, maintainable code
- Tech: .NET 10 Minimal API, EF Core, SQL Server
- Repo / Demo: (add link)

If you want, I can add direct repository links and demos for each project (just provide URLs or confirm repo names).

---

## Example: Minimal API usage (register / login)
Below is a short curl example showing how a Minimal API might expose register/login endpoints.

Register:
```bash
curl -X POST https://api.example.com/auth/register \
  -H "Content-Type: application/json" \
  -d '{"email":"you@example.com","password":"P@ssw0rd!"}'
```

Login:
```bash
curl -X POST https://api.example.com/auth/login \
  -H "Content-Type: application/json" \
  -d '{"email":"you@example.com","password":"P@ssw0rd!"}'
```

Response (example):
```json
{
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...",
  "expiresIn": 3600
}
```

---

## Contact
- Email: [samwelmarzouk3@gmail.com](mailto:samwelmarzouk3@gmail.com)  
- LinkedIn: [Samuel Marzouk](https://www.linkedin.com/in/samuel-marzouk-0a815821a/)  
- GitHub: [github.com/samwel314](https://github.com/samwel314)

---

## Contributing & License
- License: (add license file or statement here, e.g., MIT)
- Contributing: If you'd like help adding repo links, demos, or a license, I can prepare a PR with those updates.

---
