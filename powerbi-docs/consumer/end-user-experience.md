---
title: Getting around in the Power BI service
description: Overview of the Power BI navigation experience
author: mihart
ms.author: mihart
ms.reviewer: mihart
featuredvideoid: removed
ms.service: powerbi
ms.subservice: pbi-explore
ms.topic: tutorial
ms.date: 01/31/2023
ms.custom: mode-portal, intro-quickstart
LocalizationGroup: Get started
#Customer intent: As a PBI consumer, I want a quick overview of how to navigate PBIS so that I can accomplish work efficiently.
---
# Tutorial - Getting around in Power BI service


Now that you know the [basics of Power BI](end-user-basic-concepts.md), let's take a look around the **Power BI service**. As mentioned in the previous article, colleagues on your team might spend all of their time in [Power BI Desktop](https://powerbi.microsoft.com/desktop/), combining data and creating reports, dashboards, and apps for others. They're *designers* and *creators*. You, on the other hand, might spend all of your time in the Power BI service, viewing and interacting with content created by others (**consuming** experience). You're a *business user*. This tutorial is for *business users* of the Power BI service. 

 
## Prerequisites

- If you're not signed up for Power BI, [sign up for a free trial](https://app.powerbi.com/signupredirect?pbi_source=web) before you begin.
- You can work through this tutorial by using sample content from the Power BI website.

- Read [Power BI service basic concepts](end-user-basic-concepts.md).

- Viewing Power BI content (reports, dashboards, apps) created by *designers* requires one of two conditions:
    - a Power BI Pro or Premium Per User (PPU) license
    - Your organization to have a Power BI Premium subscription, and the content to be shared with you from Premium capacity.    
    [Learn about licenses and subscriptions](end-user-license.md).     

    For the purposes of this tutorial, we aren't requiring either of these conditions to be met. Microsoft has made sample content available to you directly from the Power BI service interface. We'll use this sample content to learn our way around the Power BI service. 

## Open the Power BI service


1. To begin, open the Power BI service (app.powerbi.com), and sign in if you're prompted. 

    ![Screenshot shows the Home page for a new user.](./media/end-user-experience/power-bi-home-page.png)    

1. Select **Learn** and in the **Learning center**, scroll down to **Sample reports**. Select the right arrow until you get to **Sales and Marketing Sample**. Select the sample report.  

   :::image type="content" source="media/end-user-experience/power-bi-sample-list.png" alt-text="Screenshot shows the sample reports on the Learn page.":::

   The **Sales and Marketing Sample** report opens.

   :::image type="content" source="./media/end-user-experience/power-bi-report-opens.png" alt-text="Screenshot shows the Sales and Marketing Sample open.":::

1. The Power BI service installs the sample in **My workspace**, your private sandbox for learning and experimenting. Only you can see your workspace. Select **My workspace** to see details about this sample report.

    :::image type="content" source="./media/end-user-experience/power-bi-my-workspace-new.png" alt-text="Screenshot shows the Power BI screen with a red border around My workspace.":::

    The sample includes one report, one dashboard, and one semantic model. Most content shared with business users doesn't include direct access to the underlying semantic models, but the samples, which are designed for all users, include semantic models.


## View workspace content
The sample content is organized within the context of a workspace. Every business user has at least one workspace, and it's called **My workspace**. You can acquire more workspaces when designers share content with you. For example, if designers assign you access permissions to one of their workspaces, that workspace will show up in your Power BI site.

**My workspace** stores all of the content that you own and create. Think of it as your personal sandbox or work area for your own content. Any sample data that you download from the Power BI Learning Center, is saved in your **My workspace**. 

A workspace is much more than a simple listing of content. On this page, you can learn a lot about the workspace's dashboards, reports, and semantic models. Workspace owners assign permissions to content in a workspace. Your permissions may allow you to take **More actions (...)** on the content in a workspace. Since we're using sample content that is saved in your **My workspace**, you have owner-level permissions by default.

![Screenshot showing App workspace screen with More actions menu displayed for the report.](./media/end-user-experience/power-bi-more-action.png)

From a workspace, you can open a dashboard or report by selecting it from the list.  You can favorite a dashboard or report by hovering and selecting the star icon. If a workspace *owner* gave you [sharing permissions](../collaborate-share/end-user-shared-with-me.md), you can share from here as well. 

Learn more about [Workspaces](end-user-workspaces.md).

## Open a dashboard and a report
A dashboard is a single page that shows visualizations of the most important elements from one or more report. 

1. The Sales and marketing sample has one dashboard. Select the name of the dashboard to open it. 

    :::image type="content" source="media/end-user-experience/power-bi-related-content.png" alt-text="Screenshot of the Related content window.":::

1. The dashboard opens in the Power BI service. Dashboards are something that differentiates the Power BI service from Power BI Desktop. [Learn about dashboards](end-user-dashboards.md).

    ![Dashboards open](./media/end-user-experience/power-bi-dash-open.png)

2. The actions you can take on a dashboard are displayed in the top menu bar. Select **More options (...)** to see the complete list.   

    :::image type="content" source="./media/end-user-experience/power-bi-top-menu-items.png" alt-text="Screenshot of the top portion of the Power BI service.":::

3. The visuals on the dashboard are arranged as *tiles*. Hover over a dashboard tile and select **More options (...)** to see the options you have for interacting with that tile.

    ![Screenshot showing the dropdown menu for a dashboard tile.](./media/end-user-experience/power-bi-tile-menu.png)


