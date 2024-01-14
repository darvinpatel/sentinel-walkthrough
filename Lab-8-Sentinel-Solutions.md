# Microsoft Sentinel Content Hub

## Objectives

In this module you will learn how to use the Microsoft Sentinel Content Hub to discover and deploy new content. Our official documentation on this topic is available here: [Microsoft Sentinel Content hub catalog](https://docs.microsoft.com/azure/sentinel/sentinel-solutions-catalog).

#### Prerequisites

This module assumes that you have completed [Lab 1](Lab-1-Setting-up-the-environment.md), as you will need a Microsoft Sentinel workspace provisioned.

## Step 1: Explore the Microsoft Sentinel Content hub

This exercise guides you through the Content Hub catalog.

1. From the Microsoft Sentinel portal, navigate to **Content hub** (under **Content Management**).



2. In the search bar, type **Cloudflare**. You will see a single result corresponding to Cloudflare solution. You could also search using the filtering options at the top.

   ![](/images/4File.jpg)

3. Select the Cloudflare solution. As you can see on the right pane, here we have information about this solution, like category, pricing, content types included, solution provider, version and also who supports it. Click **Install**.


4. Notice the different artifacts that are included in this solution: Data Connector, Parser, Workbook, Analytics Rules and Hunting Queries. Each Solution can contain a different set of artifacts.

    ![](/images/3File.jpg)

5. Feel free to navigate to other solutions. In the next exercise, we will install one of them.

## Step 2: Deploy content from Content Hub Catalog.

This exercice guides you through installing Standalone content and Solutions from the Content Hub catalog.

#### Task 1: Deploy standalone content items

We're going to look at a few items available standalone in the Content hub.

#### Workspace Usage Report Workbook

Find the Workspace Usage Report workbook.

#### Other useful standalone Workbooks

You can optionally search for, explore and Save these workbooks:
  
| Title                         | Description                                           |
| ------                        | ------                                                |
| **Analytics Health & Audit**  | Displays Sentinel rule execution and health 
| **AMA migration tracker**     | Helps understand how clients are connecting to the workspace
| **Insecure Protocols**        | If monitoring SecurityEvent from Windows hosts, identifies usage of poorly-secured protocols
| **SOC Handbook**              | A structured workbook you can edit to reflect your SOC processes
   
## Summary

In this module your learned how to use the Microsoft Sentinel content hub to bring new content into your workspace.

