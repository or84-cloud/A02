# A02

*All About: Git*
-- 
Have you ever worked hard on a project and forgot to save it? This happens all too often to developers and their teams. Sure, it happens, but what if there was a way to save your code, and be able to reference different versions of the source code? This is what Linus Torvalds and his team experienced when creating the Linux kernel in 2005. This new kind of version control lets developers save "snapshots" of their projects to experiment with new features safely. It also allows for developing tems to create and share versions with each other without overwriting. The team initially used "BitKeeper" but switched to Git after licensing disagreements. In fact, Torvalds famously wrote the program in 10 days and preformed his first commit for Git with... Git! 

*All About: GitHub*
-- 
Despite the intial confusion, GitHub and Git are similar, but actually unrelated. Github is a cloud-based platform for hosting Git repositories. It's like a social network for your coding projects. You can store your projects online, collaborate with other developers, share your work, and contribute to open-source projects. GitHub adds features like issue tracking, pull requests, and project management tools on top of Git. 

*All About: Jetbrains -- WebStorm*
-- 
Webstorm is a powerful integrated development environment (IDE) made by JetBrains specifically for web development. JetBrains was founded in 2000 and has built it's reputation on creating intelligent, productivity enhancing tools for software developers and teams. It provides intelligent code completion, debugging tools, built-in Git integration, and support for JavaScript, TypeScript, HTML, CSS, and modern frameworks like React, Vue, and Angular. It makes coding faster and easier with its smart features. As well as this, it also supports other applications like Webstorm that are better for other coding lanugages meant for diffferent purposes (i.e, PyCharm, IntelliJ IDEA and CLion)

*How To: Add Git to your workstation*
--
First, open your internet browser of choice, and write: 'https://git-scm.com' into the search bar and press the 'enter or 'return' key. Once you reach the website, you'll be greeted with a short description of what Git is and a place to download the latest version. Scroll down, and stop when you see the computer monitor with the download link to for your operating system. The website should automatically recognize what operating system you're working from, so you don't need to look for a specific version.

<ins>*For Linux and Mac Users:*</ins> At this point in the process, you will need an extra tool for **Git** to be able to work on your device. While on the website, open a seperate tab and write 'https://homebrew.sh' in your browser's webpage. Here, you'll be able to download Homebrew, an open-source software package manager for these operating systems that simplifies installation and software management processes. Search for the following script to be able to enter it in your Terminal or shell management app in coordination with your specific Linux distro. 

Once Homebrew is installed, return to your 'https://git-scm.com' tab. Then, click the download button that appears on the image of the computer screen. This will put you on a page that shows you the script to download **Git**. Here, you'll need to return to your Terminal, or your shell management system. Copy and paste the script from the website and enter it into the shell. Press the 'Enter' or 'Return' key and wait until the installation process is complete. 

<ins>*For Windows Users:*</ins> You may skip the Hombrew installation and proceed with downloading **Git** directly from the website. Once downloaded, open the .exe file and continue along the set up process that will include where you want **Git** to stay on your device, which IDE you will be able to use Git in, and the licensing agreement. 

To check if you have the latest version of **Git**, enter or copy and past the following script into the Terminal or shell management system: 'git --version'

Congratulations! You now have **Git** installed to your device. 

*How To: Create an Account with GitHub*
-- 
Now that you have **Git** installed, it'll be a good idea to get a GitHub account set up, especially, if you plan to develop projects often. To do this, enter your web browser again and enter 'github.com' and press the 'enter' or 'return' key. On the site, you will be able to see the 'Sign in' and 'Create Account' tabs. Click on the 'Create Account' tab and enter the required credientials. 

*Note: If you have specialized credientials that give you a premium version of GitHub, check in your profile's settings to activate it, or contact your group, professor, or administrator.*

