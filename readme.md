# DotNetCore

> .NET Core is a runtime. It can execute applications that are built for it.


-  ASP.NET Core is a collection of libraries that form a Framework for building web applications. 
- ASP.NET Core libraries can be used on both .NET Core and the "Full .NET Framework" (which has shipped with windows for many years).

> The confusing part is that an application using the libraries and tools of ASP.NET Core is usually referred to as "ASP.NET Core Application", which in theory doesn't say if it is built for .NET Core or .NET Framework. So an "ASP.NET Core Application" is also a ".NET Core Application" or a ".NET Framework Application".

![diff](/Images/diff.png)

- Here you can see that ASP.NET Core is built "on top of" both .NET Framework and .NET Core, while "ASP.NET" (now often referred to as "classic ASP.NET") is .NET Framework only.

- ASP.NET Core using .NET Core - all dependencies are self-contained, can use most NuGet packages, can't use Windows-specific packages, can execute on Windows, Linux, and Mac.

- ASP.NET Core using .NET Framework - most dependencies are self-contained, only executes on Windows, will have access to Windows-specific NuGet packages, needs the .NET framework version which is targeted installed on the machine.