# Module 2: Create an App from a Spreadsheet

## Introduction

Now that you are logged into your workspace, you can start creating APEX applications. In this module, you will build a simple application based on a spreadsheet. Keep in mind that APEX is great for a variety of apps, from simple ones like this to large, sophisticated apps based on local database objects, REST enabled SQL objects, and even REST APIs.

While APEX developers spend the majority of their time in the App Builder, you should also investigate the SQL Workshop, where you can create and maintain database objects, Team Development, where you can track large APEX development projects, and the App Gallery, which contains numerous productivity and sample apps that can be installed within minutes.

***To log issues***, click here to go to the [github oracle](https://github.com/oracle/learning-library/issues/new) repository issue submission form.

## Module 2 Objectives

- Load project and tasks data
- Create and run an application

## Parts

### **Part 1:** Load project and tasks data

1. Click **App Builder**, then click **Create a New App**. {Note: You can also click Create if you already have an app defined}

   ![](images/2/create-a-new-app.png)

2. Click **From a File**.

   ![](images/2/from-a-file.png)

   When creating an application from a file, APEX allows you to upload CSV, XLSX, XML, or JSON files and then build apps based on their data. Alternatively, you can also copy and paste CSV data or load sample data. 

3. Within the wizard, click **Copy and Paste**. From the sample data set list select **Project and Tasks** and click **Next**.

   ![](images/2/project-and-tasks-data.png)

4. Review the pasted data, and for Table Name enter **SPREADSHEET** and click **Load Data**. {Note: The Error Table Name is automatically populated based on the Table Name with a postfix of \_ERR$}

   ![](images/2/load-data-settings.png)

### **Part 2:** Create and run an application

The wizard has created a new table and populated that table with the records from the sample data. Now you can create an app based on this new table.

1. Click **Continue to Create Application Wizard**.

   ![](images/2/load-data-results.png)

2. Within the Create Application Wizard, for Name enter **App from a Spreadsheet**, 
for Features click **Check All** and click **Create Application**.

   ![](images/2/create-app-options.png)
  
   ![](images/2/create-app-options-2.png)

   Now that the wizard has created the app, you should run the app to review what has been created.

3. Click **Run Application**.

   ![](images/2/run-app.png)

4. On the Sign In page, enter your database username and password as entered in Lab 1, Step 3. Then click **Sign In**. 

5. Click on the **Spreadsheet** option in the navigation menu to view the sample data, then click the edit icon for a record to display the form page. Next, navigate to the **Dashboard** page and review the charts displayed there. Finally, review the options available under **Administration**.

   ![](images/2/app-home-page.png)

## Summary

This completes Module 2. You now know how to create applications on top of data imported from other sources, such as spreadsheets. Use the navigation menu to navigate to Module 3.