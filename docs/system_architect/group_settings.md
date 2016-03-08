##Overview

###System Information

This section controls general system information.

Note: We use the term "Legacy" for more than a few of these settings. Legacy means the toggle or setting only exists because OLD Systems may use the toggle, and that newer methods have been invented to update the toggle or setting. Anything marked Legacy will direct you where to go to update the setting in question.

![Image](/img/system_settings_system_information1.png)<br />

1. **System Name**
    - This is where we set the name of the System - you should never edit this (Accounting only)
2. **Exit URL**
    - This is the URL to take the user to once they sign out. Clicking the Sign Out button will first end the user's session with LightSpeed and then take them to the URL. Typically this is set to the client's login page.
<br /><br />
    ![Image](/img/system_settings_system_information2.png)<br /><br />
3. **System Active Yes/No**
    - This toggle will activate/deactivate the system.
4. **System Status**
    - Choose from: In Factory, Live, Preso (Presentation), or Internal
5. **System Description**
    - This area is to briefly describe the System.

###Content Containers

![Image](/img/system_settings_content_containers1.png)<br />

Here we can assign a system to a Content Container. This is how we keep the content isolated so that it is not possible (without severe human error) for content to cross over into unintended systems. It is possible for multiple systems to pull all from the same Container - but it is not possible for one system to pull from multiple Containers.

1. **Use Content Container Yes / No**
    - If this system is not yet attached to a container, you will be given the option to create one for it. If this system is already attached to a container, you will be given the option to manage that container.
2. **Auto Populate Content Roles Yes / No** - <span style="color:red">Default: No</span>
    - It is possible to auto-populate content roles based on access levels. For example, if you want to ensure that when a "Manager" access level is assigned, you can auto-populate the desired Management Content Roles. This makes it easier to ensure each user is receiving the proper content when being created - either by a human or through the API.
3. **Content Role and Access Level Instructions**
    - Here you can customize the instructions that users/managers see on the front end when selecting Content Roles and Access Levels for users. Examples are:<br /><br />
        - **Content Roles:** Content Roles determine what content a user sees, you can set a user to as many content roles as desired.<br /><br />
        - **Access Levels:** Specify below the Access Level desired for this user - the Access Levels determine if this user is a Manager that can view reports, or just a standard Employee. A user can be set to only one Access Level at a time. 

###System Settings

Below are the System settings and notes about how they work and what they do, and the default setting for each.

1. **Allow SU B Extended Privileges** - <span style="color:red">Default: No</span>
    - This allows the SUPER USER B access level to be enabled to grant different system admin privileges. If this is YES, then each desired "Super User B" needs specifically to be touched to be set - it is not a "carte blanche" setting for SUBs at this system.
2. **Search Enabled** - <span style="color:red">Default: Yes</span>
    - This will turn on/off the search feature.
3. **Favorites Enabled** - <span style="color:red">Default: Yes</span>
    - This will turn on/off the Favorites feature.
4. **Ratings Enabled** - <span style="color:red">Default: Yes</span>
    - This will turn on/off the Ratings feature.
5. **Show Chapter Extras (TC Tubes)** - <span style="color:red">Default: Yes</span>
    - This will turn on/off the "tubes" that appear below chapter titles in the training center.
6. **File Vault Active / Friendly Name (Legacy)** - <span style="color:red">Default: Yes</span>
    - This will turn on/off the File Vault. You can also rename the File Vault here for Legacy systems. Any newer system using Themer 2.0 will need to be renamed in there.
7. **Show Teams** - <span style="color:red">Default: Yes</span>
    - When teams are ON, each location has their own ability to create their own teams. The team names are location specific, they are not shared across the whole system.
    - **Use Teams Plus** - This setting puts the teams into a "genealogy" - where when the Access Level "Mgr-C" (Access level 6) is set to a "Team Leader" - then they only see users that are on their team. More information can be found <a href="http://support.lightspeedvt.com/teams-plus/" target="_blank">HERE</a>.
8. **Show Job Positions** - <span style="color:red">Default: No</span>
    - This will activate a new drop-down when creating or editing users to assign them a Job Position. A Super User B with the "Manage Systems" privilege can manage the Job Positions. This setting is "System Wide" (not able to be different per location)
9. **Show User Interests (Legacy)** <span style="color:red">Default: No</span>
    - This is a feature that was partially built and not ready for use.
10. **Show Lock Username/Password** <span style="color:red">Default: No</span>
    - This is a feature that is useful when there is another system integrated into LSVT, where the other system is controlling/creating usernames and passwords - such as NCM, and you want to have a Toggle on the user's profile where they cannot update/change the username or password. This is so it does not get out of sync with the integration.
