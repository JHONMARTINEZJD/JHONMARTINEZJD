### Jhonatan Martínez — desarrollo backend y herramientas de sistema

Construyo servicios backend y herramientas que trabajan cerca del sistema operativo o de formatos
de archivo concretos. Prefiero parsers propios a regex frágiles, procesos deterministas y
arquitecturas que se entienden leyendo el código.

### Proyectos

**[hp-gaming-control](https://github.com/JHONMARTINEZJD/hp-gaming-control)** — Control de rendimiento,
ventiladores y temperatura para portátiles HP OMEN y Victus, en Linux y Windows desde un solo código en Rust.
Servicio en segundo plano con protección térmica 24/7, CLI, ventana Slint y bandeja que hablan con él
por un socket local sin root; lo residente ocupa ~11 MB de RAM. Linux funciona hoy; Windows, en curso.

**[cs2-cfg-snapshot](https://github.com/JHONMARTINEZJD/cs2-cfg-snapshot)** — Motor en PowerShell que
descubre, parsea, clasifica, valida y exporta la configuración viva de Counter-Strike 2.
Tokenizer propio carácter a carácter para `.vcfg`/`.vdf` y `.cfg`, 50 categorías y sincronización
determinista donde la configuración del jugador prevalece sobre los valores por defecto.

**[AnimeAPI](https://github.com/JHONMARTINEZJD/AnimeAPI)** — API REST en Spring Boot para un catálogo de anime.
Autenticación JWT, reseñas, favoritos y listas de seguimiento sobre PostgreSQL, con documentación OpenAPI.

**[PortafolioAcademicoWeb](https://github.com/JHONMARTINEZJD/PortafolioAcademicoWeb)** — Plataforma web
para portafolios académicos con enfoque SENA (fichas, competencias, evidencias), en Next.js.
Sesión server-side en cookie HTTP-only, persistencia en PostgreSQL, reportes CSV y auditoría de eventos.

### Stack

`Rust` · `Java` · `Spring Boot` · `TypeScript` · `Next.js` · `PowerShell` · `PostgreSQL` · `JPA/Hibernate`
