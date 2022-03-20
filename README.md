<h1 align="center">All About The Sauce Recipe Storing and Sharing Website Application</h1>

[View the live project here on Heroku.](https://ci-ms3-recipe-app.herokuapp.com/)

This is a peer sharing recipe application to be used by anyone wishing to get, share, or store recipes.

<h2 align="center"><img src="https://cdn.pixabay.com/photo/2016/12/31/09/17/food-1942403_960_720.jpg"></h2>

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site and immediately see some recipes to get inspired.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to easily be able to register an account.

    -   #### Frequent User Goals
        1. As a Frequent User, I want to update my recipes and add newly discovered ones.
        2. As a Frequent User, I want to check on other users' recipes.
        3. As a Frequent User, I want to manage my account easily.

-   ### Design
    -   #### Colour Scheme
        -   Italian inspired - "Il tricolore" = Philippine Green (#008C45); Anti-Flash White (#F4F5F0); Fire Engine Red (#CD212A)
    -   #### Typography
        -   The Montserrat font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Montserrat is a clean font used frequently in programming, so it is both attractive and appropriate.
    -   #### Imagery
        -   Imagery is important. The large, background hero image is designed to be striking and catch the user's attention. It also has a modern, energetic aesthetic.

*   ### Wireframes

    -   Home Page (public) Wireframe - [View](https://github.com/greggo58/CI_MS3_Recipe_App/blob/main/wireframes/Home%20screen%20-%20private.png)

    -   Home Page (private) Wireframe - [View](https://github.com/greggo58/CI_MS3_Recipe_App/blob/main/wireframes/Home%20screen%20-%20private.png)

    -   Login Page (public) Wireframe - [View](https://github.com/greggo58/CI_MS3_Recipe_App/blob/main/wireframes/Login%20screen%20-%20private.png)

    -   Register Page (public) Wireframe - [View](https://github.com/greggo58/CI_MS3_Recipe_App/blob/main/wireframes/Register%20screen%20-%20private.png)

    -   Account Page (private) Wireframe - [View](https://github.com/greggo58/CI_MS3_Recipe_App/blob/main/wireframes/Account%20screen%20-%20private.png)

    -   New Recipe Page (private) Wireframe - [View](https://github.com/greggo58/CI_MS3_Recipe_App/blob/main/wireframes/New%20Recipe%20screen%20-%20private.png)

## Features

-   Responsive on all device sizes
-   Interactive elements
-   CRUD operations with a database

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
-   [Python](https://en.wikipedia.org/wiki/Python_(programming_language))
-   [Flask](https://en.wikipedia.org/wiki/Flask_(web_framework))
-   [MongoDB](https://en.wikipedia.org/wiki/MongoDB)

### Frameworks, Libraries & Programs Used

1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [Materialize](https://materializecss.com/)
    - Materialize was used as a CSS style bootstrap for the navbar and screen elements.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site and immediately see some recipes to get inspired.
        1. As a First Time Visitor, when I enter the site I immediately see the title "All About The Sauce" and am drawn to the hero image of the pasta dish.
        2. As a First Time Visitor, I can see the search area with the recipes listed below.
    2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
        1. As a First Time Visitor, I only need to be on the main page of recipes. One click is all it takes to get to the registration page.
-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to easily be able to register an account.
        1. As a Returning Visitor, it is easy to find the option to register and the form is intuitive and easy to complete.

-   #### Frequent User Goals
    1. As a Frequent User, I want to update my recipes and add newly discovered ones.
        1. As a Frequent User, I am able to log into the application and begin working on and viewing recipes.
    2. As a Frequent User, I want to check on other users' recipes.
        1. As a Frequent User, I can see recipes from other creators.
    3. As a Frequent User, I want to manage my account easily.
        1. As a Frequent User, I am able to delete my account very easily.

### Further Testing

-   The Website was tested on Google Chrome, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, Android Smartphone, Apple iPhone.
-   A large amount of testing was done to ensure that all pages were linking correctly and thte data binding was functioning correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

-   On some mobile devices the title on the navbar overflows.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

### Heroku

[Heroku - Github Integration](https://devcenter.heroku.com/articles/github-integration)

#### **Enabling GitHub Integration**
You can configure GitHub integration in the **Deploy** tab of apps in the [Heroku Dashboard](https://dashboard.heroku.com/).

<img src="https://devcenter1.assets.heroku.com/article-images/2349-imported-1443570588-2349-imported-1443555058-421-original.jpg">

To configure GitHub integration, you have to authenticate with GitHub. You only have to do this once per Heroku account.

>GitHub repo admin access is required for you to configure automatic GitHub deploys. This is because Heroku has to register a service hook on the GitHub repo, and this action requires admin access. For GitHub organisations, your GitHub account will also need to be a member of the organisation and not an outside collaborator.

>If your repo is in a GitHub organization that has third-party application restrictions enabled, an organization admin needs to approve Heroku for use with the organization. More details are available on GitHub.

After you link your Heroku app to a GitHub repo, you can selectively deploy from branches or configure auto-deploys.

If you do not have any apps, you must approve integration for your organization from GitHub. For more information about this process, see Approving OAth Apps for your organization.

#### **Manual Deploys**
With manual deploys, you can create an immediate deployment of any branch from the GitHub repo that’s connected to your app. Use manual deploys if you want to control when changes are deployed to Heroku.

<img src="https://devcenter1.assets.heroku.com/article-images/2349-imported-1443570589-2349-imported-1443555058-422-original.jpg">

You can also use manual deploys to temporarily deploy a branch other than the one that’s configured for automatic deployment. For example, you might have a development app synced to the **development** GitHub branch, but you temporarily want to test a feature branch. Simply trigger a manual deploy of the feature branch to test it on the Heroku app. Note that release of the feature branch is overwritten on the next successful GitHub push to the **development** branch.

#### **Automatic Deploys**
When you enable automatic deploys for a GitHub branch, Heroku builds and deploys all pushes to that branch. If, for example, you have a development app on Heroku, you can configure pushes to your GitHub development branch to be automatically built and deployed to that app.

<img src="https://devcenter3.assets.heroku.com/article-images/2349-imported-1443570589-2349-imported-1443555058-423-original.jpg">

If you’ve configured your GitHub repo to use automated Continuous Integration (with Travis CI, for example), you can check the “Wait for CI to pass before deploy” checkbox. When enabled, Heroku will only auto-deploy after all the commit statuses of the relevant commit show **success**.

This commit won’t auto-deploy because one of the checks shows a **pending** status:<img src="https://devcenter3.assets.heroku.com/article-images/1516299367-Screen-Shot-2018-01-18-at-9.35.09-AM.png">

This commit will auto-deploy because all of the checks show a status of success:<img src="https://devcenter0.assets.heroku.com/article-images/1516299538-Screen-Shot-2018-01-18-at-10.12.16-AM.png">

#### **Review Apps**
With review apps enabled for a Heroku app, Heroku will create temporary test apps for each pull request that’s opened on the GitHub repo that’s connected to the parent app. Review apps are great if you’re using [GitHub Flow](https://guides.github.com/introduction/flow/) to propose, discuss, and merge changes to your code base. Because pull request branches are deployed to new apps on Heroku, it’s very simple for you and your collaborators to test and debug code branches. You can also run automated integration tests on the Heroku app representing a GitHub branch.

See the [Review apps article](https://devcenter.heroku.com/articles/github-integration-review-apps) for details.

#### **Heroku CI**
Once you’ve connected your GitHub repo to your Pipeline, you can turn on Heroku CI, our visual, low-configuration test runner that integrates easily with Heroku Pipelines (and so complements Review apps, existing Heroku apps, and our GitHub integrations). Any Heroku Pipeline is already Heroku CI ready – just turn it on in the Pipeline’s Settings tab.

#### **Links to Diffs**
For apps that are linked to GitHub repos, releases in the Dashboard Activity tab will include a “View Diff” link. Following the link will take you to the GitHub comparison view, showing the changes made since the last release.

<img src="https://devcenter0.assets.heroku.com/article-images/2349-imported-1443570590-2349-imported-1443555059-411-original.jpg">

#### **Disconnecting from GitHub**
Disconnecting Individual Apps
Individual apps can be disconnected in the GitHub pane of the **Deploy** tab for the app.

<img src="https://devcenter3.assets.heroku.com/article-images/2349-imported-1443570591-2349-imported-1443555059-434-original.jpg">

#### **Disconnecting Account**
You can disconnect your Heroku and GitHub accounts in the [Applications pane on your Dashboard account page](https://dashboard.heroku.com/account/applications#third-party-applications).

<img src="https://devcenter2.assets.heroku.com/article-images/1576871458-Screen-Shot-on-2019-12-20-at-11-50-08.png">

## Credits

### Code

-   The full-screen hero image code came from [Pixabay](https://pixabay.com/photos/food-cooking-restaurant-italian-1942403/)

### Content

-   All content was written by the developer.

-   Psychological properties of colours text in the README.md was found [here](http://www.colour-affects.co.uk/psychological-properties-of-colours)

### Media

-   The hero image was collected from [Pixabay](https://pixabay.com/photos/food-cooking-restaurant-italian-1942403/).

### Acknowledgements

-   Friends and family for their support and help.