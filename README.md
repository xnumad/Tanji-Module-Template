# Tanji Module Template
![New project](New%20project.png)

Basic Tanji module framework:
- Visual C# Windows Forms App
- targeting .NET Framework 4.7.1
- added `using` directives
- added mandatory `[Module()]` line
- renamed inheritence from `Form` to `ExtensionForm`

# Acknowledgements
Based on Darkbox Urban resource ["Tanji/For developers/Plugin development/Setting up"](https://urban.darkbox.nl/tanji/develop/7) (revision: last edited: 23-05-2018 19:16:31) by [Squiz](https://urban.darkbox.nl/account/Squiz) which details the manual steps.

# Add the template
Place the ZIP in the default Project template directory `%userprofile%\Documents\Visual Studio 2017\Templates\ProjectTemplates\`

If you set a custom directory, you can see it in Visual Studio menu bar "Tools"/Options…/Projects and Solutions/Locations/User project templates location

# Delete the template
Simply delete the ZIP.

# Use the template
- Create a new project in Visual Studio
- Choose the "Visual C#" category in which the template should appear as last in the list
- Add the dependencys Sulakore and Tangine!
If you open Form1.cs before adding the dependencys it will fuck you up. If so, add the dependencys *then* and *close and reopen* the solution (if you only open it while a file in it is the active tab, it won't reload).

# Make a template yourself
Visual Studio menu bar "Project"/Export Template…
E.g. if Tanji modules target a new .NET Framework version and you want to contribute by pushing an updated version.