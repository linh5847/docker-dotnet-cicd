# docker-dotnet-sample

A simple .NET web application example for Docker's .NET Language Guide.

PreRequisites:- Requires to install Docker Desktop on the macOS first and startup daemon. Do not install Rancher Desktop as docker init doesn't run correctly on Rancher Desktop.

https://docs.docker.com/guides/dotnet/containerize/

Use the below link

https://docs.docker.com/guides/dotnet/

Modules

    Containerize your app = https://docs.docker.com/guides/dotnet/containerize/ Learn how to containerize an ASP.NET application.

    Develop your app = https://docs.docker.com/guides/dotnet/develop/ Learn how to develop your .NET application locally using containers.

    Run your tests = https://docs.docker.com/guides/dotnet/run-tests/ Learn how to run your .NET tests in a container.

    Configure CI/CD = https://docs.docker.com/guides/dotnet/configure-ci-cd/ Learn how to Configure CI/CD for your .NET application

    Test your deployment = https://docs.docker.com/guides/dotnet/deploy/ Learn how to deploy your application


clone the repo and do **docker compose up --build** as the app relies on postgres database. Run separately won't work.