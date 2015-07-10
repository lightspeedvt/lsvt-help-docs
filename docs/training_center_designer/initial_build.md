#Initial Build (Look and Feel Real)

This section will cover the initial build steps of creating a Topic, Category, Course, Chapter, and Test question for a Look and Feel Real system. More advanced Configuration steps are covered in the [Content Administrator](/content_admin/) section.

<div class="admonition note">
    <p class="first admonition-title">
        Note
    </p>
    <p class="last">
Even though in the LightSpeed heirarchy the Topics menu comes first, it is an optional componant, so we're going to start with Categories. This is explained in more detail in the Topics section.
    </p>
</div>

##1. Categories Overview

A category is made up of courses, a description (in text), an image tile (picture or image representing the content) and if applicable, a rollover image tile.

To get started, navigate to Manage Content under the Super User Dashboard, **400 - Application Administration**, and then **402 - Content Management.** You will see a screen that looks like this:
		
<img src="/img/content_mgmt.png"/>

----

###Create new Category

From this screen you can either **Search** for an existing category, or **Create a new category**. For this lesson, click on **Create a new category.**

On the **Create New Category** menu, we see the following fields (click on the image to open it in a new window):

<a href="/img/create_new_cat1.png" target="_blank"><img src="/img/create_new_cat1.png"/></a>

Create your category by filling out these fields:

1. **Name**
	- Enter the name of the category here.
2. **Copied From** - <span style="color:red">_Leave blank for now._</span>
	- This field will be populated automatically if you created this category using the "Copy" feature. If you did not, you can leave this blank for now.
3. **Description**
	- Enter the description of the category. If there was none provided, enter something as a temporary placeholder.
4. **Internal Description**
	- Enter the internal description. This is a LightSpeed viewable field only. This is used to quickly identify which client a category belongs to, or adding other important details, such as recent changes.
5. **Thumb Nail Image Path**
	- Enter the image path to the category image. This will be the web URL to where the image is hosted on our cloud server. Because we did not build the image yet, put in a generic path as a placeholder: <span style="color:red">_http://videos.lightspeedvt.com/video_files/client_name/tiles/category_name.jpg_</span>
	- Note: We will cover the image creation and uploading/pathing it to the server later in the [Artwork Design](/artwork_design.md) section. 
6. **Rank**
	- The Rank is the order in which this category will display in the training center. The lower the rank (1, 2, 3, etc.) the _higher_ the category will be listed. Rank 1 = the very first category. Rank 999 = the very last category.
7. **Active Yes/No**
	- Select whether this category should be active or not. (It is perfectly safe to always select "Yes" here - the content will not be on display for anyone until you complete your very last step of this process. We cover that in the [Admin Activation](/admin_activation.md) section.)
8. **Rollover Image URL** - <span style="color:red">_Leave blank for now._</span>
	- Enter the path to the category rollover image - this is similar to the Thumb Nail Image Path above, where you can enter a generic path for now. 
	- Note: We will cover the image creation and uploading/pathing it to the server later in the [Artwork Design](/artwork_design.md) section. 
9. **Pre-composed Yes/No**
	- The default setting here is usually "No". The "No" setting will automatically add rounded edges and a highlight effect to the rollover. If you set this to "Yes", it will assume you are adding the rollover and rounded corners through other means (css, flash, etc.)

Example:

Pre-composed = No | Pre-composed = Yes 
----------------- | ------------------
<img src="/img/pre-composed-no.png"> | <img src="/img/pre-composed-yes.png">

When you have entered all of your information, click **"Save"**, and move on to the next section.

<div class="admonition note">
    <p class="first admonition-title">
        Note
    </p>
    <p class="last">
You may ignore the "VT2GO" section here for now, we'll cover that in a later topic.
    </p>
</div>

----

##2. Courses Overview

A Course is made up of a series of Chapters, a description (in text), an image tile (picture or image representing the content) and a Course Preview Trailer (video). 

###Create new Course

Now that your category is created, you can click on the **"Courses"** tab at the top of your screen, and then click on **"Create New Course"**.

On the **Create New Course** menu, we see the following fields (click on the image to open it in a new window):

