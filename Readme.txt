OverView:
This assignment involves creating a full stack web application that utilizes SQLite for the database, C# (ASP.NET Core) for the backend, React.js for the frontend, and Three.js for 3D graphics. The project focuses on the following key functionalities:
Database Management: Use SQLite to store and manage case data, including operations for creating, reading, updating, and deleting (CRUD) cases.
Backend Development: Implement the backend using ASP.NET Core in C#. This includes setting up a DbContext for SQLite and creating API endpoints to handle CRUD operations.
Frontend Development: Build a user interface with React.js to interact with the backend API, allowing users to perform CRUD operations on case data.
3D Graphics Integration: Utilize Three.js to render a 3D cube with realistic shadows. Implement a Z-Lock feature, ensuring the cube can only be rotated left and right (along the Z-axis) and not top and bottom.
This assignment tests the ability to integrate and work with a range of technologies to build a cohesive web application with both data management and interactive 3D graphics.


Instructions:
Backend :
1. Visual Studio 2022 with .net version net6.0
2. Nuget Package
    <PackageReference Include="Microsoft.EntityFrameworkCore" Version="6.0.30" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.Sqlite" Version="6.0.30" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.Tools" Version="6.0.30"> 
3. Migration to create table in SQLite
	Add-Migration intial
	update-database
4. Run backend application

Frontend
1. Visual Studio Code
2. Install node modules by using 'npm install' command in terminal
3. check backend url in the browser and compare with baseUrl in BaseClass.js file
4. To execute fronend run 'npm start' in terminal
5. Copy browser url and paste into incognito mode and remove s from https url will be like this http://localhost:3000/