---
layout: post
title: Conference on Javascript
date: 2017-09-10 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: js-1.png # Add image post (optional)
tags: [Js, Conference] # add tag
---
Kiddy-Up is an application that assists parents in building and managing the child's routine by collecting pertinent scheduling information from multiple online sources and presenting the information to each child at a grade-appropriate level. 

Kiddy-Up application focuses on taking third party calander API's or utilizing the built in calander to import and parces events. These events are parced to either user accounts or to precreated sub children accounts, SpaCy uses natural language processing to parces and handle event duplications and collisions. 

Events will then be displayed using preselected age comprehension levels to display events in age approaprate interfaces. In addition to basic interface customization, users can create impliment a rewards system for one or all sub children accounts. 

Kiddy-Up repository can be acccessed at [GitHub][1].

 The following is a walkthrough of the basic use and functionality of Kiddy-Up

[1]: https://github.com/LightWaveEmpire/Kiddy-Up       "Kiddy-Up"


<h1> Walkthrough</h1>


<h2>Glossery</h2>
1. Getting Started
	1. [Creating an Account](#Creating-an-Account)
	2. [Changing Your Password](#Change-Password)
2. Accessing Kiddy-Up as a Parent
	1. [Logging In](#Logging-into-Kiddy-Up-as-a-Parent)
	2. [Account Setup](#Setting-up-Your-Kiddy-Up-Account)
		1. [Adding Children](#Adding-Children)
		2. [Adding Rewards](#Adding-Rewards)
		3. [Adding Tasks](#Adding-Tasks)
	3. [Parent Dashboard](#Parent-Dashboard)
	4. [Manage Children](#Manage-Children)
	5. [Manage Rewards](#Manage-Rewards)
	6. [Manage Tasks](#Manage-Tasks)
3. Accessing Kiddy-Up as a Child
	1. [Logging In](#Logging-into-Kiddy-Up-as-a-Child)
	2. [Child Dashboard](#Child-Dashboard)
	3. [Tasks](#Tasks)
	4. [Rewards](#Rewards)
	6. [Configure Child Account](#Child-Configuration)




<h2>Getting Started</h2>

<h3>Creating an Account <a name="Creating-an-Account"></a> </h3> 


	To create an account, go to the Kiddy-Up website and select "Register" from the top navigation bar.

![Macbook]({{site.baseurl}}/assets/img/1.jpg)

	Enter a unique username, a valid email address, and a password in the fields provided.

	You must use a password that meets certain complexity rules:

		Must contain 8 or more characters

		Must not be similar to the user's name or email address

		Must not be too common

		Must not be entirely numeric


	Press "Register".

![Macbook]({{site.baseurl}}/assets/img/2.jpg)

	You will be sent an email to complete your registration.

![Macbook]({{site.baseurl}}/assets/img/3.jpg)

	Clicking the registration link in the received email will finalize your accoun creation and you will be logged into Kiddy-Up as a parent.

<h3>Change Password <a name="Change-Password"></a> </h3>


	If you need to change your password, go to the login page and select the "Lost password?" link.


![Macbook]({{site.baseurl}}/assets/img/4.jpg)


	Enter your email address and press "Reset password"


![Macbook]({{site.baseurl}}/assets/img/5.jpg)


	You will receive an email with a link to reset your password. Click the link in the email to go to the Change Password page.

![Macbook]({{site.baseurl}}/assets/img/6.jpg)

	Enter your new password twice and click the "Change my password" button.

![Macbook]({{site.baseurl}}/assets/img/7.jpg)

	Now you can log in to Kiddy-Up using your username and new password.

![Macbook]({{site.baseurl}}/assets/img/8.jpg)

<h2>Accessing Kiddy-Up as a Parent </h2>

<h3>Logging into Kiddy Up as a Parent <a name="Logging-into-Kiddy-Up-as-a-Parent"></a> </h3>

	To login to Kiddy-Up, select "Login" from the top navigation bar.


![Macbook]({{site.baseurl}}/assets/img/9.jpg)


	Enter your username and password and press "Login".


![Macbook]({{site.baseurl}}/assets/img/10.jpg)


	You will be logged into Kiddy-Up as a parent and redirected to the Parent Dashboard.

<h2>Setting up Your Kiddy Up Account  <a name="Setting-up-Your-Kiddy-Up-Account"></a> </h2>


	Kiddy-Up provides the user the ability to add and manage children and rewards within the settings page.

<h3>Access Settings</h3>

![Macbook]({{site.baseurl}}/assets/img/11.jpg)


	To access the settings page, click your profile picture in the top-right corner. A dropdown menu will appear with a link to the settings page. When the link is pressed, you will be taken to the settings page as shown below.

<h3>Settings Options</h3>

![Macbook]({{site.baseurl}}/assets/img/12.jpg)

	The settings page allows you to add and edit your Zip Code, your Children,  the Rewards, and the ability to link your Google calendar and task list for automated task import

	From this page you can add and edit children or rewards, click on the edit button next to the desired item.

<h3>Setup Zip Code</h3>

	The parents also have the option to add a zip code to their account. Adding a zip code provides the parents and the children with custom weather forecasts.

![Macbook]({{site.baseurl}}/assets/img/13.jpg)


	You can edit the zip code should you move locations. Click on the link named “edit”  in the Zip Code section and you will be shown an update page. Enter in the new zip code, then press save.


<h2>Adding Children <a name="Adding-Children"></a> </h2>

	To add a child, scroll to the children section of the settings page and click on add child.

![Macbook]({{site.baseurl}}/assets/img/14.jpg)

	You will be shown an “add child” page with the following rows for a child: PIN/Image Code, child name, target reward, age, comprehension level, and point balance. Fill in the information on this page then press save to save new child.

![Macbook]({{site.baseurl}}/assets/img/15.jpg)

<h2>Adding Rewards <a name="Adding-Rewards"></a> </h2>

	To add a reward, scroll to the reward section of the settings page and click on add reward.

![Macbook]({{site.baseurl}}/assets/img/16.jpg)

	You will be shown an “add reward” page with the following rows for a reward: Reward name and cost. Fill in the information on this page then press save to save new reward.


![Macbook]({{site.baseurl}}/assets/img/17.jpg)


<h2>Adding Tasks <a name="Adding-Tasks"></a></h2>

	Parents have three options for adding tasks into Kiddy-Up for the tasks to be shown to the children. The parents can either link to their online calendars, add a task manually, or fill out an entry form. All three of these options can be accessed through the settings page.

<h3>Automated Task Syncing</h3>

	To link to Google and pull your tasks and events, go to the bottom of the settings page and click on the Link Account link.

![Macbook]({{site.baseurl}}/assets/img/18.jpg)


	You will be redirected to the Google Accounts login pages, asking for your google email and password. You will be asked to grant permission to Kiddy-Up to read your calendar events and tasks.
	
	Enter your Google accout email when prompted.

![Macbook]({{site.baseurl}}/assets/img/19.jpg)

	Enter your Google password.


![Macbook]({{site.baseurl}}/assets/img/20.jpg)


	You will see on the bottom of the settings page that your Google account is now linked. You can now click the Get Google Events and Tasks link to import your tasks and events from Google.

![Macbook]({{site.baseurl}}/assets/img/21.jpg)

<h3>Manual Task Entry</h3>

	The manual task entry option allows parents to enter a task written in conversational English. The task is then added to the appropriate child's dashboard. You access the manual task entry from the bottom of the settings page.

![Macbook]({{site.baseurl}}/assets/img/22.jpg)


	After entering in the details of the task for the child, press Save.

![Macbook]({{site.baseurl}}/assets/img/23.jpg)

<h3>Add Task by Form</h3>

	To add a task by form, access the link at the bottom of the settings page.

![Macbook]({{site.baseurl}}/assets/img/24.jpg)


	This form allows you to enter in each attribute of your child's task. After entering in the details of the task for the child, press Save.

![Macbook]({{site.baseurl}}/assets/img/25.jpg)

<h2>Parent Dashboard <a name="Parent-Dashboard"></a></h2>

	The Dashboard page provides an overview of assigned and completed tasks and the children's earned rewards.

	The Parent's Kiddy-Up navigation bar is accessible on all Parent pages and contains links to the Dashboard, all the children's tasks, all the rewards the children can earn, all the children, and the Child login screen. It also contains the parent's profile avatar. Clicking the profile avatar reveals a drop-down menu to access the parent's profile, the settings page, and the logout link.

![Macbook]({{site.baseurl}}/assets/img/26.jpg)

	The parents dashboard contains a list of tasks that have been marked as complete by the children. The parents can confirm that the task was completed by clicking the "Mark as Complete" button. Clicking the "Mark Unfinished" button sets the task as not complete and sends the task back to the child.

	Once you have issues a reward to the child, click on the "Give Reward" button to remove it from the list.


<h2>Manage Children <a name="Manage-Children"></a></h2>

	To view and manage your children, click on the "Children" link in the top navigation bar.

![Macbook]({{site.baseurl}}/assets/img/27.jpg)

	From this page you can view each child's details and edit their information. You can add a new child by clicking on the Add a Child link.

<h3>Edit Child</h3>

	To edit the child, select the "Edit" button to the right of the child's row.

![Macbook]({{site.baseurl}}/assets/img/28.jpg)

	Here you can set the child's name, PIN/Image Code, target reward, age, comprehension level, and current point balance.

	Press the "Save" button to finalize any changes on the page.

<h2>Manage Rewards <a name="Manage-Rewards"></a></h2>

	To view and manage your children's potential rewards, click on the "Rewards" link in the top navigation bar.

	From this page, you can view and edit potential rewards for your children. You can add a new reward by clicking on the Add a Reward link. You can also access the list of active rewards that your children have earned.

![Macbook]({{site.baseurl}}/assets/img/29.jpg)

<h3>Edit Reward</h3>

	To edit a reward, select the "Edit" button to the right of the reward's row.

![Macbook]({{site.baseurl}}/assets/img/30.jpg)

	Here you can set the reward's name and point cost.

	Press the "Save" button to finalize any changes on the page.

<h3>Managing Earned Rewards</h3>
