# .NET-terminology

If you wander through the developer forums, one of the topics to always be questioned is about product name terminology related to .NET and ASP.NET Core. It is fair to say that Microsoft has a rather complicated history of naming their development frameworks from version to version, so it is not surprising that many people find this confusing.

## Differences between ASP.NET Core and .NET

Oddly enough, there are always a lot of questions in the forums about the difference between .NET and ASP.NET Core (former ASP.NET). It's pretty simple, ASP.NET Core is a full-stack web development framework, and this framework is just part of .NET platform.

You can use ASP.NET Core to build a website with a database at its back end, and are looking for a good tool to use. Of course, it would be your choice for ASP.NET Core as there are many competitors—you can build web applications using Java, Spring, PHP, Laravel, Python or Python with Flask, JavaScript with NodeJS, and so on.

The important thing is why might you prefer to use ASP.NET Core? The answer here is simple: ASP.NET Core gives you a tool to create enterprise-level web applications. More importantly, this framework is not only to build apps for the big brands. With Microsoft C# and ASP.NET Core, you can build web applications for your startup too.

Another reason to use ASP.NET Core is in continuity of development tools is important. Hot trends for development tools change quickly. Your ecommerce web site or any other web app should be live for at least few years, and should be maintained and updated all that time—meaning, you must be sure that you will find both developers and software tools. And here is where Microsoft significantly outperforms the competition: ASP.NET has been around since early 2000s and is continually evolving.

## Why use .NET?
.NET is a free, open-source developer platform from Microsoft that is useful for building a plethora of applications. .NET is available for Windows, Linux, and macOS. The other definition of .NET is as “software development framework” created by Microsoft you can use to build a wide range of applications. 

In the more than 20 years since the first versions of .NET were released in the early 2000s, Microsoft has turned this development platform into a near-perfect set of tiils including frameworks, programming languages, libraries, runtime compilers, cloud services for developing applications of any use case and any complexity.

One key advantage of .NET is that it is free to use for any developer. .NET includes support for multiple programming languages, making it easy for developers to build applications using the language of their choice. 

In addition, .NET provides a wide range of libraries and tools that can be used to create both desktop and web-based applications. .NET also includes a garbage collector, which helps to manage memory usage and improve performance. As a result, .NET is a powerful and flexible platform that can be used to build a wide range of high-quality applications.

Some core facts about .NET:
- Current .NET 6.0 was released in November 2021 and will be supported by Microsoft til mid-2024 (previous .NET 5.0 was released on November 10, 2020). 
- The .NET SDK includes the .NET Runtime, which you can use to run .NET applications. The .NET Runtime includes the just-in-time (JIT) compiler, which compiles your code at run time. The .NET SDK also includes the Native Image Generator (NGen), which compiles your code ahead of time so that it runs faster when you deploy it. 

For business owners it is important to know that .NET helps to keep IT costs down by allowing to use the same platform to build a variety of applications.  


## .NET — a Unified Development Platform at a Glance

There is an official Microsoft’s document on what the key components of .NET are, to read it click to Announcing .NET 6 — The Fastest .NET Yet. This page includes a huge number of links to other Microsoft's clarifying documents. And now have a look on a more concise and popularized overview of these key components prepared exactly for your attention. 

