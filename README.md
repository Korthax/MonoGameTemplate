# Empty MonoGame 3.6 dotnet new project template

This repository contains the templating code to create an project using the amazing [MonoGame](http://www.monogame.net/) framework.

[![MonoGame](https://img.shields.io/badge/WWW-monogame-blue.svg)](http://www.monogame.net/)
[![NuGet Version](http://img.shields.io/nuget/v/MonoGameTemplate.svg?style=flat)](https://www.nuget.org/packages/MonoGameTemplate/)

## Requirements
* [MonoGame 3.6](http://www.monogame.net/2017/03/01/monogame-3-6/)
* [.NET Core cli](https://www.microsoft.com/net/core#windowsvs2017)

## Usage
### From Source
1. Clone the repository
2. Install the template ```dotnet new -i [path\to\repository]\content```
    * Make sure the path does not end in a ```\``` else the template install will fail silently
3. Create a new project ```dotnet new monogame [--name Name]```

### From NuGet
1. Install the template ```dotnet new -i MonoGameTemplate::*```
    * Make sure the path does not end in a ```\``` else the template install will fail silently
2. Create a new project ```dotnet new monogame [--name Name]```

## General Notes

I've created this template for my own use to speed up adding a new monogame project. Use at your own risk :)