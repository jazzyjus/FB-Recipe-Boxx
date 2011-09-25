Recipe Boxx -- Open Graph Custom Actions using Facebook JS SDK
===============================================================

This is a simple one page app showing how to publish custom actions using the Facebook JS SDK.

This app is based on the Recipe of the Day app in the [Facebook Example Gallery](http://developers.facebook.com/docs/samples/)

Before running the code, create a Facebook application. 

Make sure that you've created the following objects and actions, using the Open Graph tab under your application in the [Developer App](https://developers.facebook.com/apps):

 * **Action: Cook** 
    * Cook is an action that is connected to a Recipe

 * **Object: Recipe**
 

Once you have taken these steps, edit lavacake.html these variables and upload the pages to the hosting server: YOUR_APP_ID, YOUR_NAMESPACE, YOUR_URL

If you encounter any problems you can use the [Debug Tool](http://developers.facebook.com/tools/debug) under Related links to make sure you've set up the objects correctly by entering the url of the Open Graph pages.


**Notes**

 * The quickest way to setup your actions and objects is as follows:
   * Under Open Graph, click on "Getting Started"
   * Specify - People can [cook] a [recipe] - then complete the wizard without changing anything. This will create a Cook action and a Recipe object and link them together.