<a href="/img/create_new_course1.png" target="_blank"><img src="/img/create_new_course1.png"/></a>

Create your course by filling out these fields:

1. **Name**
	- Enter the name of the course here.
2. **Copied From** - <span style="color:red">_Leave blank for now._</span>
	- This field will be populated automatically if you created this course using the "Copy" feature. If you did not, you can leave this blank for now.
3. **Description**
	- Enter the description of the course. If there was none provided, enter something as a temporary placeholder.
4. **Internal Description**
	- Enter the internal description. This is a LightSpeed viewable field only. This is used to quickly identify which client a course belongs to, or adding other important details, such as recent changes.
5. **Active Yes/No** - <span style="color:red">_Default: Yes_</span>
	- Select whether this course should be active or not. (It is perfectly safe to always select "Yes" here - the content will not be on display for anyone until you complete your very last step of this process. We cover that in the [Admin Activation](/admin_activation.md) section.)
6. **Hide Course - Reports** - <span style="color:red">_Default: No_</span>
	- This will show/hide the course in reporting sections.
7. **Hide Course - Search** - <span style="color:red">_Default: No_</span>
	- This will toggle the course from being searchable.
8. **Enable Notes** - <span style="color:red">_Default: Yes_</span>
	- This will toggle on and off the notes feature for the entire course. Additionally you can control the notes feature at the Group level, and at the Chapter level. This should **always** be set to "Yes" unless indicated otherwise.
9. **Rank**
	- The Rank is the order in which this course will display in the training center. The lower the rank (1, 2, 3, etc.) the _higher_ the course will be listed. Rank 1 = the very first course. Rank 999 = the very last course.
10. **Duration** - <span style="color:red">_Leave blank for now._</span>
	- This field is for the duration, in minutes, of the course. (This feature is currently not in use.)
11. **Complete Chapters in Order** - <span style="color:red">_Default: No_</span>
	- Setting this toggle to "Yes" will force the user to complete the chapters in order.  
12. **Thumb Nail Image Path**
	- Enter the path to the course image. This will be the web URL to where the image is hosted on our cloud server. Because we did not build the image yet, put in a generic path as a placeholder: <span style="color:red">_http://videos.lightspeedvt.com/video_files/client_name/tiles/course_name.jpg_</span>
	- Note: We will cover the image creation and uploading/pathing it to the server later in the [Artwork Design](/artwork_design.md) section.
13. **Preview Path**
	- Enter the path to the course video preview (If this is your initial build, you likely do not have this video yet, so you can leave this path blank for the Content Admin to populate.)
14. **Author**
	- Enter the name of the author of this material (Usually the client's name - but if it's a collaboration, enter the name of the System, ex. Patricia Fripp as an individual, or NCM OnDemand as a collaboration, etc.)
15. **Keywords**
	- Add any keywords associated with this course. These should be separated by a pipe "|" - ex. Sales|Selling|Closing
16. **Category Assignment**
	- Select which category this course should go in. For this exercise you will choose the category you just created.
17. **Privileges**
	- You can leave these access level privileges blank. These are for legacy clients that are not yet on Content Containers. However, if a group is NOT on content containers, then these access levels would be used (but this is rare - all new groups should be on content containers).
18. **Extended Info** - <span style="color:red">_Leave blank for now._</span>
	- This is for advanced Content Configuration. You can leave this empty for now - this is covered more in the Content Administrator section.
19. **Callout Fields** - <span style="color:red">_Leave blank for now._</span>
	- This is for advanced Content Configuration. You can leave this empty for now - this is covered more in the Content Administrator section.


When you have entered all of your information, click **"Save"**, and move on to the next section.

<div class="admonition note">
    <p class="first admonition-title">
        Note
    </p>
    <p class="last">
You may ignore the "VT2GO" section here for now, we'll cover that in a later topic.
    </p>
</div>

----

##3. Chapter Overview

Once a user clicks into a Course, they may select a Chapter of their choice, unless you changed the toggle to require them to take the chapters in order.  

A Course may have as many Chapters as needed. Each Chapter may consist of multiple Chapter parts. Each Chapter part may consist of any number of different media types: video, Flash SWF, PDF document, HTML, etc.. 

