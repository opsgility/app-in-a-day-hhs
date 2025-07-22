# App In a Day Environment Validation 

## Section 1: Create a new solution
--------------------------------

In this task, you create a new solution and a publisher. The solution will contain and track all your work.

1. Select **Solutions > + New solution**.

    [![Screenshot of the Solutions list with a red rectangle around the add New solution button.](images/2f4c3ddab2c55db787622cea7319ad28380204b5.svg)](https://learn.microsoft.com/en-us/training/modules/power-apps-canvas-app-online-workshop/media/new-solution.svg#lightbox)

2. Enter `Contoso Coffee` for the **Display name** and then select the **\+ New publisher** button.

    [![Screenshot of the create New solution dialog with a red rectangle around the add New publisher button.](images/7c04cd96155efc20a83b2549e594e074b8df48fa.svg)](https://learn.microsoft.com/en-us/training/modules/power-apps-canvas-app-online-workshop/media/new-publisher.png#lightbox)

3. Enter `Contoso` as the **Display name**, `Contoso` as the **Name**, and `contoso` for **Prefix**. Select **Save**.

    [![Screenshot of the create New publisher dialog.](images/a9f74edc12ea6584479e91d6dcb3a37b59777da0.svg)](https://learn.microsoft.com/en-us/training/modules/power-apps-canvas-app-online-workshop/media/new-publisher-details.svg#lightbox)

4. Select the **Contoso** publisher that you created for **Publisher** and then select **Create**.

    [![Screenshot of the create New solution dialog.](images/166e0a0ecac8bad42caa197476b7f8111d1fbf15.svg)](https://learn.microsoft.com/en-us/training/modules/power-apps-canvas-app-online-workshop/media/new-solution-details.svg#lightbox)

5. Select the **Contoso Coffee** solution that you created.

6. Don't navigate away from this page.

## Section 2: Create a new application
-----------------------------------

In this task, you create a new application by following these steps:

1. Make sure that you're in the **Contoso Coffee** solution.

2. Select **\+ New** and then select **App > Canvas app**.

    [![Screenshot of the create new canvas application button.](images/97422bb1f876fb425987b3782c336f08033ab79d.svg)](https://learn.microsoft.com/en-us/training/modules/power-apps-canvas-app-online-workshop/media/new-canvas-application.svg#lightbox)

3. Enter `Machine Ordering App` in the **App name** field, select the **Tablet** option under **Format**, and then select **Create**.

    [![Screenshot of the create canvas app dialog.](images/906c518d453df8273d64c4ec02f55701283cbc0e.svg)](https://learn.microsoft.com/en-us/training/modules/power-apps-canvas-app-online-workshop/media/create-canvas-app-dialog.svg#lightbox)

4. If prompted, select your region and then select **Get started**.

5. Select **Skip** if you receive the **Welcome to Power Apps Studio** prompt.

## Section 3: Create a custom table

In this task, you create a custom table to store machine order requests.

1. Select **Solutions** and then open the **Contoso Coffee** solution.

2. Select the **\+ New** drop down from the tool bar at the top of the page, hover over the **Table** option and then choose **Table (advanced properties)**.

    [![Screenshot showing the create new button and the Table option.](https://learn.microsoft.com/en-us/training/modules/dataverse-lab-manual-online-workshop/media/new-table.svg)](https://learn.microsoft.com/en-us/training/modules/dataverse-lab-manual-online-workshop/media/new-table.svg#lightbox)

3. Enter `Machine Order` in the **Display name** field. The **Plural name** field automatically populates based on your entry in the **Display name** field. These fields are editable if you need to make changes. The system uses the plural name by default whenever a set of rows are shown.

    Select the **Enable attachments** option because it allows you to create notes on the machine order.

    ![Screenshot showing the New table dialog, with the Display name and Plural name fields filled in.](https://learn.microsoft.com/en-us/training/modules/dataverse-lab-manual-online-workshop/media/new-table-dialog.png)

4. Select the **Primary column** tab.

5. Change the **Display name** field to `Machine Name`. The **Primary** column defaults to being named **Name**. For some scenarios, that label might not be the best one, so you can customize it if needed. However, the **Primary** column is always a text column that isn't changeable.

6. Select **Save**.

    ![Screenshot of the Primary column tab, showing the Display name field changed to Machine Name.](https://learn.microsoft.com/en-us/training/modules/dataverse-lab-manual-online-workshop/media/primary-column.png)

## Section 4: Sign in to the Power Automate website

1. Go to [Power Automate](https://flow.microsoft.com/) and make sure that you're in the **correct environment** where you have been building your apps for these labs.

2. Select **Solutions** and then select to open the **Contoso Coffee** solution.

3. Select **\+ New** and then select **Automation** > **Cloud flow** > **Automated**.

    [![Screenshot showing the create new automated cloud flow option.](https://learn.microsoft.com/en-us/training/modules/integrate-power-apps-online-workshop/media/new-flow.png)](https://learn.microsoft.com/en-us/training/modules/integrate-power-apps-online-workshop/media/new-flow.png#lightbox)