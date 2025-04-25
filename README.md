# Branch
BRANCH CRUD
The Branch Management API is a simple web service built using C# .NET 6.0 that provides CRUD (Create, Read, Update, Delete) operations for managing branch data. This API allows users to perform common operations such as creating new branches, retrieving branch information, updating existing branches, and deleting branches. It provides a RESTful interface with secure endpoints, optimized for handling data in a scalable and efficient manner.

Se debe clonar o descargar el codigo atraves de consola.
Restaurar los Nuget Package para que se instalen las dependencias del proyecto.
Configurar ConnectionString , este se encuentra en el archivo appsettings.development.json 
El proyecto esta realizado con EF Core, por tal motivo orrer la migraciones del proyecto, para esto nos dirigimos al 
Package Manager Console y ejecutamos el comando add-Migration Initial para que se creen las tablas y luego Update-Database
Se debe tener en cuenta encuenta el puerto con el cual se levanta el localhost ya que asi mismo se debe habilitar el CORS