4. Select a dashboard tile to open the report that was used to create that tile. The report opens to the page that contains the visual that is on the tile. Here, I've selected the dashboard tile with the treemap. The Power BI service opens the **YTD Category** report page.

    ![Report opens.](./media/end-user-experience/power-bi-report.png)

    A report is made up of one or more pages. In most cases, each page is designed to tell a story and that story is told with visualizations, text, shapes, and images. 

    Reports have several sections. On the left is the clickable list of report pages. Across the top, is the menu bar containing actions you can take with the report.  The options available will depend on the role and permission the report *designer* assigned to you. On the right side is the **Filters** pane. And the center canvas contains the report itself. Similar to the dashboard, there are actions that you can take for the entire report, for individual visuals, and also for a single report page. 

    Learn more about [Power BI reports](end-user-reports.md).

## Using the left navigation pane (nav pane)
The nav pane will become more useful as colleagues share content with you. In this section of the tutorial, we'll look at the Power BI service for a *business user* who works with colleagues who've shared lots of reports, dashboards, and apps. 

:::image type="content" source="media/end-user-experience/power-bi-nav-pane.png" alt-text="Screenshot of the left navigation menu.":::

:::image type="content" source="media/end-user-experience/power-bi-home-icon.png" alt-text="Screenshot of the Home icon."::: 

The top icon in the nav pane is your Power BI **Home**. It's the default landing page when you log in to the Power BI service. Home is a great starting point for viewing and navigating your content. **Home** bring together the searching and sorting tools, the nav pane, and a canvas with *cards* that you can select to open content. At first, you might not have many cards on your Home canvas, but that will change as you start to use Power BI with your colleagues.

![Screenshot of a full Home.](./media/end-user-experience/power-bi-home-page.png)

To learn more, see [Power BI Home](end-user-home.md)

## Browse

:::image type="content" source="media/end-user-experience/power-bi-browse-icon.png" alt-text="Screenshot of the Browse folder icon."::: 

See your full list of favorites, recent, and shared content by selecting **Browse** on the nav pane. Here you find content lists that provide details about reports, apps, and dashboards.

:::image type="content" source="./media/end-user-experience/power-bi-browse.png" alt-text="Screenshot of the Browse page on the navigation pane.":::

For more information, see [Recent content](end-user-recent.md), [Favorite dashboards, reports, and apps](end-user-favorite.md), and [Dashboards and reports that have been shared with me](../collaborate-share/end-user-shared-with-me.md).

## Open Apps

:::image type="content" source="./media/end-user-experience/power-bi-apps-icon.png" alt-text="Screenshot of the Apps icon on the navigation pane.":::

Go directly to your apps by selecting **Apps** on the navigation pane. You might not have any apps yet, but this is the content area that will store  all apps that have been shared with you or that you've installed.

For more information, see [Apps in Power BI](end-user-apps.md).

## Open the Learning center

:::image type="content" source="./media/end-user-experience/power-bi-learn-icon.png" alt-text="Screenshot of the icon for the Learning center.":::
For new users, the Learning center is especially helpful, with getting started content, samples, and links to videos.


### Search and sort content
:::image type="icon" source="./media/end-user-experience/power-bi-search-icon.png":::

When you're new to the Power BI service, you only have a few pieces of content. But as colleagues begin sharing data with you and you begin downloading apps, you might end up with long lists of content. That's when you find searching and sorting extremely helpful.

Search is available from almost every part of the Power BI service. Just look for the search box or search magnifying glass icon.  

In the Search field, you can type all or part of the name of a dashboard, report, workbook, app, or owner. Power BI searches all of your content.

:::image type="content" source="./media/end-user-experience/power-bi-search-field.png" alt-text="Screenshot showing text in the search bar.":::

There are also many ways to sort content. Hover over column headers and look for arrows indicating that the column can be sorted. Not all columns can be sorted.

:::image type="content" source="./media/end-user-experience/power-bi-sort-icon.png" alt-text="Screenshot shows arrow next to Type column heading.":::

Or, look for the search **Filters** near the upper right corner of your content lists. Find content quickly by filtering categories, like type of content or owner.  

:::image type="content" source="./media/end-user-experience/power-bi-filter.png" alt-text="Screenshot showing a search filter for content lists.":::

For more information, see [Navigation for Power BI business users: global search](end-user-search-sort.md).

## Find the owner

And we'll end this tutorial with a helpful tip. If you have questions about a dashboard, report, app, or other content--you can look up the owner. With the content open, select the title menu to display the owner's contact link. The owner or contact may be a person or a group.

:::image type="content" source="./media/end-user-experience/power-bi-owner.png" alt-text="Screenshot showing the title menu where contact information is.":::

## Clean up resources
You can now delete the sample report, dashboard, and semantic model from your **My workspace** if you wish.   

1. Open the Power BI service (app.powerbi.com) and select **My workspace**.  

3. Hover over the report and select **More options (...)** > **Delete**. Repeat to remove the dashboard and semantic model.

   :::image type="content" source="./media/end-user-experience/power-bi-delete.png" alt-text="Screenshot showing the more options dropdown on the My workspace page.":::

## Related content

> [!div class="nextstepaction"]
> [Learn about the Power BI capabilities for business users](end-user-reading-view.md)