Then, it will give you the option to set up two-factor authentication. This is a key tool in securing your account(s) from future cyberattacks. They can come in many different forms, but the most easiest is to download an authenticator app like Google Authenticator, Microsoft Authenticator, or use your campus' authenticator. This can vary in university's (or a college's) policy. At the undergraduate level at a four-year university, DUO will likely be your school's authenticator.

Now, follow the setting up instructions given in your confirmation email, and add Two-Factor authentication to your account. 

Congratulations! You now have GitHub! 

*How To: Add WebStorm to your workstation* 
--
With Git installed and a GitHub created, the next application to download is Webstorm. This IDE is great for website development as well as other front-end developing. First, re-enter your internet browser and visit JetBrains' official website at 'jetbrains.com/webstorm' and press the 'enter' or 'return' key. 

*Note:* If you have been given the clearance, or have special credentials, log in now to be able to change your Webstorm's license so that you can access the app without needing to pay for the subscription after the 30-day free trial. If not, continue along with the process, but just know that it is a paid software like Microsoft Office 365 and all Adobe creative products.

Once you arrive at the website, click the download button and select your operating system. 

*For Windows Users:* Open the .exe file and follow the given instructios from the installation wizard. Then, select your installation location and make sure that it is in a file or place on your device that has easy access. Now, you can select and customize your options like creating shortcuts and adding 'Open Folder as Project' commands onto the context menu. 

*For MacOS Users:* Open the .dmg file and drag the Webstorm icon to the applications folder. Then, double click on the application to open the file. The set up processes is likely to be universal for all operating systems. 

*For Linux users:* Extract the downloaded '.tar.gz' file and navigate to the extracted file in your terminal. Run the following script: './bin/webstorm.sh' and continue along with the setup wizard. 

*Configuring Git Integration (Optional, but highly recommended):*

Open Webstorm and and click the file tab (click on the gear icon on MacOS), then navigate to the 'Version Control' Section. Webstorm will automatically detect it if it is installed on your device. If so, select 'Test' and make sure that the version number of your Git is the latest one. (You can also link yout GitHub here in Version Control as well.)

*Glossary*
--
1. *Branch:* A branch, or branching may also refer to to act of switching execution to a different instruction sequence as a result of executing a branch instruction.
   
3. *Clone:* Downloads an existing repository from a remote server.
   
5. *Commit:* Saves changes to the local repository. You can also make changes to your git commit.
   
7. *Fetch:* Downloads objects and tags from another repository.
   
9. *Git:* An app dedicated to the version control of source code files.
    
11. *Github:* A web-based interfaced that uses Git, the open source version control software that lets multiple that lets multiple people make seperate changes to web pages at the same time. It also allows developers to create, store and manage and share their code.
    
13. *Merge:* A **merge** allows the developer to join two different forked histories together again.
    
15. *Merge Conflict:* A system error that occurs when more than one file changes are made to the same line of code, or section of a file. **Git** can't automatically decide which changes to keep and which to discard.
    
16. *Push:* The **push** command uploads the data content from a local repository to a remote repository, like **Github**.
    
17. *Pull:* A command used to download and integrate changes from a remote repository (Like GitHub) into your local repository.

18. *Remote:* The management tool for the record of remote repositories. It'll allow you to save long URLs as shortend handles so you don't need to write out the entire title all of the time. This'll also allow you to use other git commands to add, change and delete them.
    
19. *Repository:* A data structure that centralizes digital storage that developers use to make and manage changes to an applications source code file. Think of a digital filing cabinet that has every saved version of your code.

*<ins>Works Cited:</ins>*
--

1. A very brief history of Git - Git Version Control. (2022, August 29). CraftQuest. https://craftquest.io/guides/git/getting-started/a-very-brief-history-of-git#:~:text=Git%20was%20created%20in%202005,used%20BitKeeper%20for%20version%20control. 

2. Blau, T. (2025, April 7). Git turns 20: A Q&A with Linus Torvalds. The GitHub Blog. https://github.blog/open-source/git/git-turns-20-a-qa-with-linus-torvalds/#:~:text=Torvalds%20famously%20wrote%20Git%20in,BitKeeper%2C%20due%20to%20licensing%20disagreements. 

3. Code Institute. (2022, September 28). What is GitHub | how to use it | benefits of GitHub [Video]. YouTube. https://www.youtube.com/watch?v=BUE2LaSzijM 

4. Corbo, A. (2025, July 8). What is Git? Built In. https://builtin.com/software-engineering-perspectives/git#:~:text=Git%2C%20a%20version%20control%20system,be%20merged%20into%20one%20location.

5. Getting started with your GitHub account - GitHub Docs. (n.d.). GitHub Docs. https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account 

6. Git - git-fetch Documentation. (n.d.). https://git-scm.com/docs/git-fetch 

7. Git - sharing and updating projects. (n.d.). https://git-scm.com/book/pl/v2/Appendix-C:-Git-Commands-Sharing-and-Updating-Projects#:~:text=git%20push,difference%20into%20the%20other%20repository. 

8. Git commands. (n.d.). Learn Version Control With Git. https://www.git-tower.com/learn/git/commands#:~:text=git%20commit%20%2D%20Saving%20changes%20to,changes%20on%20a%20remote%20server 

9. History of GitHub. (n.d.). https://pslmodels.github.io/Git-Tutorial/content/background/GitHubHistory.html 

10. What is Repo? - Repository Explained - AWS. (n.d.). Amazon Web Services, Inc. https://aws.amazon.com/what-is/repo/#:~:text=your%20repo%20requirements%3F-,What%20is%20a%20repo%3F,of%20documents%20when%20developing%20software. 

11. Wikipedia contributors. (2025a, September 17). JetBrains. Wikipedia. https://en.wikipedia.org/wiki/JetBrains Wikipedia contributors. (2025b, September 18).
    
12. Git. Wikipedia. https://en.wikipedia.org/wiki/Git#:~:text=Git%20is%20free%20and%20open,development%20of%20the%20Linux%20kernel.
