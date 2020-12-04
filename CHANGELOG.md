# C# Snippets Changelog

### Change Log
* All notable changes to the "vscode-csharp-snippets" extension will be documented in this file.



## [1.1.0] (2020-12-04)

```
 New Snippets
```
  - `[api_controller]` :: Creates the base of a controller
  - `[api_delete]` :: Creates the Delete Action of the WebApi
  - `[api_get]` :: Creates the Get Action of the WebApi
  - `[api_put]` :: Creates the Put Action of the WebApi
  - `[api_post]` :: Creates the Post Action of the WebApi
  - `[method]` :: Creates a Method structure
  - `[method_async]` :: Creates an Async Method structure
  - `[rz_code]` :: Creates a code block for Razor
  - `[rz_if]` :: Creates an if statement for Razor
  - `[rz_iflese]` :: Creates an if else statement for Razor
  - `[rz_implements]` :: Implements an interface for Razor
  - `[rz_inherits]` :: Creates an inherits directive for Razor
  - `[rz_inject]` :: Creates an inject directive for Razor
  - `[rz_foreach]` :: Creates a foreach statement for Razor
  - `[rz_functions]` :: Creates a functions block for Razor
  - `[rz_model]` :: Specifies the model to use for Razor
  - `[rz_namespace]` :: Specifies the namespace to use for Razor
  - `[rz_renderbody]` :: Creates a RenderBody for Razor
  - `[rz_switch]` :: Creates a switch statement for Razor
  - `[rz_try]` :: Creates a try catch finally for Razor
  - `[rz_using]` :: Creates an using statement for Razor
  - `[rz_viewbag]` :: Creates a ViewBag for Razor
  - `[rz_viewdata]` :: Creates a ViewData for Razor
  - `[rz_while]` :: Creates a while loop for Razor
```
 Renamed
```
  - `[ac_rz_code]` to `[rz_directive]` :: Creates a directive block for Razor
  - `[ac_rz_comment]` to `[rz_comment]` :: Creates a comment block for Razor
  - `[ac_rz_for]` to `[rz_for]` :: Creates a for statement for Razor
  - `[ac_rz_raw]` to `[rz_raw]` :: Creates a HTML markup for Razor


## [1.0.2] (2020-11-22)

```
 New Snippets
```
  - `[ac_comment]` :: Creates a comment block for ASP.NET
  - `[ac_rz_code]` :: Creates a code block for Razor
  - `[ac_rz_comment]` :: Creates a comment block for Razor
  - `[ac_rz_for]` :: Creates a for statement for Razor
  - `[ac_rz_raw]` :: Creates a HTML markup for Razor
  - `[ex_md5_from_stream]` :: Extension for get the MD5 value from a stream 
  - `[ex_stream_to_string]` :: Extension for convert a stream to string 
  - `[ex_string_to_stream]` :: Extension for convert a string to stream
  - `[todo]` :: Creates a TODO comment 


## [1.0.1] (2020-11-14)

```
 New Snippets
```
  - `[sln_2019]` :: Creates a soluction file for Visual Studio 2019 (.NET Core and ASP.NET Core)

```
 Renamed
```
  - `[sln]` to `[sln_2017]` :: Creates a soluction file for Visual Studio 2017 (.NET Core and ASP.NET Core)


## [1.0.0] (2020-11-11)

```
 New Snippets
```
  - `[ac_action]` :: Creates a MVC/Api Action
  - `[ac_csproj_3.1]` :: Creates a MVC/Api Action  
  - `[class]` :: Creates a class
  - `[dowhile]` :: Creates a do while loop
  - `[else]` :: Creates an else statement  
  - `[enum]` :: Creates an enum type
  - `[exception]` :: Creates an exception class
  - `[for]` :: Creates a for loop
  - `[foreach]` :: Creates a foreach statement
  - `[if]` :: Creates an if statement
  - `[ifelse]` :: Creates an if else statement
  - `[iif]` :: Creates a conditional operator
  - `[interface]` :: Creates an interface
  - `[lock]` :: Creates a lock statement
  - `[main]` :: Creates a Console Main structure
  - `[msgbox]` :: Creates a Windows Message Box
  - `[namespace]` :: Creates a Namespace
  - `[struct]` :: Creates a struct
  - `[switch]` :: Creates a switch statement
  - `[tls]` :: Creates a C# 9 top-level statement
  - `[try]` :: Creates a try catch
  - `[tryf]` :: Creates a try catch finally
  - `[using]` :: Creates an using
  - `[while]` :: Creates a while loop


## [0.6.1] (2020-11-10)

```
Bug Fixing
```
- Fixed a typo error in the `[record]` C# snippet 


## [0.6.0] (2020-11-10)

