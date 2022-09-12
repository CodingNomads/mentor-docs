# Tools for CodingNomads Mentors

This page contains a collection of quick how-to guides for using the necessary tools to be an effective CodingNomads Mentor. It starts with a list of the absolutely essential tools, then describes how to use them in more detail.

[TOC]

## Essential Software

You'll need these tools in order to be able to mentor a CodingNomads student:

- [TopTracker](05_tools.md#time-tracking-with-toptracker)
- [Google Calendar](05_tools.md#recording-meetings-on-google-calendar)
- [Discord](05_tools.md#video-sessions-and-communication-with-discord)
- [Learning Platform](05_tools.md#progress-check-ins-with-the-learning-platform)
- [GitHub](05_tools.md#code-reviews-with-github)

Please make sure to install these programs and request access where necessary. You'll find more detailed descriptions in the dedicated sections.

## Time Tracking With TopTracker

Please use **TopTracker** to record your time spent mentoring.

### Set Up TopTracker

To get started, please follow these steps:

- **Sign up** for a free account by clicking _Get Started as a Freelancer_.
- **Notify** Jared (or Ryan) to add you to the _Onboarding_ project. You'll receive an invitation from `admin@codingnomads.co` to join the project called _Onboarding_ as a _Freelancer_.
- **Track** the time you spend on onboarding under that project. You can also add manual time entries, for the time you tracked before we managed to invite you to the project.
- **Download** [TopTracker for Desktop](https://www.toptal.com/tracker), if you prefer to track your time in a dedicated app.

**Skip Payoneer Setup:** We _don't_ use Payoneer for payment. You can skip that section while setting up your TopTracker account.

### Track Mentorship Time

Once you've started working with a student, we will set up a **Project** with your **student's name** and invite you as a _Freelancer_. From then on, you'll track the time you spend mentoring this student in their dedicated project. If you are working with multiple students, make sure to record your time for each student in the correct project. 

To minimize your effort, when logging time to a student project, you can limit your tracking entries to the following keywords:

1. call
2. forum
3. discord
4. code review
5. organization


Watch the screencast below, which shows you how mentorship time tracking with TopTracker works in practice:

<iframe width="560" height="315" src="https://www.youtube.com/embed/Kho8-5TcapE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Please follow this workflow to keep track of the time you spend working with your student. **Your compensation is based on the recorded tixme, and the invoices you generate (see next step).**

### Mentor_Admin and Community Support Projects
We will also invite you to two projects called _mentor_admin_ and _Community Support_. _Mentor_admin_ can be used for miscellaneous administrative activities such as internal meetings (e.g., _Python Mentors Meeting_). _Community Support_ can be used to answer questions on the forum or the general Discord channels (i.e., helping students for which you don’t have a specific project). 

**When charging to these two projects, please put both a keyword (from the list above) and a specific description in the TopTracker activity description.** For example: “Discord: supporting Tiffany, connecting to databases, general JDBC” or “Forum: responded to this question: https://forum.codingnomads.co/t/lab-9-data-wrangle-a-dataset/1244”.  This desription format helps us to understand how to allocate budget for these two projects.

### Wait, but what if I forget turn on my tracker?!  Or, even worse, forget to turn it off!?!
On its web application, in the "my activities" tab, TopTracker allows you to manually add, edit, or delete time.

<img style="display: inline-block;" alt="how to edit time on TopTracker" src="../images/editing_time.png"/> 

### Generate and Submit Your Invoices

On the first day of each month, please submit an invoice for each of your TopTracker projects for the previous month. Please see the screenshot below for this process, and refer to the [Monthly Payment Process](07_payment.md#monthly-payment-process) for more details about invoicing and payments.

1. Click _Invoices_ tab on the left
2. Click the green button called _Create Invoice_ in the top right 
3. Select the project you want to invoice for
4. Adjust dates to the first and last day of the previous month
5. Click _Save Draft_ and _Preview_ in the bottom right
6. Click _Send Invoice_

![Select Dates for TopTracker Invoice](images/toptracker_select_dates.png)

You need to submit a separate invoice for each of your students. Please submit all invoices each month in order to get paid.

## Scheduling With Google Calendar

You'll use **Google Calendar** for scheduling your student calls. If you don't have a Google account, please [sign up for one](https://accounts.google.com/signup/v2/webcreateaccount?service=cl&continue=https%3A%2F%2Fcalendar.google.com%2Fcalendar%2Frender&gmb=exp&biz=false&flowName=GlifWebSignIn&flowEntry=SignUp).

### Booking Meetings With Calendly

To make life easier for you, you can use [Calendly](https://calendly.com/). It's a handy tool that allows you to block out your availability and let students book meeting times with you through a shareable link.

Using their free tier, you can specify the times you are available for meetings, then send your student a link where they can choose a time that works for them.

Calendly can significantly reduce the effort needed to find a time that works for both you and your students. It also integrates with Google Calendar.

### Recording Meetings On Google Calendar

Every student meeting you have needs to be recorded on our **CN Scheduling Calendar** at `calendar@codingnomads.co`. We use this information to keep track of student's meetings and how far along they are in their subscription.

This means you need to:

- **include** the student _and_ mentor names in the event title - for example "Ryan & Michael"
- **invite** `calendar@codingnomads.co` to every student meeting
- **update** any changes to your student meetings on these shared calendar events

Sometimes, students will need to cancel or move a meeting. Make sure to update the calendar by moving or deleting the meeting.

![Example Google Calendar Event](images/google-calendar.png)

**We can only guarantee payment for meetings that show up on this calendar.**

You will also be invited to a calendar invite that represents the student's last week at CodingNomads.  If you and your student decide not to meet one week, please update the calendar to add a week to the student's program.  For example, if your student requests a week off for christmas (encouraged!), and their last date is January 1st, then update the calendar to show that their last date is now January 8th.  If there is any confusion on this topic, please ask Jared or Michael. 

## Video Sessions and Communication With Discord

Discord includes screen-sharing capabilities that can be used for 1-on-1 sessions with students. Google Meet is our recommended alternative in case a student would like to record sessions.

### Set Up Discord

Before proceeding, please reference the <a href='https://codingnomads.github.io/discord-guide/' target='_blank'>Discord Guide for Members</a> to get an idea of what the Discord experience looks like for subscribing members. The process of joining the server is the same for mentors. The difference is that shortly after joining, roles will be added to your profile that unlock additional channels and abilities on the server.

### Server Roles

Permissions on the server are moderated using roles. All users who have been verified for access are assigned the **Member** role. Roles are then "stacked", adding additional permissions to a user. For example:

* Subscribing members (self-study): **Member**
* Mentored students: **Member** + **Mentored**
* Mentors: **Member** + **Mentor**
* Mentor/Moderators: **Member** + **Mentor** + **Moderator**

![Role Colors](https://raw.githubusercontent.com/CodingNomads/static/main/discord/discord-roles.png?raw=true)

Username color on the server is dictated by their "highest ranking" role. Mentors can easily be identified by the yellow color of their name. Members and Mentored students are represented by slightly different shades of blue.

![Mentor Color](https://raw.githubusercontent.com/CodingNomads/static/main/discord/discord-mentor.png?raw=true)

There are also a collection of "interest roles" that can be applied to your profile by visiting the `#interest-management` channel. We ask mentors to add all topics they can assist with to their profile.

### Channels

Please take the time to visit the `#introduce-yourself` channel and share a short bio message with the community. Let everyone know you are human!

Support channels are broken down into two categories. Your focus as a mentor will be on the channels within the `MENTORED SUPPORT` category. These channels are only accessible by mentored students, and should be actively monitored by all mentors who have the ability to assist.

For example, if you are a **Java** mentor, you should right-click the `#Java` channel (in the MENTORED SUPPORT category) and under Notification Settings -> Select **All**.

You can also right-click the CodingNomads server icon on the left and click Notification Settings for a dialog with additional options. Here you can quickly set up notification overrides for individual channels or entire categories.

![Notification Overrides](https://raw.githubusercontent.com/CodingNomads/static/main/discord/discord-notifications.png?raw=true)

The `#general_...` support channels (within the `CODINGNOMADS` category) are community supported - please do not bill for support in these channels. Admin staff will lend a hand to help members here, and point them to the forum in the case of more complicated requests.

The way Discord handles direct messages between two individuals is different than Slack. If you message a user on Discord, you are taken out of the server, in to your private messaging area. This means that server nicknames or server profiles no longer apply. If you are "Sam Smith" on the CodingNomads server, but your username is "smoothcriminal5000", the student is suddenly communicating with **smoothcriminal5000**. Not a professional look. This goes both ways as well, all of the sudden you have to keep track of your student's real name, _and_ username (which may not be pretty).

To avoid this situation, all mentors will require _two_ dedicated channels for each of their actively mentored students - a **Text** channel and a **Voice** channel. The format should always be consistent:

`#firstname-lastname`

And if you are Sam Smith, these channels will be located within a category titled:

`SAM'S STUDENTS` or `SAM'S MENTEES`

This way, all direct communication between you and your students remains inside the CodingNomads server and will not impede on your personal message space. This configuration also comes with the added benefit of allowing custom notification settings for each student.

![Student Channels](https://raw.githubusercontent.com/CodingNomads/static/main/discord/discord-sam.png?raw=true)

### Mentor Support and Sessions

Your student's dedicated text channel is the primary space for direct support. Encourage students to reach out often, assured that you will respond at your earliest convenience. For times when you will be unavailable for an extended period, point students to the `MENTORED SUPPORT` category channels for support. That way, other mentors can step in to help.

Voice channels in Discord have built-in screen sharing capabilities. This allows mentors and students to quickly and easily connect for recurring and impromptu support sessions. Once you and your student both join the dedicated voice channel, you can start chatting right away. When the student is ready to share their screen, they can simply click one of two "Share Your Screen" buttons.

![Screen Sharing](https://raw.githubusercontent.com/CodingNomads/static/main/discord/discord-screen.png?raw=true)

From there, they can choose to share a single window (Applications), or the entire screen (Screens).

If you or your student have trouble sharing - black screen, constant loading, etc. it has been found that disabling the following Discord setting can help:

**Settings** -> **Voice & Video** -> **Open H264 Video Codec provided by Cisco Systems, Inc.** -> _Disable_

As mentioned, we recommend sticking to the audio channels in Discord for 1-on-1 sessions with your students. However, if your student would like to record their 1-on-1 sessions, or either party is having any difficulty with meeting over Discord, we recommend using Google Meet as an alternative.

## Progress Check-Ins With The Learning Platform

You'll need to keep track of how your student is progressing through the course materials in order to give them actionable feedback and help them keep moving.

Make sure that you have an active account on the [CodingNomads learning platform](https://platform.codingnomads.co/learn/). After you've completed onboarding, you'll get upgraded to the role of _Non-editing Teacher_ to be able to access everything. If you need that access and don't have it yet, please contact <img style="display: inline-block;" alt="contact address for ryan" src="../images/email_ryan.png"/>.

To find your students' **progress logs**, go to the main course page of your course. You'll see a button in the top left called _Participants_. Click it:

![Access Participants](images/report_participants.png)

This brings you to a page with a list of all course participants. Use the search field to find your student:

![Overview page showing all Participants of the course](images/report_participants_view.jpg)

Then click on the student's name to access their profile page.

**Tip: Bookmark this page for each of your students, so you'll be able to access it quickly. Checking up on your students' progress shoud be a simple routine task that doesn't take much of your time.**

On the right of that page, you can see a _Reports_ section. Feel free to explore the different types of reports:

![How to access the 'Outline Report' for a student](images/report_click_outline.jpg)

The **_Outline Report_** gives you a quick overview of which resources your student accessed, how often, and when. When a student has accessed a page, it'll show a view count and a date next to the resource name:

![Outline Report showing pages visited by the student](images/report_seen.png)

If they haven't accessed the resource yet, these two columns will be missing:

![Outline Report showing pages not yet visited by the student](images/report_unseen.png)

The **_Outline Report_** allows you to quickly understand where your student is currently at, whether they are making progress, and it can help you understand what they might be struggling with.

## Code Reviews With GitHub

We use GitHub inline comments for code reviews. Check out the forum post [Giving and getting code reviews](http://forum.codingnomads.co/t/about-the-code-reviews-category/38) for suggestions on how to give helpful and effective code reviews.

If you are not familiar with giving code reviews in GitHub, check out our [Guide on giving GitHub Reviews](14_tips.md#do-code-reviews-on-github).


## Student Communication Templates

You can set communication snippets up as [Gmail templates](https://www.lifewire.com/how-to-set-up-and-use-email-templates-in-gmail-1172103) or copy-paste the content from the resource linked below. Please replace the fields marked with `{ALL_CAPS}`.

Feel free to personalize as much as you want to. These templates are meant to make it quicker for you to get started communicating with your students, but _personal_ communication is priceless for good mentorship results.

- [Student Communication Templates](12_templates.md)

Please add any relevant repeating communications that you create so that other mentors can benefit from it, or let us know when you think that something is missing.

## Other Useful Tools

The following tools have been useful for some mentors. You can include them in your workflow if they seem helpful for you.

### Worldtimebuddy

A great tool for scheduling across multiple time zones. I use this all the time.

![WorldTimeBuddy view with different time zones displayed](images/worldtimebuddy.png)

- [https://www.worldtimebuddy.com/](https://www.worldtimebuddy.com/)

### Doodle

Helpful for remotely deciding for a call time, especially when there are many people involved. Can also be helpful for scheduling your first orientation call with your student.

- [https://doodle.com/create](https://doodle.com/create)

However, setting up your [Calendly](https://calendly.com/) account is probably more convenient and easier to handle.

### There

A MacOS app that helps keeping track of all your students' current times across multiple time zones. Nicely integrated in OS X and helps to quickly check up on whether someone's up or sleeping.

![Screenshot of There being used and showing different people with their time zones](images/there.png)

- [https://there.pm/](https://there.pm/)
