# Introduction

The Azure Cosmos DB for MongoDB Migration extension helps you assess your MongoDB workload to Azure Cosmos DB. The end-to-end assessment helps you find out the necessary actions you may need to take to seamlessly migrate your workloads to Azure Cosmos DB.

The report presents findings at the account, database, and collection levels, each marked as Critical, Warning, or Informational based on severity to aid prioritization. These include

- **Unsupported Features and Syntax**: It flags unsupported MongoDB features, commands, query syntax, and index types, with usage frequency to prioritize fixes.

- **Resource-Specific Recommendations**: Each finding includes the affected resource name, actionable recommendations, and relevant technical details for remediation.

- **Environment Overview**: Summarizes key aspects of the source MongoDB environment—such as version, license, instance type, and stats for databases and collections.

- **Compatibility and Platform Constraints**: Details Cosmos DB-specific quotas, limits, and potential shard key incompatibilities for sharded workloads.

## Telemetry

VS Code collects usage data and sends it to Microsoft to help improve our products and services. Read our [privacy statement](https://go.microsoft.com/fwlink/?LinkID=528096&clcid=0x409) to learn more. If you don’t wish to send usage data to Microsoft, you can set the `telemetry.enableTelemetry` setting to `false`. Learn more in our [FAQ](https://code.visualstudio.com/docs/supporting/faq#_how-to-disable-telemetry-reporting).

## Privacy Statement

To learn more about our Privacy Statement visit [this link](https://go.microsoft.com/fwlink/?LinkID=824704).

## License

Copyright (c) Microsoft Corporation. All rights reserved.
This extension is licensed under the [EULA](https://github.com/Azure/ads-extension-mongo-migration-assets/blob/main/migrationextension_license.md).
