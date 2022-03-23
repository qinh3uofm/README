# How to Host resume online
--------------------------------------------

## Purpose: 

- Describe the practical steps of how to host and format my resume using Markdown, Visual studio code, GitHub Pages, and Jekyll.  

- Relate the practical steps described above to the general principles of current Technical Writing, as explained in Andrew Etter's book Modern Technical Writing 

---------------------------------------------


## Prerequisites:
- In order to host your resume in GitHub page, you will need your resume formatted in Markdown.
- A GitHub account is needed to use GitHub page.
- Markdown editor is highly recommanded, although you can edit markdown file on github, it is much easier to do it in applications like Visual Studio Code.

Here is a demo:
![](https://github.com/qinh3uofm/qinh3uofm.github.io/blob/main/ezgif.com-gif-maker.gif)

---------------------------------------------


## How I write my resume using Etter's protocol:

### 1. Use a lightweight markup language.
Etter believes simplicity is very important by using lightweight markups. Compared to other text editors the way to use Markdown files is easier to learn, markdown files can save users a lot of time when they get used to them because it is much faster. 

### 2. Format a document with a static site generator.
To make your website easy to read and navigate, Etter recommends using a static site generator to create a website. GitHub page with help from built-in Jekyll is a great way to accomplish this task.

### 3. Share/Host documents on a distributed version control system.
Etter recommends using distributed version control systems (DVCS) like Git and Mercurial over centralized systems in his book. Distributed version control systems keep our files up-to-date while allowing local editing. In our case, we chose to use GitHub.

-------------------------------------------------

### Specific instructions using three protocols mentioned above
- Create a new public repository and name it yourusername.github.io where "yourusername" is your GitHub username.
- Copy the URL of your new repository then open Visual Studio Code and clone the URL to it.
- Create resume.md, readme.md, and _config.yml file in Visual Studio Code.
   - readme.md has the information on how to create and host you resume online using GitHub pages.
   - resume.md is the resume you want to host.
   - _config.yml holds the settings of your website.
- Commit the changes then push your local file onto GitHub.
- Go to your repository on GitHub and check if the files are successfully uploaded. If it did not appear in your repository, check the link of your repository in Visual Studio Code is correct.
- Type yourusername.github.io in the search bar of your browser to see your readme file online.
- Type yourusername.github.io/resume in the search bar of your browser to see your resume online.
- To change the settings and layout of your websites, you can change the content of the _config.yml
- You are all set and your resume page is ready now!

---------------------------------------------


### Other tips in Etter's book that might be helpful:

#### 1.Catalog the Diff
Etter believes record changes to a product are one of the most important functions of a technical writer. Good change logs convince people to upgrade, inspire confidence in the direction of a product, and help developers take advantage of new features. Before I make changes to my resume, I create a new branch on my repository first, after I have down all the changes I merge the new branch to the main branch and commit it.

#### 2.Build a Website
Building and hosting a website is necessary for modern technical writing, PDFs and other documentation goes out of date and becomes stale as time goes by. A newer version might be better but the modern web browser does not overwrite the old files. By hosting a website all the information is synced quickly thus information provided there is up to date.

#### 3. Help Others Write
By using Github Page, everyone can see my resume website and commit changes to it. Any help is appreciated since my resume might have a large space for improvement that I am not aware of.

#### 4.Publish Frequently
Publishing is very easy using Github Page, just commit your code then click commit changes then you are good to go. In a few minutes, you can see your newly published website.

---------------------------------------------

### More Resource:
1. Learn more about markdown [here](https://www.markdowntutorial.com).

2. You can find Etter's book Modern Technical Writing[here](https://github.com/qinh3uofm/qinh3uofm.github.io/blob/main/Andrew_Etter_-_Modern_Technical_Writing__An_Introduction_to_Software_Documentation_2016.epub).

3. I learned how to make gifs using screenshots on [this](https://ezgif.com/maker) website.

---------------------------------------------


## Authors and Acknowledgments:

- Author: Hao Qin
- Author of Modern Technical Writing: Andrew Etter
- Group members:
   - Kyle Calinisan
   - Scott Jodoin
   - Tahmidul Zidaan
   - Raven Carencia

---------------------------------------------


## FAQs:
1. **Why is Markdown better than a word processor?**


Markdown gets rid of complicated buttons of Microsoft word; more importantly, you do not even need a mouse when writing a Markdown file. All the modification of format is done by keyboard using simple instruction which is easy to learn in less than an hour. It saves a lot of time for the advanced writer who is familiar with Markdown files. 


2. **Why is my resume not showing up?**


It might take a few minutes for your resume to show up due to internet latency. If it still does not show up, you might want to check if you put your resume in the right repositories named 'yourusername'.github.io and make sure the resume is in the main branch as default. The resume needs to be an HTML or markdown file


