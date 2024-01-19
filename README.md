# A11y Study Group - Websites Project

This community open source project is a set of very accessible websites with minimal styling to support the [GitHub repo for the Web Accessibiilty Study Group](https://github.com/codingtherapist/webAccessibilityStudyGroup). It's inspired by Dorlyn's comments during the opening live stream of our second term on Thursday, January 19, 2024. Doryln is a screenreader user with an awesomely adorable guide dog.

Some members find using an well coded website more accessible than using GitHub to read study group information.

The Web Accessibility Study Group started in August and September of 2023 by [Africa Kenya](https://github.com/codingtherapist). It's snowballed and the last time one of us checked we had people from 11 countries.

Please go to [the main repo discussion forum](https://github.com/codingtherapist/webAccessibilityStudyGroup/discussions/5) to ask for more information about our group and to join. This repo is just for the community website project.

## Project Goals

1. To have a set of highly accessible websites that are highly customized for our members who are screenreader, refreshable braille display, keyboard, and alternative input/output device users, and/or are disabled, neurodiverse.
2. To provide a community supported project where members of the Web Accessibility Study Group can practice their accessible coding skills, Git/GitHub skills while contributing to an open source project.
3. To provide a reference of accessible example code for the wider developer community. 

## Contributors

Members of the Web Accessibilty Study Group who are developers or who want to work on their coding and Git/GitHub skills while contributing to open source are invited to contribute to this project.

## How to Contribute

1. Please be nice! I'm using the [TorontoJS Code of Conduct]() because I'm a member and volunteer there. It works and why reinvent the wheel.
2. Please comment on an issue
3. If you don't see an issue you're interested in you are welcome to create one.
4. Please follow the file structure detailed below and in the code directories
5. While you can @ mention me in a discussion thread in this repo, @ mentioning me or DMing me in our discord channel is likley to be quicker.
6. Project resources for those newer to coding and/or markdown are in the [resources.md file]() of this repo. **HEY LIZ ADD THE LINK WHEN YOU CREATE THE FILE!**
7. Please use CSS variables. See the example below and in the /styles.css
8. Contributors and other Web Accessibility Study Group members are invited to be part of the [TorontoJS](https://torontojs.com) Code Buddy Club. I'm a co-founder and co-organizer. Information about the TorontoJS Code Buddy Club is in my January 2024 [LinkedIn Post](https://www.linkedin.com/posts/elizabethmccready_github-javascript-softwareengineering-activity-7147949670831468544-q2VC?utm_source=share&utm_medium=member_desktop) You can also reach out to the other TorontoJS Code Buddy Club co-founders [Sami] or [Marco Campos].

### File Structure - Rendered Pages (e.g. .html files)

To facilitate this projects' two goals please follow the file structure below:

#### /index

The project's home page. Please do not edit or submit an issue unless there's a spelling mistake or something is inaccessible.
This page is a dark theme with slightyly larger text. I've chosen that because it's my personal preference, and I'm the one developing it.

#### /index/theme-name-home
  
The home page of a specific theme

#### /index/theme-name-home/page-name

A site page styled with the specific theme. If this were a single site the address would be `index/page-name`

#### /index/js/theme-name and /index/js/flavour-of-javascript-name/index.html

If you're going to use JavaScript in a site, please put everything inside the /js directory! JavaScript adds a level of complexity and responsiblity for ensuring that the code is accessible for screenreader, refreshable braille display, keyboard, and alternative input/output device users.

If you use a Javascript library or framework, and/or a UI library such as Tailwind, Charka UI, or Material UI please place it inside the `/index/js/` directory. **Please subnit an issue if you are going to use anything but vanilla js and vanilla css.** There is nothing wrong with not using vanilla js and css - my favourite stack right now is Next.js and Tailwind - but the primary goal of this project is to create sites that are accessible for our study group members.

- Pages inside sites with vanilla JavaScript would have the following file structure: `/index/js/theme-name/page-name`

#### /index/language-name/theme-name

If anyone ever wants to go to town and use another programming language besides vanilla JavaScript or a JS framework of library, (e.g. Ruby on Rails), please follow this file structure. While it's not a priority, experimenting with coding accessiblity in other programming langages that can be used to create web apps is welcome. 

Please contact me by submitting an issue before creating a site with another

#### /index/theme-name/theme-name-styles.css

Please name your css file with `theme-name-styles.css` and place it inside your `/index/theme-name` directory.