* **A Chapter may consist of:**
	* Training parts and a Chapter test.
	* Training parts and no test.
	* No training parts and only a test.

By default, a test is followed by a "Recap" Chapter part if the user fails to pass the test. (this is optional)

Chapter creation is unique from Categories and Courses in which you can only **"Create New Chapter"** from an existing **_course_**. So you'll see after you save your course from the previous section that there is now a **"Create New Chapter"** button at the top. 

Click on that when you're ready to create your chapter.

<img src="/img/create-new-chapter1.png">

###Create New Chapter - Part 1

On the **Create New Chapter** menu, we see the following fields (click on the image to open it in a new window):

<a href="/img/create-chapter-1.png" target="_blank"><img src="/img/create-chapter-1.png"></a>

Create your chapter by filling out these fields:

1. **Name**
	- Enter the name of the chapter here.
2. **Active**
	- You must add at least 1 test question in order for you to receive the option to activate the chapter.
3. **Rank**
	- The Rank is the order in which this chapter will display. The lower the rank (1, 2, 3, etc.) the _higher_ the chapter will be listed. Rank 1 = the very first chapter. Rank 999 = the very last chapter.
4. **Number of Test Questions** - <span style="color:red">_Default: 1_</span>
	- Enter the number of test questions that will be pulled for this chapter. If you enter a number here smaller than the total number of test questions active, then it will randomly select that number from that **"pool"** of available questions. For example - if there are 10 active test questions for this chapter, and the number of test questions is set to 5, each time a user takes the test it will randomly serve up 5 of the 10 total questions.
	- Note: You will not be able to activate this chapter until this number matches the number of test questions added.
5. **Test Pass Percentage** - <span style="color:red">_Default: 100_</span>
	- Enter the minimum test percentage a user must receive in order to pass the test and move on to the next chapter. 
6. **Test Instructions / Setup (Seen before test)**
	- Enter the test instruction text the user will see before starting the test. The default language we use here is: <span style="color:red">This chapter test is a quick check of your knowledge so far. As you select your answers, each question is timed and all results are recorded on your “Report Card.” Click START below when you are ready.</span>
7. **Test Summary (Passed Test) (Seen upon test completion)**
	- Enter the test summary for when the user passes the test. The default text is already populated if you do not need to change it.
8. **Test Summary (Failed Test) (Seen upon test completion)**
	- Enter the test summary for when the user fails the test. The default text is already populated if you do not need to change it.
9. **Test Type** - <span style="color:red">_Default: Standard_</span>
	- Your options here are: Standard, Survey, Only Test, No Test. More on testing mechanisms can be found _here_.
10. **Pull Questions in Order By Rank** - <span style="color:red">_Default: No_</span>
	- This will pull all of the test questions in order by rank, and no longer serve them up randomly.
11. **Fail Test on Incorrect** - <span style="color:red">_Default: No_</span>
	- Setting this to "Yes" will cause the user to fail the test on ANY missed question - rather than allowing them to complete the entire test first.
12. **Answer Notifications** - <span style="color:red">_Default: No_</span>
	- Setting this to "Yes" will allow you to enter an email address **_per answer_** which will notify the recipient of that user's answer. This is often used with the Survey test type.
13. **Show Test Stats** - <span style="color:red">_Default: Yes_</span>
	- This toggle will show or hide the test stats before and after the test. This is often used with the Survey test types.
14. **Show Test Summary Nav Buttons** - <span style="color:red">_Default: Yes_</span>
	- This toggle will show or hide the navigation buttons after the test.
15. **Enable Notes** - <span style="color:red">_Default: Yes_</span>
	- This will toggle on and off the notes feature for this specific chapter. Additionally you can control the notes feature at the Group level, and at the Course level. This should **always** be set to "Yes" unless indicated otherwise.
16. **Social** - <span style="color:red">_Leave blank for now._</span>
	- You can enter in social information **per chapter**.
17. **Chapter Part Info** - <span style="color:red">_Default: 1_</span>
	- You must enter at least "1" chapter part here.

Once you have filled out each field, hit **Save**. After the course is created there will be some additional fields to complete before moving on.

###Create New Chapter - Part 2

