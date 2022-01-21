# MSBuild examples

This repo is created to include msbuild examples

1. The first example is the creation of a custom task for code generation. The idea is consume a txt file and generate code from it during build process. It is simple in order to show the mechanism, then you will be able to create more complex piece of code. Part of this effort includes how to ship and consume the custom task as nuget package.
   [Please see the Custom Task-Code Generation Readme](./custom-task-code-generation/README.md)

1. Define how to test a custom task, unit and integration test

1. Generate a Rest Client API during the build process. The example use [NSawg](https://docs.microsoft.com/aspnet/core/tutorials/getting-started-with-nswag?view=aspnetcore-6.0&tabs=visual-studio) as client generator. It is a very common scenario and it sill use the pre defined msbuild [Tool Task](https://docs.microsoft.com/dotnet/api/microsoft.build.utilities.tooltask) to do that.

1. Investigate some action not related to code generation, for example send an email and used if some situation is detected.