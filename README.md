# Assessment Tools

Additions to Blackboard to support large scale digital testing.

In order to use this building block you require a license key. Contact nestorsupport@rug.nl for more information.

## Links
- [Download Latest Release ![Latest release](https://img.shields.io/github/release/rijksuniversiteit-groningen/b2-AssessmentTools.svg)](https://github.com/rijksuniversiteit-groningen/b2-AssessmentTools/releases/latest)
- [View All Releases](https://github.com/rijksuniversiteit-groningen/b2-AssessmentTools/releases)
- [Administrators Manual](AdministratorsManual.pdf)
- [User Manual](UserManual.pdf)

## Release Notes

### 3800.210304.0 
(This is a pre-release)
* Rework exam backups, introduce new unified backup system where backups are placed at exam closing and at reviews.
* Also show possible points for assignments and tests for students
* IOS-568 Show manage attempts for assignments
* Disable steganography

### 3800.210226.2
* Add filter option in grading
* Fix tooltips for Firefox in grading

### 3800.210226.0
* IOS-539 Fix displaying of photo
* Renew grading, review, basic editor and printing module
* IOS-173 Add score filter in grading
* IOS-536 After changing backup indexing reverting backup would revert to the wrong backup
* IOS-155 Add due date to essay assignments to prevent students submitting the assignment during review
* Student sets used by question flow are unavailable by default

### 3800.210202.0
* Show time of pledge
* Brighter colors for parentheses in info block
* Info block folder unavailable should go to folder settings
* Only save username to backup if a revert action was executed, save username of the administrator user, not of the student
* Add do not review status to essay backups
* Add extra event types in the user log (Do Not Review, Do Not Review Cleared, )
* Fix grade adaptive release grade criteria, when no grade is selected

### 3800.210120.0
* Make the different settings in the info block clickable, improve spacing and introduce colored parentheses
* Input fields can be added to the pledge
* add overview to review submitted pledges
* Question flow groups should be unavailable, to prevent students seeing each other
* Info block should show latest end time instead of earliest
* Add possibility to reopen blackboard tests
* Supporters can use preview user in exams, if they are not enrolled with the associated s-account

### 3800.201222.0
* IOS-425 Show announcement like notification for course messages received from instructors

### 3800.201216.0
* IOS-363 Add an info block summarizing the most important settings to the assessment folder
* IOS-412 Support student pledge
* IOS-437 Clear ip restrictions during review

### 3800.201203.0
* IOS-324 Updating sorting of exams in scheduled exams overview
* Add backups to course archive

### 3800.201117.0	
* Question Flow: Add mode to show all questions at all times
* Add safety measures to make sure students make all sub questions of an essay assignment
* Fix setting total score when changing sub scores using the property button
* Improve wordcounter, discrepancies occurred while counting <, > and & characters
* Prevent an error at accessing a question flow exam as admin without an enrollment
* Improve the UI of question flow
* Improve ordering of a question flow, concurrency issues could sometimes lead to students getting too many questions
* Replace Ephorus with Urkund


### 3800.201022.0
* No longer auto size columns, required font library is missing
* IOS-332 - Show locations in SubmissionOverview 
* Improve access error messages
* Introduce wait page which will be shown if students enter an exam early
* Mask External IP if not admin
* IOS-329 Fix several problems with disabled users

### 3800.200924.0
* IOS-290 More robust annotations restoring, disable google translate 

### 3800.200904.0
* IOS-250 Access check derives course_id from the content supplied by the content_id parameter, fixes Urkund assignments in assessment folder
* IOS-242 Fix linear order to be in folder order instead of alphabetically on group name

### 3800.200825.0
* Fix url of viewing attempt from student folder
* Fix viewing submission page when there are no content items in the folder
* Fix downloading scores from the manage attempts page
* Show "This item is invisible to students" for unavailable content items in an assessment folder
* Add option to enable My Grades tool in set up review

### 3800.200804.2
* Fix permissions to change attempt status
* Display linear or random mode of a question flow 
* IOS-114 Add download buttons in manage submissions page
* IOS-177 Add Open Exam Options Screen
* IOS-150 Apply max image size

### 3800.200716.0
* Implement extra properties for score and max points
* Add option to reset do not review
* Add view folder submissions, shows an overview of all submissions done in the folder
* Improve display of user events page
* New context menu option to open an exam in an assessment folder

### 3800.200703.0
* Fix XML export scheduled exams
* Distinguish edit and create for question groups
* Fix printing of images in essay submissions

### 3800.200622.0
* Include content collection in the archive which is made at setting up a review
* Fix the selection of viewing the student answer for essay assignments when setting up a review
* Fix showing white page instead of error page
* Fallback for large submissions, if blackboard cannot process a submission it will be saved without formatting

### 3800.200617.2
* Fix access for essay assignment and assessment folder when using a course duration
* Fix the functioning of question flow
* Fix creation of new assessment folders


### 3800.200612
* Enable more feedback options when setting up a review on a Blackboard test
* Fix zipping crashes because of duplicate file names while downloading submissings
* Create a course archive when setting up a review (#1414)
* New property screen which allows easily changing many properties at the same time
* Add feature switch for announcement polling
* Revert check on empty essay submission at finish all button
* Fix getting the "last" attempt of a grade in question flow
* Fix export of question flow, ids should also be mapped in the exporter
* Show a notification when a new announcement is posted during an exam. Can show announcements in assessment folder (#1406)

### 3800.200608.2
* Improve layout for smaller screens
* Add warning when submitting an essay assignment when not all sub items are answered.
* Feature to download submissions suitable for plagiarism scan in Ephorus
* All adaptive release rules on items will be deleted when setting up a review
* Can define a question flow in an assessment folder
* Disable tooltips in Firefox in grading
* Fix sorting of students in grading when shuffled option is selected 
* Only count student enrollments in scheduled exams page
* Feedback is now included in score download
* Add option in properties to randomize options for all questions in a Blackboard test 
* Privilege for closing an exam can also be assigned to the instructor course role
* Advanced adaptive release can be reached from the context menu after the title in the folder view
* Add Ephorus assignment as possible item to add to an asssessment folder
* Fix score download when question sets are used
* Several improvements for automatic archiving exams
* Add an administrator view for viewing the progress of a single user in an exam 

### 3400.200207
* Copying an exam in close exam now deals with the case that the destination exam course already exists.
* Fix new lines in the basic editor
* Fix bullets in the question text when using the basic editor
* Fix exception when using an essay assignment with empty titles for sub questions
* Translate the submission page for an essay assignment when the basic editor is used to Dutch.

### 3400.191210
* Change required privileges to delete log files

### 3400.191126
* Add automation for closing exam
* Add automation for creating a review
* Tweak security measures for support users

### 3400.190911
* Fix basic editor in Internet Explorer
* Add a dashboard which generates alarms if Nestorsupport performs suspicious actions

### 3400.190822
* UI elements of basic editor is more distinguished

### 3400.190813
* Make compatible with 3500 release of Blackboard
* Fix 'Delivery Type' property setting 

### 3400.190719.0
* Restrict a class of admin users to exam courses (course id starting with EXAM- or KOPIE-EXAM-)
* Alter the way words are counted in the word counter. The word count used in the basic editor matches the word count of other places.
* Basic Editor: Improve error handling and error recovering (auto)saving
* Possibility to restrict exam access for admin users based on user's location
* Editor type can be changed using the property editor

### 3400.190718.2
(This is a pre release)
* Admin user require to apply for a pass before accessing an exam course (works on courses with prefix EXAM- or EXAM-KOPIE-)
* When scheduling an exam a lean exam environment can be selected, which does not sacrifice student screen space for a photo. Presence tool app can be used to view photo's on a tablet.
* (Experimental) Introduce a new text editor, should be more stable than Blackboard default editor. 
* Use more stylish colors for attempt status

### 3400.190605
* Fix the "open in new window" property on the property edit page
* Don't show exam selection errors of exams where user is not enrolled
* Fix finalizing attempts of Blackboard tests
* Make the default height of the editor configurable
* Improve presence taking tool
* Include number of exam enrollments in scheduling
* Fix validation of points possible when using the Dutch language pack, the minimum points on a question is reduced to 0.1
* Show do not review status in essay submission print

### 3400.190521
* Fix downloading attempts if unenrolled users are present in the course
* Change text of save button in grade unique answers
* Fix time in save indicator in grade unique answers

### 3400.190507 
* Grading: Fix accessing grading

### 3400.190502
* Grading: Fix loaded snippets not being saved
* Print: Fix shuffling of options of multiple choice and multiple answer questions
* Change technical: For SSO from the virtual exam environment the IP is also hashed
* Fix student preview mode in assessment folder / essay assignment
* Grading: Show indicator for attempts marked as 'do not review'
* Fix the attempt count shown in the assessment folder, attempts of disabled users are not counted
* Fix finishing Blackboard assessments form the manage attempt page
* Fix incorrect autosave when the full screen editor is opened
* Print: Fix formatting of the options of a matching question 
* Add tooling for taking presence on an external device
* Grading: Grade by answer is accessible from the general grading settings
* Show number of enrolled students in today's exams
* Print: Fix printing of question sets
* Can add Short Answer Method item to an assessment folder

### 3400.190403.0
* Temporary disable grade short answers

### 3400.190329.0
* Only enforce exam access to content items if they are inside an assessment folder. This fixes WorkflowTool / Scorion being denied access.

### 3400.190326.0
* Fix blocking guest access for non-Blackboard tests
* Fix recall action after editing folder settings
* Fix page listing building block's log page
* Fix printing of content items
* Fix printing the general question text for essay assignments with sub questions 

### 3400.190320.2
* Fix printing jumbled sentence submission if one of the option was left blank
* Print instructions of a Blackboard test

### 3400.190320
(This is a pre-release) 
* Can change feedback settings of Blackboard tests using "Properties" button
* Fix several bugs in printing: Missing possible points for tests, example answer essay, print match options in matching questions, use unnumbered lists for jumbled sentence / order question

### 3400.190319
(This is a pre-release) 
* Add button to create another essay assignment when creating an essay assigment
* Add Do Not Reviews in score download
* Grading: Fix bug when entering text in a feedback balloon

### 3400.190318
(This is a pre-release)
* Grading: Change marker user interface
* Add facilities to archive exams to PDF by an external system
* Grading: Improve layout
* Grading: Help button opens in new tab
* Grading: Disable tooltips for internet explorer


### 3400.190307
(This is a pre-release)
- Change essay icon
- Add a feature to grade unique answers

### 3400.190207
(This is a pre-release)
- Improve XSRF security 
- Enable Assessment Folder functionality in a normal folder
- Introduce user log to diagnose student claims
- Generalized printing. Single print for both submissions and definitions


### 3400.180720.11
- Fix grading decimal scores when the Dutch language is used


### 3400.181204 
(This is a pre-release)
- Improve look and feel of essay assignment grading
- Add clickable overview of graded and ungraded attempts in instructor view of an assessment folder
- Fix not being able to create menu item of an assessment folder
- Improve technical: (auto)saving of essay assignment
- Improve technical: Logging of building block, can now use an Elastic server
- Improve technical: The way texts and their dutch translations are handled
- Remove unused webservices for data integration
- Minor layout improvement: Add separators in assessment folder context menu 
- Add option in submission print to print example answer
- Improve printing layout
- Improve wording in essay assignment settings "Show assignment details in review" -> "Show question in review"
 
### 3400.180720.10
- Include HTML/JS PDF viewer
 
### 3400.180720.9
- Improve formatting of points: format whole points as 10 instead of 10.00

### 3400.180720.8
- Fix showing a zero for ungraded regular essay assignment on the grading page
- Fix showing NaN for ungraded essays in the matrix 

### 3400.180720.7
- Changes required to make compatible with Blackboard 2018.2
  - Points migrated to BigDecimal
  - Fix hiding course menu in exam environment
  - Fix annotations been rendered differently 

### 3200.180720.6
- Fix error when performing do not review at the folder level, when there are finalized essays present. Instead apply do not review at those items.
- Fix layout help pop up in the exam environment


### 3200.180720.5 
- Add help pop up in exam environment

### 3200.180720.4
- Sort users in the matrix during grading case insensitive  

### 3200.180720.3
(This is a pre-release)
- Fix sorting of users in the matrix during grading

### 3200.180720.2
(This is a pre-release)
- Fix reordering of essay assignments
- Fix adding sub-items to an essay assignment
- \#32 Fix copying of sub questions, fixes rijksuniversiteit-groningen/b2-AssessmentTools
- \#31 Re-enable toggle options (View, Edit, Manage) when viewing an essay assignment 
- Add total column to Excel export and more distinguished layout
- Fix adding subitems to an essay assignment

### 3200.180720
(This is a pre-release)
- Show student location in attempt overview
- \#28 Default folder action changed to view
- \#26 Fix manage essay attempts when there are attempts of unenrolled users (introduced in 3200.180619)  
- \#29 Copy attachment in visual text box editors of essay assignments
- Fix error downloading scores

### 3200.180620
(This is a pre-release)
- Fix editing essay assignment when there are attempts of unenrolled users (introduced in 3200.180619) 

### 3200.180619
(This is a pre-release)
- Assessment Folder: Show warning for essay assignments without grade center column
- Grading: Speed up loading of the matrix 

### 3200.180525
(This is a pre-release)
- Allow instructors to copy part of the student answer during grading
- Technical improved essay assignment
- Fix displaying math symbols during grading
- Save indicator at grading takes less space
- Instructor can clear attempts of essay assignments
- Generalize manage attempts in assessment folder, it is also available for Blackboard tests
- Manage attempts is reachable by clicking the attempt count
- Default action when edit mode is enabled in an assessment folder is edit
- View assessment folder can be used without being enrolled in the course, when user has sufficient privileges
- An alternative IP address can be registered, for when a remote virtual PC environment is used

### 3200.180511
- Fix Property 'hasEssayAssignments' not found on type nl.rug.blackboard.assessment.data.folder.viewFolder.ViewFolderModel

### 3200.180509
- issue #22 Fix submission print of students which do not have feedback
- Hide viewToggle of edit essay assignment when creating new essay assignment
- Some textual improvements
- Support SVG icon set

### 3200.180416
- Minor text improvement
- Changed column headers in score excel export
- Fix layout issue essay assignments during submit

### 3200.180405
(This is a pre-release)
- case 244231 Fix layout of buttons (logout and homepage) in the header exam environment
- Fix Excel download of scores in an Assessment Folder
- Improve validation message for invalid points of essay assignments
- Fix pressing enter/space when creating a new snippet from the snippet library 
- New print template for essay assignment submissions
- Improve texts
- Align snippets in the snippet picker to the left

### 3000.180323
(This is a pre-release)
- Fix printing essay assignment submissions with subitems
- Take menu item availability status into account in status indicator in exam scheduling

### 3000.180320
(This is a pre-release)
- Disallow copying essay assignments using course copy when 'Gradecenter' was deselected
- Button to download scores and subscores as an Excel sheet.

### 3000.180316
(This is a pre-release)
- case 242572 Optimize spacing in grading
- Use default max points of 1 when switching back from an essay assignment with sub items to a regular one
- Fix configuring max points essay assignment on an essay assignment without sub items

### 3000.180314
(This is a pre-release)
- Print annotated feedback in submissions print of an essay assignment
- Improvement laying out subscores on review page
- case 242570 Can load a feedback snippet from the library in an existing annotation balloon
- Change access check on the viewing and managing pages of an assessment folder: should be analogue to Blackboard's check on listContent and listContentEditable. Takes into account privilege 'view unavailable course'.
- Skip IP check if user has 'view unavailable course' privilege.
- Parse possible points of an essay assignment in the current locale: use , in dutch and . in english.

### 3000.180219
- Grading: Fix styling of feedback picker
- Fix error when finishing grading using the grade button in an essay assignment
- Remove remainders of old review page of an essay assignment

### 3000.180207
- case 242150 Prevent grading attempts marked as 'do not review'
- Fixed 'The do not review' option for newly created essay assignments
- case 242046 Grading: Fixed Next/Previous button after entering score
- case 235200 Grading: Confirm screen closing grading if changes are not saved
- case 235200 Grading: Keep save indicator visible to prevent distraction
- case 241926 Question text of an essay assignment can be left blank

### 3000.180124
- Fix error viewing folder in Assessment Tools 3000.180123

### 3000.180123
- Review page no longer shows 'undefined' when an attempt has not been graded
- Remove legacy frame based examination environment
- The version of the building block no longer install on Blackboard running other versions than 2016.4
- case 238223 Tool buttons of a feedback balloon no longer overlaps other balloons
- case 238166 No longer possible to create an invalid feedback snippet which corrupts the snippet manager
- case 238673 Fix using a tool button in grading and then refreshing the page breaks the grading application
- Improve technical: Editing or adding an essay assignment
- Leaving a sub item of an essay assignment empty no longer removes the sub item
- Remove old grading method
- Fix link to "Edit the Test" of a Blackboard test in the assessment folder
- Fix broken essay attempts after archive/restore of a course
- (beta) Track of exam related events
- case 238696 Fix rendering bold texts in internet explorer
- Show error when using a copied essay assignment when the grade center was not copied 

### 3000.180102.2
- Fix reordering of items in an assessment folder

### 3000.180102
- Fix line height of annotations on the review page

### 3000.171222
(This is a pre-release)
- Fix archiving/restoring essay assignments with sub questions
- Sort users in grading case insensitive
- Fix error when formatting fractional scores in submission print
- Change text wrapping in feedback balloons
- Fix width of feedback balloons
- Removed beta indicator for the new grading interface

### 3000.171219
(This is a pre-release)
- Clearing a snippet title made the snippet manager non functional
- Fix layout of annotations in review screen, annotations and student answer are displayed side by side
- Fix height of navigation buttons
- Fix pressing F5 on the matrix view
- case 237574 Total score is not updated when switching assignment in grading beta
- case 237572 Sort students on name while grading not anonymously
- Round student score to two fraction digits when printing results
- nicer save button and go back to folder after saving in the property editor
- case 237569 Remove column distinct values in property editor
- case 237569 Show new ip restrictions instead of existing after editting folder
- case 237214 Question set should be treated as random block when printing a test
- case 236776 Enter in feedback possible by pressing shift-enter
- Improve technical: Exam restrictions checking (IP checking)
- Improve technical: Downloading submissions and downloading essay submissions 


### 3000.171208
(This is a pre-release)
- In manage folder as instructor fix link to Edit Test
- Fix rendering of images to students in an assessment folder
- Fix rendering of attached files to items in an assessment folder
- Fix save indicator in grading beta
- Improve technical: Student view / instructor manage of an assessment folder
- Improve technical: XML export of scheduled exams
- Improve technical: Scheduling of exams
- Improve technical: Editting the properties of an assessment folder and the creation of a new assessment folder
- No longer print content type image in print of submissions
- Remove subquestions numbering in printing of submissions
- Simplify printing of scored attempt
- Improve handling of expiring sessions during grading beta
- Improve Dutch texts 'Afsluiten' is now called 'Inleveren'
- Improve the possibilty to give general feedback in grading beta
- Optimize height of the header in grading beta
- Show an incomplete total score in grading beta when not all sub items have been graded
- Fix for exam environment under Blackcboard 2017.2

### 3000.171130
(This is a pre-release)
- Fix randomized answers multiple choice print, not randomizing the correct answer
- Improve technical: Viewing an assessment folder as student
- Fix do not review on folder level in combination with an essay assignment with sub items
- Improve technical: Manage an assessment folder as instructor
- Improve technical: Grading beta 
- Introduce maximum score of 10000 in grading beta
- Fix deletion of annotations corrupting the feedback in grading beta
- Fix deletion of snippets in grading beta
- Fix logout button was hidden after using do not review
- Improve stability of saving in grading beta
- Fix toolmenu staying open when switching attempts in grading beta
- Fix formatting of content items in the assessment folder, fix the use of included images for instance
- Introduce multi-property editor accessible from the assessment folder
- Remove action "Manage Essay Assignments" from the grade center. The actions are now included in the edit menu of an essay assignment.
- Improve technical: Retrieving the matrix in grading beta
- Support course copy, import and export for essays with sub items

### 3000.171003.1
- Change location of log out button
- Introduce beta of new grading window
- Introduce subquestions

### 3000.170531
- Verberg foutmeldingen na mislukte inlogpoging 

### 3000.170501
- Nieuw login mechanisme dat onafhankelijk werkt van gebruikte authenticatiemethode

### 3000.170418
Scheduling:
- XML export gemaakt tbv applicatietoetsen
- Mogelijkheid URL's te definieren in ingeplande examens
- case 193292 Datumselectie in scheduling opgelost
 
Printversie: 
- Blackboard test: case 201970 Random blocks worden geprint
- case 202050 Lettertype in printen geffxied
- case 199649 Aantal woorden in essay worden geprint
- case 203038 Sortering tijdens printen geintroduceerd
- case 203039 Print gelinkte vragen, als een vraag niet geprint kan worden print waarschuwing
- case 200953 Print opmaak/afbeeldingen in keuzeopties bij multiplechoicevragen
- case 203036 Print woordenlimiet
- case 203822 Blackboard test: Print correcte antwoorden indien gekozen
 
Afname:
- case 202571 Workaround voor probleem met de text editor
- case 203041 Toon max score van essayvragen in de folder
 
Grading:
- Toon missende velden, zoals de vraag, titel, aantal woorden
- case 196399 Kan op groep graden (ook bij print)
- case 203039 toon vraag tijdens indien gewenst
- case 203255 Do not review optie geintroduceerd
 

### 3000.161216.2
* Functionaly equivalent to 3.7.7
