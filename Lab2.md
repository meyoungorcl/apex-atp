# Lab 2: Create an App From a Spreadsheet

## Introduction

Now that you are logged into your workspace, you can start creating APEX applications. In this lab, you will build a simple application based on a spreadsheet. Keep in mind that APEX scales well, from simple apps to large, sophisticated ones based on local database objects, REST enabled SQL objects, and even REST APIs.

Within the APEX development environment, you will spend the majority of your time in the App Builder. In your own time you should also investigate the SQL Workshop, where you can create and maintain database objects, Team Development, where you can track large APEX development projects, and the App Gallery, which contains numerous productivity and sample apps that can be installed within minutes.

***To log issues***, click here to go to the [github oracle](https://github.com/oracle/learning-library/issues/new) repository issue submission form.

## Lab 2 Objectives

- Load project and tasks data
- Create and run an application

## Steps

### **STEP 1:** Load project and tasks data

-  Click **App Builder**, then click **Create a New App**. {Note: You can also click Create if you already have an app defined}

    ![](images/Lab200/001.png)

- Click **From a File**.

  ![](images/Lab200/002.png)

  When creating an application from a file, APEX allows you to upload CSV, XLSX, XML, or JSON files and then build apps based on their data. Alternatively, you can also copy and paste CSV data or load sample data. 

- Within the wizard, click **Copy and Paste**. From the sample data set list select **Project and Tasks** and click **Next**.

  ![](images/Lab200/003.png)

- Review the pasted data, and for Table Name enter **SPREADSHEET** and click **Load Data**. {Note: The Error Table Name is automatically populated based on the Table Name with a postfix of \_ERR$}

  ![](images/Lab200/004.png)

### **STEP 2:** Create and run an application

The wizard has created a new table and populated that table with the records from the sample data. Now you can create an app based on this new table.

- Click **Continue to Create Application Wizard**.

  ![](images/Lab200/005.png)

- Within the Create Application Wizard, for Name enter **App from a Spreadsheet**, 
for Features click **Check All** and click **Create Application**.

  ![](images/Lab200/006.png)
  
  ![](images/Lab200/007.png)

Now that the wizard has created the app, you should run the app to review what has been created.

- Click **Run Application**.

  ![](images/Lab200/008.png)

- On the Sign In page, enter your database username and password as entered in Lab 1, Step 3. Then click **Sign In**. 

- Click on the **Spreadsheet** option in the navigation menu to view the sample data, then click the edit icon for a record to display the form page. Next, navigate to the **Dashboard** page and review the charts displayed there. Finally, review the options available under **Administration**.

  ![](images/Lab200/009.png)
