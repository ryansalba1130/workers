---
languages:
- csharp
products:
- dotnet
page_type: sample
name: "Worker Services in .NET"
urlFragment: "csharp-workers-fundamentals"
description: "Several .NET 5 worker service applications that contain sample source code for interacting with IHostedService, and BackgroundService."
---

# Logging in .NET sample source code

There are six sample source code projects in this collection of samples. The samples are written in C# and the related docs content is covered in [Worker Services in .NET][workers] articles. In addition to an overview, there are in-depth articles discussing queue service implementations, `BackgroundService` scenarios, custom `IHostedService` implementations, Windows Services interop with the `BackgroundService`, and even deploying a worker to Azure.

## Sample prerequisites

The samples are written in C# and targets .NET 5. It requires the [.NET 5.0 SDK](https://dotnet.microsoft.com/download/dotnet/5.0) or later.

## Building the sample

To download and run the sample, follow these steps:

1. Download and unzip the sample.
2. In Visual Studio (2019 or later):
    1. On the menu bar, choose **File** > **Open** > **Project/Solution**.
    2. Navigate to the folder that holds the unzipped sample code, and open the C# project (.csproj) file.
    3. Choose the <kbd>F5</kbd> key to run with debugging, or <kbd>Ctrl</kbd>+<kbd>F5</kbd> keys to run the project without debugging.
3. From the command line:
   1. Navigate to the folder that holds the unzipped sample code.
   2. At the command line, type [`dotnet run`](https://docs.microsoft.com/dotnet/core/tools/dotnet-run).

## More information

- [Worker Services in .NET][workers]
- [Create a Queue Service][queue]
- [Use scoped services within a `BackgroundService`][scoped-bgs]
- [Create a Windows Service using `BackgroundService`][win-bgs]
- [Implement the `IHostedService` interface][timer-svc]
- [Deploy a Worker Service to Azure][cloud-svc]

[workers]: https://docs.microsoft.com/dotnet/core/extensions/workers
[queue]: https://docs.microsoft.com/dotnet/core/extensions/queue-service
[scoped-bgs]: https://docs.microsoft.com/dotnet/core/extensions/scoped-service
[win-bgs]: https://docs.microsoft.com/dotnet/core/extensions/windows-service
[timer-svc]: https://docs.microsoft.com/dotnet/core/extensions/timer-service
[cloud-svc]: https://docs.microsoft.com/dotnet/core/extensions/cloud-service
