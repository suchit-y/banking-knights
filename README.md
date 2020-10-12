# banking-knights
A robust banking application

Bank Application

Software Requirements:
1. IDE for running Java (Eg. STS)
2. Jdk 1.8 or higher version
3. DB-Derby 10.14.2.0( derbyclient.jar)
4. Apache Tomcat Server 9.0.38(servlet-api.jar)
5. Suitable OS for running Java Applications(Mac 10.12 / Windows 7 or higher)
6. Includes suitable Jar Files(For XML Parsing : JDom Jar files)
    
Packages:
1.com.hsbc.codefury.errorKnights.app.dao:
It is DAO layer which  contains implementations of all the modules.

2.com.hsbc.codefury.errorKnights.app.entity:
It is an entity layer which  contains basic entity  classes such as Customer,Account,Transaction.

3.com.hsbc.codefury.errorKnights.app.service:
It is a service layer which contains required servlets as Controllers.

4.com.hsbc.codefury.errorKnights.app.exceptions:
It involves customized Exceptions. Eg-AccountNotFound Exception,TransactionFailed Exception

5.Web-Content Folder:
It contains all the required JSP,HTML,CSS,JS files.
