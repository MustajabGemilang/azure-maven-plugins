# Maven Plugins for Azure Services
This repository contains all Maven plugins for Microsoft Azure services. A complete list of all plugins is shown as below. Visit our [Wiki](https://github.com/microsoft/azure-maven-plugins/wiki) for detailed documentation.

Maven Plugin | Maven Central Version | Build Status
---|---|---
[Maven Plugin for Azure Web Apps](./azure-webapp-maven-plugin/README.md) | [![Maven Central](https://img.shields.io/maven-central/v/com.microsoft.azure/azure-webapp-maven-plugin.svg)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.microsoft.azure%22%20AND%20a%3A%22azure-webapp-maven-plugin%22) | [![AppVeyor Webapp Plugin](https://ci.appveyor.com/api/projects/status/0vr4svfgl9u3rcaw/branch/develop?svg=true)](https://ci.appveyor.com/project/xscript/azure-maven-plugins-xt3xm)
[Maven Plugin for Azure Functions](./azure-functions-maven-plugin/README.md) | [![Maven Central](https://img.shields.io/maven-central/v/com.microsoft.azure/azure-functions-maven-plugin.svg)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.microsoft.azure%22%20AND%20a%3A%22azure-functions-maven-plugin%22) | [![AppVeyor Function Plugin](https://ci.appveyor.com/api/projects/status/5jti4qwh0j4ekh72/branch/develop?svg=true)](https://ci.appveyor.com/project/xscript/azure-maven-plugins-vvy0i)
[Maven Plugin for Azure Spring Cloud](./azure-spring-cloud-maven-plugin/README.md) | [![Maven Central](https://img.shields.io/maven-central/v/com.microsoft.azure/azure-spring-cloud-maven-plugin.svg)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.microsoft.azure%22%20AND%20a%3A%22azure-spring-cloud-maven-plugin%22) | 

## Feedback and Questions
To report bugs or request new features, file issues on [Issues](https://github.com/microsoft/azure-maven-plugins/issues). Or, ask questions on [Stack Overflow with tag azure-java-tools](https://stackoverflow.com/questions/tagged/azure-java-tools).

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once in all repositories using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Telemetry
This project collects usage data and sends it to Microsoft to help improve our products and services.
Read Microsoft's [privacy statement](https://privacy.microsoft.com/en-us/privacystatement) to learn more.
If you would like to opt out of sending telemetry data to Microsoft, you can set `allowTelemetry` to false in the plugin configuration.
Please read our [documents](https://aka.ms/azure-maven-config) to find more details.