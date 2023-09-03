# Employee Management System 
<h3>Introduction</h3>
This system provides a portal through which employees can apply for approvals, report to managers while managers can review,comment and make decisions on these reports. Employee issues such as paid time approval, overtime approvals, reimbursements and contract approvals are handled effectively. The system maintains employee attendance and availablity records which enable ease of operations. 


<h3>Technology and Frameworks</h3>
1.database management system- MS SQL Server.<br>
2..Net Framework 4.6.1<br>
3.Visual Studio - ASP.NET - C#<br>

<h3>Technical Points</h3>
1.Password Hash&Salt<br>
2.Session State<br>
3.Repeater<br>
  a.Load Data from Datasource(session is used here)<br>
  b.Create hyperlink with ID as suffix(http://localhost:58556/Views/Outputs/OvertimeRead?OAppId=1.aspx)<br>
4.Read/Unread pages<br>
  a.Get url with ID suffix from current page<br>
  b.Use ID to get data from Database using SQL (SELECT, UPDATE)
