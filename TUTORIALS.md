## Demos - Use of the C# snippets


### Hello World Sample (.NET Core 2.0 Console App with C#)

Snippets used: `[csproj_2.0]` and `[#helloworld]`

* The video has a duration of 50 seconds. In this time, you will be able to generate your first .NET Core app.

![alt text](https://github.com/J0rgeSerran0/vscode-csharp-snippets/raw/master/videos/csproj_2_csharp_helloworld_snippet.gif "C# Snippets")


### Hello World Sample (ASP.NET Core 2.0 with C#)

Snippets used: `[dnac_csproj_2.0]`  `[dnac_#helloworld_Startup]` and `[dnac_#helloworld_WebApp]`

> The dnac* snippets have been renamed to ac_* 

* The video has a duration of 50 seconds. In this time, you will be able to generate your first ASP.NET Core app.

![alt text](https://github.com/J0rgeSerran0/vscode-csharp-snippets/raw/master/videos/csproj_2_aspnetcore_helloworld_snippet.gif "C# Snippets")


### Hello World Sample (.NET 5 and Grpc C#) - STEP BY STEP

Snippets used: `[gRPC_client_csproj]`  `[gRPC_client_program]` `[gRPC_proto]` `[gRPC_server_csproj]` `[gRPC_server_program]` `[gRPC_server_service]` `[gRPC_server_settings]` and `[gRPC_server_startup]`

[gRPC for .NET](https://github.com/grpc/grpc-dotnet)


#### Project structure
1. Create a folder (for example: **GrpcHelloWorld**)
2. Create three folders (**Client**, **Proto**, **Server**)

#### Client
1. Go to the **Client** folder
2. Create a file named *Client.csproj.cs*
3. Apply the `[gRPC_client_csproj]` snippet
4. Rename the file to *Client.csproj*
5. Create a file named *Program.cs*
6. Apply the `[gRPC_client_program]` snippet

#### Proto file
1. Go to the **Proto** folder
2. Create a file named *greet.proto.cs*
3. Apply the `[gRPC_proto]` snippet
4. Rename the file to *greet.proto*

#### Server
1. Go to the **Server** folder
2. Create a file named *Server.csproj.cs*
3. Apply the `[gRPC_server_csproj]` snippet
4. Rename the file to *Server.csproj*
5. Create a file named *Program.cs*
6. Apply the `[gRPC_server_program]` snippet
7. Create a file named *GreeterService.cs*
8. Apply the `[gRPC_server_service]` snippet
9. Create a file named *appsettings.json.cs*
10. Apply the `[gRPC_server_settings]` snippet
11. Rename the file to *appsettings.json*
12. Create a file named *Startup.cs*
13. Apply the `[gRPC_server_startup]` snippet

#### Build
1. Open the terminal
2. Go to the **Client** folder
3. Write the command **dotnet build --source https://api.nuget.org/v3/index.json** 
4. Go to the **Server** folder
5. Write the command **dotnet build --source https://api.nuget.org/v3/index.json** 

#### Testing
1. Open two terminals or command line windows
2. Go to the **Client** and **Server** folders
3. Start the **Server** writting the command **dotnet run** or the **Server.exe** from the bin folder 
4. Start the **Client** writting the command **dotnet run** or the **Client.exe** from the bin folder 
