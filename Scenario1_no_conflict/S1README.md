<h1 align="center">Welcome to scenario1 - the world is simple 👋</h1>
<p>
</p>

> Instructions on how to practice this scenario yourself

## Usage

<ol>
Steps to reproduce:       
     
Setup       

<li>navigate to desired folder</li>
<li> git init - this creates the file (hidden) where the commit IDs are saved.</li>     
     
Master Branch

<li> Create file for “init” commit. (By default Master)</li>
<li>git commit -am “commit #2”</li>
<li>git commit -am “commit #3”</li>        
      
Feature Branch    

<li>git commit -am “commit #5”</li>
<li>git commit -am “commit #6”</li>
<li>git checkout master (now on master)</li>
<li>git rebase feature</li>
<li> git reset <ID> —hard</li>
<li>git merge feature</li>
</ol>
<br/>
## Author

👤 **Chaim Finson**
