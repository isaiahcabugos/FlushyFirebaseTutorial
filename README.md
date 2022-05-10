# FlushyFirebaseTutorial

# Basics
Our Firestore database' main use is to store reviews for bathrooms. Within each review is 7 fields, listed below.
<ul>
  <li> ID: an alphanumeric identifier automatically stored with each review </li>
  <li> comment: the text for the full review </li>
  <li> name: the title of the review </li>
  <li> rate: a number ranging from 1-5 reflecting the rating of the bathroom (1 is the worst, 5 is the best) </li>
  <li> street: the street address associated with the review </li>
  <li> state: the state associated with the review </li>
  <li> postal: the postal code of the address associated with the review </li>
</ul>

Depending on the language you are using for your project, the way you need to implement this feature changes. Google supports 16 different processes to implement firebase. This repository has 3 example "project" files which showcase how to read from the database in each language. The first of which is taken directly from our project with minor changes to improve documentation. The remaining project is basic code are taken from the google firestore tutorial showcasing how to implement in unity (link to official tutorial at bottom). 

Aside from these three project files, the proper firebase authentification configuration for web development will be sent in the discord in the "FirestoreAPI" channel.

# General Idea
<ol>
  <li> Initialize the API key </li>
  <li> Read from database using API key  </li>
  <li> Use the data somewhere </li>
</ol>

<h1> Important Notes </h1>
Please be aware we have only implemented Firebase in web form, meaning we may not have all the answers if questions arise for your specific project's language. Furthermore, we only have a limited amount of bandwidth available each day. Thus far, our group by itself has yet to reach anywhere near that limit. However, with 7 groups that may easily change. Specifically, Google allows 50K reads per day. With this in mind, it would be most beneficial for everyone if groups kept great care in where and how they implement interactions with the database. In other words, be wary when calling the database in loops or otherwise cyclical/indirect fashion. A simple bug may overload the bandwidth for that day. 

Also be aware that if you want to add Firebase integration to your project and you are not developing some sort of website, you will likely need to contact us so we can add extra settings to our firebase console to make your project usable with google firebase.

# Official Google Tutorial
Link: https://firebase.google.com/docs/firestore/quickstart#web-version-9
