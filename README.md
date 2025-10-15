# BrightTech Solutions - Sales Dashboard

Welcome to BrightTech Solutions! This project delivers a powerful and intuitive Lightning App that gives sales managers the insights they need to drive success.

## Problem Being Solved

Sales managers need a centralized dashboard to monitor sales performance, track leads and opportunities, and make data-driven decisions quickly. This custom Sales Dashboard app provides a streamlined interface with all essential sales metrics and tools in one place.

## Learning Objectives

After completing this challenge, you'll be able to:

- Create a custom Lightning App
- Configure app navigation with standard and custom object tabs
- Design a custom home page with key performance components
- Assign the app to user profiles

## What's Included

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
