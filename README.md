# BrightTech Solutions - Sales Dashboard# Salesforce DX Project: Next Steps



Welcome to BrightTech Solutions! This project delivers a powerful and intuitive Lightning App that gives sales managers the insights they need to drive success.Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.



## Problem Being Solved## How Do You Plan to Deploy Your Changes?



Sales managers need a centralized dashboard to monitor sales performance, track leads and opportunities, and make data-driven decisions quickly. This custom Sales Dashboard app provides a streamlined interface with all essential sales metrics and tools in one place.Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).



## Learning Objectives## Configure Your Salesforce DX Project



After completing this challenge, you'll be able to:The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.



- Create a custom Lightning App## Read All About It

- Configure app navigation with standard and custom object tabs

- Design a custom home page with key performance components- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)

- Assign the app to user profiles- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)

- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)

## What's Included- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)


### Sales Dashboard Lightning App
A custom Lightning application with:
- Navigation tabs for Leads, Opportunities, Accounts, Reports, and Dashboards
- Custom home page with sales performance widgets
- Integrated utility bar for quick access to tools

### Custom Home Page
Features:
- Hero chart for key metrics visualization
- Report chart displaying flow screen analytics
- Recent items widget for quick access
- Today's tasks container for sales activities

## Project Structure

```
force-app/main/default/
├── applications/
│   └── Sales_Dashboard.app-meta.xml
└── flexipages/
    ├── Sales_Dashboard_Home_Page.flexipage-meta.xml
    └── Sales_Dashboard_UtilityBar.flexipage-meta.xml
```

## Deployment

Deploy to your Salesforce org:
```bash
sf project deploy start --source-dir force-app
```

## Resources

- [Salesforce Lightning App Builder](https://help.salesforce.com/s/articleView?id=sf.lightning_app_builder_overview.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
