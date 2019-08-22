# Module 4: Create and Modify an APEX App

## Introduction

In this module, you will create a new application that will utilize the database objects you created in the previous module. You will create and modify an application with an Interactive Grid and Calendar page.

***To log issues***, click here to go to the [github oracle](https://github.com/oracle/learning-library/issues/new) repository issue submission form.

## Module 4 Objectives

- Create an Interactive Grid
- Enhance the Interactive Grid
- Save the report settings
- Add a Calendar page

## Parts

### **Part 1:** Create an Interactive Grid

1. Click **Create App from Script**. Note: If you are back on SQL Scripts and don’t see the **Create App from Script** button, perform the following steps:
   - Within the Results column, click “1” for the script you just ran.
   - Under View Results, click the magnifying glass. The results page shown above should now be displayed again.

   ![](images/4/create-app-from-script.png)

2. For Name, enter **Projects** and click **Appearance**. For Theme Style, select **Vita-Slate** and click **Save Changes**.

   ![](images/4/app-name-and-appearance.png)

3. For Features, click **Check All**.

   ![](images/4/app-features.png)

4. Click **Create Application**.

  ![](images/4/create-application.png)

5. Your new application will be displayed in Page Designer. Click **Run Application**.

   ![](images/4/run-application.png)

6. Enter your credentials and review your new application.

   ![](images/4/app-home-page.png)

7. From the development environment, click **App Builder**, and then select **Create**.

   ![](images/4/navigate-to-create.png)

8. Click **New Application**.

   ![](images/4/new-application.png)

9. In the Create App Wizard, click **Load Blueprint** and for Projects, click **Load**. 

   ![](images/4/load-blueprint.png)

10. Click **Add Page** and then click **Interactive Grid**.

    ![](images/4/add-page.png)

11. For Page Name, enter **Milestones**, for Table or View, select **HOL_MILESTONES** and click **Add Page**.

    ![](images/4/add-interactive-grid-page.png)

12. Click and hold the mouse when hovering over the hamburger for the Milestones – Interactive Grid page. Move it up until the page is under Projects and release the mouse.

    ![](images/4/drag-milestones-under-projects.png)

13. For Milestones – Interactive Report with Form page, click **Edit** and then click **Delete**.

    ![](images/4/delete-form-page.png)

14. Click **Create Application**. In Page Designer, click **Run Application**.

    ![](images/4/app-home-page-2.png)

15. In the runtime environment, click **Milestones**.

    ![](images/4/navigate-to-milestones.png)

### **Part 2:** Enhance the Interactive Grid

1. In the Developer Toolbar, click **Edit Page 6**.

   ![](images/4/edit-page-6.png)

2. In Page Designer, under Milestones, click **Columns** and click **PROJECT_ID**.

   ![](images/4/project-id.png)

3. In the Property Editor, update the following and click **Save and Run the App**.
   -  Identification: Type – select **Select List**
   -  Heading: Heading – enter **Project**
   -  List of Values: Type – select **SQL Query**
   -  List of Values – SQL Query enter **select name d, id r from hol_projectsorder by 1**
   -  Display Extra Values – click **No**
   -  Display Null Value – click **No** 

   ![](images/4/configure-project-id.png)

4. Select one of the projects in the list and you see that it is now a select list.

   ![](images/4/project-as-select-list.png)

5. Select the list to see all the projects you can select from.

   ![](images/4/project-select-list-open.png)

6. You can also select one of the Due Date values to see the Date Picker widget is available.

   ![](images/4/date-picker.png)

7. You can change the columns that are displayed. Click **Actions** and select **Columns**.

   ![](images/4/actions-columns.png)

8. Uncheck some of the columns. In this case, uncheck Row Version, Updated and Updated By and click **Save**.

   ![](images/4/uncheck-displayed.png)

9. To see all of the Milestones grouped by Project, you need to add a control break on the **Project** column. Click **Actions** and select **Format** > **Control Break**.

   ![](images/4/control-break.png)

10. Select the **+** and select the **Project** column, then click **Save**.

    ![](images/4/control-break-settings.png)

11. Note that the control break on Project was applied.

    ![](images/4/milestones-with-control-break.png)

### **Part 3:** Save the report settings

1. You want to save this report so you don't need to apply the changes you just made every time. Click **Actions**, select **Report**, select **Save As**.

   ![](images/4/save-as.png)

2. Select **Alternative** for Type, enter a Name and click **Save**.

   ![](images/4/alternative-report.png)

3. Note the Report List in the Interactive Tool bar is now available. If you want to go back to the Primary Report, you can select it from the list.

   ![](images/4/view-alternative-report.png)

### **Part 4:** Add a Calendar page

1. You want to create a schedule of all your projects in a calendar. Click the Application link in the developer toolbar.

   ![](images/4/developer-toolbar.png)

2. Click **Create Page**.

   ![](images/4/create-page.png)

3. Select **Calendar** and click **Next**.

   ![](images/4/calendar-page.png)

4. Enter **Calendar** for Page Name, select **Breadcrumb** for Breadcrumb and click **Next**.

   ![](images/4/calendar-page-attributes.png)

5. Select **Create a new navigation menu entry** and click **Next**.

   ![](images/4/calendar-navigation-menu.png)

6. Select **HOL_PROJECTS** for Table / View Name and make sure only the following columns are in the right column and click **Next**.

   - ID
   - ROW Version
   - Name
   - PROJECT_LEAD
   - STATUS
   - COMPLETED_DATE

   ![](images/4/calendar-source.png) 

7. Select **NAME** for Display Column, **COMPLETED_DATE** for Start Date Column and End Date Column and click **Create**.

   ![](images/4/calendar-settings.png)

8. Click **Save and Run Page**.

   ![](images/4/run-page.png)

9. The Calendar is displayed. You may need to change the month to see any projects. Note that the new Calendar page is an entry in the Navigation Menu.

   ![](images/4/view-calendar-page.png)

**This completes the Lab!**
