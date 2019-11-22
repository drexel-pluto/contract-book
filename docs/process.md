# Stack / Technologies
![mern stack](_media/mern.jpg)


The technologies we're using to operate our server will help us serve a scalable, maintainable, flexible API. Since many of our developers only have experience writing JavaScript (JS) for front-end, we'll be using a full JS stack for front-end and back-end development.

Pluto will run on Node.JS using the Express.JS web application framework. For our database, we'll be using MongoDB and Mongoose.JS for object data modeling, which will help us maintain communicate with our database in the JS ecosystem. To maintain the integrity of our codebase, we'll be implementing Jest.JS to test our platform each time a new feature is added.

For front-end development, we'll be using React Native to develop a native mobile application. React Native will maintain our singular language ecosystem, while also enabling us to launch on iPhone and Android platforms.

# Version Control

Throughout development, we'll be using GitHub for version control. Here is a link to our GitHub organization, where our repositories lay in comfort: [https://github.com/drexel-pluto](https://github.com/drexel-pluto).

# New Code Additions
We'll be using feature-branching and pull requests as we develop on separate machines.

For teammates:
After you've written code for a new feature on your local machine, you'll want to get that work in the master branch for everyone to see and use. If you get confused and run into issues, reach out to Clay or Mike on Slack to assist you. To begin merging your code, there are a few steps:
1. Make sure your code is up to date and won't overwrite any new additions
2. Make sure your work in on a new branch titled as the feature you're working on
    - `git checkout -b Encrypts-Newly-Created-Passwords`
3. Push your code to the branch on your remote repository
    - `git add -A`
        - Make sure these are the correct files you want to add!
        - Check by running `git status`
    - `git commit -m 'Encrypts newly added passwords'`
    - `git push origin Encrypts-Newly-Created-Passwords`
5. Create a pull request to the repository, specifying that you'd like to merge your `Encrypts-Newly-Created-Passwords` branch onto the master








