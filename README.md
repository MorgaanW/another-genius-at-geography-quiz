## Genius At Geography Quiz!

![image (2)](https://github.com/MorgaanW/another-genius-at-geography-quiz/assets/153202221/0beaace5-a2ec-4588-abe8-cf1f06eb949a)


## User Stories
* As a Site owner!

  * As a site owner, I want to implement responsive design principles to ensure that the quiz game is accessible and functional across a variety of devices and screen sizes, to maximize reach and engagement.
  * As a site owner, I want to integrate an API for generating quiz questions seamlessly , ensuring that it fetches a diverse range of geography-related questions reliably and  efficiently.
  * As a site owner, I want to incorporate gamification elements, such as  leaderboards, and Higscores
  * As a site owner, I want to optimize the quiz game for search engines (SEO) by incorporating relevant keywords and meta tags to attract  traffic and improve visibility in search results.
  * As a site owner, I want to configure the API request parameters to  1.Number of questions to return; 2. category of questions ex: geography, animals,etc and 3. multiple choice questions
* As a Player
  * As a player, I want to track my progress during the quiz, including the number of questions answered correctly and questions answered incorrecty
  * As a player, I want the quiz to be visually appealing and user-friendly, with clear instructions and intuitive navigation, to enhance my overall experience.
  * As a player, I want the quiz to be accessible on multiple devices, including desktop computers, laptops, tablets, and smartphones, so that I can play anytime, anywhere.
  * As a player, I want to access a clear and concise rules section within the quiz interface so that I can understand the game mechanics and expectations before starting.
  * As a player, I want the questions and answers to load quickly and without delay so that I can smoothly progress through the quiz and focus on answering the questions accurately.

## Features
* Home page - The home page includes a visually appealing background image with two buttons. The first button displays the simple "How to play" instructions for the game. The "Start" button begins the quiz for the user. 

* Game page - The game page has the following features:

    * A question counter, so the user is aware of what number question they are on and how many questions remain.

    * Multiple choice answer buttons that immediately log the gamers' answer and automatically displays the next question. 

    * A feedback point score that updates as the user moves through the questions on the quiz.

* End page - The end page lets the user know their final score at the end of the quiz, with an added option to save their username and score to the leaderboard, if they would like. If so, the user is then taken to the leaderboard page to see the top scores!
    * The end page also includes a button that takes the user back to the home page without saving their result and the option to take the quiz again from the home page.

* Leaderboard page - This page consists of a table showing the top scores from saved quiz takers and also a button to return the user back to the home page.

## Future features

* An event listener that plays an audio sound depending on the users' correct/incorrect answers.
* Players to be able to choose difficulty level & category.
* Increased number of questions in a game session to up the challenge.
  

## Design

## Wireframes

![Wireframe H2 first page](https://github.com/MorgaanW/another-genius-at-geography-quiz/assets/153202221/8b610b2d-2ea7-4761-82bf-b3092aad2660)
![question page H2 low](https://github.com/MorgaanW/another-genius-at-geography-quiz/assets/153202221/c286c43e-c81d-413a-b703-75ba723d1809)
![Wireframe H2 end page](https://github.com/MorgaanW/another-genius-at-geography-quiz/assets/153202221/0f09139b-e0bb-41b7-935c-821c5732d516)
![top score page wireframe H2 ](https://github.com/jenaleigh01/genius-at-geography-quiz/assets/153202221/43421560-354c-4978-822c-7fbd3d4e2d9c)

## Font

* Quicksand, sans-serif - main font.
* Arial, helvetica, sans-serif - used for font inside answer boxes.

## Media

* Background image - A visual appealing image is used to cover the background of each page on the quiz. The image is a map of the world, which may help the users' when answering questions! 

## Colors

* #ffffff
* #000000
* #713535

The above colors are used for font color, link and answer buttons.


## Technologies used

## Languages
* HTML 

* CSS 

* JavaScript

 ## Frameworks, Libraries & Programmes Used

* Google Fonts as font resource

* GitHub as software hosting platform to keep project in a remote location

* Git as version-control system tracking

* GitPod as developer hosting platform

* Balsamiq as wireframing tool application

* Pixabay for background image resource

* Am I Responsive to ensure the site is responsive across different devices

* W3C Markup Validator to validate HTML

* W3C CSS Validator to validate CSS

* JShint for JavaScript code Validator

* [API - Open Trivia geography quiz ](https://opentdb.com/api_config.php).  

## Testing and Validation
## HTML

![image (3)](https://github.com/MorgaanW/another-genius-at-geography-quiz/assets/153202221/5e8bb266-29ba-4a07-97aa-1752befaad00)




![image (4)](https://github.com/MorgaanW/another-genius-at-geography-quiz/assets/153202221/ffcc5be2-3fed-49ea-a81b-203d25768d00)

## CSS

![image (6)](https://github.com/MorgaanW/another-genius-at-geography-quiz/assets/153202221/49184b6c-d33e-4e2f-ba8a-12e31235e4cf)




![image (5)](https://github.com/MorgaanW/another-genius-at-geography-quiz/assets/153202221/6149bccc-8f4d-4792-8fe6-42d20dce84e7)


## JS Testing 

A total of 40 warnings were flagged by the JSHint Validator on the JavaScript. All of these flags are to do with variable names (let and const) and their availability on different browsers and some missing semicolons.


![image (8)](https://github.com/MorgaanW/another-genius-at-geography-quiz/assets/153202221/77130a5e-d575-41e0-ac21-0eef90f29d36)




## Lighthouse tools was used to test the website

 ![image (7)](https://github.com/MorgaanW/another-genius-at-geography-quiz/assets/153202221/958f099a-89d9-4e81-8aa4-355c8aa398e3)

     
* New visitor
  
New visitors to the website can easily navigate to the how to play section. With a minamilist design making it easy for the new visitor to jump straight into the quiz, across different devices to suit their needs. 
 
* Returning visitor
 
Returning visitors have the chance to beat their old score when they play the game again. Whilst improving their knowledge about geography, enjoying a different set of questions selected from the Open Trivia API.


## Deployment

  GitHub Pages

**This site was deployed to GitHub pages as follows.**
 * Go to the Settings tab of GitHub repo.
 * On the left-hand sidebar, in the Code and automation section, select Pages.
 * Make sure: Source is set to 'Deploy from Branch'.
 * Main branch is selected.
 * Folder is set to / (root).
 * Under Branch, click Save.
 * Go back to the Code tab. Wait a few minutes for the build to finish and refresh your repo.
 * On the right-hand side, in the Environments section, click on 'github-pages'.
 * Click View deployment to see the live site.

**The URL link is available here**

* GitHub Clone
   1. 	Install GitPod browser if you don’t already have it.
   2. 	Log into GitHub and locate the repository.
   3. 	Just below settings click the Gitpod button
      
## Credits

* Arrow functions-[YouTube] [https://www.youtube.com/watch?v=ajTvmGxWQF8&ab_channel=ColorCode]
  
*Spread operator-[YouTube] https://www.youtube.com/watch?v=1INe_jCWq1Q&ab_channel=NetNinja]

* Traversing the DOM-[YouTube] [https://www.youtube.com/watch?v=VMRo6Uv856E&ab_channel=NetNinja]
  
* Build a loader W3 Schools-[Link] [https://www.w3schools.com/howto/howto_css_loader.asp]

* Array.from function-[YouTube][https://www.youtube.com/watch?v=NPbDqbwtr-4&ab_channel=dcode]
    
* Build a quiz app with JavaScript tutorial-[YouTube] [https://www.youtube.com/playlist?list=PLDlWc9AfQBfZIkdVaOQXi1tizJeNJipEx]
  
* Promises-[YouTube] [https://www.youtube.com/watch?v=TnhCX0KkPqs&ab_channel=ColorCode]
  
* CSS Transform properties-[YouTube] [https://www.youtube.com/watch?v=rzD-cPhq02E&ab_channel=WebDevSimplified]
  
* Fetch API-[YouTube] [https://www.youtube.com/watch?v=37vxWr0WgQk&ab_channel=BroCode]

* Callback Functions- [YouTube] [https://www.youtube.com/watch?v=cNjIUSDnb9k&ab_channel=CodewithAniaKub%C3%B3w]



* Arrow functions-[YouTube] [https://www.youtube.com/watch?v=ajTvmGxWQF8&ab_channel=ColorCode]
  
* Spread operator-[YouTube] https://www.youtube.com/watch?v=1INe_jCWq1Q&ab_channel=NetNinja]

* Traversing the DOM-[YouTube] [https://www.youtube.com/watch?v=VMRo6Uv856E&ab_channel=NetNinja]
  
* Build a loader W3 Schools-[Link] [https://www.w3schools.com/howto/howto_css_loader.asp]

* Array.from function-[YouTube][https://www.youtube.com/watch?v=NPbDqbwtr-4&ab_channel=dcode]
    
* Build a quiz app with JavaScript tutorial-[YouTube] [https://www.youtube.com/playlist?list=PLDlWc9AfQBfZIkdVaOQXi1tizJeNJipEx]
  
* Promises-[YouTube] [https://www.youtube.com/watch?v=TnhCX0KkPqs&ab_channel=ColorCode]
  
* CSS Transform properties-[YouTube] [https://www.youtube.com/watch?v=rzD-cPhq02E&ab_channel=WebDevSimplified]
  
* Fetch API-[YouTube] [https://www.youtube.com/watch?v=37vxWr0WgQk&ab_channel=BroCode]

* Callback Functions- [YouTube] [https://www.youtube.com/watch?v=cNjIUSDnb9k&ab_channel=CodewithAniaKub%C3%B3w]

* Alessandra Costa - Alex Pub Quiz- [link] [[https://github.com/alessandracosta8/alex-pub-quiz-pp2/tree/main)]
* Iris Smok - Kids Memory Game
* Youtube = https://www.youtube.com/watch?v=3aKOQn2NPFs - API Intergration
* https://www.w3schools.com/css/css3_buttons.asp - Button Functionality

## Acknowledgements

* A big thank you to team Script Squad for their hard work!
* Coding coaches at Code Institute for all help when needed.


