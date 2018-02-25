# Guideline

For writing the Begin With It pages, we will be using Markdown syntax. Following materials will be useful if you are not familiar with Markdown syntax.
* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

Followings are the guidelines of writing the pages which should be located in [/content](https://github.com/asankasri/begin-with-it-alpha/tree/master/content) directorly.

After create a new page, please do not forget to add it in the main [README.md](https://github.com/asankasri/begin-with-it-alpha/blob/master/README.md) file.

## File Name
* Name of the file should be lowercase and seperated with hyphen for multiple words
* Files should be in .md format
* Ex:
  * angular.md
  * react-native.md

## Structure
* Icon
* Title
* Official Links
* Content

### >>> Icon
* Icons should be located in [/icons](https://github.com/asankasri/begin-with-it-alpha/tree/master/icons) directorly
* Icon names should follow the file names
* Icon format is .png and the size is 128x128
* So that the full name of the should be, {filename}_128x128.png
* Ex:
  * angular_128x128.png
  * react-native_128x128.png

### >>> Title
* Title should follow the title case.
* Format of the title is, "Begin with {Technology Name}"
* Icon also will stay together with the title.
* Ex:
```
# ![Angular](https://raw.githubusercontent.com/asankasri/begin-with-it-alpha/master/icons/angular_128x128.png "Angular") Begin with Angular
```
```
# ![React Native](https://raw.githubusercontent.com/asankasri/begin-with-it-alpha/master/icons/react-native_128x128.png "React Native") Begin with React Native
```
* Note: raw.githubusercontent.com is used to fetch the icon.

### >>> Official Links
* Useful official links should goes here.
* Ex:
  * Official Website
  * Docs / Guides
  * Github Repo

### >>> Content

#### >> Intro
A breif explanation of the technology, problably in one or two sentences.

#### >> QuickStart
This is the heart of the page. Idea of this section is to give a tiny and clear explanation for the beginners to experiment the relevant technology in no time.

##### > Installation
Commands to install the prerequisites and the relevant technology.
  
##### > Create a new project
This could be either creating a new project from scratch or creating a local project by cloning an official github example project.

##### > Run the project
Commands to run the project in dev or production enviroment.

**NOTE: Headings of the QuickStart can be varied depending on the technology. So feel free to structure the headings according to the technology.**

#### >> Courses & Tutorials
Since there might be tons of courses / videos and tutorials, let's try to keep some of most relevant, interesting and updated learning materials for helping the beginners to learn deeply in addition to our guide.

