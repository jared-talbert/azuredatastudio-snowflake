# SnowflakeSQL extension for Azure Data Studio (preview)

Connect, query, and manage Snowflake databases with Azure Data Studio, a modern data editor available for Linux, MacOS, and Windows. This (preview) extension enables you to interact with Snowflake using Azure Data Studio features like:

* Connect to Postgres anywhere
* Searchable object explorer view for database objects
* Query authoring and editing with Intellisense, syntax highlighting and code snippets
* View query results and save to csv, JSON, xml, or Excel
* Integrated terminal for Bash, PowerShell, and cmd.exe
* Go to Definition and Peek Definition for examining the DDL of objects
* Source control integration with Git
* Customize dashboards and insight widgets using SQL 
* Server groups for organizing connections
* Customizable keyboard shortcuts, multi-tab support, color theme options
* Backup and Restore

See our [quickstart] for a step by step guide to getting started with Snowflake in Azure Data Studio.

## Offline Installation
The extension will download and install a required Snowflake Tools Service package during activation. For machines with no Internet access, you can still use the extension by choosing the
`Install from VSIX...` option in the Extension view and installing a bundled release from our [Releases](https://github.com/jared-talbert/azuredatastudio-snowflake/releases) page.
Each operating system has a .vsix file with the required service included. Pick the file for your OS, download and install to get started.
We recommend you choose a full release and ignore any alpha or beta releases as these are our daily builds used in testing.

## Support
Support for this extension is provided on our [GitHub Issue Tracker]. You can submit a [bug report], a [feature suggestion] or participate in discussions.

## Contributing to the Extension
See the [developer documentation] for details on how to contribute to this extension.

## Code of Conduct
This project has adopted the [Microsoft Open Source Code of Conduct]. For more information see the [Code of Conduct FAQ] or contact [opencode@microsoft.com] with any additional questions or comments.

## Privacy Statement
The [Microsoft Enterprise and Developer Privacy Statement] describes the privacy statement of this software.

## License
This extension is [licensed under the MIT License]. Please see the [third-party notices] file for additional copyright notices and license terms applicable to portions of the software.

[quickstart]: https://docs.microsoft.com/sql/azure-data-studio/quickstart-postgres
[GitHub Issue Tracker]:https://github.com/Microsoft/azuredatastudio-snowflake/issues
[bug report]:https://github.com/jared-talbert/azuredatastudio-snowflake/issues/new?labels=bug
[feature suggestion]:https://github.com/jared-talbert/azuredatastudio-snowflake/issues/new?labels=feature-request
[developer documentation]:https://github.com/jared-talbert/azuredatastudio-snowflake/wiki/How-to-Contribute
[Microsoft Enterprise and Developer Privacy Statement]:https://go.jared-talbert.com/fwlink/?LinkId=786907&lang=en7
[licensed under the MIT License]: https://github.com/jared-talbert/azuredatastudio-snowflake/blob/master/LICENSE
[third-party notices]: https://github.com/jared-talbert/azuredatastudio-snowflake/blob/master/ThirdPartyNotices.txt
[Microsoft Open Source Code of Conduct]:https://opensource.microsoft.com/codeofconduct/
[Code of Conduct FAQ]:https://opensource.microsoft.com/codeofconduct/faq/
[opencode@microsoft.com]:mailto:opencode@microsoft.com
