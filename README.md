# **Wanderlust Recipes** - by Russell Oakham

## **Project overview**

'Wanderlust Recipes' is a community-focused website, where user accounts can create, share and review recipe ideas.

The site is created to engage users of all ages and backgrounds, so is branded in a light, clean and neutral style. Additionally, the term 'Wanderlust' is defined as a ['lust for wandering'](https://www.merriam-webster.com/dictionary/wanderlust), so styling elements have been chosen to promote curiosity and exploration.

## **Deployed site**

## **Table of Contents**

1. [**UX**](./#1-ux)
   * [**User-Stories**](./#user-stories)
   * [**Structure**](./#structure)
   * [**Skeleton**](./#skeleton)
   * [**Surface**](./#surface)
2. [**Features**](./#2-features)
   * [**Existing Features**](./#existing-features)
   * [**Features to consider in future**](./#features-to-consider-implementing-in-future)
3. [**Technologies Used**](./#3-technologies-used)
4. [**Testing**](./#4-testing)
5. [**Deployment**](./#5-deployment)
   * [**GitHub Pages**](./#github-pages)
6. [**Credits**](./#6-credits)
   * [**Design and Research**](./#design-and-research)
   * [**Technical**](./#technical)
   * [**Content**](./#content)
   * [**Media**](./#media)
   * [**Acknowledgements**](./#acknowledgements)

## 1. **UX**

Overview of UX decisions, structure etc. Examples of websites I have viewed as part of research & resulting UX design decisions.

### **User Stories**

<details>
<summary>Browsing</summary>

* \(US001\) - As a user I want the website to clearly display recipe suggestions to me so I can be introduced to new content.
* \(US002\) - As a user I want to see recipe reviews and comments from other users, so I am informed of the best recipes.
</details>
<details>
<summary>Searching</summary>

* \(US003\) - As a user, I want to be able to view recipes by category, so I can find recipes of specific type I would like to make.
* \(US004\) - As a user, I want to be able to search recipes by keyword, so I can find recipes easily, for example by name or by included ingredient.
* \(US005\) - As a user, I want to be able to search and filter recipes by rating, so I can find only the highest-rated recipes to choose from.
* \(US006\) - As a user, I want to be able to search and filter recipes by serving size, so I can find recipes suited to the number of people I am catering to.
* \(US007\) - As a user, I want to be able to search and filter recipes by preparation and cooking time, so I find recipes that are suitable to my available time.
* \(US008\) - As a user, I want to be about to save my favourite recipes, so I can quickly find them again in future.
</details>

<details>
<summary>Uploading Recipes</summary>

* \(US009\) - As a user, I want to be able to upload my own recipes, so other users can benefit from them.
* \(US010\) - As a user, I want to gain feedback on the recipes I upload, so I can determine improvements.
* \(US011\) - As a user, I want to be able to edit and improve recipes I have already uploaded.
</details>

<details>
<summary>Users</summary>

* \(US012\) - As a user, I want to be able to register with the site, so I can upload and edit recipes, plus save my favourite recipes.
* \(US013\) - As a registered user, I want to be able to login to my account, so I can access and edit my recipes, and find my favourite recipes.
* \(US014\) - As a registered user, I want to be able to submit ratings and reviews for recipes submitted by other users.
</details>

<details>
<summary>Administration</summary>

* \(US015\) - As an admin I want to be able to edit content, to ensure it adheres to site rules.
* \(US-16\) - As an admin I want to be able to add and edit food categories, to continuously improve user experience.
</details>

<details>
<summary>General</summary>

* \(US013\) - As a user I want to recieve clear feedback for my actions on the site, so I know they are complete or if further steps are needed.
</details>
&nbsp;

### **Structure**

<details><summary>Home Page:</summary>

  * _Header/Footer_: For easy navigation across the site and to external resources such as social media pages.
  * _Website Logo_: To easily identify the 'Wanderlust Recipes' site branding.
  * _Recipe Cards_: To easily provide users key information on featured recipes, including visual image, short description, user rating, serving size and prep/cook times.
  * _Search Bar_: Text input bar, allowing users to search recipes by keyword, category, time requirement and minimum rating..
   * _Search Results_: Once user search input, latest recipes replaced by recipe cards matching the search query.
  * _Pagination_: Page is paginated after 10 recipes are displayed, to ensure quick page load and easy user navigation.
  </details>

<details><summary>Recipe Page:</summary>

  * _Recipe Image_: Provides users a visual of the final recipe, to entice users to want to create it themselves.
  * _Recipe Title_: Provides users with the name of the dish, indicating the style and main ingredients of the dish.
  * _Star Rating_: Provides users visual feedback regarding how highly other users have rated the recipe.
  * _Preparation & Cooking Time_: Provides users information on-time requirement to prepare the recipe.
  * _Serving Size_: Provides users information on the serving size the recipe creates, allowing users to adjust ingredient amounts on their own judgement.
  * _Ingredient List_: Provides users with a list of all ingredients and measures needed to complete the recipe.
  * _Method_: Provides users step-by-step method for creating the dish.
  </details>

<details><summary>User Login / Registration Page:</summary>

  * _Username Input_: Text input box, allowing users to enter their username.
  * _Password Input_: Text input box, allowing users to enter their username.
  * _Password Confirmation (Registration)_ : Text input box, must match password input, to ensure user does not incorrectly type password while registering.
  * _Submit / Cancel_: Buttons allowing users to submit entered information, or cancel and restart.
  </details>

<details><summary>User Profile Page:</summary>

  * _Username Banner_: Banner displaying the username of logged in account, allowing users to quickly identify if they are logged into their correct desired account.
  * _Recipes Submitted_: All historical recipes uploaded by the user displayed in list format, allowing users to easily access their owned recipes for review or edit.
  * _Favourite Recipes_: All favourited recipes are displayed in list format, allowing users quick access.
  </details>

<details><summary>New Recipe Page:</summary>

  * _Input areas for below recipe data points_:
    * Recipe Name - Text
    * Recipe Image - File upload and preview
    * Serving Size - Numeric
    * Preparation Time - hh:mm as drop down menu
    * Cooking Time - hh:mm as drop down menu
    * Recipe Category Selection - Drop down menu
    * Recipe Description: Textbox of 25 to 160 characters
    * Ingredients - List text input
    * Recipe Steps - List text input
    </details>
&nbsp;
### **Skeleton**

At this point I began creating wireframes, using the above structure considerations. I used [Balsamiq](https://balsamiq.com/) these below;

* [Home page on desktop and mobile](./)

### **Surface**

This is the sensory design section of a website, or how it looks, feels and sounds.

#### **Colour & Styling**

Upon deciding to brand the website as 'Wanderlust Recipes' I found [this](assets/images/wanderlust-whitebg.png) logo on shutterstock. The logo comprises white and blue colours, which give a light and clean asthetic. With this in mind i consulted [this article](https://elearningindustry.com/the-elearning-color-guide-evoking-the-right-emotion) on how colours evoke emotions, wishing to promote a feelings of calm, optimism, energy, nature and creativity, I chose to use a color pallete consisting of whites, blues and greens.

I used the website [image color picket](https://imagecolorpicker.com/), to determine the blue used in the logo is Gunmetal (#1E2B3A). I then used the website [Coolers](https://coolors.co/) to generate the rest of my colour palette, using Gunmetal (#1E2B3A) as the starting colour and finding additional colours infitting to the style I wished to achieve.. 

The resulting palette is below;

![Wanderlust Color Scheme](assets/images/wanderlust-recipes-color-palette.svg)

<details>
<summary>Color Palette</summary>

* Gunmetal - #1E2B3A
* Indigo Dye - #213F61
* Metallic Seaweed - #077787
* Y in Mn Blue - #38506C 
* Light Sea Green - #2BBBAD
</details>

I also used a selection of off-white and off-black colours to provide additional accenting to generic white/black website elements, such as backgrounds and fonts.

#### **Language/Tone**

I wanted the language to reflect a casual and fun atmosphere, to reflect a backpackers lifestyle, so content was written in line with this. Avoiding technical or formal language where possible.

Similarly, I wanted to use fonts that reinforce the casual identity of the site and also be easy to read. To achieve this I used two [Google Fonts](https://fonts.google.com/);

* [Roboto](https://fonts.google.com/specimen/Roboto) - A font which promotes natural reading rhythm.
* [Open Sans](https://fonts.google.com/specimen/Open+Sans) - A humanist sans serif, designed for excellent legibility with a neutral, yet friendly in appearance.
* Sans-serif - Web safe font, used if primary two fonts fail to load.

#### **Styling Considerations**

Before beginning development, I listed some styling ideas that I felt benefit the website. The majority of these can be seen in the wireframes.

* Favicon: Desktop and Mobile.
* Navigation
  * Sticky top
  * Mobile: 'Burger' menu icon, expanding on click.
  * Logo: Navigates to the home page on click.
* Recipe Cards:
  * Visual Image showing final recipe dish, to entice users to select.
* Recipe Pages:
  * Icons: Icons used to highlight key recipe info, serving size, preparation time, rating.
  * Ingredients & Method - Displayed in tabular format, which user can dynamically choose between via click or swipe.

## 2. **Features**
The site allows users to upload new recipes and edit existing ones. Users can search for recipes based on name, description, recipe type, number of servings and minimum rating. Users can favourite recipes, which are displayed on their profile page. Users can also rate others users submitted recipes and comment their feedback.

### **Existing Features**
<details>
<summary>The Header:</summary>

* **Website Logo**: Builds brand awareness amongst users.
* **Navigation Bar**: Allows users to navigate the site easily and intuitively, as well as login/register their account.
</details>

<details>
<summary>The Footer:</summary>

* **Website Developer**: Copyright information for website developer brand awareness.
* **Developer Social Links**: Links to GitHub and LinkedIn of website developer for brand awareness.
* **Business Social Links**: Links to company social media sites, to raise brand awareness.

Both the Header and Footer are present and consistent on all website pages.
</details>

<details>
<summary>Home page:</summary>

* **Image Banner**: Visually pleasing design, allowing users to immediately identify the site brand.
* **Latest Recipes**: List of latest recipes submitted to the site, showing key information; recipe image, type, rating, preparation time and serving size.
* **Search Bar**: Allows user to enter keywords to search recipe database
* **Advanced Search**: Allows user to enter additional search criteria; recipe type, minimum rating, serving size.
* **Search Results**: Replace latest recipes when search is submitted. Recipe cards displayed as search return results.
</details>

<details>
<summary>Login / Registration page:</summary>

* **Image Banner**: Visually pleasing design, allowing users to immediately identify the site brand.
* **Username Input**: Input area for users to enter their profile username.
* **Password**: Input area for users to enter their profile password.
* **Confirm Password** (Registration page): Input area for users to confirm password, must match password input for successful registration.
* **Cancel**: Cancellation button, clearing input text allowing users to refill entries.
* **Login/Registration Button**: Button allowing users to login to their account or register for a new account.
</details>

<details>
<summary>User Profile page:</summary>

* **Image Banner**: Visually pleasing design, allowing users to immediately identify the site brand.
* **Username sub-banner**: Text banner showing username of logged in account, allowing users to quickly identify if they are using their correct desired account.
* **Favourite Recipes**: Recipes favourited by the user are displayed in list order, allowing quick and easy access.
* **Submitted Recipes**: Recipes previously submitted by the user are displayed in list order, allowing users quick and easy access for review or edit.
</details>

<details>
<summary>New Recipe page:</summary>
* **Image Banner**: Visually pleasing design, allowing users to immediately identify the site brand.
* **Input areas for below recipe data points**:
    * _Recipe Name_ - Text
    * _Recipe Image_ - File upload and preview
    * _Serving Size_ - Numeric
    * _Preparation Time_ - hh:mm as drop down menus
    * _Cooking Time_ - hh:mm as drop down menus
    * _Recipe Category Selection_ - drop down menu
    * _Recipe Description_: Textbox of 25 to 160 characters
    * _Ingredients_ - List text input
    * _Recipe Steps_ - List text input
</details>
&nbsp;

### **Features to consider implementing in future**
As this is a community focused platform, there are a number of future features which would be worth considering implementation:
* **Social Media Sharing** - Allow users to share recipes directly to their personal social media accounts.
* **Nutritional Information API Integration** - Integrate the platform to a third party API which automatically calculates the nutritional information of recipes based on their ingredients and serving size. This would be highly beneficial to health concious users.
* **Vegetarian/Vegan Alternative Recipes** - Allow users to enter Vegetarian or Vegan alternative ingredient lists and methods for existing recipes. Update recipe pages to allow users to choose an alternative option of the recipe and dynamically update the page contents in line with choice.
* **User Comment Section** - Allow users to comment on each others recipes, allowing constructive feedback and additional context to reviews.

&nbsp;
## 3. **Technologies Used**

### Languages
<ul>
<li><a href="https://en.wikipedia.org/wiki/HTML">HTML</a> - Programming language providing content and structure of the website.</li>
<li><a href="https://en.wikipedia.org/wiki/CSS">CSS</a> - Programming language providing styling of the website.</li>
<li><a href="https://en.wikipedia.org/wiki/JavaScript">JavaScript</a> - Programming language used various interactive elements of the website, including game logic, audio options etc.</li>
<li><a href="https://en.wikipedia.org/wiki/Python_(programming_language">Python</a> - Programming language used to drive core site functionality including user login and push/retrieving database information.</li>
<li><a href="https://en.wikipedia.org/wiki/Jinja_(template_engine)">Jinja</a> - Used to generalt HTML from site templates</li>
</ul>

### Librararies
<ul>
<li><a href="https://materializecss.com/">Materialize CSS Framework</a> - Library of pre-built HTML and CSS components, used for various aspects of the site, such as navigation bar.</li>
<li><a href="https://fontawesome.com/">Font Awesome</a> - Library used for icons, such as social links and other images.</li>
<li><a href="https://fonts.google.com/">Google Fonts</a> - Font style library.</li>
<li><a href="https://jqueryui.com/">jQuery</a> - JavaScript library used for simplification of JS scripts and DOM manipulation.</li>
<li><a href="https://flask.palletsprojects.com/en/1.1.x/">Flask</a> - Micro-framework to simplify Python scripting and web server tasks.</li>
<li><a href="https://werkzeug.palletsprojects.com/en/1.0.x/">Werkzeug</a> - Python library to manage user management integrity.</li>
</ul>

### Editors
<ul>
<li><a href="https://github.com/">GitHub</a> - Remote code repository.</li>
<li><a href="https://gitpod.io/">GitPod</a> - IDE (Integrated Development Environment), for writing, editing and saving code.</li>
<li>dbDiagram</li>
<li><a href="https://balsamiq.com/">Balsamiq</a> - Wireframes for visual design testing.</li>
</ul>

### Tools
<ul>
<li><a href="https://pythonhosted.org/Flask-paginate/">Flask-Paginate</a> - Flask plugin, allowing easy pagination of recipe content page</li>
<li><a href="https://tinypng.com/">TinyPNG</a> & <a href="https://tinyjpg.com/">TinyJPG</a> -  Minimise image file sizes and maximise page load speed.</li>
<li><a href="https://www.remove.bg/">remove.bg</a> - Remove backgrounds from png images.</li>
<li><a href="https://coolors.co/">Coolers</a> - Color Palette Generation</li>
<li><a href="https://imagecolorpicker.com/">Image Color Picker</a> - Determine Hex code color in exisiting graphics</li>
<li><a href="https://realfavicongenerator.net/">Real Favicon Generator</a> - Generate favicons and icons for desktop and mobile usage.</li>
<li><a href="https://autoprefixer.github.io/">Autoprefixer</a> - Vendor prefixes to CSS rules.</li>
<li><a href="http://ami.responsivedesign.is/">Am I Responsive?</a> - Responsive design demo in ReadMe summary.</li>
<li><a href="https://www.responsivedesignchecker.com/">Responsive Design Checker</a> - Check website response across device types.</li>
<li><a href="https://www.lambdatest.com/">Lambdatest</a> - Check website response across device types.</li>
</ul>

### Database Management
<ul>
<li><a href="https://www.mongodb.com/">MongoDB</a> - Cloud based database management system, used for storying user profile and recipe information.</li>
</ul>

### Deployment Platform
<ul>
<li><a href="https://www.heroku.com/">Heroku</a> - Remote hosting platform, for hosting of python driven websites and applications.</li>
</ul>

## 4. **Testing**

The testing process can be seen in the [TESTING.md](https://github.com/RussOakham/wanderlust-recipes/tree/20dd255966ec540dc5cf918a15783c3440fe2b9a/TESTING.md) document.

## 5. **Deployment**

### Database Deployement

### Application Hosting
### **Heroku**

The site is hosted using Heroku, deployed directly from the master branch of GitHub. The deployed site will update automatically as new commits are pushed to the master branch.

#### Creating a Heroku app

#### Setting Environmental Variables

#### Deployment

#### Automatic Deployment

### GitHub and GitPod repository management

### **Hot to clone 'Wanderlust Recipes' in GitHub and GitPod.**

To run a version of the site locally, you can clone this repository using the following steps;

In a code editor of your choice;

1. Go to [GitHub.com](https://github.com/)
2. Click on 'Responsitories'
3. Click on 'Avengers Snap'
4. Click on the 'Code' button.
5. Under 'HTTPS' click the clipboard icon to the right of the URL.
6. In your IDE of choice, open a repository or create a new repository.
7. Open Terminal \('Terminal' then 'New Terminal' from the top ribbon menu in GitPod.\)
8. Type 'git clone', paste URL link and press enter.

Additional information around these cloning steps can be found on [GitHub Pages Help Page](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

## 6. **Credits**

### **Design and research**

The following are websites and articles that I used for reference and inspiration:

### **Technical**

* [Real Favicon Generator](https://realfavicongenerator.net/): For the generation of Favicon icons and code.
* [Bootstrap Docs](https://getbootstrap.com/docs/5.0/getting-started/introduction/): For guidance on Bootstrap use and adaptations.
* [CSS-Tricks](https://css-tricks.com/): For implementing CSS effects such as box-shadow.
* [w3Schools](https://www.w3schools.com/): For checking proper syntax of HTML and CSS elements. 
* [Autoprefixer](https://autoprefixer.github.io/) - For generating CSS browser prefixes.
* [Stackoverflow](https://stackoverflow.com/) - For researching and troubleshooting JavaScript and Python code issues.

### **Content**

All text content on the site was written originally by myself, with the below notes;

### **Media**

The colour palette for the site was inspired and adapted from;

The photos and images used for this site were obtained from;

* [**Shutterstock**](https://www.shutterstock.com/): From the following contributors;

### **Acknowledgements**

* Thanks to my mentor, [Precious Ijege](https://github.com/precious-ijege) for his suggestions, time and support.
* Thanks to those on Slack for reviewing my project and making suggestions.
* Thanks to my housemates, friends and family for reviewing the project and offering constructive feedback.

