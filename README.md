# GitHub Tutorial

# _by **Rahdner Savain**_

---
## Git vs. GitHub

Git Is Software (**version control**) That Keeps "**Snapshots**" Or Pieces Of Code. Version Control Software Keeps Track Of Every Change To The Code (Snapshots) In A Database. 


GitHub Is An **Internet Server** That Holds Variety Of Git Projects. Github Provides Easy Access And Availabiltity To Your Code. Stores Your Projects Into A "Cloud" (Internet) For Which You Can Aceess From Home Or Any Device That Can Go On The Internet


Difference Between both Git & Github Is That In Order To Access Github You Must Already Utilised Git And Doesnt **_Work Without Git_**

---
## Initial Setup 

##### Making A Gihub Account Is Easy.
1. First you go to [Github.com](github.com)  
2. Then you set a username and password 
3. Check your email for verfication from github  
4. Open and click verify!  
5. Then go back to github.com and click on "Free Account"
6. To finalize making your github account click on "Finish Sign Up"
7. Click on your profile icon on the top right
8. Then click on settings
9. Go to the left sidebar and click on "SSH and GPG keys"
10. Click on "New SSH key"
11. Make the title _cloud9_
12. Now go back to cloud9
13. Click on the gear icon in the top right corner
14. Click on "SSH Keys"
15. Copy the SSH Key given
16. Then go back to github.com and paste the SSH key
17. Then add the SSH Key
18. Now go back to cloud9 again and open "github-learning IDE"
19. Then type in `ssh -T git@github.com`
20. Finally a message should come up that say that it worked but you dont have shell access

---
## Repository Setup
 This Is Where We Begin The Gritty Part Of Our The Coding. Making Your First Repository!!!
 
* Repository Setup Is Easy If You Already Completed Steps Of The Initial Setup On Github. 
* All You Would Need Is To Do Is Curently Be In Your Workspace And Create An Directory (Folder) And Initialize It.
* To Initialize, You Need To Go Into That Folder And Type In The Command `git init`.
* This Git Command Would Allow You To Use (Initialize) For Version Control/Git. 
* This Would On Be Used Once Throughout The Whole Workflow In This Repository.
* After You Have Initiliazed It; You Would Need To Go Into That File That You Are Working On Currently On.
* Once You Are Done The File You Are Using Wouldnt
Be "Added" To The Staging Area So It Can Be "Commited". Added Files Would Be Added * To The Remote Repository. You Would Need To Use The Command `git add .` or `git --all`
* After You Have Finished Changing Your File Than You Would Need To Commit The File. The Git Command `git commit -m` Would Enable You To Commit The File To The Repository In Which You Can Push/Pull To External Repos. Or The Cloud

---
## Workflow & Commands
* After You Get The Hang Of Basic "Git"; You Would Need An Workflow Or An System Of Checking To See Your Work Periodicaly.
* The Best Reccomended Flow Is Using `git status`,`git add .` `git commit` Than `git push`. 
* The Command `git status` Allows You To See Filles That Have Changed Since Your Last Commit. 
* This Commands Is Very Resourceful Because It Allows You To See Changes To Check If Your Previous File Worked . Next Would Be To Add The Files That You Have Edited. 
`git add .` Would Allow You To Had The Change For It To Be Commited. The Command`git conmit` Would Commit To The Staging Area. After Committing You Would Need To Push It Up To An External Repository (Github). 
