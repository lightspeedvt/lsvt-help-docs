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
2. **Copied From** - _Leave blank for now._
	- This field will be populated automatically if you created this category using the "Copy" feature. If you did not, you can leave this blank for now.
3. **Description**
	- Enter the description of the category. If there was none provided, enter something as a temporary placeholder.
4. **Internal Description**
	- Enter the internal description. This is a LightSpeed viewable field only. This is used to quickly identify which client a category belongs to, or adding other important details, such as recent changes.
5. **Thumb Nail Image Path**
	- Enter the path to the category image (we cover this later in the Artwork Design section.)
6. **Rank**
	- The Rank is the order in which this category will display in the training center. The lower the rank (1, 2, 3, etc.) the _higher_ the category will be listed. Rank 1 = the very first category. Rank 999 = the very last category.
7. **Active Yes/No**
	- Select whether this category should be active or not. (It is perfectly safe to always select "Yes" here - the content will not be on display for anyone until you complete your very last step of this process. We cover that _here_.)
8. **Rollover Image URL**
	- Enter the path to the category rollover image (we cover this later _here_.)
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

A Course is made up of a series of Chapters, a Course description (in text), a Course thumbnail (picture or image representing the Course) and a Course Preview Trailer (video). 

###Create new Course

Click on the **"Courses"** tab at the top of your screen, and then click on **"Create New Course"**.

On the **Create New Course** menu, we see the following fields (click on the image to open it in a new window):

<a href="/img/create_new_course1.png" target="_blank"><img src="/img/create_new_course1.png"/ alt="Click to open this in a new tab"></a>

1. **Name**
	- Enter the name of the course here.
2. **Copied From**
	- This field will be populated automatically if you created this course using the "Copy" feature. If you did not, you can leave this blank for now.
3. **Description**
	- Enter the description of the course. If there was none provided, enter something as a temporary placeholder.
4. **Internal Description**
	- Enter the internal description. This is a LightSpeed viewable field only. This is used to quickly identify which client a course belongs to, or adding other important details, such as recent changes.
5. **Active Yes/No**
	- Select whether this course should be active or not. (It is perfectly safe to always select "Yes" here - the content will not be on display for anyone until you complete your very last step of this process. We cover that _here_.)
6. **Hide Course - Reports**
	- This will show/hide the course in reporting sections.
7. **Hide Course - Search**
	- This will toggle the course from being searchable.
8. **Enable Notes**
	- This will toggle on and off the notes feature for the entire course. Additionally you can control the notes feature at the Group level, and at the Chapter level. This should **always** be set to "Yes" unless indicated otherwise.
9. **Rank**
	- The Rank is the order in which this course will display in the training center. The lower the rank (1, 2, 3, etc.) the _higher_ the course will be listed. Rank 1 = the very first course. Rank 999 = the very last course.
10. **Duration**
	- This field is for the duration, in minutes, of the course. (This feature is currently not in use.)
11. **Complete Chapters in Order**
	- Setting this toggle to "Yes" will force the user to complete the chapters in order.  
12. **Thumb Nail Image Path**
	- Enter the path to the course image (we cover this later _here_.)
13. **Preview Path**
	- Enter the path to the course video preview (If this is your initial build, and you do not have this video yet, you can leave this path blank.)
14. **Author**
	- Enter the name of the author of this material (Usually the client's name - but if it's a collaboration, enter the name of the System, ex. Patricia Fripp, NCM OnDemand, etc.)
15. **Keywords**
	- Add any keywords associated with this course. These should be separated by a pipe "|" - ex. Sales|Selling|Closing
16. **Category Assignment**
	- Select which category this course should go in.
17. **Privileges**
	- You can leave these access level privileges blank. These are for legacy clients that are not yet on Content Containers. If a group is NOT on content containers, then these access levels would be used.
18. **Extended Info**
	- This is for advanced Content Configuration. You can leave this empty for now - this is covered more in the Content Administrator section.
19. **Callout Fields**
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

**A Chapter may consist of...**

* Training parts and a Chapter test.
* Training parts and no test.
* No training parts and only a test.

By default, a test is followed by a "Recap" Chapter part if the user fails to pass the test. (this is optional)

Chapter creation is unique from Categories and Courses in which you can only **"Create New Chapter"** from a **_course_**. So you'll see after you save your course from the previous steps that there is now a **"Create New Chapter"** button at the top. 

Click on that when you're ready to create your chapter.

<img src="/img/create-new-chapter1.png">

###Create New Chapter - Part 1

On the **Create New Chapter** menu, we see the following fields (click on the image to open it in a new window):

<a href="/img/create-chapter-1.png" target="_blank"><img src="/img/create-chapter-1.png"></a>

1. **Name**
	- Enter the name of the chapter here.
2. **Active**
	- You must add at least 1 test question in order for you to receive the option to activate the chapter.
3. **Rank**
	- The Rank is the order in which this chapter will display. The lower the rank (1, 2, 3, etc.) the _higher_ the chapter will be listed. Rank 1 = the very first chapter. Rank 999 = the very last chapter.