Now let's go left to right and talk about these .NET components.
- Azure cloud is Microsoft's cloud services. With very close integration of Visual Studio, you can gain development experience for Azure cloud infrastructure using services like Azure Logic Apps, Azure Function, etc. 
You are welcome to read our posts how we use advanced Azure services:
How We Launched Virto Commerce B2B eCommerce Platform in Serverless Mode on Azure Functions and Low Code Integration Scenarios in Virto Commerce Using Azure Logic Apps.
- ASP.NET Core is a framework with a .NET component for creating web applications. Blazor is a tool or service that enables you to create rich, interactive UIs using C# rather than JavaScript. It also allows for the sharing of server-side and client-side applications logic between both environments with .NET. The power behind Blazor lies in its ability to break down traditional limitations imposed by today's internet browsers, thus paving the way for more complex apps.
- Desktop Windows Forms (WinForms) is a UI tool that allows developers to create native Windows desktop applications with .NET wrappers over user interface libraries such as User32 and GDI+. WinForms also offers controls specifically for use within the context of this particular type or style guide. 
- Mobile .NET Multi-Platform App UI (.NET MAUI) enables you to build apps that perform great on any device running Windows, macOS, or iOS from a single code base. Coupled with Visual Studio productivity tools and emulators, it significantly speeds up the development process of building modern workloads targeted toward all major platforms including Android and iOS.
- IoT, the .NET libraries available for IoT devices and scenarios, allows developers to write applications that interact with sensors, displays, and input devices. These capabilities are provided on top of features like GPIO pins or serial ports. This enables them in building powerful software solutions tailored specifically toward interacting with physical world objects via IoT connections. In ecommerce, for example, these are mainly warehouse sensors and barcode scanners. Azure Functions service is great for IoT signal processing in an ecommerce solution.
- AI (Machine Learning for .NET) is a cross-platform, open-source, machine learning (ML) framework for .NET. It allows the development of custom AI models in applications such as Windows and MacOS, by creating them with minimal knowledge about ML model development, or previous experience in tools like Python or R, to build, train, develop, and evaluate results. The platform provides data load from files and databases, enables transformations, and includes many ML-based methods. Our Virto Professional Service team has experience integrating Azure ML services with the Virto Commerce platform. Read our post AI in eCommerce: Challenges & Solutions. How to Use Machine Learning in eCommerce.

Development services, which Microsoft calls “ecosystem” allow developers to work with a high level of productivity and comfort.
- NuGet is the code-sharing mechanism supported by Microsoft for .NET, which defines how to create, host, and use .NET applications and provides tools for each of them. The mechanism by which programmers can create and share code with others is an important tool for any modern development platform. Occasionally this code is distributed in "packages", which includes compiled code (in the form of DLLs) and other required information on the projects for those who work on them.
- GitHub is a cloud-based service and platform that helps developers store code, as well as track and control changes to code. Version control helps developers manage changes to an application's code, as well as track and manage changes in software projects. When the development of software projects grows, version control is important. The Git is a specific open-source version control system invented by Linus Torvalds. With GitHub, you have the possibility of accessing all codebase and history on every developer’s computer, allowing easy branching and merging.

Feel free to visit and use Virto Commerce’s repository in GitHub.

- Components, tools, and library are simply references to the presence of related services that developers use in .NET. These are identification and authorization services, etc.

.NET integrated development environment (IDE) in fact means software applications that provide comprehensive facilities to computer programmers for software development. At the moment, an IDE is normally composed of source code editor and build-automation tools, as well as a debugger and intelligent code completion.
- Visual Studio, Visual Studio for Mac, and Visual Studio Code. The first two create an integrated environment for Windows and Mac that provides tools and services to develop apps for desktops, mobile devices, and the cloud. Visual Studio is a suite of component-based software development tools. On the other hand, Visual Studio Code is Microsoft’s version of Sublime code editor.
- .NET CLI (Command Line Interface) is a cross-platform toolchain for developing, building, running, and publishing .NET applications. The .NET Command Line Interface is included in the SDK for .NET. The CLI works with the dotnet command and performs two functions. It provides commands to work with .NET projects and it runs .NET applications. 

Hope after reading this post, you now have a better understanding of the inner workings of .NET—at least, better than most people who are not developers. To consolidate the success of your new knowledge, take a look at full story about .NET and ASP.NET terminology in Virto Commerce blog.

The more topics covered in the full story on our blog:
- What Is a Framework for Developers?
- The Scope of ASP.NET Core (former ASP.NET)
- Understanding All Parts of The ASP.NET Core Term
- How the Atomic Architecture™ Framework Helps Virto Commerce Developer
- What is Cross-Platform Development in .NET with Xamarin
