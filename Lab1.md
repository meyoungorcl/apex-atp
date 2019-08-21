# Lab 1: Obtain a Workspace

## Introduction

Oracle Application Express (APEX) is a feature of Oracle Database, including the Autonomous Data Warehouse (ADW) and Autonomous Transaction Processing (ATP) services. To start, you will need to create an ATP instance and then access APEX from within the Service Console. 

When you first go into APEX you will need to log in as an APEX instance administrator to create a workspace. A workspace is a logical domain where you define APEX applications. Each workspace is associated with one or more database schemas (database users) which are used to store the database objects, such as tables, views, packages, and more. These database objects are generally what you base APEX applications on.

***To log issues***, click here to go to the [github oracle](https://github.com/oracle/learning-library/issues/new) repository issue submission form.

## Lab 1 Objectives

- Log in to your Oracle Cloud account
- Create an Autonomous Transaction Processing instance
- Create a new workspace in APEX
- Log in to your new workspace

## Steps

### **STEP 1:** Log in to your Oracle Cloud account

- You should have signed up for your Oracle Cloud trial account. If not, return to the Workshop Introduction page and complete Step 1.

- Once you receive the **Get Started Now with Oracle Cloud** email, make note of your **Username**, **Password**, and **Cloud Account Name**.

- From any browser go to [https://cloud.oracle.com/en_US/sign-in](https://cloud.oracle.com/en_US/sign-in)

- Enter your **Cloud Account Name** in the input field and click the **Next** button.

  ![](images/Lab100/001.png)

- Enter your **Username** and **Password** in the input fields and click **Sign In**.

  ![](images/Lab100/002.png)

### **STEP 2:** Create an Autonomous Transaction Processing instance

- From the Cloud Dashboard, select the navigation menu icon in the upper left-hand corner and then select **Autonomous Transaction Processing**.

  ![](images/Lab100/003.png)

- Click **Create Autonomous Database**.

  ![](images/Lab100/003a.png)

- Leave all of the default selections, enter a password for the ADMIN user, then click **Create Autonomous Database**. Remember the password as it will be required later on.

  ![](images/Lab100/003b.png)
  ![](images/Lab100/003c.png)
  ![](images/Lab100/003d.png)

  After clicking **Create Autonomous Database**, you will be redirected to the Autonomous Database Details page for the new instance. Continue to the next step when the status changes from **PROVISIONING...** to **AVAILABLE**.

### **STEP 3:** Create a new workspace in APEX

- Click the **Service Console** button.

  ![](images/Lab100/003f.png)

- Click **Development** option in the menu on the left, then click the **Oracle Application Express** option.

  ![](images/Lab100/004.png)

- Enter the password for the Administration Services and click **Sign In to Administration**. The password is the same as the one entered for the ADMIN user when creating the ATP instance.

  ![](images/Lab100/005.png)

- Click **Create Workspace**.
  
  ![](images/Lab100/006.png)

- Enter your database user details and click **Create Workspace**:
  -  Database User = **DEMO**
  -  Password = <Your Password> {Note: The password must conform to Oracle Autonomous standards}
  -  Workspace Name = {Will default to Database User}
  
  ![](images/Lab100/007.png)

- Click the Account Menu (top right of the screen) and click **Sign Out**. This will log you out of APEX administration so that you can log into your new workspace. Once logged out, click the **Return to Sign In Page** button.
	
  ![](images/Lab100/008.png)

- Enter your workspace details and click **Sign In**.

![](images/Lab100/009.png)
