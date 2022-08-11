# CMPG-323-32737742-

<h1>CMPG 323</h1>

<p>Repository for CMPG 323 for myself 32737742 in which I will add various items such as milestones, labels, a readME file that will be continuously updated throughout the semester, charts and projects related to CMPG 323 etc...</p>

<p>I will be seperating all my projects into their own respevtive repositories and use anchor elements in a single repository to link all the relevant projects:</p>
<h3>Repositories to be used: </h3>
<ul>
  <li>Project 1 - Agile & Scrum</li>
  <li>Project 2 - API Development</li>
  <li>Project 3 - Standards & Patterns</li>
  <li>Project 4 - Testing & RPA</li>
  <li>Project 5 - Reporting & Monitoring</li>
  <li>CMPG 323 - Linking Repositories</li>
 </ul>
 
 <h3>Branching strategy to be used: </h3>
 <p>After the intitial setup of all the comonents (when everything is in order after project 1), the way I will implement branches to my repositories is as follow.</p>
 
 <p>I will create a branch off of the main/default branch and implement all my changes within the secondary branch I have created. Anything that I do on the secondary branch I will then commit and merge into the main branch once I feel that it is neccessary. However, if there are any errors that I encounter after committing and merging the branches, I will create another branch named hot-fix and assign a version to the branch in order to keep track of updates. In this hot-fix branch I will simply fix the error, update the version number, and merge this branch into the main/default branch.</p>
 
 <h3>Use of .gitignore</h3>
 <p>When.gitignore is used it essentially tells Git whether there are files that should be ignored when committing a project to your repository.</p>
 
 <h3>Storage of credentials and sensitive information</h3>
 <p>This type of information should never be stored in git repositories. We should rather add these sensitive files to gitignore thus excluding these files from being pushed into the repositories. Furthermore, simply creating a private repository will not be enough as these type of repositories are seen as "High value" targets in which others may gain some valuable information.</p>
 
<h4>Methods to protect sensitive information:</h4>
<h6>(Simon Maple, 2018)</h6>
<ul>
  <li>Addition of SECURITY.md file</li>
  <li>Access control</li>
  <li>Do not always trust third-party GitHub applications</li>
  <li>Consider puurchasing GitHub Enterprise</li>
  <li>Audit sensitive data before committing to repositories</li>
 </ul>