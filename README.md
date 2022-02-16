# ASP.NET Core
ASP.NET Core is an open source, cross-platform framework developed by Microsoft for building web applications. First let’s break down ‘ASP’ ‘.NET’ ‘Core’.
## What is .NET?
.NET (pronounced as ‘dot net’) stands for Network Enabled Technologies. It is a free, open source, and cross-platform developer platform created by Microsoft to build software applications. These applications can be console apps, mobile apps, web apps, Windows desktop apps, cloud apps, or Internet of Things (IoT) apps. .NET applications can be created on Windows, macOS, and Linux.<br />
.NET applications can be written in C# (pronounced as ‘c sharp’), F# (pronounced as ‘f sharp’), and VB (Visual Basic). All 3 of these programming languages were developed by Microsoft. C# and VB are object-oriented programming languages; F# is majorly functional programming language, but it can be used to create object-oriented code as well. .NET uses a CLR (Common Language Runtime) which allows the developers to create an application using any or all of these languages. This source code is then compiled into an IL (Intermediate Language) code which is further compiled into machine code and executables using CLR.<br />
There are 3 implementations of .NET:
1.	**.NET**: It is a cross-platform implementation of .NET for running websites, services, and console apps on Windows, macOS, and Linux. It was previously called .NET Core.
2.	**.NET Framework**: It is the original Windows-only implementation of .NET. It can be used to build and run websites, services, desktop apps, and more on Windows.
3.	**Xamarin**: It is an additional cross-platform framework of .NET that allows building iOS (also macOS, watchOS, tvOS from Apple) and Android apps. Xamarin apps can be developed on Windows, macOS, and Linux.
## So where is ASP.NET Core?
ASP stands for Active Server Pages. It was Microsoft’s first server-side scripting language and engine for creating dynamic web pages (web pages requiring a lot of user interaction and updating of content based on the specific user). Dynamic web pages have client-side scripting (actions handled within the browser, generally using JavaScript) and server-side scripting (actions sent to-and-fro server). ASP handled the server side. If you have come across a website or a webpage ending with .asp or .aspx (Active Server Pages Extended), it was using ASP. <br />
ASP.NET is the successor to ASP. It is an open source, cross-platform, server-side web-application framework for building dynamic web apps and services. It uses .NET as a base and extends its functionality, specifically in the domain of web applications. ASP.NET apps use C# in addition to HTML, CSS, and JavaScript. These apps can be developed and run on Windows, macOS, and Linux.<br />
There are 4 main frameworks (without add-ons) within ASP.NET, identified on the basis on development styles:
1. **ASP.NET Web Pages**: These are used to create simple web sites and basic web applications.
2. **ASP.NET Web Forms**: These are used to create complex web sites and fully-featured web applications.
3. **ASP.NET MVC**: It used to build dynamic web sites by enabling a clean separation of concerns between various components of the web sites.
4. **ASP.NET Web API**: It is used to create HTTP services to run in browsers. It is ideally used to build RESTful applications.  <br />
The above frameworks are not mutually exclusive, and often use components from one another.<br />
ASP.NET Core is the successor to ASP.NET, combining Web Pages and Web Forms, and giving the choice to use F# (instead of C#) to build web applications.<br />
## Features of ASP.NET Core:
Till now we have understood that ASP.NET Core is used to build and run web applications. It is a one-stop solution from Microsoft for full-stack web development (both back-end and front-end web development). These web applications can be built and deployed on all of the major operating systems (Windows, macOS, Linux) and Docker. Apart from this, ASP.NET Core can be used to build IoT apps and mobile backends too. It also has deep integrations with Microsoft Azure Cloud for cloud deployment of web applications, though the deployment can be done on-premise or on another cloud platform like GCP (Google Cloud Platform) and AWS (Amazon Web Services) too. ASP.NET applications can also be connected with databases like Microsoft SQL Server, MySQL, Oracle, etc. for collecting and retrieving data within websites.<br />
Here is a list of other salient features of ASP.NET Core applications:
* Applications can use other front-end technologies like Angular, React, Bootstrap, etc.
* **Razor**: C# code can be combined with HTML pages instead of JavaScript for client-side scripting logic in .cshtml files (instead of .html).
* **Razor Pages**: A modification of MVC (Model-View-Controller) in which the controller is replaced by ViewModel which contains <OnGet> (~ doGet()) and <OnPost> (~ doPost()) methods to create a two-way binding between the client-side and server-side.
* **Blazor**: A FOSS (free and open source) SPA (Single Page Application) development framework that uses C# instead of JavaScript to create interactive web applications. Based on where (client browser or server) the code is run and processed, Blazor supports two different hosting methods:
  - **Blazor WebAssembly**: The entire page is downloaded to the client browser, and the connection with server is on as-need basis only
  - **Blazor Server**: A small part of the page is downloaded to the client browser, and the connection to the server is used to update web page using small connections called SignalR (a library of ASP.NET to add real-time functionality to web apps).<br /><br />
