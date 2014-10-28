=== Plugin Name ===
Contributors: wpmudev
Tags: elearning, lms, education, courses, lessons, assignments, students, teachers
Requires at least: 4.0
Tested up to: 4.0
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

CoursePress turns WordPress into a powerful online learning platform.

== Description ==

CoursePress turns WordPress into a powerful online learning platform. Set up online courses by creating learning units with quiz elements, video, audio etc. You can also assess student work, sell your courses and much much more.

= The easy way to create, manage and sell online courses in WordPress. =
CoursePress makes it easy to quickly create courses in WordPress and display them from a beautiful interface. It’s the perfect solution for selling and sharing your knowledge.

[youtube https://www.youtube.com/watch?v=HXzOBRYVjDw&list=UULgqhMisF-ykzHZzuMEfV4Q&hd=1]

= It's all in the box =
With options for building video-driven courses, letting participants upload and download content, quiz creation, sharing audio and course discussion boards baked right in – CoursePress has everything you need to produce top-notch content. Entice new students to register by sharing a course preview and overview complete with a video preview.

= Options for both free and paid courses =
Whether you want to share courses for free, or sell them, we've included tools for accepting free-students, manual payments and automated credit card payments.

= Manage courses like a pro =
CoursePress features tools for managing everything – grading, marking, assessments, reporting (including automatic grading and reporting), student & instructor management and everything else you'd expect from a complete Learning Management System.

= Integrates with almost every theme =
Use the official built-in CoursePress theme to get rolling quickly or the complete widget and shortcode catalog that covers every aspect of the plugin, allowing you to easily use it with any WordPress theme.

= Level-up with CoursePress Pro =

While CoursePress is suitable for offering a few courses, you may have bigger goals for your site. [CoursePress Pro](http://premium.wpmudev.org/project/coursepress-pro "Create, manage and sell online courses in WordPress") takes the features you love from CoursePress and unlocks the ability to create an unlimited number of courses. Plus get over 12 payment gateways making it even easier to accept payments for your premium content.

Check out all the goodies bundled in CoursePress Pro:

* Unlimited Course creation (Limit 2 for CoursePress)
* Manage and develop everything from tutorials to a full online school
* Intuitive tools for course promotion and marketing
* Entice new students with a course ‘teaser’ – including previews of video, course elements  and a description
* Add over a dozen payment gateways for accepting payments for premium courses (The standard version only offers PayPal, Simplify and manual payments)
* Both automated and manual assessment and reporting features – including automatic grading
* Offer free courses and attract new users
* Complete media integration for quickly adding video and audio content
* Out-of-the-box setup using the included ‘CoursePress’ theme – or dynamically integrate with any theme using shortcodes
* Interactive discussion boards to help develop a more robust learning environment
* Allow students to download and upload quiz files or any other file types
* Provide a complete course description, promotional video and image – let your students know exactly what they are registering for
* Offer genuinely assessed certification
* Live [Chat](https://premium.wpmudev.org/project/wordpress-chat-plugin/ "The best stand-alone live chat WordPress plugin") integration for real-time interaction
* And it works great with Multisite

Easily add beautiful courses to your WordPress install or Multisite network.

== Installation ==

= To Install =

* Download the CoursePress plugin file
* Unzip the file into a folder on your hard drive
* Upload the /coursepress/ folder to the /wp-content/plugins/ folder on your site
* Visit your Dashboard -> Plugins and Activate it there.

= To Set Up And Configure CoursePress = 

You can find [in-depth setup and usage instructions with screenshots here »](http://premium.wpmudev.org/project/coursepress-pro/#usage "CoursePress plugin installation and usage help")

== Screenshots ==

1. All the elements you need to create a great course
2. Your courses have never looked so good
3. Real-time interaction with Chat
4. Will your course have a six figure launch?
5. Offer certification with your courses with grading, marking and assessment tools
6. Display and promote your courses however you like
7. Massively customizable
8. Over a 13 payment gateways

== Changelog ==

== Changelog ==

= 1.2.1.9=
* Added new settings (Privacy) for controlling visibility of instructor username in the URL
* Resolved issues with cp_get_file_size functions and fatal error if filesize cannot be retrieved

= 1.2.1.8 =
* Fixed issue course excerpt (not showing on course single and archive pages)
* Fixed issue with popup windows (responsive)

= 1.2.1.7 =
* Resolved issue with plugin update

= 1.2.1.6 =
* Fixed bug where visual editor prevented unit elements from saving.
* Fixed bug after duplicating course. Can now edit the course again.

= 1.2.1.5 =
* Fixed issue with instructor's profile avatar shortcode
* Fixed conflicts with bbPress (not showing topics when CoursePress is active)
* Resolved issue with course front-end edit links (caused by empty spaces)

= 1.2.1.4 =
* Fixed issue with incorrect registration of module post type
* Fixed issues with hard coded http:\\ resources (google fonts and images in the theme and plugin)
* Fixed issue with not saving Login Slug
* Added additional options in settings for pages (instead of virtual pages) for enrollment process, login page, signup page, student dashboard and student settings
* Visual editor improvements.  
* Small code improvements

= 1.2.1.3 =
* Fixed issue with MarketPress product page infinite loop when CoursePress is active
* Fixed issue with instructor avatars preview

= 1.2.1.2 =
* Fixed issue with enrollment date and time (it uses now current_time( 'timestamp') instead of time())
* Fixed issue with media shortcode display in the CoursePress theme
* Fixed issue with course archive for courses without media set

= 1.2.1.1 =
* Added additional settings for controlling wp-login redirection
* Fixed issue with "Instructor Capabilities" settings access as a student
* Various database improvements. 
* Added course progress display to student workbook.  
* Added unit progress to CoursePress theme on student workbook.  
* Added categories in the single post and blog archive
* Fixed issue with hidden comment form when plugin is activated
* Added passcode fields on login and signup popup forms
* Minor changes to enrollment popup window. 

= 1.2.1 =
* Fixed issue with incorrectly displayed footer on student login page
* Fixed issue with BuddyPress autocomplete on Compose Message page
* Added a number of hooks in the main CoursePress class

= 1.2 =
* Added Duplicate Course feature
* Fixed issue with "units" slugs
* Fixed jQuery conflicts with theme options in WPMU Dev themes  
* Added Unit restriction options to avoid confusion between 'completed answers' and 'successfull/passed answers'.  
* Fixed unit restriction checking on front end 'Units' page. Will now show restrictions required from previous unit.

= 1.1.1 = 
* Fixed issue with protection of the next unit when previous unit has set "User needs to complete current unit in order to access the next one"
* Fixed bug with removing a Single Choice element from a Unit

= 1.1.0 =
* Fixed issue with course limits in PRO version

= 1.0.9 =
* Resolved issue with details button on courses archive and inconsistent shortcode used

= 1.0.8 = 
-------------------------------------------------
* Upgraded MarketPress Bundle to 2.9.5.3
* Added warning message (for admins) to the course overview page if "anyone can register" is not selected
* Fixed issue with instructor capabilities settings and saving
* Fixes possible issues with rewrite rules formating and avoid 404s
* Fixed issue with non-protected discussions for students who didn't enroll to the course
* Fixed issue with visibility of the draft units for admins and instructors* Fixed up issues with course completion checking  
* Added file size indicator next to downloadable files  

= 1.0.7 = 
-------------------------------------------------
* Resolved issues with wrong pre_get_posts filtering within the admin

= 1.0.6 = 
-------------------------------------------------
* Improved security
* Fixed: Auto-update issue with text editor in course setup  
* Slightly larger content editor for more convenient editing
* Fixed: Course completion now calculates correctly
* Resolved issue with incorrect saving of Single Line / Multiple Lines option in input text element
* Added student username (and link to the student's profile) in the assessment column
* Dynamic MarketPress path set

= 1.0.5 =
-------------------------------------------------
* Resolved issues with displaced content when PopUp Pro plugin is active
* Resolved issue with (not honoring) WP Settings for registrations
* CoursePress Theme CSS fixes
* Settings changes and Improved security  


= 1.0.4 =
-------------------------------------------------
* Shortcode changes and Improved security
* Fixed textdomain issues
* Resolved potential issue if Mcrypt library is not installed on server

= 1.0.3 =
-------------------------------------------------
* Improved security
* Resolved CSS issues with MarketPress popup called from CoursePress
* Fixed issue with theme location in the CoursePress theme
* Fixed CSS issue with uploaded videos in CoursePress theme (plus better responsive)
* Resolved issue with output buffer in shortcodes
* Added missing text domain on a number of places
* Other code improvements

= 1.0.2 =
-------------------------------------------------
* Resolved issue with mobile menu
* Resolved issue with listing images, videos and overlapping content in the CoursePress theme
* Responsive fixes for admin pages

= 1.0.1 =
-------------------------------------------------
* Resolved issue with deleting media files (selected in elements) upon deleting a unit or a module.

= 1.0.0 =
-------------------------------------------------
* 1.0 First Release.