11. **Use HTML Main Menu (Legacy)** <span style="color:red">Default: Yes</span>
    - This is a toggle to switch between the main menu using Flash code or HTML code. This needs to be YES for all new clients.
12. **Use Blue Steel (HTML Training Center) (Legacy)** <span style="color:red">Default: Yes</span>
    - Similar to the toggle above, this is a toggle to switch between using Flash or HTML. This needs to be YES for all new clients.
13. **Use Boilerplate** <span style="color:red">Default: Yes</span>
    - The Boilerplate is the most basic component of the LSVT platform and represents the global UI of the system. It may help to think of it as the "Page Template" of the system. This toggle is controlled by the System Design team when they create the initial theme and will be set to YES for all new clients.
14. **Use Main Menu 5000** <span style="color:red">Default: Yes</span>
    - This toggle goes hand-in-hand with the Boilerplate and Themer 2 - the System Design team will toggle this when they create the initial theme and it will be set to YES for all new clients.
15. **Use Themer 2** <span style="color:red">Default: Yes</span>
    - This will enable the System to use the new Themer. As above, the System Design team will toggle this when they create the initial theme and it will be set to YES for all new clients.
16. **Enable Notes (HTML Training Center / Report in Search)** <span style="color:red">Default: Yes</span>
    - This toggle will control the "My Notes" tab that shows up on the left side of the video player in the Training Center. There is also an over ride at the COURSE and CHAPTER level, in case a client has something like a "Final Compliance Course" where they do not want NOTES on that particular course or chapter available.
17. **Mobile Skip Video Disable** <span style="color:red">Default: No</span>
    - Mobile devices by default can fast forward through content. Enabling this toggle will check the length of the chapter, say 5 minutes, and if the user completes the chapter before that 5 minute runtime, it will prevent them from moving forward to the test or next chapter, and they'll be forced to watch the chapter again.
18. **VMS Enabled (Legacy)** <span style="color:red">Default: No</span>
    - This feature is in progress and not ready for LIVE yet.
19. **Calendar Enabled** <span style="color:red">Default: Yes</span>
    - On legacy systems, this turns on automatically in the System Modules on the Main Menu. On newer systems, the System Design team must manually add the button to the Theme. This is a System wide setting.
20. **Google Analytics Account ID**
    - This is an account number specifically for this client. It allows the client to utilize Google Analytics to track usage around their system. This is typically added by the System Design team.
21. **TC Home Icon URL (Legacy)**
    - Use this to override the HOME icon URL in the Training Center. Example: /tc/#/trainingcenter/topics/acme_main - this is a Legacy setting. On new systems, this Home Icon URL is controlled in the Themer 2.
22. **TC Use New Category Layout** <span style="color:red">Default: No</span>
    - Changing this to "Yes" will make the category menu in the Training Center look like Topics.
23. **TC Layout Column Count** 
    - If the New Layout setting (Above) is set to "Yes" - this setting will control how many columns to lay the Categories out in. Typically "3" is a good default.
24. **Boilerplate Theme URL**
    - This URL is added by the System Design team, it tells the System which CSS file to use for the Theme.

###Language Settings

1. **Enable Google Translation** <span style="color:red">Default: Yes</span>
    - Google Translate is a basic machine translation that will translate the text on all of the pages and screens of our System, it will not translate any text on graphics or video content.
2. **Enable Smartling Translation** <span style="color:red">Default: No</span>
    - If utilizing Smartling, then turn off "Google Translation." Also, when using Smartling, you need to select which languages you want to use for this System. Once done, there may be a few words to "translate" per System, depending on what buttons they may have renamed.

More information on Language and System Localization can be found <a href="https://sites.google.com/a/lightspeedvt.com/lsvt-employee-wiki/localization" target="_blank">HERE</a>.

###Enrollment

As a default, this is a System setting, however it can also be configured per Theme - so it is possible that many multiple Enrollment emails can be configured into one System.

This feature allows Admins and Managers (who have the privilege to "Create Users") to easily enroll users at their location. 

Detailed information on steps to configure this can be found on the Knowledge Base <a href="http://support.lightspeedvt.com/enrollment-feature/" target="_blank">HERE</a>. 

###Location Settings

Here you can set the "Max Users Exceeded Error Message." If a Location has a Maximum Users limit, and an Admin or Manager attempt to create another user, this is the error message they will see on the screen.

The Default text is: This location has exceeded the maximum number of active users. Please contact support.

