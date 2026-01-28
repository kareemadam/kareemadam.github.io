---
layout: "default"
title: "🚀 QueryDump - Export Your Database Queries Easily"
description: "📊 Export database data to Parquet, CSV, or another database with ease, while ensuring low memory use and supporting data anonymization and transformation."
---
# 🚀 QueryDump - Export Your Database Queries Easily

[![Download QueryDump](https://img.shields.io/badge/Download_QueryDump-Here-brightgreen)](https://github.com/kareemadam/QueryDump/releases)

## 🛠️ Overview

QueryDump is a performance-focused command-line tool designed to help you export database queries quickly and efficiently. Whether you need to save data in Parquet or CSV formats, QueryDump has built-in data masking capabilities to ensure your sensitive information stays secure. 

This tool is ideal for users who regularly handle large datasets and want to streamline their export process without needing deep technical knowledge.

## 💻 System Requirements

To run QueryDump, ensure your system meets the following requirements:

- Operating System: Windows 10 or later, MacOS Catalina or later, or a suitable Linux distribution.
- .NET Core 3.1 or later installed on your machine.
- A database connection to Oracle, SQL Server, or DuckDB.

## 📦 Download & Install

To get started, visit this page to download: [QueryDump Releases](https://github.com/kareemadam/QueryDump/releases).

Once on the releases page, follow these steps:

1. Locate the latest version of QueryDump.
2. Download the appropriate version for your operating system. 
3. Follow the installation instructions for your OS to set up QueryDump on your machine.

## 🔍 Features

- **Export Options:** Save your data in both Parquet and CSV formats.
- **Data Masking:** Protect sensitive information in your datasets by applying built-in data masking techniques.
- **Performance Optimization:** Designed for swift data exports, handling large queries without lag.
- **User-Friendly Interface:** Easily accessible through the command line without complex setup.

## ⚙️ Usage Guidelines

After installing QueryDump, you can start using it by opening your command line interface (CLI). Here's how to run it:

1. Open your terminal or command prompt.
2. Navigate to the directory where QueryDump is installed.
3. Use the following command structure to export your data:

   ```
   QueryDump --source <database_connection_string> --output <output_file_path> --format <parquet|csv>
   ```

### 👥 Command Parameters

- `--source`: This parameter requires your database connection string. Replace it with your actual connection details.
- `--output`: Specify the complete path for the output file (e.g., `C:\exports\mydata.csv`).
- `--format`: Choose the format in which you'd like to save your data (either `parquet` or `csv`).

### 📖 Example Command

Here’s an example of how to use QueryDump:

```
QueryDump --source "Server=myServer;Database=myDB;User Id=myUser;Password=myPass;" --output "C:\exports\mydata.csv" --format csv
```

This command will connect to your database and export the data to a CSV file at the specified location.

## 🌟 Tips for Success

- Ensure your database credentials are correct to avoid connection issues.
- Use the data masking feature if you are dealing with sensitive information.
- Regularly check for updates on the releases page to take advantage of new features and improvements.

## ⚡ Frequently Asked Questions

### How do I find my database connection string?

Your connection string is specific to your database setup. If you're unsure, consult your database documentation or ask your database administrator.

### Can I export data from multiple databases?

Yes, you can run separate queries for each database by executing multiple instances of QueryDump.

### Is QueryDump safe for handling sensitive data?

Yes, QueryDump includes data masking capabilities to ensure that sensitive information does not get exposed during exports.

## 🛠️ Support & Contributions

If you encounter issues or have questions, please visit the [Issues page](https://github.com/kareemadam/QueryDump/issues) for support. Contributions are welcome, and you can follow the guidelines provided in our repository to help improve QueryDump.

## 🚀 Additional Resources

For more insights on how to maximize your use of QueryDump, consider visiting our [Wiki](https://github.com/kareemadam/QueryDump/wiki) for tutorials and advanced usage techniques.

## 🎉 Get Started Today!

To download QueryDump, visit this page: [QueryDump Releases](https://github.com/kareemadam/QueryDump/releases). 

With QueryDump, exporting your database queries has never been easier!