# ASP.NET-Exam-Test Step
<ol>
<li>Create Database > Project</li>
<li>Connection String<li>
<pre>
<code>
  <connectionStrings>
    <add name="" connectionString="" providerName="System.Data.SqlClient"/>
  </connectionStrings>
</code>
</pre>
<li>CREATE (Execute)</li>
<li>RETRIEVE (Query & Query Single)</li>
<ul><li>
  4.1 with grid</li></ul>
<pre>
<code>
    var grid = new WebGrid (source:SQL, rowsPerPage:N)
    @gird.GetHTML...
</code>
</pre>
<li>5.UPDATE & DELETE (GET & Execute)</li>
</ol>