Typically you will want to customize this per client/System and include an email or support number to contact.

###LightPad Settings

The LightPad is User-to-user messaging within the VT System. This communication features can also be utilized to send SMS Text messages and emails to users as well, if configured to do so. (NOTE: This is an optional feature that can be disabled.)

1. **Enable LightPad Yes/No** <span style="color:red">Default: Yes</span>
    - This will turn off or on the LightPad
2. **LightPad From Address**
    - This field is not required - if left blank it will default to "support@lightspeedvt.com". If the client has a support email address you will enter that here.
3. **Custom LightPad Support Yes/No**
    - This feature is nicknamed the “Ask The Expert” feature, where users can send a message to a pre-determined admin user that you can specify. You can use this to have a feature where users can interact with you and you can respond, within the System. Common uses for this are: “Ask The Expert,” “Notify Support,” etc.
4. **LightPad Support Title**
    - This is the Title of the custom support message. Example: Ask Tony Robbins!
5. **Support Button Name** 
    - This is the name of the button users click to send a message to support. Example: Click Here for Help.
6. **Support Image** 
    - Enter the path to the Image. This image appears next to the support verbiage.
7. **Support Recipient** 
    - Enter the Username of the person who will receive these messages.
8. **Support Verbiage** 
    - Enter the Support Verbiage. This text appears on the main LightPad form.
9. **Extended Instructions** 
    - Enter the Extended Instructions. This text appears on the page where the user sends the message.

![Image](/img/system_settings_lightpad.png)<br />

###Message Delivery Options

These settings control which message delivery options are available to users of the System. 

Once these options have been toggled to YES, they become available to to add to each user. This flexibility allows some users to opt for Emails, Text Messages, or LightPad messages only, based on their personal preference.

Once toggled to "Yes", a new tab will appear on both the location "Manage Users" screen and the Super User Dashboard, "Search and Manage all Users" screen, for the users of that System.

Adding each delivery option to a User will prompt you for more information, either adding an email address or phone number for text messages.

Once the delivery methods have been added to each user, when you create a new message in the LightPad and choose the recipients, an icon will appear next to the users name based on which delivery method is available.

1. **Message Delivery - LightPad** <span style="color:red">Default: Yes</span>
    - This will turn on or off the ability to send a message to other users via the LightPad. 
2. **Message Delivery - SMS** <span style="color:red">Default: No</span>
    - This will turn on or off the ability to send a message to other users from the lightpad to the user's email. (Note: In order to reply to the message, the user would have to login to the system and navigate to the LightPad.) 
3. **Message Delivery - Email** <span style="color:red">Default: No</span>
    - This will turn on or off the ability to send a message to other users from the lightpad to the user's cell phone.
4. **Sendgrid Subuser**
    - This feature in progress and not yet ready for LIVE.

Note: If the LightPad is enabled, at least one delivery option must be selected in order for it to function. 

###Watchdogs

The Watch Dog feature is a series of reports where, in theory, a “watch dog” is placed at certain areas of the System and “barks” when it sees something it is told to look for. It can push these reporting details out to you via email and/or SMS Text Messages. These reports can be activated under System Settings, and configured per location as desired.

1. **Watchdog Enabled Yes/No** <span style="color:red">Default: Yes</span>
    - 
2. **Training Expectations Friendly Name** 
    - 
3. **Progress Report Friendly Name**
    - 
4. **User Tracker Friendly Name**
    - 



###Search Settings

This is an open field for users to search for content in the Training Center by title, description and keyword. We can also add a drop-down contextual menu to force desired search words/phrases.

1. **Use Search Terms Yes/No** <span style="color:red">Default: No</span>
    - 
2. **Search Terms** 
    - 


###Certification Settings (Legacy)

**Note to Brian: double check on where these are set... in System or Themer? Both?

1. **My Certification Name (Legacy)** 
    - 
2. **Certification Reports Name (Legacy)** 
    - 

###Usage Reports Friendly Name (Legacy)


1. **My Usage Name (Legacy)** 
    - 
2. **Quick Links Usage Name (Legacy)** 
    - 


###Report Card Friendly Name (Legacy)


1. **My Report Card (Legacy)** 
    - 
2. **Quick Links Report Card Name (Legacy)** 
    - 


###No Access Custom Message

If a user attempts to click on an area of the training center that they do not have access to, you can customize that error message here.

1. **No Access Custom Message (Legacy)** 
    - 

###Auto Email Upon User Creation



###Pass Back URL Settings

###System Images

###Main Menu Welcome Message Config

###WebHooks Settings

###Notes and Attachments



