# ASP.NET-Exam-Test Step
1.Create Database > Project
2.Connection String
  <connectionStrings>
    <add name="" connectionString="" providerName="System.Data.SqlClient"/>
  </connectionStrings>
3.CREATE (Execute)
4.RETRIEVE (Query & Query Single)
  4.1 with grid
    var grid = new WebGrid (source:SQL, rowsPerPage:N)
    @gird.GetHTML...
5.UPDATE & DELETE (GET & Execute)