<a href="/img/create-chapter-2.png" target="_blank"><img src="/img/create-chapter-2.png"></a>

1. **Show Captions** - <span style="color:red">_Leave blank for now._</span>
	- Selecting this button will show the optional Caption fields.
2. **Video Path, Mobile Path, Asset Path**
	- **Video Path**: This is the path to the chapter part media (MP4, PDF, etc.)
		- For a default video for a "LaFR" we use: <span style="color:red">http://videos.lightspeedvt.com/video_files/coming_soon.mp4</span> - this is a path to a placeholder "Coming Soon" video. This is used so we can show our clients a completed system without actually having any of their content ready.
	- **Mobile Path**: This is the path to the mobile encoded version of the above video path. <span style="color:red">Leave Blank for now.</span>
	- **Asset Path**: This is a legacy field, it is for content that still utilizes flash side assets that lay on top of the video parts, before they were edited into the video itself. Most of the time this can remain blank. <span style="color:red">Leave blank for now.</span>
3. **Rehash/Recap - Video Path**
	- A recap HTML file is linked here by default. If the user fails the test then the user will be prompted to take a _recap_ before taking the test again. This HTML file will let the user know they have 1 more chance to pass the test or else they'll have to watch the chapter part over again.
4. **Add Question** - <span style="color:red">Be sure to hit "Save" before you hit "Add Question" - as you will lose any modifications you have made to the chapter if you do so.</span>
	- This is where you can add test questions to this chapter. We'll cover that in the next section.

Once all of the chapter information has been added, you're ready to move on to the next section - adding test questions.


##4. Test Questions (Quick) Overview

There are 4 main testing mechanisms, we'll only cover #1 in this section. More on test questions can be found in the [Content Administrator](/content_admin/) section:

1.	Multiple Choice
2.	Drag and Drop / Order
3.	Matching (Match a Term to a Definition)
4.	Fill in the Blank

###Create new Test Question

<a href="/img/create-test-question.png" target="_blank"><img src="/img/create-test-question.png"></a>

After your chapter has been saved, click on **"Add Question"** and follow the steps below.

1. **Question**
	- This is where you enter the question text. For this exercise, we'll enter a placeholder question. Enter this text into the Question field: <span style="color:red">Did you understand everything in this chapter?</span>
2. **SWF File Path (Not Required)** - <span style="color:red">_Leave blank for now._</span>
	- This field is named for some legacy test question content, and it is used presently for new content - but for this exercise you can leave it blank for now.
3. **SWF Data (not required)** - <span style="color:red">_Leave blank for now._</span>
	- This field is similar to the one above - it is used for some legacy content and it is also used for new content - but for this exercise you can leave it blank for now.
4. **Question Active** - <span style="color:red">_Default: Yes_</span>
	- This is a simple toggle - this will default to yes.
5. **Question Rank**
	- This field will increase in rank for each test question you add. It is only used when the chapter toggle **"Pull Questions in Order by Rank"** is set to **"Yes"**.
6. **Answer A) & B)**
	- This field is for the first possible test question answer. For this exercise enter this as the answer: <span style="color:red">Yes</span>
	- In the **Answer B)** field, enter: <span style="color:red">No</span>
7. **Show Correct / Inc.** - <span style="color:red">_Default: Checked_</span>
	- These checkboxes will be selected by default. If this is unchecked, after a user answers a test question, the **"Correct"** and **"Incorrect"** dialogue pop-ups will not be active.
8. **Response Action** - <span style="color:red">_Default: None_</span>
	- This drop-down box is where you can setup an answer response. You can either select a video response or a text response. If a video response is selected (FLV), then you will enter a path to that video in the **Response Info** field. If Text is selected, then you will enter your text answer response in the **Response Info** field.
9. **Response Info** - <span style="color:red">_Leave blank for now._</span>
	- This field will be filled out only if the Response Action field is active.
10. **Points** - <span style="color:red">_Leave blank for now._</span>
	- You can assign a point value to each different answer. This feature was designed to eventually lead to a "Leaderboard" where users can see how they rank against other users. Currently this feature is disabled, but the field was left here for when the development team eventually circles back to it.
