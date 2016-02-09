# Awesome .NET!

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Join the chat at https://gitter.im/quozd/awesome-dotnet](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/quozd/awesome-dotnet?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A collection of awesome .NET libraries, tools, frameworks, and software.

Inspired by [awesome-ruby](https://github.com/markets/awesome-ruby), [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) and [ruby-bookmarks](https://github.com/dreikanter/ruby-bookmarks).

Contributions are always welcome! Please take a look at the [contribution guidelines and quality standard](https://github.com/quozd/awesome-dotnet/blob/master/CONTRIBUTING.md) pages first. We accept proprietary and commercial software too.

Thanks to all [contributors](https://github.com/quozd/awesome-dotnet/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

* [Awesome DotNet](#awesome-dotnet)
  * [API](#api)
  * [Application Frameworks](#application-frameworks)
  * [Application Templates](#application-templates)
  * [Artificial Intelligence](#artificial-intelligence)
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
  * [DateTime](#datetime)
  * [Decompilation](#decompilation)
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
  * [Micro Framework](#micro-framework)
  * [Minification](#minification)
  * [Misc](#misc)
  * [MVVM](#mvvm)
  * [Office](#office)
  * [ORM](#orm)
  * [Package Management](#package-management)
  * [PDF](#pdf)
  * [Profiler](#profiler)
  * [Push Notifications](#push-notifications)
  * [Queue](#queue)
  * [Reactive Programming](#reactive-programming)
  * [Scheduling](#scheduling)
  * [SDK and API Clients](#sdk-and-api-clients)
  * [Search](#search)
  * [Serialization](#serialization)
  * [State machines](#state-machines)
  * [Static Site Generators](#static-site-generators)
  * [Style Guide](#style-guide)
  * [Template Engine](#template-engine)
  * [Testing](#testing)
  * [Trading](#trading)
  * [Visual Studio Plugins](#visual-studio-plugins)
  * [Web Frameworks](#web-frameworks)
  * [Web Servers](#web-servers)
  * [WebSocket](#websocket)
  * [Windows Services](#windows-services)
  * [Other Lists](#other-lists)

* [Other Awesome Lists](#other-awesome-lists)

## API

* Frameworks
  * [NancyFx](https://github.com/NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .Net and Mono
  * [ASP.NET WebAPI](http://www.asp.net/web-api) - Framework that makes it easy to build HTTP services that reach a broad range of clients, including browsers and mobile devices
  * [Breeze](http://breeze.github.io/doc-net/) - Api framework enabling rich data access by using the OData 3 protocol. Client libraries available for Javascript and C#.
  * [ServiceStack](https://github.com/ServiceStack/ServiceStack) - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all
  * [Nelibur](https://github.com/Nelibur/Nelibur) - Nelibur is message based web service framework on the pure WCF. Nelibur simplifies creating high-performance and message based web services and you certainly have all the power of the WCF.

* [WebAPI Contrib](https://github.com/WebApiContrib/WebAPIContrib) - Collection of open source projects to help improve your work with ASP.NET Web API

## Application Frameworks

* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) - A starting point for new modern ASP.NET MVC web applications with best practices and most popular tools.
* [Orleans](https://github.com/dotnet/orleans) - Orleans is a framework that provides a straight-forward approach to building distributed high-scale computing applications, without the need to learn and apply complex concurrency or other scaling patterns
* [CoreFX](https://github.com/dotnet/corefx) -  The corefx repo contains the library implementation (called "CoreFX") for .NET Core. It includes System.Collections, System.IO, System.Xml and many other components. It builds and runs on Windows. You can 'watch' the repo to see Linux and Mac support being added over the next few months.
* [CSLA .NET](https://github.com/MarimerLLC/csla) - business layer development framework http://cslanet.com/
* [Mono](https://github.com/mono/mono) - Mono open source ECMA CLI, C# and .NET implementation
* [Mono-Addins](https://github.com/mono/mono-addins) - Mono.Addins is a generic framework for creating extensible applications, and for creating add-ins which extend those applications
* [peasy](https://github.com/peasy/Peasy.NET) - Peasy is a middle tier framework that offers an easy to use and flexible rules engine and was designed to address common challenges such as concurrency handling, transactional support, fault tolerance, threading, scalability, async and multiple client support, and easy testability, all without a huge learning curve!
* [Spring.Net](https://github.com/spring-projects/spring-net) - Spring.NET is an open source application framework that makes building  enterprise .NET applications easier

## Application Templates

* [MVC.Template](https://github.com/NonFactors/MVC5.Template) - ASP.NET MVC 5 project starter template
* [ProjectScaffold](https://github.com/fsprojects/ProjectScaffold) - A prototypical .NET solution recommended by the F# Foundation---includes file system setup, Paket for dependencies and FAKE for build/test automation. By default, build process also compiles documentation and generates NuGet packages.
* [Side-Waffle](https://github.com/LigerShark/side-waffle) - Large collection of useful templates for Web and Desktop development.
* [Template10](https://github.com/Windows-XAML/Template10) - Windows 10 templates with design patterns.

## Artificial Intelligence
* [AIMLBot (Program#)](http://aimlbot.sourceforge.net/) - A small, fast, standards-compliant yet easily customizable implementation of an AIML (Artificial Intelligence Markup Language) based chatter bot in C#.
* [SIML](http://simlbot.com/) - Synthetic Intelligence Markup Language, a next generation Chatbot & Digital Assistant Language.

## Assembly Manipulation

* [dnSpy](https://github.com/0xd4d/dnSpy) - dnSpy is a .NET assembly editor, decompiler, and debugger forked from ILSpy.
* [Fody](https://github.com/Fody/Fody) - Extensible tool for weaving .net assemblies
* [Mono.Cecil](https://github.com/jbevain/cecil) - Cecil is a library to generate and inspect programs and libraries in the ECMA CIL form.

## Assets

* [Cassette](https://github.com/andrewdavey/cassette) - Manages .NET web application assets (scripts, css and templates)
* [NodeAssets](https://github.com/ajorkowski/NodeAssets) - Asset Manager for .net that has live css updates using SignalR and can optionally leverage NodeJS compilers
* [Bundle Transformer](http://bundletransformer.codeplex.com/) - Modular extension for [Microsoft ASP.NET Web Optimization Framework](http://aspnetoptimization.codeplex.com/). Its modules supports LESS, Sass, CoffeeScript, TypeScript, Mustache, Handlebars, Autoprefixer along with a bunch of different JS and CSS minifiers.
* [Bundler](https://github.com/ServiceStack/Bundler) - Compile & Minify Less/Sass/Stylus/Css/JS/CoffeeScript/LiveScript files. Integrates with MVC and ServiceStack
* [SquishIt](https://github.com/jetheredge/SquishIt) - Lets you *easily* bundle some css and javascript

## Authentication and Authorization

* [ASP.NET Identity](https://aspnetidentity.codeplex.com/) - New membership system for ASP.NET applications
* [DotNetOpenAuth](https://github.com/DotNetOpenAuth/DotNetOpenAuth) - A C# implementation of the OpenID, OAuth and InfoCard protocols
* [Logibit Hawk](https://github.com/logibit/logibit.hawk/) - A F# [Hawk](https://github.com/hueniverse/hawk#usage-example) authentication library
* [IdentityModel](https://github.com/IdentityModel) - Helper library for identity & access control in .NET 4.5 and MVC4/Web API.
* [IdentityServer](https://github.com/IdentityServer) - Extensible OAuth2 and OpenID Connect provider framework.
* [OAuth](https://github.com/danielcrenna/oauth) - A very lightweight library for generating OAuth 1.0a signatures written in C#

## Build Automation

* [Psake](https://github.com/psake/psake) - .NET-based build automation tool written in PowerShell
* [FAKE](https://github.com/fsharp/FAKE) - F# Make, a cross platform build automation system
* [Invoke-Build](https://github.com/nightroman/Invoke-Build) - PowerShell build and test automation tool inspired by Psake.
* [MSBuild](https://github.com/Microsoft/msbuild) - The Microsoft Build Engine (MSBuild) is the build platform for .NET and Visual Studio
* [Cake](https://github.com/cake-build/cake) - Cake (C# Make) is a cross platform build automation system with a C# DSL.

## Caching

* [CacheCow](https://github.com/aliostad/CacheCow) - An ASP.NET Web API HTTP caching implementation both on client and server
* [Akavache](https://github.com/akavache/Akavache) - An asynchronous, persistent key-value store
* [CacheManager](https://github.com/MichaCo/CacheManager) - A common interface and abstraction layer for caching.

## CLI

* [Command Line Parser](https://github.com/gsscoder/commandline) - The Command Line Parser Library offers to CLR applications a clean and concise API for manipulating command line arguments and related tasks
* [Fluent Command Line Parser](https://github.com/fclp/fluent-command-line-parser) - A simple, strongly typed .NET C# command line parser library using a fluent easy to use interface
* [Power Args](https://github.com/adamabdelhamed/PowerArgs) - PowerArgs converts command line arguments into .NET objects that are easy to program against. It also provides a ton of optional capabilities such as argument validation, auto generated usage, tab completion, and plenty of extensibility
* [UnionArgParser](https://github.com/fsprojects/Argu) - Declarative CLI argument & XML configuration parser for F# applications.

## CLR

* [CoreCLR](https://github.com/dotnet/coreclr) - The coreclr repo contains the complete runtime implementation (called "CoreCLR") for .NET Core. It includes RyuJIT, the .NET GC, native interop and many other components. It builds and runs on Windows. You can 'watch' the repo to see Linux and Mac support being added over the next few months.

## CMS

* [Composite C1](https://github.com/Orckestra/C1-CMS) - A web CMS that focus on UX and adaptability
* [mojoPortal ](https://mojoportal.codeplex.com/) - MojoPortal is an extensible, cross database, mobile friendly, web content management system (CMS) and web application framework written in C# ASP.NET
* [N2CMS](http://www.n2cms.com/) - Open source, lightweight, code-first CMS able to seamlessly integrate into any MVC project.
* [Orchard ](https://github.com/OrchardCMS/Orchard) - Free, open source, community-focused project aimed at delivering applications and reusable components on the ASP.NET platform
* [Piranha CMS](https://github.com/PiranhaCMS/Piranha) - Piranha is the fun, fast and lightweight .NET framework for developing cms-based web applications with an extra bite. It's built on ASP.NET MVC and Web Pages and is fully compatible with both Visual Studio and WebMatrix. http://piranhacms.org
* [Umbraco](https://github.com/umbraco/Umbraco-CMS) - Umbraco is a free open source Content Management System built on the ASP.NET platform

## Code Analysis and Metrics

* [CodeMaid](http://www.codemaid.net/) - Visual studio extension to cleanup, dig through and simplify C#, C++, F#, VB, PHP, JSON, XAML, XML, ASP, HTML, CSS, LESS, SCSS, JavaScript and TypeScript coding.
* [StyleCop](https://stylecop.codeplex.com/) - StyleCop analyzes C# source code to enforce a set of style and consistency rules
* [Gendarme](https://github.com/spouliot/gendarme) - Extensible rule-based tool to find problems in .NET applications and libraries
* [Metrics-Net](https://github.com/danielcrenna/metrics-net) - Capturing CLR and application-level metrics. So you know what's going on.

## Compiler

* [Bridge.NET](https://github.com/bridgedotnet/Bridge) - Open Source C# to JavaScript Compiler http://bridge.net/
* [ClojureCLR](https://github.com/clojure/clojure-clr) - A port of Clojure to the CLR, part of the Clojure project
* [F#](https://github.com/fsharp/fsharp/) -  The F# compiler, core library and tools - a functional programming language for safer, faster, better code writing.
* [FunScript](http://funscript.info/) - F# to JavaScript compiler with JQuery etc. mappings through a TypeScript type provider.
* [IronScheme](https://github.com/leppie/IronScheme) - R6RS Scheme compiler, runtime and many standard libraries
* [JSIL](https://github.com/sq/JSIL) - CIL to Javascript Compiler http://jsil.org/
* [Mono-basic](https://github.com/mono/mono-basic) - Visual Basic Compiler and Runtime
* [Nemerle](https://github.com/rsdn/nemerle) - Nemerle is a high-level statically-typed programming language for the .NET platform. It offers functional, object-oriented and imperative features. It has a simple C#-like syntax and a powerful meta-programming system. http://nemerle.org
* [Netjs](https://github.com/praeclarum/Netjs) - .NET to TypeScript and JavaScript compiler. Portable Class Libraries work great for this. You can even pass EXEs.
* [Roslyn](https://github.com/dotnet/roslyn) - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs. It enables building code analysis tools with the same APIs that are used by Visual Studio.
* [VisualFSharp](https://github.com/Microsoft/visualfsharp) - The Visual F# compiler and tools

## Compression

* [SharpCompress](https://github.com/adamhathcock/sharpcompress) - SharpCompress is a compression library for .NET/Mono/Silverlight/WP7 that can unrar, un7zip, unzip, untar unbzip2 and ungzip with forward-only reading and file random access APIs. Write support for zip/tar/bzip2/gzip are implemented
* [DotNetZip.Semverd](https://github.com/haf/DotNetZip.Semverd) - An open-source project that delivers a .NET library for handling ZIP files, and some associated tools. (fork of [**Unmaintained** DotNetZip](http://dotnetzip.codeplex.com))
* [SharpZipLib](http://icsharpcode.github.io/SharpZipLib/) - a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform

## Continuous Integration
* [TeamCity](http://www.jetbrains.com/teamcity/) - Ready to work, extensible and developer-friendly build server — out of the box **[$]**
* [CruiseControl.NET](http://www.cruisecontrolnet.org/) - an Automated Continuous Integration server, implemented using the .NET Framework
* [MyGet](http://www.myget.org/) - Continuous Integration and Deployment, Hosted Package Repository for NuGet, NPM, Bower and VSIX. **[[Free for OSS](https://www.myget.org/opensource)]** **[$]**
* [AppVeyor](http://www.appveyor.com/) - .NET Continuous Integration and Deployment as a service. **[$]** **[Free for OSS]**

## Cryptography

* [BouncyCastle](https://bouncycastle.org/) - Together with the .Net System.Security.Cryptography, the reference implementation for cryptographic algorithms on the CLR.
* [HashLib](http://hashlib.codeplex.com/) - HashLib is a collection of nearly all hash algorithms you've ever seen, it supports almost everything and is very easy to use
* [libsodium-net](https://github.com/adamcaudill/libsodium-net) - libsodium for .NET - A secure cryptographic library
* [StreamCryptor](https://github.com/bitbeans/StreamCryptor) - Stream encryption & decryption with libsodium and protobuf

## Database

* [BrightstarDb](https://github.com/BrightstarDB/BrightstarDB) - BrightstarDB is a native .NET RDF triple store
* [Event Store](https://github.com/EventStore/EventStore) - The open-source, functional database with Complex Event Processing in JavaScript. https://geteventstore.com
* [LiteDB](https://github.com/mbdavid/LiteDB) - A .NET NoSQL Document Store in a single data file - http://www.litedb.org
* [RavenDB](https://github.com/ravendb/ravendb) - A linq enabled document database for .NET

## Database Drivers

* [MySQL Connector](https://dev.mysql.com/downloads/connector/net/) - Connector/Net is a fully-managed ADO.NET driver for MySQL
* [Npgsql](https://github.com/npgsql/Npgsql) - .Net data provider for Postgresql
* [MongoDB](https://github.com/mongodb/mongo-csharp-driver) - Official MongoDB C# Driver
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver/) - A RethinkDB database driver in C# striving for 100% ReQL API compatibility and completeness.
* [ServiceStack Redis](https://github.com/ServiceStack/ServiceStack.Redis) - .NET's leading C# Redis Client
* [StackExchange Redis](https://github.com/StackExchange/StackExchange.Redis) - General purpose redis client from StackExchange
* [Cassandra](https://github.com/datastax/csharp-driver) - DataStax .NET Driver for Apache Cassandra
* [Couchbase](https://github.com/couchbase/couchbase-net-client) - Official couchbase .NET client library, based on the Enyim memcached client
* [Firebird.NET](http://sourceforge.net/projects/firebird/) - The .NET Data provider is written in C# and provides a high-performance, native implementation of the Firebird API

## Datetime

* [NodaTime](https://github.com/nodatime/nodatime) - Noda Time is an alternative date and time API for .NET. It helps you to think about your data more clearly, and express operations on that data more precisely. http://nodatime.org/

## Decompilation

* [ILSpy](http://ilspy.net/) - ILSpy is the open-source .NET assembly browser and decompiler
* [JustDecompile Engine](https://github.com/telerik/JustDecompileEngine) - The decompilation engine of [JustDecompile](http://www.telerik.com/products/decompiler.aspx)

## Deployment

* [Unfold](https://github.com/thomasvm/unfold) - Powershell-based deployment solution for .net web applications
* [DbUp](https://github.com/DbUp/DbUp) - .NET library that helps you to deploy changes to SQL Server databases. It tracks which SQL scripts have been run already, and runs the change scripts that are needed to get your database up to date

## DirectX

* [SlimDX](https://slimdx.org/) - DirectX framework wrapper for .NET applications
* [SharpDX](https://github.com/sharpdx/SharpDX) - SharpDX is an open-source project delivering the full DirectX API for .Net on all Windows platforms, allowing the development of high performance game, 2D and 3D graphics rendering as well as realtime sound application.

## Distributed Computing

* [Orleans](https://github.com/dotnet/orleans) - Orleans is a framework that provides a straight-forward approach to building distributed high-scale computing applications, without the need to learn and apply complex concurrency or other scaling patterns. It was created by Microsoft Research.
* [Akka.net](https://github.com/akkadotnet/akka.net) - Akka.NET is a port of the popular Java/Scala framework Akka to .NET. This is a community driven port and is not affiliated with Typesafe who makes the original Java/Scala version.

## Documentation

* [Sandcastle](http://shfb.codeplex.com/) - Sandcastle Help File Builder similar to NDoc
* [SharpDox](https://github.com/Geaz/sharpDox) - A c# documentation tool
* [SourceBrowser](https://github.com/KirillOsenkov/SourceBrowser) - Source browser website generator that powers http://referencesource.microsoft.com and http://source.roslyn.io
* [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle) - Seamlessly adds a swagger to WebApi projects!
* [F# Formatting](http://tpetricek.github.io/FSharp.Formatting/) - Tools for documenting F# and C# projects from F# Script files, Markdown documents and inline XML or Markdown comments

## E-Commerce and Payments

* [Paypal Merchant SDK](https://github.com/paypal/merchant-sdk-dotnet) - Official Paypal Merchant SDK for .NET
* [NopCommerce](https://nopcommerce.codeplex.com/) - nopCommerce. Free open-source ecommerce shopping cart (ASP.NET MVC)
* [ServiceStack.Stripe](https://github.com/ServiceStack/Stripe) - Typed .NET clients for stripe.com REST APIs
* [SmartStoreNET](https://github.com/smartstoreag/SmartStoreNET) - Free ASP.NET MVC Ecommerce Shopping Cart Solution http://www.smartstore.com/net/en
* [Stripe.Net](https://github.com/jaymedavis/stripe.net) - Stripe.net is a full service .net api for https://stripe.com/
* [BeYourMarket](https://github.com/beyourmarket/beyourmarket) - BeYourMarket is a peer-to-peer marketplace framework http://beyourmarket.com
* [Virto Commerce](https://github.com/VirtoCommerce/vc-community) - Virto Commerce is the second generation release and is the only enterprise level e-commerce product fully available under Open Source license. Virto Commerce is based on .NET 4.5 with extensive use of MVC, IoC, EF, Azure, Angular JS and many other cutting edge technologies. It can be deployed in Microsoft Cloud (Azure), Amazon Web Services (AWS) and on-premise. http://virtocommerce.com

## Environment Management

* [DNVM](https://github.com/aspnet/dnvm) - The .NET SDK Manager, a set of command line utilities to update and configure which runtime (DNX) to use.

## ETL

* [Reactive ETL](https://reactiveetl.codeplex.com/) - Reactive ETL is a rewrite of Rhino ETL using the reactive extensions for .NET

## Game

* [MonoGame](https://github.com/mono/MonoGame) - One framework for creating powerful cross-platform games
* [CocosSharp](https://github.com/mono/CocosSharp) - CocosSharp is a C# implementation of the Cocos2D and Cocos3D APIs that runs on any platform where MonoGame runs
* [Duality](https://github.com/AdamsLair/duality) - Duality is a 2D game development framework. Focused on modularity, comes with a visual editor.
* [Paradox](https://github.com/SiliconStudio/xenko) - Paradox Game Engine http://xenko.com/
* [Wave Engine](https://waveengine.net/Engine) - Wave engine is a free c# component-based modern game engine which allows you to create cross-platform games supporting kinect, oculusrift, vuforia, cardboard, leapmotion and much more. **[Free][Proprietary]**

## Gis

 * [NetTopologySuite](https://github.com/NetTopologySuite/NetTopologySuite/)  A .NET GIS solution that is fast and reliable for the .NET platform
 * [SharpMap](https://sharpmap.codeplex.com/) An easy-to-use mapping library for use in web and desktop applications

## Git Tools

* [Bonobo Git Server](https://github.com/jakubgarfield/Bonobo-Git-Server) - Bonobo Git Server for Windows is a web application you can install on your IIS and easily manage and connect to your git repositories. https://bonobogitserver.com/
* [GitExtensions](https://github.com/gitextensions/gitextensions) - GitExtensions is a shell extension, a Visual Studio 2008/2010/2012/2013 plugin and a standalone Git repository tool. http://gitextensions.github.io/
* [GitLink](https://github.com/GitTools/GitLink) - let's users step through their code hosted on GitHub or BitBucket
* [GitVersion](https://github.com/GitTools/GitVersion) - Generate a Semantic Version Number based on the state of your Git Repository
* [LibGit2Sharp](https://github.com/libgit2/libgit2sharp) - LibGit2Sharp brings all the might and speed of libgit2, a native Git implementation, to the managed world of .Net and Mono.
* [NGit](https://github.com/mono/ngit) - NGit is a port of JGit to C#
* [posh-git](https://github.com/dahlbyk/posh-git) - A PowerShell environment for Git

## Graphics

* [Oxyplot](https://github.com/oxyplot/) - OxyPlot is a cross-platform plotting library for .NET
* [OpenTK](http://www.opentk.com/) - The Open Toolkit is an advanced, low-level C# library that wraps OpenGL, OpenCL and OpenAL
* [NGraphics](https://github.com/praeclarum/NGraphics) - NGraphics is a cross-platform library for rendering vector graphics on .NET

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
* [Fluent.Ribbon](https://github.com/fluentribbon/Fluent.Ribbon) - Fluent Ribbon Control Suite is a library that implements an Office- and Windows 8-like Ribbon for WPF.
* [Perspex](https://github.com/Perspex/Perspex) - A multi-platform .NET UI framework.
* [MaterialSkin](https://github.com/IgnaceMaes/MaterialSkin) - Theming .NET WinForms, C# or VB.Net, to Google's Material Design Principles.

## HTML and CSS

* [AngleSharp](https://github.com/AngleSharp/AngleSharp) - Complete HTML5 DOM and CSS3 OM construction
* [CsQuery](https://github.com/jamietre/CsQuery) - HTML5 parser with jQuery style DOM interaction
* [dotless](https://github.com/dotless/dotless) - .NET Port of the ruby Less CSS lib http://www.dotlesscss.org
* [ExCSS](https://github.com/TylerBrinks/ExCSS) - CSS3 parser Library for C#
* [FluentBootstrap](http://fluentbootstrap.com) - Makes the Bootstrap CSS framework easier to use from ASP.NET MVC or WebPages.
* [HtmlAgilityPack](http://htmlagilitypack.codeplex.com/) - an agile HTML parser that builds a read/write DOM and supports plain XPATH or XSLT

## HTTP

* [Http.fs](https://github.com/relentless/Http.fs) - A functional HTTP client for `[F#]`.
* [RestSharp](https://github.com/restsharp/RestSharp) - Simple REST and HTTP API Client for .NET
* [Flurl.Http](http://tmenier.github.io/Flurl) - Fluent, portable, testable REST/HTTP client library
* [EasyHttp](https://github.com/hhariri/EasyHttp) - Http Library for C#
* [Refit](https://github.com/paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET
* [RestEase](https://github.com/canton7/RestEase) - Easy-to-use typesafe REST API client library, which is simple and customisable. Heavily inspired by Refit

## IDE

* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop) - A free IDE for .NET programming languages
* [MonoDevelop](https://github.com/mono/monodevelop) - MonoDevelop is a cross platform IDE mostly aimed at Mono/.NET developers
* [Visual Studio Express](https://www.visualstudio.com/en-us/products/visual-studio-express-vs.aspx) - The free lightweight version of Visual Studio for .NET programming.
* [Visual Studio Community](https://msdn.microsoft.com/en-us/visual-studio-community-vs.aspx) - A full-Featured IDE - Free
* [Waf DotNetPad](http://dotnetpad.codeplex.com) - A simple and fast code editor that makes fun program with C# or Visual Basic.
* [Visual Studio Code](https://code.visualstudio.com/) - Excellent free editor from Microsoft, based on GitHub Atom.

## Image Processing

* [ImageResizer](http://imageresizing.net/) - Add commands to image URLs to get altered versions in milliseconds. Resizing, editing etc of images in real-time.
* [ImageProcessor](http://imageprocessor.org/) - Open-source .NET library to manipulate images on-the-fly.
* [DynamicImage](http://dynamicimage.apphb.com/) - High-performance open-source image manipulation library for ASP.NET.
* [MetadataExtractor](https://github.com/drewnoakes/metadata-extractor-dotnet) - Extracts Exif, IPTC, XMP, ICC and other metadata from image files.
* [Emgu CV](http://www.emgu.com/wiki/index.php/Main_Page) - Cross-platform .NET wrapper for the OpenCV library.
* [DotImaging](https://github.com/dajuric/dot-imaging) - Minimalistic .NET imaging portable platform

## Install tools

* [Wix Toolset](http://wixtoolset.org/) - The most powerful set of tools available to create your Windows installation experience
* [Squirrel](https://github.com/squirrel/squirrel.windows) - Squirrel is both a set of tools and a library, to completely manage both installation and updating your Desktop Windows application.

## Internationalization

* [i18n](https://github.com/turquoiseowl/i18n) - Smart internationalization for ASP.NET MVC

## Interoperability

* [CefSharp](https://github.com/cefsharp/CefSharp) - .NET (WPF and Windows Forms) bindings for the Chromium Embedded Framework
* [CppSharp](https://github.com/mono/CppSharp) - Tools to surface C++ APIs to C#
* [Sharpen](https://github.com/mono/sharpen) - Sharpen is an Eclipse plugin created by db4o that allows you to convert your Java project into C#
* [CXXI](https://github.com/mono/cxxi) - C++ interop framework

## IoC

* [Castle Windsor](https://github.com/castleproject/Windsor) - Castle Windsor is best of breed, mature Inversion of Control container available for .NET and Silverlight
* [Unity](https://github.com/unitycontainer/unity) - Lightweight extensible dependency injection container with support for constructor, property, and method call injection
* [Autofac](https://github.com/autofac/Autofac) - An addictive .NET IoC container
* [Ninject](https://github.com/ninject/ninject) - The ninja of .net dependency injectors
* [StructureMap](https://structuremap.github.io/) - The original IoC/DI Container for .Net
* [Spring.Net](https://github.com/spring-projects/spring-net) - Spring.NET is an open source application framework that makes building  enterprise .NET applications easier
* [LightInject](https://github.com/seesharper/LightInject) - A ultra lightweight IoC container
* [TinyIoC](https://github.com/grumpydev/TinyIoC) - Single-file, easy and cross-platform IoC container
* [Simple Injector](https://github.com/simpleinjector/SimpleInjector) - Simple Injector is an easy-to-use Dependency Injection (DI) library for .NET 4+ that supports Silverlight 4+, Windows Phone 8, Windows 8 including Universal apps and Mono.

## Logging

* [Essential Diagnostics](http://essentialdiagnostics.codeplex.com/) - Extends the inbuilt features of System.Diagnostics namespace to provide flexible logging
* [NLog](https://github.com/nlog/NLog/) - NLog - Advanced .NET and Silverlight Logging
* [Logazmic](https://github.com/ihtfw/Logazmic) - Open source nlog viewer for Windows
* [ELMAH](https://elmah.github.io/) - Official ELMAH site
* [Elmah MVC](https://github.com/alexbeletsky/elmah-mvc) - Elmah for MVC
* [Logary](http://logary.github.io/) - Logary is a high performance, multi-target logging, metric, tracing and health-check library for mono and .Net. .Net's answer to DropWizard. Supports many targets, built for micro-services.
* [Log4Net](https://logging.apache.org/log4net/) - The Apache log4net library is a tool to help the programmer output log statements to a variety of output targets
* [Serilog](https://github.com/serilog/serilog) - A no-nonsense logging library for the NoSQL era. Combines the best of traditional and structured diagnostic logging in an easy-to-use package.
* [StackExchange.Exceptional](https://github.com/NickCraver/StackExchange.Exceptional) - Error handler used for the Stack Exchange network
* [Semantic Logging Application Block (SLAB)](http://slab.codeplex.com/) - Extends the inbuilt features of System.Diagnostics.Tracing namespace (EventSource class) to log to several sinks including Azure Tables, Databases, files (JSON, XML, text). Supports in-process and out-of-process logging through ETW, and Rx for real-time filtering/aggregating of events.

## Machine Learning and Data Science
* [Infer.NET](http://research.microsoft.com/en-us/um/cambridge/projects/infernet/default.aspx) - A framework for running Bayesian inference in graphical models. It can also be used for probabilistic programming. **[[Proprietary](http://research.microsoft.com/en-us/um/cambridge/projects/infernet/docs/Frequently%20Asked%20Questions.aspx)]** **[Free]** **[Research]**
* [Accord.NET](http://accord-framework.net/) - Machine learning framework combined with audio and image processing libraries (computer vision, computer audition, signal processing and statistics).
* [Accord.NET Extensions](https://github.com/dajuric/accord-net-extensions) - Advanced image processing and computer vision algorithms made as fluent extensions.
* [AForge.NET](http://www.aforgenet.com/) - Framework for developers and researchers in the fields of Computer Vision and Artificial Intelligence (image processing, neural networks, genetic algorithms, machine learning, robotics).
* [Deedle](http://bluemountaincapital.github.io/Deedle/) - Data frame and (time) series library for exploratory data manipulation with C# and F# support
* [FsLab](http://fslab.org/) - A collection of data science and machine learning libraries for F# and .NET
* [numl](https://github.com/sethjuarez/numl) - Designed to include the most popular supervised and unsupervised learning algorithms while minimizing the friction involved with creating the predictive models.
* [R Provider](http://bluemountaincapital.github.io/FSharpRProvider/) - Type provider that exposes R packages and functions in a type-safe way to F# callers
* [F# Data](http://fsharp.github.io/FSharp.Data/) - F# type providers for accessing XML, JSON, CSV and HTML files (based on sample documents) and for accessing WorldBank data

## Markdown Processors
* [MarkdownSharp](https://code.google.com/p/markdownsharp/) - Open source C# implementation of Markdown processor, as featured on Stack Overflow.
* [F# Formatting](http://tpetricek.github.io/FSharp.Formatting/) - Tools for documenting F# and C# projects.  The library contains extensible Markdown parser as a core component.
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - Implementation of CommonMark specification in C# for converting Markdown documents to HTML. Optimized for maximum performance and portability.

## Mail

* [FluentEmail](https://github.com/lukencode/FluentEmail) - A Fluent Wrapper for System.Net.Mail with razor templating support.
* [MailKit](https://github.com/jstedfast/MailKit) - A complete cross-platform mail stack including IMAP, POP3, SMTP, authentication and more. Built on top of MimeKit.
* [MimeKit](https://github.com/jstedfast/MimeKit) - A cross-platform .NET MIME creation and parser library with support for S/MIME, PGP, TNEF and Unix mbox spools.
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.

## Mathematics

* [MathNet](http://www.mathdotnet.com/) - Math.NET is an opensource initiative to build and maintain toolkits covering fundamental mathematics, targetting advanced but also every day needs of .Net developers

## Media

* [TagLib#](https://github.com/mono/taglib-sharp) - TagLib# (aka taglib-sharp) is a library for reading and writing
metadata in media files, including video, audio, and photo formats

## Metrics

* [C# StatsD Client](https://github.com/Pereingo/statsd-csharp-client) - C# client for Etsy's StatsD

## Micro Framework
* [.NET Micro Framework Interpreter](https://github.com/NETMF/netmf-interpreter) - Microsoft® .NET Micro Framework (NETMF) for developing embedded applications on small devices using Visual Studio

## Minification

* [Microsoft Ajax Minifier](http://ajaxmin.codeplex.com/) - Contains JS and CSS minifiers which have a highest performance, because its have been specifically designed for .NET. Optionally produce Source Maps for JS code.
* [Web Markup Minifier](http://webmarkupmin.codeplex.com/) - .NET library that contains a set of markup minifiers. The objective of this project is to improve the performance of web applications by reducing the size of HTML, XHTML and XML code.

## Misc
* [.NET Fiddle](https://dotnetfiddle.net/) - Write, compile and run C# code in the browser. The C# equivalent of JSFiddle.
* [CSharp Pad](http://csharppad.com) - A web based C# REPL with awesome code completion.
* [AzureCrawler](https://github.com/yagopv/AzureCrawler) - Take HTML Snapshots for your Angular, Ember, Durandal or any JavaScript applications
* [BitSharp](https://github.com/pmlyon/BitSharp) - C# Bitcoin Node
* [CSScript](http://www.csscript.net/) - CS-Script is a CLR based scripting system which usesC# as a programming language. CS-Script currently targets Microsoft implementation of CLR (.NET 2.0/3.0/3.5/4.0/4.5) with full support on Mono. Comes with many additional features, such as script hosting.
* [CsvHelper](https://github.com/JoshClose/CsvHelper) - Library to help reading and writing CSV files https://github.com/JoshClose/CsvHelper
* [FluentValidation](https://github.com/JeremySkinner/FluentValidation) - A small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules.
* [Humanizer](https://github.com/Humanizr/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities
* [LINQPad](http://www.linqpad.net) - a C#/VB/F# scratchpad that instantly executes any expression, statement block or program with rich output formatting and a wealth of features. Also lets you interactively query databases in LINQ. [$]
* [Polly](https://github.com/App-vNext/Polly) - Express transient exception handling policies such as Retry, Retry Forever, Wait andRetry or Circuit Breaker in a fluent manner. (.NET 3.5 / 4.0 / 4.5 / PCL / Xamarin)
* [Rant](https://github.com/TheBerkin/Rant) - The Rant Procedural Text Generation DSL http://berkin.me/rant/
* [ScriptCS](https://github.com/scriptcs/scriptcs) - Write C# apps with a text editor, nuget and the power of Roslyn!
* [Shielded](https://github.com/jbakic/Shielded) - Software Transactional Memory (STM) implementation for .NET
* [TinyMapper](https://github.com/TinyMapper/TinyMapper) - a tiny and quick object mapper for .Net.
* [Jint](https://github.com/sebastienros/jint) - Javascript interpreter for .NET which provides full ECMA 5.1 compliance and can run on any .NET plaftform.

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
* [Gemini](https://github.com/tgjones/gemini) - IDE framework similar in concept to the Visual Studio Shell. Built on WPF, AvalonDock, and Caliburn Micro.

## Office

* [ExcelDna](https://github.com/Excel-DNA/ExcelDna) - ExcelDna makes it easier to create and deploy Excel Add-Ins using C#, F# or VB .NET
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
* [Fluent NHibernate](https://github.com/jagregory/fluent-nhibernate) - Fluent, XML-less, compile safe, automated, convention-based mappings for NHibernate.
* [FluentMigrator](https://github.com/schambers/fluentmigrator) - Fluent Migrations framework for .net
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) - Light, simple and fast convention-based POCO ORM **[[Free for OSS](https://github.com/ServiceStack/ServiceStack.OrmLite/blob/master/license.txt)]** **[$]**
* [Massive](https://github.com/FransBouma/Massive) - A small, happy, data access tool that will love you forever.
* [LINQ to DB](https://github.com/linq2db/linq2db) - The fastest LINQ database access library offering a simple, light, fast, and type-safe layer between your POCO objects and your database.
* [MicroLite ORM](https://github.com/TrevorPilley/MicroLite) MicroLite ORM is a micro Object Relational Mapper for the .NET framework. It is designed to be easy to use, extensible and testable.
* [PetaPoco](http://www.toptensoftware.com/petapoco/) - A tiny ORM-ish thing for your POCOs
* [AsyncPoco](https://github.com/tmenier/AsyncPoco) - A long-"awaited" fully asynchronous PetaPoco fork
* [NPoco](https://github.com/schotime/NPoco) - Simple microORM that maps the results of a query onto a POCO object. Based on Schotime's branch of PetaPoco

## Package Management

* [NuGet](https://www.nuget.org/) - THE .NET Package Manager
* [MyGet](http://www.myget.org/) - Hosted Package Repository for NuGet, NPM, Bower and VSIX. Also provides CI as-a-Service. **[[Free for OSS](https://www.myget.org/opensource)]** **[$]**
* [Paket](https://github.com/fsprojects/Paket) - A package dependency manager for .NET with support for NuGet packages and GitHub repositories. http://fsprojects.github.io/Paket/

## PDF

* [ITextSharp](https://github.com/itext/itextsharp) - iText is a PDF library that allows you to CREATE, ADAPT, INSPECT and MAINTAIN documents in the Portable Document Format (PDF)**[$]****[Free for OSS]**

## Profiler

* [MiniProfiler](https://github.com/MiniProfiler/dotnet) - A simple but effective mini-profiler for ASP.NET websites
* [Glimpse](https://github.com/glimpse/glimpse) - The open source diagnostics platform for the web

## Push Notifications

* [PushSharp](https://github.com/Redth/PushSharp) - A server-side library for sending Push Notifications to iOS, OSX, Android, Chrome, Windows Phone, Windows 8, Blackberry, and Amazon devices.

## Queue

* [NServiceBus](https://github.com/Particular/NServiceBus) - The most popular service bus for .NET
* [Hangfire](https://github.com/HangfireIO/Hangfire) - Incredibly easy way to perform fire-and-forget, delayed and recurring tasks inside ASP.NET applications
* [RabbitMQ.NET](http://hg.rabbitmq.com/rabbitmq-dotnet-client/) - Implementation of an AMQP client library for C#, and a binding exposing AMQP services via WCF
* [NetMQ](https://github.com/zeromq/netmq) - NetMQ is 100% native C# port of ZeroMQ
* [MassTransit](https://github.com/MassTransit/MassTransit) - MassTransit is lean service bus implementation for building loosely coupled applications using the .NET Framework.
* [Rebus](https://github.com/rebus-org/Rebus) - Rebus is a lean service bus implementation for .NET, similar in nature to NServiceBus and MassTransit, only leaner
* [RestBus](https://github.com/tenor/RestBus) - A service oriented .NET messaging library for RabbitMQ. 
* [EasyNetQ](https://github.com/EasyNetQ/EasyNetQ) - An easy to use .NET API for RabbitMQ
* [Warewolf ESB](https://github.com/Warewolf-ESB/Warewolf-ESB) - An easy to use service bus and microservices platform. Easily build applications and services in a visual IDE.

## Reactive Programming

* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) - The Reactive Extensions (Rx) is a library for composing asynchronous and event-based programs using observable sequences and LINQ-style query operators
* [Dynamic Data](https://github.com/RolandPheasant/DynamicData) - Reactive Extensions (Rx) for collections

## Scheduling

* [QuartzNet](https://github.com/quartznet/quartznet) - Quartz Enterprise Scheduler .NET

## SDK and API Clients

* [AWS SDK](https://github.com/aws/aws-sdk-net) - The AWS SDK for .NET enables .NET developers to easily work with Amazon Web Services
* [Azure PowerShell](https://github.com/Azure/azure-powershell) - A set of PowerShell cmdlets for developers and administrators to develop, deploy and manage Microsoft Azure applications
* [Octokit.NET](https://github.com/octokit/octokit.net) - A GitHub API client library for .NET
* [DropNet](https://github.com/DropNet/DropNet) - Client Library for the Dropbox API

## Search

* [Elasticsearch .NET](https://github.com/elastic/elasticsearch-net) - Elasticsearch.Net & NEST
* [PlainElastic.Net](https://github.com/Yegoroff/PlainElastic.Net) - Plain .Net client for ElasticSearch
* [SolrNet](https://github.com/mausch/SolrNet) - Solr client for .Net
* [Lucene.net](http://lucenenet.apache.org/) - Lucene.Net is a port of the Lucene search engine library, written in C# and targeted at .NET runtime users

## Serialization

* [Protobuf.NET](https://github.com/mgravell/protobuf-net) - Protocol buffers is the name of the binary serialization format used by Google for much of their data communications
* [Json.NET](https://github.com/JamesNK/Newtonsoft.Json) - Popular high-performance JSON framework for .NET
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) - JSON, JSV and CSV Text Serializers used in servicestack.net
* [Msgpack-Cli](https://github.com/msgpack/msgpack-cli) - MessagePack implementation for Common Language Infrastructure
* [Jil](https://github.com/kevin-montrose/Jil) - Fast .NET JSON Serializer, built on Sigil (used by StackOverflow)
* [ProtoBuf](https://github.com/hultqvist/ProtoBuf) - Generate C# code for protocol buffer serialization from a .proto specification.
* [F# Data](http://fsharp.github.io/FSharp.Data/) - F# type providers for accessing XML, JSON, CSV and HTML files (based on sample documents) and for accessing WorldBank data
* [Bond](https://github.com/Microsoft/bond) - cross-platform framework for working with schematized data. It supports cross-language de/serialization and powerful generic mechanisms for efficiently manipulating data.

## State machines

* [Stateless](https://github.com/nblumhardt/stateless) - Create state machines and lightweight state machine-based workflows directly in .NET code
* [Automatonymous](https://github.com/MassTransit/Automatonymous) - A state machine library for .Net - allows you to write fluent style state machines

## Static Site Generators
* [FsBlog](https://github.com/fsprojects/FsBlog/) - Blog aware, static site generation using F#
* [Pretzel](https://github.com/Code52/pretzel) - A site generation tool (and then some) for .NET platforms
* [Sandra.Snow](https://github.com/Sandra/Sandra.Snow) - Jekyll inspired static site generation for .NET
* [Wyam](http://wyam.io) - A simple to use, highly modular, and extremely configurable static content generator

## Style Guide

* [C# Style Guide](http://stackoverflow.com/questions/4678178/style-guide-for-c) - StackOverflow Q & A on style guides
* [C# Coding Conventions](https://msdn.microsoft.com/library/ff926074.aspx) - Official MSDN C# code conventions

## Template Engine

* [RazorEngine](https://github.com/Antaris/RazorEngine) - Open source templating engine based on Microsoft's Razor parsing engine
* [Nustache](https://github.com/jdiamond/Nustache) - Open source library for logic-less templates
* [DotLiquid](https://github.com/dotliquid/dotliquid) - C# port of the Ruby Liquid templating language

## Testing

* [AutoFixture](https://github.com/AutoFixture/AutoFixture) - AutoFixture is an open source framework for .NET designed to minimize the 'Arrange' phase of your unit tests
* [BDDfy](https://github.com/TestStack/TestStack.BDDfy) - BDDfy is the simplest BDD framework EVER!
* [Bogus](https://github.com/bchavez/Bogus) - A simple and sane fake data generator for C#. Based on and ported from the famed faker.js.
* [ExpressionToCode](https://github.com/EamonNerbonne/ExpressionToCode) - Use plain C# syntax in assertions that include both the expression expression and subexpression values in the failure message.
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy) - The easy mocking library for .NET http://fakeiteasy.github.io
* [Fluent Assertions](https://github.com/dennisdoomen/fluentassertions) - A set of .NET extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style test
* [FluentAutomation](https://github.com/stirno/FluentAutomation) - Simple Fluent API for UI Automation
* [FsCheck](https://github.com/fscheck/FsCheck) - Random Testing for .NET.
* [Fuchu](https://github.com/mausch/Fuchu) - A unit-testing library for F# with tests-as-values which makes DSLs extemely easy to create.
* [Machine.Specifications](https://github.com/machine/machine.specifications) - Machine.Specifications (MSpec) is a context/specification framework that removes language noise and simplifies tests.
* [Moq](https://github.com/Moq/moq4) - The most popular and friendly mocking framework for .NET
* [NBuilder](https://github.com/garethdown44/nbuilder) - Rapid generation of test objects
* [NSubstitute](http://nsubstitute.github.io/) - A friendly substitute for .NET mocking frameworks
* [NUnit](https://github.com/nunit/nunit) - A unit-testing framework for all .Net languages
* [Rhino Mocks](https://github.com/ayende/rhino-mocks) - Dynamic Mocking Framework for .NET
* [Shouldly](https://github.com/shouldly/shouldly) - Shouldly is an assertion framework which focuses on giving great error messages when the assertion fails while being simple and terse.
* [SpecFlow](https://github.com/techtalk/SpecFlow/) - Binding business requirements to .Net code
* [xBehave.net](https://github.com/xbehave/xbehave.net) - A BDD/TDD framework based on xUnit.net and inspired by Gherkin. http://xbehave.github.io
* [xUnit](https://github.com/xunit/xunit) - xUnit.net is a free, open source, community-focused unit testing tool for the .NET Framework

## Trading

* [Lean](https://github.com/QuantConnect/Lean) - Lean Engine is an open-source fully managed C# algorithmic trading engine built for desktop and cloud usage. https://lean.quantconnect.com
* [StockSharp](https://github.com/StockSharp/StockSharp) - Trading and algorithmic trading open source platform (stock markets, forex, bitcoins and options). http://stocksharp.com

## Visual Studio Plugins

* [Web Essentials](https://github.com/madskristensen/WebEssentials2013) - Web Essentials extends Visual Studio with lots of new features that web developers have been missing for many years
* [VsVIM](https://github.com/jaredpar/VsVim) - VIM in Visual Studio
* [Nuget Package Manager](https://visualstudiogallery.msdn.microsoft.com/27077b70-9dad-4c64-adcf-c7cf6bc9970c) - NuGet is the package manager for the Microsoft development platform including .NET
* [SideWaffle](https://github.com/ligershark/side-waffle) - A collection of Item Templates for Visual Studio 2012/2013 that makes any web developer's life much easier
* [Resharper](http://www.jetbrains.com/resharper/) - Developer Productivity Tool for Visual Studio **[$]**
* [Refactoring Essentials](http://vsrefactoringessentials.com/) - Open source extension for C# and VB.NET refactorings, including code best practice analyzers.
* [CodeContracts](https://github.com/Microsoft/CodeContracts) - Source code for the CodeContracts tools for .NET
* [Git Diff Margin](https://github.com/laurentkempe/GitDiffMargin) - Displays live Git changes of the currently edited file on Visual Studio margin and scroll bar
* [Productivity Power Tools](https://visualstudiogallery.msdn.microsoft.com/d0d33361-18e2-46c0-8ff2-4adea1e34fef) - A set of extensions to Visual Studio Professional (and above) which improves developer productivity.

## Web Frameworks

* [ASP.NET MVC](https://aspnetwebstack.codeplex.com/) - ASP.NET is a free web framework for building great web sites and applications
* [FubuMVC](https://github.com/DarthFubuMVC/fubumvc) - A front-controller style MVC framework for .NET http://fubuworld.com/fubumvc/
* [NancyFx](https://github.com/NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .Net and Mono
* [IISNode](https://github.com/tjanczuk/iisnode) - Host NodeJS applications in IIS
* [Suave.IO](https://suave.io/) - Framework/library/web server that makes you cry tears of joy after finishing your project ahead-of-time when you look at the beautiful code you've written in `[F#]`.

## Web Servers

* [EmbedIO](https://github.com/unosquare/embedio) - Web server built on Mono and cross-platform
* [Jexus web server](http://www.jexus.org) - Web server for Linux
* [XSP](https://github.com/mono/xsp) - Mono's ASP.NET hosting server. This module includes an Apache Module, a FastCGI module that can be hooked to other web servers as well as a standalone server used for testing (similar to Microsoft's Cassini)

## WebSocket

* [Fleck](https://github.com/statianzo/Fleck) - Fleck is a WebSocket server implementation in C#. Branched from the Nugget project
* [SignalR](https://github.com/SignalR/SignalR) - Library for ASP.NET developers that makes it incredibly simple to add real-time web functionality to your applications
* [SuperSocket](https://github.com/kerryjiang/SuperSocket) - SuperSocket is a light weight extensible socket application framework
* [Websocket-Sharp](https://github.com/sta/websocket-sharp) - A C# implementation of the WebSocket protocol client and server
* [WebSocket4NET](https://websocket4net.codeplex.com) - WebSocket client for .NET 2.0+, Xamarin, Mono, Silverlight, Windows Phone, & WinRT
* [XSockets](https://xsockets.net/) - Provides a great set of tools for you to build real-time applications on the Microsoft.NET plattform and much more
* [WampSharp](https://github.com/Code-Sharp/WampSharp) - A C# implementation of [The Web Application Messaging Protocol](http://wamp.ws) - a protocol that provides messaging patterns of Remote Procedure Calls and Publish/Subscribe over WebSockets.

## Windows Services

* [TopShelf](https://github.com/Topshelf/Topshelf) - An easy service hosting framework for building Windows services using .NET

## Other Lists

* [.NET-libraries-that-make-your-life-easier](https://github.com/tallesl/net-libraries-that-make-your-life-easier) - Open Source .NET libraries that make your life easier
* [awesome-LINQ](https://github.com/aloisdg/awesome-linq) - A curated collection of awesome LINQ libraries, tools, and more.
* [C# Algorithms, Data Structures](https://github.com/aalhour/C-Sharp-Algorithms) - A list of algorithms and data structures implementations.

# Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

# License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Vitali Fokin](http://quozd.com) has waived all copyright and related or neighboring rights to this work.
