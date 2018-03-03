# C# Snippets Changelog

### Change Log
* All notable changes to the "vscode-csharp-snippets" extension will be documented in this file.



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
  