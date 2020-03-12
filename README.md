# _To Do List_

#### _C# Testing practice for Epicodus_, _Mar. 11, 2020_

#### By _**Michelle Morin, Geoff Goetz**_

## Description

_This application is a to-list with basic functionality to record items with a description.._

## Specifications:

| Specification | Example Input | Example Output |
| ------------- |:-------------:| -------------------:|
| Application creates an instance of an Item | Item newItem = new Item() | typeof(Item) is Item |
| Application returns description of Item (e.g., "walk the dog") | newItem.Description | "walk the dog" |
| Application sets a description for an Item (e.g., "walk the dog") | Item newItem = new Item("walk the dog") | newItem.Description = "walk the dog" |
| Application adds all new instances of Item to a static list | Item newItem = new Item("walk the dog") | newItem is added to static list property of Item class |
| Application returns all items in the static list of items | Item newItem = new Item(description) | List<Item> result = { newItem } | 

## Setup/Installation Requirements

### Install .NET Core

#### on macOS:
* _[Click here](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.106-macos-x64-installer) to download a .NET Core SDK from Microsoft Corp._
* _Open the file (this will launch an installer which will walk you through installation steps. Use the default settings the installer suggests.)_

#### on Windows:
* _[Click here](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.203-windows-x64-installer) to download the 64-bit .NET Core SDK from Microsoft Corp._
* _Open the .exe file and follow the steps provided by the installer for your OS._

#### Install dotnet script
_Enter the command ``dotnet tool install -g dotnet-script`` in Terminal (macOS) or PowerShell (Windows)._

### Clone this repository

_Enter the following commands in Terminal (macOS) or PowerShell (Windows):_
* ``cd desktop``
* ``git clone`` followed by the URL to this repository.
* ``cd`` followed by the repository name.

_Confirm that you have navigated to the correct directory (e.g., by entering the command_ ``pwd`` _in Terminal)._

_Run this console application by entering the following command in Terminal (macOS) or PowerShell (Windows):_
* ``dotnet run``

_To view/edit the source code of this application, open the contents of this directory in a text editor or IDE of your choice (e.g., to open all contents of the directory in Visual Studio Code on macOS, enter the command_ ``code .`` _in Terminal)._

## Technologies Used
* _Git_
* _C#_
* _.NET Core 2.2_
* _dotnet script_

### License

*This webpage is licensed under the MIT license.*

Copyright (c) 2020 **_Michelle Morin, Geoff Goetz_**
