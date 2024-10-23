## Overview

[Tableau](https://www.tableau.com/) is a powerful data visualization and business intelligence tool that helps users to analyze data and create interactive dashboards.

The `ballerinax/tableau` package provides APIs to connect and interact with [Tableau REST API](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm) endpoints, specifically designed to enable operations such as retrieving data, managing users and workbooks, and publishing content to Tableau Server or Tableau Cloud.


## Setup guide

To use the Tableau connector, you must have access to the Tableau REST API through a [Tableau Developer Account](https://www.tableau.com/developer), and you must have created a project and an API token for authentication. If you do not have a Tableau Developer account, you can sign up for one [here](https://www.tableau.com/developer).

### Step 1: Create a Tableau Developer Account

1. Sign up for a [Tableau Developer Account](https://www.tableau.com/developer).

2. Access the [Tableau Developer Portal](https://onlinehelp.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm) to explore API documentation and projects you might want to connect to.

### Step 2: Create a Personal Access Token (PAT)

1. Sign in to your Tableau Server or Tableau Cloud account and navigate to the **My Account Settings** page.

    ![Create Personal Access Token](https://help.tableau.com/current/api/rest_api/en-us/images/create-pat.png)

2. Under the **Personal Access Tokens** section, click **Create a new token**.

3. Provide a **Token Name** and click **Create**. You will receive the **Token Value** that serves as the access token. Store it securely as it will not be shown again.

    ![Token Value](https://help.tableau.com/current/api/rest_api/en-us/images/token-value.png)

4. Make sure to store the **Token Value** and the **Token Name** for later use in your application.

### Step 3: Get Your Tableau Server or Tableau Cloud URL

You will need to use the Tableau Server URL or Tableau Cloud URL for the API requests. For Tableau Server, use the server's base URL. For Tableau Cloud, use the URL provided in your account dashboard.

Example Tableau Cloud URL: `https://10ax.online.tableau.com`

### Step 4: Obtain Your Site ID

1. To interact with the Tableau REST API, you will also need the **Site ID**. The Site ID can be found on the Tableau account's site management page.

2. In Tableau Server, the Site ID is usually displayed in the URL when you navigate to a specific site: 
    ```
    https://your-server-name/#/site/<site-id>/projects
    ```

    In Tableau Cloud, it can also be found in the URL in a similar format.

## Quickstart

[//]: # (TODO: Add a quickstart guide to demonstrate a basic functionality of the module, including sample code snippets.)

## Examples

The `Tableau` connector provides practical examples illustrating usage in various scenarios. Explore these [examples](https://github.com/module-ballerinax-tableau/tree/main/examples/), covering the following use cases:

[//]: # (TODO: Add examples)
