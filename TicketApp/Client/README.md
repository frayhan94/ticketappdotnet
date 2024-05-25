Ticket App

Reference 
1. https://getbootstrap.com/docs/5.0/getting-started/introduction/ | Bootstrap 

Pre-requisite
1. Include this <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
   to make the interaction component works

Section 1
1. Add basic UI to display all list of ticket
2. Remove unnecessary file for better focus on learning
3. Add navigation item on the header

Section 2
1. make the component ticket list so the code is less

Section 3
1. Add sql server to connection string JSON appsettings.json  under server folder
2. Make sure dotnet ef is already installed by running dotnet ef if not yet the run this command to install
   dotnet tools install --global dotnet-ef
3. Install these NuGet Packages
   a. Microsfot.EntityFrameworkCore version 6
   b. Microsfot.EntityFrameworkCore.Design (for migration) version 6
   c. Microsfot.EntityFrameworkCore.SqlServer version 6

Section 4
1. Create data context class to connect to database
2. Register data context to program.cs