Due to its ease of development and deployment, code reusability within the websites, combined with its scalability, ASP.NET Core is mostly used by the enterprises to build their web sites, which are more akin to web applications due to the vast number of features and functionality like searching, login, logging, etc. included in the website.<br />
## Building ASP.NET Core Application:
ASP.NET Core comes built-in with .NET SDK (Software Development Kit) for Windows, macOS, and Linux. .NET 6 SDK installation is required on ASP.NET Core development machine. To run ASP.NET Core apps, .NET Runtime is required (it is bundled with .NET 6 SDK). <br />
IDEs (Integrated Development Environments) would be a strong recommendation for building ASP.NET Core apps because IDEs generate most of the rudimentary code to set the basis of the applications. On Windows, Visual Studio is the best IDE to build ASP.NET Core applications because of good integration of Visual Studio with .NET and Windows. Visual Studio Code (with the right set of extensions) and JetBrains Rider (not free) are good alternatives to build and run .NET applications on Windows, macOS, and Linux.<br />
For the purposes of this blog post, I will be using .NET 6 SDK and Visual Studio 2022 Community (free) edition (the latest ones at the time of publishing of the blog) for demonstration of the features of ASP.NET Core.<br />
Here is a video demonstrating the installation of .NET 6 SDK on Windows:

Here is a video demonstrating the installation of Visual Studio 2022 on Windows:

Here is a video demonstrating the creation of ASP.NET Core MVC web application project from the templates provided by Visual Studio: 

In the next blog, I will be demonstrating the CPRG352 Web application Programming final project using ASP.NET Core MVC.
References:
https://dev.to/alagrede/lean-how-to-build-your-personal-blog-with-github-pages-42ae
https://pages.github.com/
https://devblogs.microsoft.com/dotnet/announcing-asp-net-core-in-net-6/
https://dotnet.microsoft.com/en-us/learn/dotnet/what-is-dotnet
https://dotnet.microsoft.com/en-us/learn/dotnet/what-is-dotnet-framework
https://dotnet.microsoft.com/en-us/learn/xamarin/what-is-xamarin
https://docs.microsoft.com/en-us/dotnet/core/introduction
https://en.wikipedia.org/wiki/.NET
https://en.wikipedia.org/wiki/.NET_Framework
https://en.wikipedia.org/wiki/ASP.NET
https://resources.infosecinstitute.com/topic/net-framework-clr-common-language-runtime/
https://docs.microsoft.com/en-us/aspnet/core/introduction-to-aspnet-core?view=aspnetcore-6.0
https://docs.microsoft.com/en-us/aspnet/core/razor-pages/?view=aspnetcore-6.0&tabs=visual-studio
https://dotnet.microsoft.com/en-us/apps/aspnet
https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps
https://dotnet.microsoft.com/en-us/apps/aspnet/mvc
https://www.c-sharpcorner.com/UploadFile/36985e/web-forms-mvc-and-web-pages-in-Asp-Net/
https://www.doteasy.com/web-hosting-articles/what-is-a-dynamic-web-page.cfm
https://hexishub.medium.com/blazor-vs-razor-1dd7548bcf29
https://dotnet.microsoft.com/en-us/languages
https://www.lifewire.com/what-is-an-aspx-file-2619705

