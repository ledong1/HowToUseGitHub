


# How to use GitHub
GitHub is a website where programmers save and share their codes. 
You can collaborate with others on one project in any language and also find a lot of interesting thing.

**If anyone feel this useful, please give me a star :)**

# Index
#### 1. On GitHub website
 * create GitHub account
 * add new repo on website (and add collaborator is its private) 
 * link online repo to local
#### 2. On your PC/Mac using cmd/terminal
 * install git
 * basic commands for cmd/terminal
 * commands for git
#### 3. Special for eclipse java
 * Already create a java file? ->init git in that path and push it
 * Don't have local Java file? ->use eclipse import function
 

# 1. On GitHub website
 ### (1) create GitHub account
 go to [github pricing](https://github.com/pricing) page and follow the instruction.
 Free version will do the work for the most of you.
 
 ### (2) add new repo (and add collaborator if it is private) 
 click **+**
 
 ![](https://help.github.com/assets/images/help/repository/repo-create.png)
 
 or **new**
 
 ![](https://github.com/ledong1/HowToUseGitHub/blob/master/Snipaste_2020-02-12_01-36-04.png?raw=true)
 
 ### (2.5) add collaborator
 * go to your private repo,click setting
 
 * click collaborator on the left
 
 ![](https://github.com/ledong1/HowToUseGitHub/blob/master/Snipaste_2020-02-12_01-51-13.png?raw=true)
 
 * search username and add
 
 ![](https://github.com/ledong1/HowToUseGitHub/blob/master/Snipaste_2020-02-12_01-52-56.png?raw=true)
 
 ### (3) Get online repo URL
![](https://github.com/ledong1/HowToUseGitHub/blob/master/geturl.png?raw=true)
 
 
# 2. On your Win/Mac using cmd/terminal
### (1)Install Git
[gin download](https://git-scm.com/downloads)
### (2) basic commands for cmd/terminal

| Comands| Win |Mac/linux  | 
|--|--|--|
|show directory | >dir |>ls  |
|change directory|>cd|>cd|
|go one floder up|>cd\.\.|>cd\.\.|
[other win commands](https://www.digitalcitizen.life/command-prompt-how-use-basic-commands)
[other mac commands](https://macpaw.com/how-to/use-terminal-on-mac)
  
### (3) commands for git
   * init local repo: ` >git init` ![enter image description here](https://github.com/ledong1/HowToUseGitHub/blob/master/git%20init.png?raw=true)
   * add changes: `>git add`
![](https://github.com/ledong1/HowToUseGitHub/blob/master/git%20add.png?raw=true)
   * commit changes: `>git commit -m "your commit note"` ![](https://github.com/ledong1/HowToUseGitHub/blob/master/git%20commit.png?raw=true)
   * add remote repo address: `>git remote add origin *URL*`![](https://github.com/ledong1/HowToUseGitHub/blob/master/git%20remote%20add.png?raw=true)

   * push to remote: `>git push -u origin master`![](https://github.com/ledong1/HowToUseGitHub/blob/master/git%20push.png?raw=true)
	 * EVERY Time you want to PUSH, First add and commit, and pull, after all these, push, or it might be 		   overwritten : (
   * pull from remote: `>git pull origin master`
     
      ![](https://github.com/ledong1/HowToUseGitHub/blob/master/git%20pull.png?raw=true)
   
     * EVERY Time you want to PULL, add and commit!!! your local repo first, or it might be overwritten : (
     * EVERY Time you want to PUSH, First add and commit, then pull, at last push, or it might be overwritten : (
   * clone from repo: `>git clone *URL* `![](https://github.com/ledong1/HowToUseGitHub/blob/master/git%20clone.png?raw=true)
   
# 3. Special for eclipse java
  ### Already create a java file?   ->`git init` in that path and push it
   1. use `cd` to get in the eclipse workspace
  (way to find where your file is)
  ![](https://github.com/ledong1/HowToUseGitHub/blob/master/eclipse%20path.png?raw=true)
    
   2. `>git init`  in that path![](https://github.com/ledong1/HowToUseGitHub/blob/master/git%20init%20in%20that%20path.png?raw=true)
    
   3. `>git add --all`
    
   4. `git commit -m '*your notes*'`
    ![](https://github.com/ledong1/HowToUseGitHub/blob/master/git%20add%20commit.png?raw=true)
    
   6. `git remote add origin *URL*`
    
   7. `git push origin master`![](https://github.com/ledong1/HowToUseGitHub/blob/master/gitpush3.png?raw=true)
  
  ### Don't have local Java file?  ->use eclipse import function
1. Right click in your eclipse Project Explorer, and choose "import"

![](https://github.com/ledong1/HowToUseGitHub/blob/master/ec%20import%201.png?raw=true)

3. "git"->"projects from git (with smart import)", then next

![enter image description here](https://github.com/ledong1/HowToUseGitHub/blob/master/e%20import%202.png?raw=true)
 
 
5.  "clone url", then next

![enter image description here](https://github.com/ledong1/HowToUseGitHub/blob/master/eimport3.png?raw=true)

7. entre the URL of your github repo in "URL", and enter your github username and password. Then click "next"

![](https://github.com/ledong1/HowToUseGitHub/blob/master/eimport4.jpg?raw=true)


5. choose the branch you want to import(just master), then "next"

![enter image description here](https://github.com/ledong1/HowToUseGitHub/blob/master/eimport5.png?raw=true)

7. "browse" your directory, to find the place you want to save it. then "next"

![enter image description here](https://github.com/ledong1/HowToUseGitHub/blob/master/eimport6.png?raw=true)

7. wait for a while, then choose the parts you want to import, then "finish"

![enter image description here](https://github.com/ledong1/HowToUseGitHub/blob/master/eimport7.png?raw=true)



## Other Resources

 [GitHub Cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)
 
 [Youtube video about github](https://www.youtube.com/watch?v=SWYqp7iY_Tc) 



