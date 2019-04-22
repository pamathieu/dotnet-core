# dotnet-core
.NET Core is an open source platform, using MIT and Apache 2 licenses, that runs on Windows, macOS and Linux operating systems. The code has the same behavior on multiple architectures, including x64, x86, and ARM. In this repo, we are primarily using C# to build applications and libriries for .NET Core. I will also do some function programming by coding in F# supported by .NET core. 

.NET Core Installations. 

1) We are using Ubuntu 18.04 on-premise to run docker image the current verstion 2.2 Remember, At this momment we are writing this doc, the LTS verstion is 2.1 which can be installed by running: docker pull mcr.microsoft.com/dotnet/core/sdk:2.1  (best suited for production in term of life time support)

    i) prerequisite: We need to install Docker. See my installation file                                                              (https://github.com/pamathieu/docker/blob/master/install_docker.sh)
    
    ii) Proceed with the installation by running:  docker pull mcr.microsoft.com/dotnet/core/sdk:2.2 
    
    
2) We are also install .NET Core in he MacOS.