```
General
```
* Created a new tutorial to create a gRPC demo using the new snippets added in this version

* Renamed of the ASP.NET Core Snippets

  - All the Snippets for ASP.NET Core have been renamed from `[dnac_*]` to `[ac_*]`.

```
 New Snippets
```
  - `[ac_#helloworld_WebApi]` :: ASP.NET Core 5 - Creates a Web Api HelloWorld sample
  - `[ac_csproj_5]` :: Creates the content of the csproj file for ASP.NET Core 5
  - `[crk]` :: Creates a call to ReadKey
  - `[cwl]` :: Creates a call to WriteLine
  - `[gRPC_client_csproj]` :: Creates the csproj content for a Grpc Client in .NET 5
  - `[gRPC_client_program]` :: Creates the Program class for a simple Grpc Client in .NET 5
  - `[gRPC_proto]` :: Creates a sample Proto file for the Grpc App
  - `[gRPC_server_csproj]` :: Creates the csproj content for a Grpc Server in .NET 5
  - `[gRPC_server_program]` :: Creates the Program class for the Grpc Server in .NET 5
  - `[gRPC_server_service]` :: Creates the Service for the Grpc Server in .NET 5
  - `[gRPC_server_settings]` :: Creates the Settings content file for the Grpc Server in .NET 5
  - `[gRPC_server_startup]` :: Creates the Startup class for the Grpc Server in .NET 5
  - `[prop]` :: Creates a property
  - `[propinit]` :: Creates an init property
  - `[propr]` :: Creates a property read-only
  - `[record]` :: Creates a record type
  - `[recordd]` :: Creates a record type with deconstructor
  

## [0.5.0] (2020-10-17)

