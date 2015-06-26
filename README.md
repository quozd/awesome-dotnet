# Awesome .NET!

[![Join the chat at https://gitter.im/quozd/awesome-dotnet](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/quozd/awesome-dotnet?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A collection of awesome .NET libraries, tools, frameworks, and software.

Inspired by [awesome-ruby](https://github.com/markets/awesome-ruby), [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) and [ruby-bookmarks](https://github.com/dreikanter/ruby-bookmarks).

Contributions are always welcome! Please take a look at the [contribution guidelines and quality standard](https://github.com/quozd/awesome-dotnet/blob/master/CONTRIBUTING.md) pages first. We accept proprietary and commercial software too.

Thanks to all [contributors](https://github.com/quozd/awesome-dotnet/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

* [Awesome DotNet](#awesome-dotnet)
  * [API](#api)
  * [Application Frameworks](#application-frameworks)
  * [Application Templates](#application-templates)
  * [Assembly Manipulation](#assembly-manipulation)
  * [Assets](#assets)
  * [Authentication and Authorization](#authentication-and-authorization)
  * [Build Automation](#build-automation)
  * [Caching](#caching)
  * [CLI](#cli)
  * [CLR](#clr)
  * [CMS](#cms)
  * [Code Analysis and Metrics](#code-analysis-and-metrics)
  * [Compiler](#compiler)
  * [Compression](#compression)
  * [Continuous Integration](#continuous-integration)
  * [Cryptography](#cryptography)
  * [Database](#database)
  * [Database Drivers](#database-drivers)
  * [Deployment](#deployment)
  * [DirectX](#directx)
  * [Distributed Computing](#distributed-computing)
  * [Documentation](#documentation)
  * [E-Commerce and Payments](#e-commerce-and-payments)
  * [Environment Management](#environment-management)
  * [ETL](#etl)
  * [Game](#game)
  * [Gis](#gis)
  * [Git Tools](#git-tools)
  * [Graphics](#graphics)
  * [GUI](#gui)
  * [HTML and CSS](#html-and-css)
  * [HTTP](#http)
  * [IDE](#ide)
  * [Image Processing](#image-processing)
  * [Install Tools](#install-tools)
  * [Internationalization](#internationalization)
  * [Interoperability](#interoperability)
  * [IoC](#ioc)
  * [Logging](#logging)
  * [Mail](#mail)
  * [Machine Learning and Data Science](#machine-learning-and-data-science)
  * [Markdown Processors](#markdown-processors)
  * [Mathematics](#mathematics)
  * [Media](#media)
  * [Metrics](#metrics)
  * [Misc](#misc)
  * [MVVM](#mvvm)
  * [Office](#office)
  * [ORM](#orm)
  * [Package Management](#package-management)
  * [PDF](#pdf)
  * [Profiler](#profiler)
  * [Queue](#queue)
  * [Scheduling](#scheduling)
  * [SDK and API Clients](#sdk-and-api-clients)
  * [Search](#search)
  * [Serialization](#serialization)
  * [State machines](#state-machines)
  * [Style Guide](#style-guide)
  * [Template Engine](#template-engine)
  * [Testing](#testing)
  * [Visual Studio Plugins](#visual-studio-plugins)
  * [Web Frameworks](#web-frameworks)
  * [Web Servers](#web-servers)
  * [WebSocket](#websocket)
  * [Windows Services](#windows-services)

* [Other Awesome Lists](#other-awesome-lists)

## API

* Frameworks
  * [ASP.NET WebAPI](http://www.asp.net/web-api/) - Framework that makes it easy to build HTTP services that reach a broad range of clients, including browsers and mobile devices
  * [ServiceStack](https://github.com/ServiceStack/ServiceStack) - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all

* [WebAPI Contrib](https://github.com/WebApiContrib/WebAPIContrib) - Collection of open source projects to help improve your work with ASP.NET Web API

## Application Frameworks

* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) - A starting point for new modern ASP.NET MVC web applications with best practices and most popular tools.
* [Orleans](https://github.com/dotnet/orleans) - Orleans is a framework that provides a straight-forward approach to building distributed high-scale computing applications, without the need to learn and apply complex concurrency or other scaling patterns
* [CoreFX](https://github.com/dotnet/corefx) -  The corefx repo contains the library implementation (called "CoreFX") for .NET Core. It includes System.Collections, System.IO, System.Xml and many other components. It builds and runs on Windows. You can 'watch' the repo to see Linux and Mac support being added over the next few months.
* [Mono](https://github.com/mono/mono) - Mono open source ECMA CLI, C# and .NET implementation
* [Mono-Addins](https://github.com/mono/mono-addins) - Mono.Addins is a generic framework for creating extensible applications, and for creating add-ins which extend those applications
* [Spring.Net](https://github.com/spring-projects/spring-net) - Spring.NET is an open source application framework that makes building  enterprise .NET applications easier

## Application Templates

* [MVC.Template](https://github.com/NonFactors/MVC.Template) - ASP.NET MVC 5 project starter template

## Assembly Manipulation

* [Fody](https://github.com/Fody/Fody) - Extensible tool for weaving .net assemblies
* [Mono.Cecil](https://github.com/jbevain/cecil) - Cecil is a library to generate and inspect programs and libraries in the ECMA CIL form.

## Assets

* [Cassette](https://github.com/andrewdavey/cassette) - Manages .NET web application assets (scripts, css and templates)
* [NodeAssets](https://github.com/ajorkowski/NodeAssets) - Asset Manager for .net that has live css updates using SignalR and can optionally leverage NodeJS compilers
* [Bundler](https://github.com/ServiceStack/Bundler) - Compile & Minify Less/Sass/Stylus/Css/JS/CoffeeScript/LiveScript files. Integrates with MVC and ServiceStack
* [SquishIt](https://github.com/jetheredge/SquishIt) - Lets you *easily* bundle some css and javascript

## Authentication and Authorization

* [ASP.NET Identity](https://aspnetidentity.codeplex.com/) - New membership system for ASP.NET applications
* [DotNetOpenAuth](https://github.com/DotNetOpenAuth/DotNetOpenAuth) - A C# implementation of the OpenID, OAuth and InfoCard protocols
* [Thinktecture IdentityModel](https://github.com/thinktecture/Thinktecture.IdentityModel.45) - Helper library for identity & access control in .NET 4.5 and MVC4/Web API.
* [OAuth](https://github.com/danielcrenna/oauth) - A very lightweight library for generating OAuth 1.0a signatures written in C#

## Build Automation

* [Psake](https://github.com/psake/psake) - .NET-based build automation tool written in PowerShell
* [FAKE](https://github.com/fsharp/FAKE) - F# Make, a cross platform build automation system
* [Invoke-Build](https://github.com/nightroman/Invoke-Build) - PowerShell build and test automation tool inspired by Psake.
* [MSBuild](https://github.com/Microsoft/msbuild) - The Microsoft Build Engine (MSBuild) is the build platform for .NET and Visual Studio

## Caching

* [CacheCow](https://github.com/aliostad/CacheCow) - An ASP.NET Web API HTTP caching implementation both on client and server
* [Akavache](https://github.com/akavache/Akavache) - An asynchronous, persistent key-value store 

## CLI

* [Command Line Parser](https://github.com/gsscoder/commandline) - The Command Line Parser Library offers to CLR applications a clean and concise API for manipulating command line arguments and related tasks
* [Power Args](https://github.com/adamabdelhamed/PowerArgs) - PowerArgs converts command line arguments into .NET objects that are easy to program against. It also provides a ton of optional capabilities such as argument validation, auto generated usage, tab completion, and plenty of extensibility
* [UnionArgParser](https://github.com/nessos/UnionArgParser) - Declarative CLI argument & XML configuration parser for F# applications.

## CLR

* [CoreCLR](https://github.com/dotnet/coreclr) - The coreclr repo contains the complete runtime implementation (called "CoreCLR") for .NET Core. It includes RyuJIT, the .NET GC, native interop and many other components. It builds and runs on Windows. You can 'watch' the repo to see Linux and Mac support being added over the next few months.

## CMS

* [Umbraco](https://github.com/umbraco/Umbraco-CMS) - Umbraco is a free open source Content Management System built on the ASP.NET platform
* [Composite C1](https://compositec1.codeplex.com/) - A web CMS that focus on UX and adaptability
* [Orchard ](https://orchard.codeplex.com/) - Free, open source, community-focused project aimed at delivering applications and reusable components on the ASP.NET platform
* [mojoPortal ](https://mojoportal.codeplex.com/) - MojoPortal is an extensible, cross database, mobile friendly, web content management system (CMS) and web application framework written in C# ASP.NET
* [N2CMS](http://www.n2cms.com/) - Open source, lightweight, code-first CMS able to seamlessly integrate into any MVC project.

## Code Analysis and Metrics

* [StyleCop](https://stylecop.codeplex.com/) - StyleCop analyzes C# source code to enforce a set of style and consistency rules
* [Gendarme](https://github.com/spouliot/gendarme) - Extensible rule-based tool to find problems in .NET applications and libraries
* [Metrics-Net](https://github.com/danielcrenna/metrics-net) - Capturing CLR and application-level metrics. So you know what's going on.

## Compiler

* [Roslyn](https://github.com/dotnet/roslyn) - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs. It enables building code analysis tools with the same APIs that are used by Visual Studio.
* [VisualFSharp](https://github.com/Microsoft/visualfsharp) - The Visual F# compiler and tools
* [Mono-basic](https://github.com/mono/mono-basic) - Visual Basic Compiler and Runtime

## Compression

* [SharpCompress](https://github.com/adamhathcock/sharpcompress) - SharpCompress is a compression library for .NET/Mono/Silverlight/WP7 that can unrar, un7zip, unzip, untar unbzip2 and ungzip with forward-only reading and file random access APIs. Write support for zip/tar/bzip2/gzip are implemented
* [DotNetZip.Semverd](https://github.com/haf/DotNetZip.Semverd) - An open-source project that delivers a .NET library for handling ZIP files, and some associated tools. (fork of [**Unmaintained** DotNetZip](http://dotnetzip.codeplex.com))
* [SharpZipLib](http://icsharpcode.github.io/SharpZipLib/) - a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform

## Continuous Integration
* [TeamCity](http://www.jetbrains.com/teamcity/) - Ready to work, extensible and developer-friendly build server — out of the box **[$]**
* [CruiseControl.NET](http://www.cruisecontrolnet.org/) - an Automated Continuous Integration server, implemented using the .NET Framework
* [MyGet](http://www.myget.org/) - Continuous Integration and Deployment, Hosted Package Repository for NuGet, NPM, Bower and VSIX. **[[Free for OSS](https://www.myget.org/opensource)]** **[$]**

## Cryptography

* [HashLib](http://hashlib.codeplex.com/) - HashLib is a collection of nearly all hash algorithms you've ever seen, it supports almost everything and is very easy to use
* [libsodium-net](https://github.com/adamcaudill/libsodium-net) - libsodium for .NET - A secure cryptographic library
* [StreamCryptor](https://github.com/bitbeans/StreamCryptor) - Stream encryption & decryption with libsodium and protobuf 

## Database

* [BrightstarDb](https://github.com/BrightstarDB/BrightstarDB) - BrightstarDB is a native .NET RDF triple store
* [RavenDB](https://github.com/ravendb/ravendb) - A linq enabled document database for .NET

## Database Drivers

* [MySQL Connector](https://dev.mysql.com/downloads/connector/net/) - Connector/Net is a fully-managed ADO.NET driver for MySQL
* [Npgsql](https://github.com/npgsql/Npgsql) - .Net data provider for Postgresql
* [MongoDB](https://github.com/mongodb/mongo-csharp-driver) - Official MongoDB C# Driver
* [ServiceStack Redis](https://github.com/ServiceStack/ServiceStack.Redis) - .NET's leading C# Redis Client
* [StackExchange Redis](https://github.com/StackExchange/StackExchange.Redis) - General purpose redis client from StackExchange
* [Cassandra](https://github.com/datastax/csharp-driver) - DataStax .NET Driver for Apache Cassandra
* [Couchbase](https://github.com/couchbase/couchbase-net-client) - Official couchbase .NET client library, based on the Enyim memcached client
* [Firebird.NET](http://sourceforge.net/projects/firebird/) - The .NET Data provider is written in C# and provides a high-performance, native implementation of the Firebird API

## Deployment

* [Unfold](https://github.com/thomasvm/unfold) - Powershell-based deployment solution for .net web applications

## DirectX

* [SlimDX](http://www.slimdx.org) - DirectX framework wrapper for .NET applications

## Distributed Computing

* [Project Orleans](https://github.com/dotnet/orleans) - Orleans is a framework that provides a straight-forward approach to building distributed high-scale computing applications, without the need to learn and apply complex concurrency or other scaling patterns. It was created by Microsoft Research.
* [Akka.net](https://github.com/akkadotnet/akka.net) - Akka.NET is a port of the popular Java/Scala framework Akka to .NET. This is a community driven port and is not affiliated with Typesafe who makes the original Java/Scala version.

## Documentation

* [Sandcastle](http://shfb.codeplex.com/) - Sandcastle Help File Builder similar to NDoc
* [SharpDox](https://github.com/Geaz/sharpDox) - A c# documentation tool
* [F# Formatting](http://tpetricek.github.io/FSharp.Formatting/) - Tools for documenting F# and C# projects from F# Script files, Markdown documents and inline XML or Markdown comments
 
## E-Commerce and Payments

* [Paypal Merchant SDK](https://github.com/paypal/merchant-sdk-dotnet) - Official Paypal Merchant SDK for .NET
* [ServiceStack.Stripe](https://github.com/ServiceStack/Stripe) - Typed .NET clients for stripe.com REST APIs
* [Stripe.Net](https://github.com/jaymedavis/stripe.net) - Stripe.net is a full service .net api for http://stripe.com. 

## Environment Management

* [KVM](https://github.com/aspnet/kvm)

## ETL

* [Reactive ETL](https://reactiveetl.codeplex.com/) - Reactive ETL is a rewrite of Rhino ETL using the reactive extensions for .NET

## Game

* [MonoGame](https://github.com/mono/MonoGame) - One framework for creating powerful cross-platform games
* [CocosSharp](https://github.com/mono/CocosSharp) - CocosSharp is a C# implementation of the Cocos2D and Cocos3D APIs that runs on any platform where MonoGame runs

## Gis

 * [NetTopologySuite](https://github.com/NetTopologySuite/NetTopologySuite/)  A .NET GIS solution that is fast and reliable for the .NET platform
 * [SharpMap](https://sharpmap.codeplex.com/) An easy-to-use mapping library for use in web and desktop applications

## Git Tools

* [LibGit2Sharp](https://github.com/libgit2/libgit2sharp) - LibGit2Sharp brings all the might and speed of libgit2, a native Git implementation, to the managed world of .Net and Mono.
* [posh-git](https://github.com/dahlbyk/posh-git) - A PowerShell environment for Git
* [GitVersion](https://github.com/Particular/GitVersion) - Generate a Semantic Version Number based on the state of your Git Repository
* [GitLink](https://github.com/CatenaLogic/GitLink) - let's users step through their code hosted on GitHub or BitBucket
* [NGit](https://github.com/mono/ngit) - NGit is a port of JGit to C#

## Graphics

* [Oxyplot](https://github.com/oxyplot/) - OxyPlot is a cross-platform plotting library for .NET
* [OpenTK](http://www.opentk.com/) - The Open Toolkit is an advanced, low-level C# library that wraps OpenGL, OpenCL and OpenAL

## GUI

* [MahApps.Metro](https://github.com/MahApps/MahApps.Metro) - Toolkit for creating Metro styled WPF apps
* [Callisto](https://github.com/timheuer/callisto) - A control toolkit for Windows 8 XAML applications. Contains some UI controls to make it easier to create Windows UI style apps for the Windows Store in accordance with Windows UI guidelines.
* [ObjectListView](http://objectlistview.sourceforge.net/cs/index.html) - ObjectListView is a C# wrapper around a .NET ListView. It makes the ListView much easier to use and teaches it some new tricks
* [DockPanelSuite](http://dockpanelsuite.com/) - The Visual Studio inspired docking library for .NET WinForms
* [AvalonEdit](https://github.com/icsharpcode/AvalonEdit) - The WPF-based text editor component used in SharpDevelop
* [XWT](https://github.com/mono/xwt) - A cross-platform UI toolkit for creating desktop applications with .NET and Mono
* [Gtk#](https://github.com/mono/gtk-sharp) - Gtk# is a Mono/.NET binding to the cross platform Gtk+ GUI toolkit and the foundation of most GUI apps built with Mono
* [MaterialDesignInXamlToolkit](https://github.com/ButchersBoy/MaterialDesignInXamlToolkit) - Toolkit for creating Material styled WPF apps
* [Eto.Forms](https://github.com/picoe/Eto) - Cross platform GUI framework for desktop and mobile applications in .NET and Mono
* [Dragablz](https://github.com/ButchersBoy/Dragablz) - Dragable, tearable WPF tab control (similar to Chrome) which supports layouts and is full themeable, including themese compatible with MahApps and Material Design.

## HTML and CSS

* [AngleSharp](https://github.com/FlorianRappl/AngleSharp) - Complete HTML5 DOM and CSS3 OM construction
* [CsQuery](https://github.com/jamietre/CsQuery) - HTML5 parser with jQuery style DOM interaction
* [ExCSS](https://github.com/TylerBrinks/ExCSS) - CSS3 parser Library for C#
* [FluentBootstrap](http://fluentbootstrap.com) - Makes the Bootstrap CSS framework easier to use from ASP.NET MVC or WebPages.
* [HtmlAgilityPack](http://htmlagilitypack.codeplex.com/) - an agile HTML parser that builds a read/write DOM and supports plain XPATH or XSLT

## HTTP

* [RestSharp](https://github.com/restsharp/RestSharp) - Simple REST and HTTP API Client for .NET
* [EasyHttp](https://github.com/hhariri/EasyHttp) - Http Library for C#
* [Refit](https://github.com/paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET

## IDE

* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop) - A free IDE for .NET programming languages
* [MonoDevelop](https://github.com/mono/monodevelop) - MonoDevelop is a cross platform IDE mostly aimed at Mono/.NET developers
* [Visual Studio Express](http://www.visualstudio.com/en-us/products/visual-studio-express-vs.aspx) - The free lightweight version of Visual Studio for .NET programming.
* [Visual Studio Community](http://msdn.microsoft.com/en-us/visual-studio-community-vs.aspx) - A full-Featured IDE - Free
* [Waf DotNetPad](http://dotnetpad.codeplex.com) - A simple and fast code editor that makes fun program with C# or Visual Basic.
* [Visual Studio Code](https://code.visualstudio.com/) - Excellent free editor from Microsoft, based on GitHub Atom.

## Image Processing

* [ImageResizer](http://imageresizing.net/) - Add commands to image URLs to get altered versions in milliseconds. Resizing, editing etc of images in real-time.
* [ImageProcessor](http://imageprocessor.org/) - Open-source .NET library to manipulate images on-the-fly.
* [DotImaging](https://github.com/dajuric/dot-imaging) - The only .NET image IO framework you need.

## Install tools

* [Wix Toolset](http://wixtoolset.org/) - The most powerful set of tools available to create your Windows installation experience

## Internationalization

* [i18n](https://github.com/turquoiseowl/i18n) - Smart internationalization for ASP.NET MVC

## Interoperability

* [CppSharp](https://github.com/mono/CppSharp) - Tools to surface C++ APIs to C#
* [Sharpen](https://github.com/mono/sharpen) - Sharpen is an Eclipse plugin created by db4o that allows you to convert your Java project into C#
* [CXXI](https://github.com/mono/cxxi) - C++ interop framework

## IoC

* [Castle Windsor](https://github.com/castleproject/Windsor) - Castle Windsor is best of breed, mature Inversion of Control container available for .NET and Silverlight
* [Unity](https://unity.codeplex.com/) - Lightweight extensible dependency injection container with support for constructor, property, and method call injection
* [Autofac](https://github.com/autofac/Autofac) - An addictive .NET IoC container
* [Ninject](https://github.com/ninject/ninject) - The ninja of .net dependency injectors
* [StructureMap](https://structuremap.github.io/) - The original IoC/DI Container for .Net
* [Spring.Net](https://github.com/spring-projects/spring-net) - Spring.NET is an open source application framework that makes building  enterprise .NET applications easier
* [LightInject](https://github.com/seesharper/LightInject) - A ultra lightweight IoC container
* [TinyIoC](https://github.com/grumpydev/TinyIoC) - Single-file, easy and cross-platform IoC container

## Logging

* [Essential Diagnostics](http://essentialdiagnostics.codeplex.com/) - Extends the inbuilt features of System.Diagnostics namespace to provide flexible logging
* [NLog](https://github.com/nlog/NLog/) - NLog - Advanced .NET and Silverlight Logging
* [ELMAH](https://code.google.com/p/elmah/) - Official ELMAH site
* [Elmah MVC](https://github.com/alexanderbeletsky/elmah-mvc) - Elmah for MVC
* [Log4Net](https://logging.apache.org/log4net/) - The Apache log4net library is a tool to help the programmer output log statements to a variety of output targets
* [Serilog](https://github.com/serilog/serilog) - A no-nonsense logging library for the NoSQL era. Combines the best of traditional and structured diagnostic logging in an easy-to-use package.
* [StackExchange.Exceptional](https://github.com/NickCraver/StackExchange.Exceptional) - Error handler used for the Stack Exchange network
* [Semantic Logging Application Block (SLAB)](http://slab.codeplex.com/) - Extends the inbuilt features of System.Diagnostics.Tracing namespace (EventSource class) to log to several sinks including Azure Tables, Databases, files (JSON, XML, text). Supports in-process and out-of-process logging through ETW, and Rx for real-time filtering/aggregating of events.

## Machine Learning and Data Science
* [Accord.NET](http://accord-framework.net/) - Machine learning framework combined with audio and image processing libraries (computer vision, computer audition, signal processing and statistics).
* [Accord.NET Extensions](https://github.com/dajuric/accord-net-extensions) - Advanced image processing and computer vision algorithms made as fluent extensions.
* [AForge.NET](http://www.aforgenet.com/) - Framework for developers and researchers in the fields of Computer Vision and Artificial Intelligence (image processing, neural networks, genetic algorithms, machine learning, robotics).
* [Deedle](http://bluemountaincapital.github.io/Deedle/) - Data frame and (time) series library for exploratory data manipulation with C# and F# support
* [FsLab](http://www.fslab.org) - A collection of data science and machine learning libraries for F# and .NET
* [R Provider](http://bluemountaincapital.github.io/FSharpRProvider/) - Type provider that exposes R packages and functions in a type-safe way to F# callers 
* [F# Data](http://fsharp.github.io/FSharp.Data/) - F# type providers for accessing XML, JSON, CSV and HTML files (based on sample documents) and for accessing WorldBank data

## Markdown Processors
* [MarkdownSharp](https://code.google.com/p/markdownsharp/) - Open source C# implementation of Markdown processor, as featured on Stack Overflow.
* [F# Formatting](http://tpetricek.github.io/FSharp.Formatting/) - Tools for documenting F# and C# projects.  The library contains extensible Markdown parser as a core component.

## Mail

* [FluentEmail](https://github.com/lukencode/FluentEmail) - A Fluent Wrapper for System.Net.Mail with razor templating support.
* [MailKit](https://github.com/jstedfast/MailKit) - A complete cross-platform mail stack including IMAP, POP3, SMTP, authentication and more. Built on top of MimeKit.
* [MimeKit](https://github.com/jstedfast/MimeKit) - A cross-platform .NET MIME creation and parser library with support for S/MIME, PGP, TNEF and Unix mbox spools.

## Mathematics

* [MathNet](http://www.mathdotnet.com/) - Math.NET is an opensource initiative to build and maintain toolkits covering fundamental mathematics, targetting advanced but also every day needs of .Net developers

## Media

* [TagLib#](https://github.com/mono/taglib-sharp) - TagLib# (aka taglib-sharp) is a library for reading and writing
metadata in media files, including video, audio, and photo formats

## Metrics

* [C# StatsD Client](https://github.com/goncalopereira/statsd-csharp-client) - C# client for Etsy's StatsD

## Misc
* [Polly](https://github.com/michael-wolfenden/Polly) - Express transient exception handling policies such as Retry, Retry Forever, Wait andRetry or Circuit Breaker in a fluent manner. (.NET 3.5 / 4.0 / 4.5 / PCL / Xamarin) 
* [AzureCrawler](https://github.com/yagopv/AzureCrawler) - Take HTML Snapshots for your Angular, Ember, Durandal or any JavaScript applications
* [LINQPad](http://linqpad.net) - a C#/VB/F# scratchpad that instantly executes any expression, statement block or program with rich output formatting and a wealth of features. Also lets you interactively query databases in LINQ. [$]
* [.NET Fiddle](https://dotnetfiddle.net/) - Write, compile and run C# code in the browser. The C# equivalent of JSFiddle.
* [Humanizer](https://github.com/MehdiK/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities
* [ScriptCS](https://github.com/scriptcs/scriptcs) - Write C# apps with a text editor, nuget and the power of Roslyn!
* [CSScript](http://www.csscript.net/) - CS-Script is a CLR based scripting system which usesC# as a programming language. CS-Script currently targets Microsoft implementation of CLR (.NET 2.0/3.0/3.5/4.0/4.5) with full support on Mono. Comes with many additional features, such as script hosting.
* [ILSpy](http://ilspy.net/) - ILSpy is the open-source .NET assembly browser and decompiler
* [BitSharp](https://github.com/pmlyon/BitSharp) - C# Bitcoin Node

## MVVM

* [Caliburn.Micro](https://github.com/Caliburn-Micro/Caliburn.Micro) - A small, yet powerful framework, designed for building applications across all XAML platforms. Its strong support for MV* patterns will enable you to build your solution quickly, without the need to sacrifice code quality or testability.
* [MVVM Light Toolkit](https://mvvmlight.codeplex.com/) - The main purpose of the toolkit is to accelerate the creation and development of MVVM applications in WPF, Silverlight, Windows Store (RT) and for Windows Phone
* [Catel](https://catel.codeplex.com/) - Catel is an application development platform with the focus on MVVM (WPF, Silverlight, Windows Phone and WinRT) and MVC (ASP.NET MVC). The core of Catel contains an IoC container, models, validation, memento, message mediator, argument checking, etc.
* [UpdateControls](http://updatecontrols.net/cs/) - Update Controls does not require that you implement INotifyPropertyChanged or declare a DependencyProperty. It connects controls directly to CLR properties. This makes it perfect for the Model/View/ViewModel pattern.
* [ReactiveUI](https://github.com/reactiveui/reactiveui/) - An MVVM framework for .NET that integrates the Reactive Extensions (Rx) framework, enabling developers to build elegant, testable applications using WPF, Windows Store Apps, WP8 or Xamarin.
* [Okra App Framework](http://okraframework.github.io) - An app centric MVVM framework for Windows 8.1 built with dependency injection in mind, including a full set of Visual Studio MVVM templates.
* [WPF Application Framework (WAF)](http://waf.codeplex.com) - A lightweight Framework that helps you to create well structured WPF Applications. It supports you in applying a Layered Architecture and the Model-View-ViewModel pattern.
* [MVVMCross](https://github.com/MvvmCross/MvvmCross) - Cross-platform mvvm mobile development framework for WPF, Silverlight for WP7 and WP8, Mono for Android, MonoTouch for iOS, Windows Universal projects (WPA8.1 and Windows 8.1 Store apps). Makes extensive use of Portable Class Libraries (PCL) to provide maintainable cross platform C# native applications.
* [Stylet](https://github.com/canton7/stylet/) - Minimal MVVM framework inspired by Caliburn Micro, with good documentation, high test coverage, and its own IoC container

## Office

* [ClosedXML](https://closedxml.codeplex.com/) - ClosedXML makes it easier for developers to create Excel 2007/2010 files
* [NPOI](http://npoi.codeplex.com/) - This project is the .NET version of POI Java project at http://poi.apache.org/. 
* [EPPlus](http://epplus.codeplex.com/) - EPPlus is a .net library that reads and writes Excel 2007/2010 files using the Open Office Xml format (xlsx).
* [Open XML SDK](https://github.com/officedev/open-xml-sdk) - The Open XML SDK provides open-source libraries for working with Open XML Documents (DOCX, XLSX, and PPTX).

## ORM

* [Entity Framework](https://github.com/aspnet/EntityFramework) - Object-relational mapper that enables .NET developers to work with relational data using domain-specific objects
* [BL Toolkit](https://github.com/igor-tkachev/bltoolkit) - Business Logic Toolkit for .NET
* [Dapper](https://github.com/StackExchange/dapper-dot-net)
* [Dapper Extensions](https://github.com/tmsmith/Dapper-Extensions) - Small library that complements Dapper by adding basic CRUD operations (Get, Insert, Update, Delete) for your POCOs
* [NHibernate](https://github.com/nhibernate) - NHibernate Object Relational Mapper
* [FluentMigrator](https://github.com/schambers/fluentmigrator) - Fluent Migrations framework for .net
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) - Light, simple and fast convention-based POCO ORM
* [Massive](https://github.com/robconery/massive) - A small, happy, data access tool that will love you forever.
* [LINQ to DB](https://github.com/linq2db/linq2db) - The fastest LINQ database access library offering a simple, light, fast, and type-safe layer between your POCO objects and your database. 

## Package Management

* [NuGet](https://www.nuget.org/) - THE .NET Package Manager
* [OpenWrap](https://github.com/openrasta/openwrap) - OpenWrap Package Manager
* [MyGet](http://www.myget.org/) - Hosted Package Repository for NuGet, NPM, Bower and VSIX. Also provides CI as-a-Service. **[[Free for OSS](https://www.myget.org/opensource)]** **[$]**

## PDF

* [ITextSharp](https://github.com/itext/itextsharp) - iText is a PDF library that allows you to CREATE, ADAPT, INSPECT and MAINTAIN documents in the Portable Document Format (PDF)**[$]****[Free for OSS]**

## Profiler

* [MiniProfiler](https://github.com/MiniProfiler/dotnet) - A simple but effective mini-profiler for ASP.NET websites
* [Glimpse](https://github.com/glimpse/glimpse) - The open source diagnostics platform for the web

## Queue

* [NServiceBus](https://github.com/Particular/NServiceBus) - The most popular service bus for .NET
* [Hangfire](https://github.com/HangfireIO/Hangfire) - Incredibly easy way to perform fire-and-forget, delayed and recurring tasks inside ASP.NET applications
* [RabbitMQ.NET](http://hg.rabbitmq.com/rabbitmq-dotnet-client/) - Implementation of an AMQP client library for C#, and a binding exposing AMQP services via WCF
* [NetMQ](https://github.com/zeromq/netmq) - NetMQ is 100% native C# port of ZeroMQ
* [MassTransit](https://github.com/MassTransit/MassTransit) - MassTransit is lean service bus implementation for building loosely coupled applications using the .NET Framework.
* [Rebus] (https://github.com/rebus-org/Rebus) - Rebus is a lean service bus implementation for .NET, similar in nature to NServiceBus and MassTransit, only leaner
* [EasyNetQ](https://github.com/mikehadlow/EasyNetQ) - An easy to use .NET API for RabbitMQ

## Scheduling

* [QuartzNet](https://github.com/quartznet/quartznet) - Quartz Enterprise Scheduler .NET

## SDK and API Clients

* [AWS SDK](https://github.com/aws/aws-sdk-net) - The AWS SDK for .NET enables .NET developers to easily work with Amazon Web Services
* [Azure SDK Tools](https://github.com/Azure/azure-sdk-tools) - A set of PowerShell cmdlets for developers and administrators to develop, deploy and manage Microsoft Azure applications
* [Octokit.NET](https://github.com/octokit/octokit.net) - A GitHub API client library for .NET
* [DropNet](https://github.com/DropNet/DropNet) - Client Library for the Dropbox API

## Search

* [Elasticsearch .NET](https://github.com/elasticsearch/elasticsearch-net) - Elasticsearch.Net & NEST
* [PlainElastic.Net](https://github.com/Yegoroff/PlainElastic.Net) - Plain .Net client for ElasticSearch
* [SolrNet](https://github.com/mausch/SolrNet) - Solr client for .Net
* [Lucene.net](http://lucenenet.apache.org/) - Lucene.Net is a port of the Lucene search engine library, written in C# and targeted at .NET runtime users

## Serialization

* [Protobuf.NET](https://code.google.com/p/protobuf-net/) - Protocol buffers is the name of the binary serialization format used by Google for much of their data communications
* [Json.NET](https://github.com/JamesNK/Newtonsoft.Json) - Popular high-performance JSON framework for .NET
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) - JSON, JSV and CSV Text Serializers used in servicestack.net
* [Msgpack-Cli](https://github.com/msgpack/msgpack-cli) - MessagePack implementation for Common Language Infrastructure
* [Jil](https://github.com/kevin-montrose/Jil) - Fast .NET JSON Serializer, built on Sigil (used by StackOverflow)
* [ProtoBuf](https://github.com/hultqvist/ProtoBuf) - Generate C# code for protocol buffer serialization from a .proto specification.
* [F# Data](http://fsharp.github.io/FSharp.Data/) - F# type providers for accessing XML, JSON, CSV and HTML files (based on sample documents) and for accessing WorldBank data

## State machines

* [Stateless](https://github.com/nblumhardt/stateless) - Create state machines and lightweight state machine-based workflows directly in .NET code
* [Automatonymous](https://github.com/MassTransit/Automatonymous) - A state machine library for .Net - allows you to write fluent style state machines

## Style Guide

* [C# Style Guide](http://stackoverflow.com/questions/4678178/style-guide-for-c) - StackOverflow Q & A on style guides
* [C# Coding Conventions](http://msdn.microsoft.com/en-us/library/vstudio/ff926074.aspx) - Official MSDN C# code conventions

## Template Engine

* [RazorEngine](https://github.com/Antaris/RazorEngine) - Open source templating engine based on Microsoft's Razor parsing engine
* [Nustache](https://github.com/jdiamond/Nustache) - Open source library for logic-less templates
* [DotLiquid](https://github.com/dotliquid/dotliquid) - C# port of the Ruby Liquid templating language

## Testing

* [NUnit](https://github.com/nunit/nunit-framework)
* [xUnit](https://github.com/xunit/xunit) - xUnit.net is a free, open source, community-focused unit testing tool for the .NET Framework
* [SpecFlow](https://github.com/techtalk/SpecFlow/) - Binding business requirements to .Net code
* [AutoFixture](https://github.com/AutoFixture/AutoFixture) - AutoFixture is an open source framework for .NET designed to minimize the 'Arrange' phase of your unit tests
* [Moq](https://github.com/Moq/moq4) - The most popular and friendly mocking framework for .NET
* [Machine.Specifications](https://github.com/machine/machine.specifications) - Machine.Specifications (MSpec) is a context/specification framework that removes language noise and simplifies tests.
* [Rhino Mocks](https://github.com/ayende/rhino-mocks) - Dynamic Mocking Framework for .NET
* [Fluent Assertions](https://github.com/dennisdoomen/fluentassertions) - A set of .NET extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style test
* [NSubstitute](http://nsubstitute.github.io/) - A friendly substitute for .NET mocking frameworks
* [NBuilder](https://github.com/garethdown44/nbuilder) - Rapid generation of test objects

## Visual Studio Plugins

* [Web Essentials](https://github.com/madskristensen/WebEssentials2013) - Web Essentials extends Visual Studio with lots of new features that web developers have been missing for many years
* [VsVIM](https://github.com/jaredpar/VsVim) - VIM in Visual Studio
* [Nuget Package Manager](http://visualstudiogallery.msdn.microsoft.com/27077b70-9dad-4c64-adcf-c7cf6bc9970c) - NuGet is the package manager for the Microsoft development platform including .NET
* [SideWaffle](https://github.com/ligershark/side-waffle) - A collection of Item Templates for Visual Studio 2012/2013 that makes any web developer's life much easier
* [Resharper](http://www.jetbrains.com/resharper/) - Developer Productivity Tool for Visual Studio **[$]**
* [CodeContracts](https://github.com/Microsoft/CodeContracts) - Source code for the CodeContracts tools for .NET
* [Git Diff Margin](https://github.com/laurentkempe/GitDiffMargin) - Displays live Git changes of the currently edited file on Visual Studio margin and scroll bar

## Web Frameworks

* [ASP.NET MVC](https://aspnetwebstack.codeplex.com/) - ASP.NET is a free web framework for building great web sites and applications
* [NancyFx](https://github.com/NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .Net and Mono
* [IISNode](https://github.com/tjanczuk/iisnode) - Host NodeJS applications in IIS

## Web Servers

* [EmbedIO](https://github.com/unosquare/embedio) - Web server built on Mono and cross-platform
* [XSP](https://github.com/mono/xsp) - Mono's ASP.NET hosting server. This module includes an Apache Module, a FastCGI module that can be hooked to other web servers as well as a standalone server used for testing (similar to Microsoft's Cassini)

## WebSocket

* [SignalR](https://github.com/SignalR/SignalR) - Library for ASP.NET developers that makes it incredibly simple to add real-time web functionality to your applications
* [Fleck](https://github.com/statianzo/Fleck) - Fleck is a WebSocket server implementation in C#. Branched from the Nugget project
* [Websocket-Sharp](https://github.com/sta/websocket-sharp) - A C# implementation of the WebSocket protocol client and server
* [XSockets](http://xsockets.net/) - Provides a great set of tools for you to build real-time applications on the Microsoft.NET plattform and much more
* [WebSocket4NET](https://websocket4net.codeplex.com) - WebSocket client for .NET 2.0+, Xamarin, Mono, Silverlight, Windows Phone, & WinRT

## Windows Services

* [TopShelf](https://github.com/Topshelf/Topshelf) - An easy service hosting framework for building Windows services using .NET

# Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.