4. **Number of Test Questions**
	- Enter the number of test questions that will be pulled for this chapter. If you enter a number here smaller than the total number of test questions active, then it will randomly select that number from that **"pool"** of available questions. For example - if there are 10 active test questions for this chapter, and the number of test questions is set to 5, each time a user takes the test it will randomly serve up 5 of the 10 total questions.
5. **Test Pass Percentage**
	- Enter the minimum test percentage a user must receive in order to pass the test and move on to the next chapter. 
6. **Test Instructions / Setup (Seen before test)**
	- Enter the test instruction text the user will see before starting the test. The default language we use here is: "_This chapter test is a quick check of your knowledge so far. As you select your answers, each question is timed and all results are recorded on your “Report Card.” Click START below when you are ready._"
7. **Test Summary (Passed Test) (Seen upon test completion)**
	- Enter the test summary for when the user passes the test. The default text is already populated if you do not need to change it.
8. **Test Summary (Failed Test) (Seen upon test completion)**
	- Enter the test summary for when the user fails the test. The default text is already populated if you do not need to change it.
9. **Test Type**
	- Your options here are: Standard, Survey, Only Test, No Test. More on testing mechanisms can be found _here_.
10. **Pull Questions in Order By Rank**
	- This will pull all of the test questions in order by rank, and no longer serve them up randomly.
11. **Fail Test on Incorrect**
	- Setting this to "Yes" will cause the user to fail the test on ANY missed question - rather than allowing them to complete the entire test first.
12. **Answer Notifications**
	- Setting this to "Yes" will allow you to enter an email address **_per answer_** which will notify the recipient of that user's answer. This is often used with the Survey test type.
13. **Show Test Stats**
	- This toggle will show or hide the test stats before and after the test. This is often used with the Survey test types.
14. **Show Test Summary Nav Buttons**
	- This toggle will show or hide the navigation buttons after the test.
15. **Enable Notes**
	- This will toggle on and off the notes feature for this specific chapter. Additionally you can control the notes feature at the Group level, and at the Course level. This should **always** be set to "Yes" unless indicated otherwise.
16. **Social**
	- You can enter in social information **per chapter**, more information on that can be found _here_.
17. **Chapter Part Info**
	- You must enter at least "1" chapter part here.

Once you have filled out each field, hit **Save**, and there will be some additional fields to complete before moving on.

###Create New Chapter - Part 2

<a href="/img/create-chapter-2.png" target="_blank"><img src="/img/create-chapter-2.png"></a>

1. **Show Captions**
	- Selecting this button will show the optional Caption fields.
2. **Video Path, Mobile Path, Asset Path**
	- **Video Path**: This is the path to the chapter part media (MP4, PDF, etc.)
		- For a default video for a "LaFR" we use: http://videos.lightspeedvt.com/video_files/coming_soon.mp4
	- **Mobile Path**: This is the path to the mobile encoded version of the above video path.
	- **Asset Path**: This is a legacy field, it is for content that still utilizes flash side assets that lay on top of the video parts, before they were edited into the video itself. Most of the time this can remain empty.
3. **Rehash/Recap - Video Path**
	- A recap HTML file is linked here by default. If the user fails the test then the user will be prompted to take a _recap_ before taking the test again. This HTML file will let the user know they have 1 more chance to pass the test or else they'll have to watch the chapter part over again.
4. **Add Question**
	- This is where you can add test questions to this chapter. We'll cover that in the next section.

<div class="admonition note">
    <p class="first admonition-title">
        Note
    </p>
    <p class="last">
Be sure to hit "Save" before you hit "Add Question" - as you will lose any modifications you have made to the chapter if you do so.</p>
</div>

Once all of the chapter information has been added, you're ready to move on to the next section - adding test questions.


##4. Test Questions (Quick) Overview

There are 4 main testing mechanisms, we'll cover all 4 of those in this sectoin:

1.	Multiple Choice
2.	Drag and Drop / Order
3.	Matching (Match a Term to a Definition)
4.	Fill in the Blank

###Create new Test Question

<a href="/img/create-test-question.png" target="_blank"><img src="/img/create-test-question.png"></a>


1. **Question**
	- Selecting this button will show the optional Caption fields.
2. **SWF File Path (Not Required)**
	- **Video Path**: This is the path to the chapter part media (MP4, PDF, etc.)
		- For a default video for a "LaFR" we use: http://videos.lightspeedvt.com/video_files/coming_soon.mp4
	- **Mobile Path**: This is the path to the mobile encoded version of the above video path.
	- **Asset Path**: This is a legacy field, it is for content that still utilizes flash side assets that lay on top of the video parts, before they were edited into the video itself. Most of the time this can remain empty.
3. **Rehash/Recap - Video Path**
	- A recap HTML file is linked here by default. If the user fails the test then the user will be prompted to take a _recap_ before taking the test again. This HTML file will let the user know they have 1 more chance to pass the test or else they'll have to watch the chapter part over again.
4. **Add Question**
	- This is where you can add test questions to this chapter. We'll cover that in the next section.





Test Timer - we default to 60 seconds, if you wish a higher or lower time please indicate it on the chapter or test question. (you can have different times per question in each chapter)





Now we're ready for...

##5. Topics

1. On the Super User Dashboard, **400 - Application Administration**, click on **408 - Use Topics**
2. Create a topic XML - 

```
	Test
```



