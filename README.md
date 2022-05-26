<h1 align="center">Movie Recommendation Engine 
  <!--<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Microsoft_logo.svg/480px-Microsoft_logo.svg.png" alt="Logo" width="25" height="25">-->
</h1>

<p align="center">
 <a target="_blank" href="https://share.streamlit.io/yuktika089/practise2/main/movierec_app.py">Link to the App</a>
    ·
 <a target="_blank" href="to edit">Video Demo</a>
</p>
    
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#salient-features">Salient Features</a></li>
        <li><a href="#compatible-platforms">Compatible Platforms</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#agile-methodology">Agile Methodology</a>
      <ul>
        <li><a href="#what-is-agile">What is Agile</a></li>
        <li><a href="#how-i-incorporated-agile-methodology-during-the-development-cycle">How I Incorporated Agile Methodology During The Development Cycle</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#navigating-through-the-app">Navigating through the App</a></li><ul>
        <li><a href="#login">Login</a></li>
        <li><a href="#chat-window">Chat Window</a></li>
        <li><a href="#video-call">Video Call</a></li>
      </ul>
    <li><a href="#resources-used">Resources Used</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project
* Movie Recommendation Engine project built during Microsoft Engage 2022 program. 
* It is a movie recommending application through which we can get recommendation on the basis of our favourite genres or our favourite movie. 
* The App is called "Recliner Lounge", as it gives the best recommendation for any occastion to watch a movie at our favoured comfort.

### Salient Features
* User registers through entering name.
* User can make choice of which type of recommendation they want - Movie based or Genres based.
* Recommendations are redirecting the user to its IMDB page, in order to give better user experience.
* The user can adjust the number of recommendations and the IMDB scores, to get optimum suggestions.

### Compatible Platforms
Laptops, Desktops, Tablet, PCs and Phones (Android and IOS).

### Built With

### Machine Learning in Python: 
* Libraries used - NumPy, Scikit-Learn, Matplotlib, Pandas
* Code built using - Jupytor, Google colab, Visual Studios

### App and Deployment: 
* App building - Streamlit
* Deployment - Streamlit

<!-- AGILE METHODOLOGY -->
## Agile Methodology

### Agile

Agile refers to a group of software development methodologies based on iterative development and is frequently being adopted in the software industry. Agile promotes teamwork, flexible procedures, and results in delivery of high quality software.

### How I Incorporated Agile Methodology During The Development Cycle

Scrum and kanban are the primary agile processes. SCRUM is a subset of Agile, a framework for developing software. SCRUM takes advantage of different techniques to achieve goals in Agile. I implemented scrum, which organizes the work in cadences called sprints, usually is performed on a very short time period. 

* Sprint 1 (May 4 - May 10): Exploring and understanding the different approaches 
    - Researched about different algorithms used in recommendation systems - Content-based filtering, Collaborative-based filtering and Hybrid Reccomendation approach.     - Understood the requirements for each algorithms and traversed through many datasets for the application.

* Sprint 2 (May 11 -May 17): Planning the Engine-making process and Determining the languages and softwares to utilise 
    - Researching about various Machine Learning libraries and platforms that can be used to make a recommendation system app with a minimum functionality to have content and collaborative filtering. 
    - Finalised to use Machine Learning in Python Language using Google Colab and Visual Studios.
    - Eventually utilised the movies_metadata dataset which consists of more than 5000 movies and their information.

* Sprint 3 (May 18 - May 24): Implementation of the Algorithm and Execution of the System built
    - Started the development process by taking help from YouTube tutorials. 
    - Built an application using Streamlit for the very first time. 

* Sprint 4 (May 25 - May 29): Debugging, Deployment and Final Submission
    - Encountered occasional bugs which I debugged timely. Made required changes in the UI, added images and mode to make it user friendly. 
    - Deployemnt was a challenge as it took several debuggings to make the app available on different platforms.

<!-- INSTALLATIONS -->

## Getting Started
To run this project on your local systems, following are the requirements:
### Prerequisites and Accessing the Application
- There are no prerequisites to run the "Recliner Lounge" - Movie Recommendation Engine on your systems.
- Just simply click on the link and the engine can be used to your satisfiability. 

<!-- APP TUTORIAL-->
## Navigating Through The Application

### How the Web App works ?

- After the link is accesssed and the web app opens you can see the very first step is to enter your name in the given space.

<img src="Images/Blank-Chat-Window.png" alt="blank chat window" width="700"/>

All the users registered with the app can be added to your chat. Photo sharing, read receipts, formatting the text, and many other things are possible in the chat. The shared photos can be viewed in the right pane. The chat can be deleted by expanding the 'Options' menu in the right pane and clicking the 'Delete' option.

<img src="Images/New-Chat.png" alt="new chat" width="700"/>

### Video Call

The video call welcome screen shows your video and has a form to enter your name. To place a call, click on 'Copy your ID' and send the random generated unique ID to the person you want to call. 

<img src="Images/Video-Call-Welcome-Screen.png" alt="video call welcome screen" width="700"/>

The person who received the ID needs to copy that in the 'ID to call' input field and click on 'Call' button. You can accept the person's incoming call by clicking on 'Answer' button.

<img src="Images/Placing-Call.png" alt="placing call" width="700"/>

Once the call is accepted, the users are connected and can video call seamlessly with the option to mute audio and video when required. The call can be stopped by clicking on 'Hang Up' button. The video call screen closes and we are navigated back to the chat window.

<img src="Images/Video-Call-2-people.png" alt="video call between 2 people" width="700"/>

<!-- ACKNOWLEDGEMENTS -->

## Resources Used

* [React video call app tutorial](https://youtu.be/oxFr7we3LC8)
* [How does webRTC work? Make a video call app using webRTC](https://youtu.be/rr_Zd16dql0)
* [Firebase chat app - React JS, Firebase, Chat Engine](https://youtu.be/Bv9Js3QLOLY)

<!--MARKDOWN LINKS-->
[front-end-shield]: https://img.shields.io/badge/Front--end-React%20JS%2C%20Material--UI-blueviolet
[back-end-shield]: https://img.shields.io/badge/Back--end-Node%20JS%2C%20Express%2C%20socket.io-blueviolet
[tools-shield]: https://img.shields.io/badge/Tools-Peer%20JS%2C%20webRTC-blueviolet
[front-end-shield-1]: https://img.shields.io/badge/Front--end-React%20JS%2C%20Ant--Design-blueviolet
[back-end-shield-1]: https://img.shields.io/badge/Back--end-Chat%20Engine-blueviolet
[tools-shield-1]: https://img.shields.io/badge/Tools-Firebase%2C%20Axios-blueviolet
