# Visual-Studio
My works related to Visual Studio, an integrated development environment (IDE) from Microsoft.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [Visual Studio shortcuts.](#shortcuts)
4. [GitHub notes.](#github)
5. [GitHub repository calculation.](#calculation)

<a name="introduction"></a>
## 1. Introduction.
<img src="visual studio.png" height="110">
Microsoft Visual Studio is an integrated development environment (IDE) from Microsoft. It is used to develop computer programs, as well as websites, web apps, web services and mobile apps. Visual Studio uses Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, Windows Store and Microsoft Silverlight. It can produce both native code and managed code.
<br /><br />
Visual Studio includes a code editor supporting IntelliSense (the code completion component) as well as code refactoring. The integrated debugger works both as a source-level debugger and a machine-level debugger. Other built-in tools include a code profiler, designer for building GUI applications, web designer, class designer, and database schema designer. It accepts plug-ins that enhance the functionality at almost every level—including adding support for source control systems (like Subversion and Git) and adding new toolsets like editors and visual designers for domain-specific languages or toolsets for other aspects of the software development lifecycle (like the Azure DevOps client: Team Explorer).
<br /><br />
Visual Studio supports 36 different programming languages and allows the code editor and debugger to support (to varying degrees) nearly any programming language, provided a language-specific service exists. Built-in languages include C, C++, C++/CLI, Visual Basic .NET, C#, F#, JavaScript, TypeScript, XML, XSLT, HTML, and CSS. Support for other languages such as Python, Ruby, Node.js, and M among others is available via plug-ins. Java (and J#) were supported in the past.
<br /><br />
The most basic edition of Visual Studio, the Community edition, is available free of charge. The slogan for Visual Studio Community edition is "Free, fully-featured IDE for students, open-source and individual developers".

<a name="references"></a>
## 2. Official references websites.
Microsoft official website : https://www.microsoft.com <br />
Visual Studio official website : https://visualstudio.microsoft.com/ <br />
Visual Studio Community official website : https://visualstudio.microsoft.com/vs/community/ <br />
Visual Studio Blog : https://devblogs.microsoft.com/visualstudio/ <br />
Visual Studio Twitch : https://www.twitch.tv/visualstudio <br />

**_Visual Studio questions and answers websites_** <br />
 Stack Overflow questions and answers website : https://stackoverflow.com <br />
 
**_Visual Studio documentation by docs.microsoft.com_** <br />
Walkthrough: Display light bulb suggestions : https://docs.microsoft.com/en-us/visualstudio/extensibility/walkthrough-displaying-light-bulb-suggestions?view=vs-2019 <br />
PropertyGroup element (MSBuild) : https://docs.microsoft.com/en-us/visualstudio/msbuild/propertygroup-element-msbuild?view=vs-2019 <br />
ItemGroup element (MSBuild) : https://docs.microsoft.com/en-us/visualstudio/msbuild/itemgroup-element-msbuild?view=vs-2019 <br />
Introduction to WPF in Visual Studio : https://docs.microsoft.com/en-us/dotnet/framework/wpf/getting-started/introduction-to-wpf-in-vs<br />

**_Visual Studio related articles_** <br />
5 Great Visual Studio Keyboard Shortcuts by Visual Studio LIVE! : https://vslive.com/Blogs/News-and-Tips/2015/04/5-VS-Keyboard-Shortcuts.aspx <br />
What is InitializeComponent() method and how to use it to learn how to create controls from code by DevComponents : https://www.devcomponents.com/kb2/?p=1327 <br />

**_Visual Studio questions and answers by Stack Overflow_** <br />
Visual Studio : short cut Key : Duplicate Line : https://stackoverflow.com/questions/2279000/visual-studio-short-cut-key-duplicate-line <br />

<a name="shortcuts"></a>
## 3. Visual Studio shortcuts.

**_Visual Studio application management_** <br />
**[ Fn ]** + **[ F5 ]** : run the application <br />
**[ Ctrl ]** + **[ F5 ]** : run the application without the debugger <br />

**_Visual Studio file management_** <br />
**[ Ctrl ]** + **[ N ]** : create new file <br />
**[ Ctrl ]** + **[ O ]** : open desired file <br />

**_Visual Studio folder management_** <br />
**[ Ctrl ]** + **[ Shift ]** + **[ Alt ]** + **[ O ]** : open desired folder <br />

**_Visual Studio project management_** <br />
**[ Ctrl ]** + **[ Shift ]** + **[ N ]** : create new project <br />
 
**_Visual Studio save management_** <br />
**[ Ctrl ]** + **[ S ]** : save the program <br />
**[ Ctrl ]** + **[ Shift ]** + **[ S ]** : save all the program <br />

**_Visual Studio text management_** <br />
**[ Ctrl ]** + **[ D ]** : duplicate the current line <br />
**[ Ctrl ]** + **[ C ]**, **[ Ctrl ]** + **[ V ]** : duplicate the current line <br />
**[ Ctrl ]** + **[ K ]** + **[ C ]** : adding comment <br />
**[ Ctrl ]** + **[ K ]** + **[ U ]** : remove comment <br />
**[ Shift ]** : add indentation

**_Visual Studio item management_** <br />
**[ Ctrl ]** + **[ Shift ]** + **[ A ]** : add new item <br />
**[ Ctrl ]** + **[ Shift ]** + **[ A ]**, **[ N ]** : skip to edit the new name of the class <br />

**_Visual Studio Solution Explorer management_** <br />
**[ Fn ]** + **[ F2 ]** : rename the file <br />
**[ Ctrl ]** + **[ X ]** : cut the file <br />
**[ Ctrl ]** + **[ C ]** : copy the file <br />
**[ Delete ]** : delete the file <br />
 
<a name="github"></a>
## 4. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/Visual-Studio.git
$ cd Visual-Studio/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 5. GitHub repository calculation.
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
JSON                             8              0              0            313
Markdown                         1             11              0             56
C#                               4             12             20             50
XML                              2              0              0             21
MSBuild script                   1              2              0              6
-------------------------------------------------------------------------------
SUM:                            16             25             20            446
-------------------------------------------------------------------------------

```
Refer to : https://github.com/syakirharis25/cloc
