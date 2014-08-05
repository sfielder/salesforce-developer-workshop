---
layout: module
title: Creating a Salesforce1 App
---

You will now make your **HotelMap** Visualforce page available in the Salesforce1 mobile app.

## Salesforce1 Setup

1. [Install the Salesforce1 App](http://www.salesforce.com/getsalesforce1/)
2. Launch the app and login with your developer account
3. You should be able to interact with the **Session** and **Speaker** custom objects

## Add the HotelMap to Salesforce1

1. In Salesforce, click the **Setup** link (upper right corner)

     ![](images/setup.jpg)

2. In the left navigation, select **Build** > **Develop** > **Pages**

3. Next to the **HotelMap** item select **Edit**

4. Check the **Available for Salesforce mobile apps** box and click **Save**

5. In the left navigation, select **Build** > **Create** > **Tabs**

6. In **Visualforce Tabs** select **New**

7. Select the **HotelMap** Visualforce page and set the following values
  - Tab Label: **Hotel Map**
  - Tab Name: **Hotel_Map**
  - Tab Style: **Map**

8. Click **Next**, **Next**, **Save**

9. In the left navigation, select **Administer** > **Mobile Administration** > **Mobile Navigation**

10. Select **Hotel Map** from the **Available** list and click **Add**, then **Save**

11. Open the menu in Salesforce1 and pull it down to refresh it.  Select the **Hotel Map** menu item.  Once the app loads you should see the hotel map.

<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="Using-JavaScript-in-Visualforce-Pages.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Previous</a>
<a href="Creating-a-Heroku-App.html" class="btn btn-default pull-right">Next <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
