# Assessment Tools

Additions to Blackboard to support large scale digital testing.

In order to use this building block you require a license key. Contact nestorsupport@rug.nl for more information.

## Links
- [Download Latest Release](https://github.com/rijksuniversiteit-groningen/b2-AssessmentTools/releases/latest)
- [View All Releases](https://github.com/rijksuniversiteit-groningen/b2-AssessmentTools/releases)
- [Administrators Manual](AdministratorsManual.pdf)
- [User Manual](UserManual.pdf)

## Release Notes

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
- Fix layout of annotations in review screen, annotations and student answer are displayed side by side.
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