```
Bug Fixing
```
- Thanks to [Jaguar9383 (Sviataslau Karavatski)](https://github.com/Jaguar9383) for resolve a typo error with `[singleton]`
- Thanks to [jonhaddow (Jon Haddow)](https://github.com/jonhaddow) for resolve a typo error with `[xml_<list>]`
- Thanks to [guntbert (Guntbert Reiter)](https://github.com/guntbert) for fix a typo error in the `README.md` file

```
 New Snippets
```
  - `[mstest]` :: Contribution of [massimilianokraus (Massimiliano Kraus)](https://github.com/massimilianokraus) Creates a MS-Test class
  - `[csproj_3.1]` :: Creates the content of the csproj file for .NET Core 3.1
  - `[csproj_5]` :: Creates the content of the csproj file for .NET 5


## [0.3.1] (2018-03-02)

```
General
```
* Deleted some Snippets

  - Thanks to [doggy8088 (Will)](https://github.com/doggy8088) for ask me and share with me his feedback about delete some snippets in the extension that you can find in the OmniSharp extension too. Now, you can use OmniSharp and this extension together without disable the C# snippets in OmniSharp. You will find this extension as an ideal complement of OmniSharp now.


## [0.2.0] (2017-08-16)

```
ASP.NET Core Snippets
```
* Existing snippets modified

  - `[dnac_csproj_2.0]` has been deleted the tag **preview** for the 2.0 version to be aligned with the .NET Core 2.0 final version published


## [0.1.6] (2017-08-04)

```
General C# Snippets
```
* Existing snippets modified

  - `[singleton]` :: Modified the snippet resolving a bug

* New snippets

  - `[singletonl]` :: Creates a singleton class with System.Lazy<T>
  - `[singletonts]` :: Creates a singleton class as thread-safe without using locks

```
.NET Core Snippets
```
* New snippets

  - `[sln]` :: sln Generator for Visual Studio 2017 (.NET Core and ASP.NET Core)

```
ASP.NET Core Snippets
```
* New snippets

  - `[dnac_controller]` :: ASP.NET Core - Creates the base of a controller
  - `[dnac_startupenv]` :: ASP.NET Core - Creates the Startup constructor to be used with the web hosting environment


## [0.1.5] (2017-07-21)

* Added a new section of snippets, for Xml Comments

```
XML Comments Snippets
```
* New snippets

  - `[xml_<c>]` :: Xml Comment - <c> Gives you a way to indicate that text within a description should be marked as code
  - `[xml_<code>]` :: Xml Comment - <code> Gives you a way to indicate multiple lines as code. Use <c> to indicate that text within a description should be marked as code
  - `[xml_<example>]` :: Xml Comment - <example> Lets you specify an example of how to use a method or other library member
  - `[xml_<exception>]` :: Xml Comment - <exception> Lets you specify which exceptions can be thrown
  - `[xml_<include>]` :: Xml Comment - <include> Lets you refer to comments in another file that describe the types and members in your source code
  - `[xml_<list>]` :: Xml Comment - <list> A list or table can have as many <item> blocks as needed
  - `[xml_<para>]` :: Xml Comment - <para> Is for use inside a tag, such as <summary>, <remarks>, or <returns>, and lets you add structure to the text
  - `[xml_<param>]` :: Xml Comment - <param> Should be used in the comment for a method declaration to describe one of the parameters for the method
  - `[xml_<paramref>]` :: Xml Comment - <paramref> Gives you a way to indicate that a word in the code comments, for example in a <summary> or <remarks> block refers to a parameter
  - `[xml_<permission>]` :: Xml Comment - <permission> Lets you document the access of a member
  - `[xml_<remarks>]` :: Xml Comment - <remarks> Is used to add information about a type, supplementing the information specified with <summary>
  - `[xml_<returns>]` :: Xml Comment - <returns> Should be used in the comment for a method declaration to describe the return value
  - `[xml_<see>]` :: Xml Comment - <see> Lets you specify a link from within text. Use <seealso> to indicate that text should be placed in a See Also section
  - `[xml_<seealso>]` :: Xml Comment - <seealso> Lets you specify the text that you might want to appear in a See Also section
  - `[xml_<summary>]` :: Xml Comment - <summary> Should be used to describe a type or a type member
  - `[xml_<typeparam>]` :: Xml Comment - <typeparam> Should be used in the comment for a generic type or method declaration to describe a type parameter
  - `[xml_<typeparamref>]` :: Xml Comment - <typeparamref> Enable consumers of the documentation file to format the word in some distinct way, for example in italics
  - `[xml_<value>]` :: Xml Comment - <value> Lets you describe the value that a property represents


## [0.1.4] (2017-07-16)

```
General C# Snippets
```
* New snippets

  - `[guid]` :: Creates a new instance of the Guid structure
  - `[guidn]` :: Creates as string, a new instance of the Guid structure without hyphens
  - `[immutable]` :: Creates an immutable object
  - `[propi]` :: Creates an immutable property

```
ASP.NET Core Snippets
```
* New snippets

  - `[dnac_conf]` :: ASP.NET Core - Creates a way to configure the JSON configuration provider
  - `[dnac_conf_file]` :: ASP.NET Core - Creates a way to configure the JSON configuration provider with a custom config file


## [0.1.3] (2017-07-13)

Included a new section with C# Snippets for ASP.NET Core.

```
General C# Snippets
```
* New snippets

  - `[classa]` :: Creates an abstract class declaration
  - `[classd]` :: Creates a disposable class
  - `[csproj_1.1]` :: Creates the content of the csproj file for .NET Core 1.1
  - `[linq_distinct]` :: Creates a LINQ Distinct sentence
  - `[linq_where]` :: Creates a LINQ Where sentence
  - `[singleton]` :: Creates a singleton class

```
ASP.NET Core Snippets
```
* New snippets

  - `[dnac_csproj_2.0]` :: ASP.NET Core 2.0 Preview2 Final csproj Generator
  - `[dnac_#helloworld_WebApp]` :: ASP.NET Core - Creates a HelloWorld sample - WebApp
  - `[dnac_#helloworld_Startup]` :: ASP.NET Core - Creates a HelloWorld sample - Startup


## [0.1.2] (2017-07-11)

```
General C# Snippets
```
* New snippets

  - `[#helloworld]` :: Creates a HelloWorld sample
  - `[cclear]` :: Creates a call to Clear
  - `[const]` :: Creates a constant
  - `[cr]` :: Creates a call to ReadLine
  - `[csproj_1.0]` :: Creates the content of the csproj file for .NET Core 1.0
  - `[csproj_2.0]` :: Creates the content of the csproj file for .NET Core 2.0
  - `[pum]` :: Creates a public string method declaration
  - `[pvm]` :: Creates a public void method declaration

* Existing snippets modified

  - `[con_general_output]` is now `[cgo]` (the content of the snippet has changed too)


## [0.1.1] (2017-07-09) - Initial release

```
General C# Snippets
```
* Snippets

  - `[#if]`
  - `[#region]`
  - `[~]`
  - `[class]`
  - `[ctor]`
  - `[cw]`
  - `[do]`
  - `[else]`
  - `[enum]`
  - `[exception]`
  - `[for]`
  - `[foreach]`
  - `[forr]`
  - `[if]`
  - `[indexer]`
  - `[interface]`
  - `[invoke]`
  - `[iterator]`
  - `[lock]`
  - `[namespace]`
  - `[prop]`
  - `[propfull]`
  - `[propg]`
  - `[sim]`
  - `[struct]`
  - `[svm]`
  - `[switch]`
  - `[try]`
  - `[tryf]`
  - `[using]`
  - `[while]`
  - ~~`[con_general_output]`~~
  