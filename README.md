# Bloomberg L.P. Interview

## Demonstrate:

- C# Inversion of Control  / dependency injection, interfaces in C# 
- Python unit and integration tests 
- VBA and Excel macros
- FIX protocol 

## C# & ASP.NET Core

*NET core: C#, F# and VB.NET all compile to intermediate language (IL)*

https://www.dotnetperls.com/il

https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-3.1#overview-of-dependency-injection

https://github.com/dotnet/AspNetCore.Docs/tree/master/aspnetcore/fundamentals/dependency-injection/samples/3.x/DependencyInjectionSample

## Python Notes

https://pypi.org/project/fixtool

https://github.com/kennt/fixtest

https://github.com/RussBaz/enforce

https://pythonspot.com/read-excel-with-pandas/

https://stackoverflow.com/questions/12287677/using-python-to-read-vba-from-an-excel-spreadsheet

https://stackoverflow.com/questions/24971818/how-to-connect-vb-net-program-with-python

### Pass VB to Python?

```vb
p.StartInfo.FileName = "C:\Python33\python.exe"
p.StartInfo.Arguments = "new.py hello"
```



## VBA

```vb
Sub Macro1()
'
' Macro1 Macro
'
'
    Range("B1").Select
    ActiveCell.FormulaR1C1 = "Hello World"
    Range("B2").Select
End Sub
 
```



## FIX Protocol 

*FIX has few public / free examples to mock a system to build tests around.*   

https://www.codeproject.com/Articles/757708/Mock-FIX-Trading-Server

http://www.quickfixengine.org/

https://stackoverflow.com/questions/11435174/how-to-test-my-fix-client-is-there-a-fake-fix-exchange-out-there-that-i-can-use

https://automationrhapsody.com/fix-messages-simulator/

https://stackoverflow.com/questions/18499447/how-do-i-run-quickfix-examples

http://quickfix-j.364392.n2.nabble.com/How-to-test-my-FIX-client-Is-there-a-fake-FIX-exchange-out-there-that-I-can-use-td7577418.html

---

## TODOs: 

- Install Office365 demo 
- Run QuickFix Execute, consume it somehow 
- Unit Test demo in Python, with enforce.py,
- https://docs.microsoft.com/en-us/dotnet/core/tutorials/with-visual-studio-code
- https://code.visualstudio.com/docs/languages/dotnet
- https://channel9.msdn.com/Blogs/dotnet/Get-started-with-VS-Code-Csharp-dotnet-Core-Ubuntu
- https://docs.docker.com/engine/examples/dotnetcore/
- Demonstrate C# Dependency Injection
- wire 'something' up: 
  - Fix Protocol --> C# Mock / Inversion of Control  or VB.NET -> Excel sheet -> VBA macro -> Python unit   



---

```
 Product: Working on migrating the UI based Test Framework with Python. 

Skills: Python Scripting (3-5 years) of Python Development

C# AND Database experience AND Visual Basic

Understanding the Financial Market (Huge Plus)

 

JD: 

   Bloomberg is seeking a Software Engineer in Test (SET) to support our AIM Buyside Quality Assurance & Engineering teams.

AIM builds on Bloomberg's core data and analytics, offering Buyside institutions, hedge funds, and proprietary trading desks a complete front-end Order Management System package. AIM delivers global, multi-asset solutions from portfolio, trading, and middle office & back office operations. Allowing clients to manage their portfolio and risk, optimize their workflows, enhance compliance and lower their operational risk.

 

We’ll trust you to:

- Build automated test scripts based on manual test cases provided by team members

- Build service level tests based on current UI automated tests

- Run and troubleshoot automated tests

- Identify and report testing gaps and/or technical challenges

- Contribute to and support our shared strategic technology agenda

- Support the team with technical troubleshooting of existing Automated Regression scripts

- Build new frameworks using python for areas of support not yet covered with an automated regression inventory

 

You’ll need to have:

- Bachelor of Science or Bachelor of Arts in Computer Science

- 3 years or more of Automation Experience

- Proficient in python

- Strong MS Excel, VB Script, VB.Net, VBA

- Strong project management skills

- Ability to quickly obtain detailed knowledge of complex products and apply software test techniques for rapid production releases

- Experience with Order Management Systems or Electronic Trading Applications

- Strong communication skills

 

We’d love to see:

- Bloomberg experience

- Knowledge of FIX Protocol
```

