# CMPG-323-32737742-

<h1>CMPG 323</h1>

<p>Repository for CMPG 323 for myself 32737742 in which I will add various items such as milestones, labels, a readME file that will be continuously updated throughout the semester, charts and projects related to CMPG 323 etc...</p>

<p>I will be seperating all my projects into their own respevtive repositories and use anchor elements in a single repository to link all the relevant projects:</p>
<h3>Repositories to be used (with links): </h3>
<ul>
  <li><a href=https://github.com/BrendanV11/CMPG-323-Overview-32737742>Project 1 - Agile & Scrum</a></li>
  <li><a href="https://github.com/BrendanV11/Project-2---API-Development">Project 2 - API Development</a></li>
  <li><a href="https://github.com/BrendanV11/Project-3---Standards-Patterns">Project 3 - Standards & Patterns</a></li>
  <li><a href="https://github.com/BrendanV11/Project-4---Testing-RPA">Project 4 - Testing & RPA</a></li>
  <li><a href="https://github.com/BrendanV11/Project-5---Reporting-Monitoring">Project 5 - Reporting & Monitoring</a></li>
 </ul>
 
 <h3>Branching strategy to be used: </h3>
 <p>After the intitial setup of all the comonents (when everything is in order after project 1), the way I will implement branches to my repositories is as follow.</p>
 
 <p>I will create a branch off of the main/default branch and implement all my changes within the secondary branch I have created. Anything that I do on the secondary branch I will then commit and merge into the main branch once I feel that it is neccessary. However, if there are any errors that I encounter after committing and merging the branches, I will create another branch named hot-fix and assign a version to the branch in order to keep track of updates. In this hot-fix branch I will simply fix the error, update the version number, and merge this branch into the main/default branch.</p>
 
 <h3>Use of .gitignore</h3>
 <p>When.gitignore is used it essentially tells Git whether there are files that should be ignored when committing a project to your repository.</p>
 
 <h3>Storage of credentials and sensitive information</h3>
 <p>This type of information should never be stored in git repositories. We should rather add these sensitive files to gitignore thus excluding these files from being pushed into the repositories. Furthermore, simply creating a private repository will not be enough as these type of repositories are seen as "High value" targets in which others may gain some valuable information.</p>
 
<h4>Method I will use to protect sensitive information:</h4>
<p>Any files/folders that appear in the repossitory that I would rather ignore when commiting in Git/GitHub I will simply add these documents to the .gitignore in order to protect the information.</p>


