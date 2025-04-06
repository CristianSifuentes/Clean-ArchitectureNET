# Clean Architecture in .NET

## Table of Contents
1. [What is Clean Architecture in .NET?](#what-is-clean-architecture-in-net)
2. [Key Characteristics](#key-characteristics)
3. [Advantages](#advantages)
4. [Disadvantages](#disadvantages)
5. [Books to Master Clean Architecture in .NET](#books-to-master-clean-architecture-in-net)
6. [Key Articles & Blogs](#key-articles--blogs)
7. [GitHub Repositories (Practical Implementations)](#github-repositories-practical-implementations)
8. [YouTube Playlists](#youtube-playlists)
9. [Pro Tips to Master Clean Architecture in .NET](#pro-tips-to-master-clean-architecture-in-net)

---

## What is Clean Architecture in .NET?
Clean Architecture, proposed by Robert C. Martin (Uncle Bob), is a software design philosophy that emphasizes separation of concerns and independence from frameworks, databases, and user interfaces. It promotes:
- Maintainability
- Scalability
- Testability
- Independence of technology

In .NET, it usually means separating the project into **Domain**, **Application**, **Infrastructure**, and **Presentation** layers.

---

## Key Characteristics
- **Framework-agnostic**: Business logic doesn’t depend on specific technologies.
- **UI-agnostic**: UI can be replaced without modifying core logic.
- **Database-independent**: You can swap databases without much hassle.
- **Testability**: Logic is easily unit tested.
- **Separation of concerns**: Each layer has clear responsibilities.

---

## Advantages
- **Maintainability**: Easier to extend and debug.
- **Scalability**: Components scale independently.
- **Flexibility**: Swap tools or frameworks freely.
- **Reduced technical debt**: Encourages clean, modular code.

---

## Disadvantages
- **Initial complexity**: Higher setup cost.
- **Learning curve**: Requires understanding of SOLID, DDD, DI, etc.
- **Overengineering**: Might be excessive for small apps.

---

## Books to Master Clean Architecture in .NET
1. [Clean Architecture: A Craftsman's Guide](https://www.amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164) – Robert C. Martin
2. [Clean Architecture with ASP.NET Core](https://www.amazon.com/Clean-Architecture-ASP-NET-Core-applications/dp/1803235941) – Jason Taylor & Steve Smith
3. [Software Architecture for .NET Developers](https://www.amazon.com/Software-Architecture-NET-Developers-maintainable/dp/1800205663) – Gabriel Baptista & Francesco Abbruzzese

---

## Key Articles & Blogs
- [Clean Architecture with ASP.NET Core – Ardalis](https://ardalis.com/clean-architecture-asp-net-core/)
- [Clean Architecture in .NET – Dev.to](https://dev.to/ipazooki/clean-architecture-in-net-1hid)
- [What is Clean Architecture? – Juanjo Blog](https://juanjoblog.com/que-es-clean-architecture-y-cuales-son-sus-beneficios-y-desventajas/)
- [Pros and Cons – LinkedIn Article](https://www.linkedin.com/pulse/exploring-depths-clean-architecture-its-pros-cons-net-hanumant-patil-oay8f)

---

## GitHub Repositories (Practical Implementations)
- [jasontaylordev/CleanArchitecture](https://github.com/jasontaylordev/CleanArchitecture)
- [ardalis/CleanArchitecture](https://github.com/ardalis/CleanArchitecture)
- [blazorhero/CleanArchitecture](https://github.com/blazorhero/CleanArchitecture)

---

## YouTube Playlists
- [Clean Architecture Step-by-Step (Spanish) – Olimpo Bonilla](https://www.youtube.com/watch?v=VKc88NWf4lw)
- [Clean Architecture in ASP.NET Core – FreeCodeCamp](https://www.youtube.com/watch?v=dK4Yb6-LxAk)

---

## Pro Tips to Master Clean Architecture in .NET
1. Understand SOLID principles deeply.
2. Practice Domain-Driven Design (DDD).
3. Use Dependency Injection consistently.
4. Write tests for Application and Domain layers.
5. Study Onion and Hexagonal Architectures.
6. Try refactoring legacy .NET projects using Clean Architecture.