11. **Correct Answer**
	- Here you can select "Any / All Correct", or any individual answer. If you hold **Ctrl/Command** you can select more than one answer. For this exercise select answer "A".
12. **Question Timer** - <span style="color:red">_Default: 60_</span>
	- Here you can set, in miliseconds, how long the question timer should be. We default to 60 seconds.

Once all of the fields are complete, hit **"Save"** and then click on the chapter name at the top of the screen to return to the chapter menu. From there you can now activate the chapter. 

###Next Steps

And that is it. You should have now successfully created a Category, Course, Chapter and Test Question.

Now, if your initial build calls for it, let's quickly cover the Topics menu. Topics are different from the rest because (as of 6/16/2015) there hasn't been an Admin menu created for it.

So let's dive right in...

##5. Topics

The topics menu in LightSpeed VT is a simple way to group categories together and display them in a condensed format. Remember - the reason we do this step last is because now you can add your list of Categories to your topic menu. Also please note that this step may be completely optional to your build - depending on the outline.

First, we want to add the topic information to the database, and then we'll create an XML file that will list all of the topics and categories. We'll then upload that XML to the cloud server and finally update the theme to access the topics menu.

###Add the Topic to the Database

To get started let's add the topic to the database. We do this from the Super User Dashboard, **400 - Application Administration**, and then click on **408 - Use Topics**

<a href="/img/use_topics.png" target="_blank"><img src="/img/use_topics.png"></a>

On this screen there are only 2 fields to worry about:

1. **Topic**
	- Enter the name of your topic - it needs to be lower case, and with no special characters or spaces. Example: **ABC Motors** you might call it: **abc_motors** - and please note that this should match the topic XML File.
2. **XML File**
	- This name should be the same as topic name you entered above, except we add the word **"topics_"** and **".xml"** to the filename. For example, **abc_motors** will now be: **topics_abc_motors.xml** in this field.

This step is now complete.

###Create the Topic XML

Now you're ready to create a topic XML. <span style="color:red">Download a Sample <a href="http://videos.lightspeedvt.com/video_files/acme/downloads/topics_abc_motors.zip" target="_blank">Here</a></span>

1. **Duplicate an existing topic XML**
	- Download an existing topic XML to your desktop and rename it to the same filename you just entered in the previous step. Ours will be named: **topics_abc_motors.xml** - Or download the sample XML file above and edit that one.
	- Topics are stored in this folder on the lsvt-cloudfront server: lsvt-cloud-front/topics
2. **Configuration via XML**
	- The topics menu uses XML configuration files to specify settings. The following values are supported:

		- **Title** - HTML formatted text that will be displayed over the topic icons. Note the usage of CDATA tags.

```

<title><![CDATA[<b>Welcome to... :</b> Please select a topic library below.]]></title>

```

>> - **Topics** - Listing of topic nodes as well as listing how many columns to display this as. (typically we use 2, 3 or 4 columns)

```

<topics columns="3">

```
>> - **ID** - Unique identifier (Typically we just increase this by 1 per topic)
>> - **SRC** - The web URL path to the tile to be displayed (typically a JPG or PNG)
>> - **Rollover** - The web URL path to the tile to be displayed as the rollover image (typically a transparent PNG file)
>> - **Url** - <span style="color:red">(Optional)</span> - If the topic should link to anywhere other than the categories list you can add a URL path of where that topic should link to. (please this between the "label" and the "description" values)
>> - **UrlTarget** - <span style="color:red">(Optional)</span>  - Include this after the URL value to indicate opening a new window (blank), same window (self), etc.
>> - **Label** - This is the Topic name (displayed below the topic on the topic screen, as well as the cookie crumb once selected) 
>> - **Description** - <span style="color:red">(Optional)</span>  - Topic description (displayed on the categories screen once a topic is selected)
>> - **Categories** - Comma delimited list of category ids for this topic

```

<topic id="001" src="http://videos.lightspeedvt.com/video_files/top_image1.jpg" rollover="http://videos.lightspeedvt.com/topic_image2_rollover.png" url="http://www.google.com" urlTarget="_blank" label="Sales Training" description=" " categories="3251,3201"/>

```

Here is an example of what it looks like all put together:

