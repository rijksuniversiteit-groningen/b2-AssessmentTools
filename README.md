# Assessment Tools

Additions to Blackboard to support large scale digital testing.

In order to use this building block you require a license key. Contact nestorsupport@rug.nl for more information.

## Links
- [Download Latest Release](https://github.com/rijksuniversiteit-groningen/b2-AssessmentTools/releases/latest)
- [View All Releases](https://github.com/rijksuniversiteit-groningen/b2-AssessmentTools/releases)
- [Administrators Manual](AdministratorsManual.pdf)
- [User Manual](UserManual.pdf)

## Release Notes

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
