# article-search-chrome-plugin
Chrome Plugin to Record Searches for Articles and Display Overlay Info



### Optional signin  
* Google authentication using Hapi plugin **Bell** & **hapi-auth-cookie**
  * Signin enables saving data into database
      * basic user information saved in user object which is in database
  * If not signed in data will still be available but no data can be added (as in read/rejected/forwarded flags)

  ![image](https://cloud.githubusercontent.com/assets/10906215/8267867/19889792-1768-11e5-9157-d6ca69e37344.png)


### Functionality

  This plug-in provides flags to let the user know if an article has been rejected/accepted by any previous viewers. Basic information can be supplied, with more details such as viewer name, decision criteria, etc. supplied upon further drill down.

  ![stage-two](https://cloud.githubusercontent.com/assets/2669229/8267816/16ccd880-1766-11e5-87bf-5ee276948187.png)

  Upon selecting an article, a pop-up form with criteria appears. The user can choose to accept or reject the article. Selecting 'more' takes user to a longer form to supply more detailed information.
  ![stage-three](https://cloud.githubusercontent.com/assets/2669229/8267822/2bf20f0a-1766-11e5-9f9c-f954d4205018.png)

  ![stage-three-accept](https://cloud.githubusercontent.com/assets/2669229/8267835/ca3631c8-1766-11e5-8468-50168534ddc1.png)

  The plug-in also provides access to a dashboard, where the user can see how many articles they have accepted/rejected as well as a timeline of their activity.

  ![user-dashboard](https://cloud.githubusercontent.com/assets/2669229/8267843/34f26ab8-1767-11e5-8083-93b642e91d9f.png)
