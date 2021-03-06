# MadLibs

#### A quick start for C Sharp projects

#### By Scott Bergler, Sheila Stephen

## Description
This template will create the directories and basic files needed to start a web project in C Sharp. I adapted it from Sayed I. Hashimi's [article](https://blogs.msdn.microsoft.com/dotnet/2017/04/02/how-to-create-your-own-templates-for-dotnet-new/). The directory structure and file contents are from Epicodus C Sharp curriculum and may not be suited for all projects.

The project files generated will have starter content as outlined in the Epicodus C Sharp course. The template will give relevant namespaces and paths for your project (i.e. MadLibs will be replaced everywhere with YourProjectName).

The directory/file structure created is as follows:

```
MadLibs.Solution
├── README.md
├── .gitignore
└── MadLibs
    ├── MadLibs.csproj
    ├── Program.cs
    ├── Startup.cs
    ├── Controllers
    │   └── HomeController.cs
    ├── Models
    └── Views
        └── Home
            └── Index.cshtml

└── MadLibs.Tests
    └── MadLibs.Tests.csproj
    └── ModelTests

```

There is a lot more a person could do with this, but I'm keeping this simple for now, trying to stay within the scope of the type of projects we're currently doing at Epicodus. I will be adding to it as the course continues.

### Specifications:
##### Spec 1: Do a thing:
- [ ] **Expect:** Input: some input; Output: some output;

## Setup/Installation Requirements
Clone the code from [GitHub](https://github.com/skillitzimberg/MadLibs.Solution).

Install the template using the command line interface (cli)/terminal: $ dotnet new --install /Users/Your/Path/Here/MadLibs.Solution;

Navigate to the directory that you want your project to be in (i.e. Desktop, Documents, or wherever you keep your projects).

Run the this command in the cli/terminal:
dotnet new madlibs -n YourProjectName -o YourProjectName.Solution

Open the directory in your text editor. Open the .template.config/template.json file and change the author name to your own. Read the article mentioned above for details on this file and how to use it.s

## Technologies Used

HTML, CSS, Json, C#.

### License

Licensed under the MIT license.

Copyright (c) 2018 
