# RabbitMQ Client 3.6.6 .NET 3.5

This repo contains the source for the stable [RabbitMQ.Client 3.6.6][1] but based on .NET 3.5.

The reason for being .NET 3.5 based is so it can be deployed as SQLCLR assembly to SQL Server 2005 and 2012. SQL Server 2014+ supports .NET 4, so the latest [NuGet RabbitMQ.Client][3] can be used and deployed.

## Dependencies

Since the target is .NET 3.5 there is a dependency on System.Threading.dll (.NET 3.5), and that dll is in the [lib folder][2].

## Building from Source

The source should be built with Visual Studio (2015, 2017). As mentioned under Dependencies, you need a reference to the System.Threading.dll in the [lib folder][2].

## License

This package is double-licensed under the Mozilla Public License 1.1 ("MPL") and the Apache License version 2 ("ASL").



[1]: https://github.com/rabbitmq/rabbitmq-dotnet-client/tree/stable
[2]: https://github.com/nberglund/rabbitmq-dotnet-client-3.6.6-stable_net_3.5/tree/master/lib
[3]: https://www.nuget.org/packages/RabbitMQ.Client/