```

<data>

<title><![CDATA[<b>Welcome to... :</b> Please select a topic library below.]]></title>

<topics columns="3">

<topic id="001" src="http://videos.lightspeedvt.com/video_files/top_image1.jpg" rollover="http://videos.lightspeedvt.com/topic_image2_rollover.png" url="http://www.google.com" urlTarget="_blank" label="Sales Training" description=" " categories="3251,3201"/>

</topics>

</data>

```

When that is ready, upload it to the cloud under the **lsvt-cloud-front/topics** folder.

###Update the Carousel and Top Navigation links in the Themer

##5a. Legacy Themer

Let's add your new topic XML file to the system now. We do that in the Themer. For the legacy themer, navigate to the Super User Dashboard, **400 - Application Administration**, and then click on **403 - Manage Legacy Themes**

1. **Select Your Theme**
	- Select the theme you are modifying from the drop-down menu. We'll be modifying two menus - the main menu carousel, and the top navigation bar.
2. **Update the Main Menu Coursel**
	- Select the Main Menu tab at the top
	- Hover over the "Select" link to identify which carousel panel is currently linking to the Training Center, and click on the pencil/edit icon. The link will be something like: /v4/training_center.cfm, or /tc/
	- Once that menu appears, update the Link Url - you will want it to say: /v4/training_center.cfm?type=**abc_motors** (where abc_motors is the name of the TOPIC you entered way up at the beginning of this lesson) and then click Save.
3. **Update the Top Nav bar**
	- Click on the Top Nav tab at the top of the screen and then click on the Pencil/Edit icon next to the "Training Center" menu link.
	- Modify that link the same way you did for the main menu, adding "**?type=abc_motors"** to the end of the url so it reads: "/v4/training_center.cfm?type=abc_motors" and then hit save.

<div class="admonition note">
    <p class="first admonition-title">
        Important Note
    </p>
    <p class="last">
When you are done managing a theme, be sure to return to the <strong>"Select Group"</strong> tab and select LightSpeed VT - Mission Control. This will place you back at your home location group so you cannot accidentally overwrite any settings.
    </p>
</div>

##5b. Themer T-1000

Let's add your new topic using the new Themer. Navigate to the Super User Dashboard, **400 - Application Administration**, and then click on **403 - Manage Themes**

1. **Select Your Theme**
	- Select the group are modifying from the drop-down menu **(1)**, and then click on **"Edit Theme"** next to the group **(2)** (see screenshot below). We'll be modifying two menus - the main menu carousel, and the top navigation bar. Both of these can be found under the **"Components"** menu in the top nav area.<br /><br />
![Image](/img/t-1000-1.png)<br /><br />
2. **Update the Main Menu Carousel**
	- Select the Main Menu Carousel from the Components tab at the top
	- Click on **"Edit"** next to the **"Training Center"** Carousel<br /><br />
	![Image](/img/t-1000-2.png)<br /><br />
	- Now update the Link Url - you will need to add **"?type=abc_motors"** to the end of the URL, so it should say: /v4/training_center.cfm?type=**abc_motors** (where abc_motors is the name of the TOPIC you entered way up at the beginning of this lesson) and then click Update.<br /><br />
	![Image](/img/t-1000-3.png)<br /><br />
3. **Update the Top Nav bar**
	- Select **"Menus"** from the Components tab at the top.
	- Find the **"Top Nav Menu"** From the list of menus (usually it is the first one)
	- Click on **"Edit"** next to the **"Training Center"** line<br /><br />
	![Image](/img/t-1000-4.png)<br /><br />
	- Now update the Link Url - similar to what you just did on the Carousel - you will need to add **"?type=abc_motors"** to the end of the URL, so it should say: /v4/training_center.cfm?type=**abc_motors** (where abc_motors is the name of the TOPIC you entered way up at the beginning of this lesson) and then click Update. <span style="color:red">**Note:** This is a good example, where this link is currently pointing to **/tc/** - so you'll want to replace that link completely with the information above.<br /><br />
	![Image](/img/t-1000-5.png)<br /><br />


Now your theme is updated, let's move on to the next section... [Artwork Design!](training_center_designer/artwork_design.md)



	


















