<properties
	pageTitle="SQL Database tutorial: Create a SQL database | Microsoft Azure"
	description="Learn how to set up a SQL Database logical server, server firewall rule, SQL database, sample data, connect with client tools, configure users, and database firewall rule."
	keywords="sql database tutorial,create a sql database"
	services="sql-database"
	documentationCenter=""
	authors="carlrabeler"
	manager="jhubbard"
	editor=""/>


<tags
	ms.service="sql-database"
	ms.workload="data-management"
	ms.tgt_pltfrm="na"
	ms.devlang="na"
	ms.topic="hero-article"
	ms.date="04/13/2016"
	ms.author="carlrab"/>

# SQL Database tutorial: Create a SQL database in minutes using the Azure portal

**Single database**

> [AZURE.SELECTOR]
- [Azure portal](sql-database-get-started.md)
- [C#](sql-database-get-started-csharp.md)
- [PowerShell](sql-database-get-started-powershell.md)

In this tutorial, you'll learn how to use the Aure portal to:

- Create a SQL Database logical server to host SQL databases
- Create a SQL database with no data, with sanple data or with data fron a SQL database backup.
- Create a server-level firewall rule for a single IP address or for a range of IP addresses.

Use these links to perform these same tasks using either [C#](sql-database-get-started-csharp.md) or [PowerShell](sql-database-get-started-powershell.md).

[AZURE.INCLUDE [Login](../../includes/azure-getting-started-portal-login.md)]

[AZURE.INCLUDE [Create SQL Database logical server](../../includes/sql-database-create-new-server-portal.md)]

[AZURE.INCLUDE [Create SQL Database database](../../includes/sql-database-create-new-database-portal.md)]

[AZURE.INCLUDE [Create SQL Database database](../../includes/sql-database-create-new-server-firewall-portal.md)]

## Next steps
Now that you've completed this SQL Database tutorial and created a database with some sample data, you're ready to explore using your favorite tools.

- If you're familiar with Transact-SQL and SQL Server Management Studio, learn how to [Connect and query a SQL database with SSMS](sql-database-connect-query-ssms.md).

- If you know Excel, learn how to [Connect to SQL database with Excel](sql-database-connect-excel.md).

- If you're ready to start coding, see [Connect and query your SQL database with C#](sql-database-connect-query.md) and [Using SQL database from .NET (C#)](sql-database-develop-dotnet-simple.md). See the [Quick start code samples to SQL Database](sql-database-develop-quick-start-client-code-samples.md) for Node.js, Python, Ruby, Java, PHP and C++ samples and how-to's in addition to C#.

- If you want to move your on-premises SQL Server databases to Azure, see [Migrating a database to Azure SQL Database](sql-database-cloud-migrate.md) to learn more.


## Additional resources

[SQL Database Overview](sql-database-technical-overview.md)

