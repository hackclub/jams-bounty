# Build a link-sharing app with Firebase

### Details:
_Outcome:_ Create your own website that allows users to log in and share links with descriptions

_Requirements:_ Replit Access, Firebase access, Basic experience in HTML and JS.

_Language used:_ HTML, JS, Firebase Web SDK

_Customization opportunity:_ You can customize the website to a specific niche you are interested in (e.g. Clash of Clans base sharing, Discord bot link sharing, Valorant clips). You can also add more fields to each post, generate usernames, develop a user dashboard, and add a comments system.

_Platform Limitations:_ Browser-based Replit Development, Firebase Database

_Time estimation:_ 1 Hour

### Breakdown
- Set up: Fork the HTML, CSS, and JS replit starter, create an account for Firebase
- Part 1: Create login.html, set up front-end with email, password, and submit inputs and a link to signup.html
- Part 2: Write JavaScript to execute Firebase Auth Login function on button click
- Part 3: Duplicate login.html and change the Firebase function to the Firebase Auth Sign Up function
- Part 4: Create createPost.html and add title, description, and link input fields
- Part 5: Write JavaScript to validate if the link is actually a link and update Firebase Firestore with field values if the user is authenticated
- Part 6: Go to index.html and fetch Firebase Firestore data and generate HTML Elements for each post. 
- Success!!! Now you have a working link-sharing website.

**Make sure your proposal (similar to the one above) answer these questions about your Jam idea:**
- How will you ensure that every outcome of the workshop varies (i.e. how will you give jammers a sense of ownership over their project)?
  - The workshop itself only provides the minimum viable product, so jammers would have full creative freedom on the purpose of the website and how it would be used. Additionally, the CSS styling would be entirely up to the creator. Some potential implementations of this project would be a school club directory, gaming link database, e-sports clips, and personal website sharing; these implementations would stem from the jammer's interests outside of coding.  
- Why should Hack Clubbers care about this project?
  - This project introduces the basics of user authentication and databases which are important tools in web development. User authentication and databases are the foundation of a lot of the apps we use on a daily basis, such as Instagram, YouTube, Reddit, and other social media platforms. Particularly, links are very versatile as they are the way we move across the internet, so this app would act like a hub. Ideally, this jam would be a good transition from the static personal website jam to more dynamic websites and could potentially show new jammers how to use their skills to create interactive apps. 
- General outline of a club meet doing the Jam
  - 10 min: set-up Replit & Firebase
  - 20 min: Parts 1-3
  - 30 min: Parts 4-6
  - 10 min: Free time to experiment and personalize the app
  - After the club meet: jammers could work on styling and fleshing out their ideas
- What Club Members will walk away with (both in terms of knowledge and in terms of product)
  - Club members will walk away with a working website that features a login/signup system and a post management system. Ideally, there would be enough time for club members to add fields specific to their idea. In terms of knowledge, club members would walk away with a basic understanding of user authentication and a document-based database.
- What makes this workshop fun or interesting for Club Members?
  - This jam would teach club members how to use their HTML and JS skills to create interactive apps. Club members might have completed other workshops like an intro to HTML, CSS, and JS workshop and want an opportunity to claim these skills as their own.
  - Club members can show off their new creations to friends and have their friends engage with the app.
  - The start of the engineer to tech start-up pipeline
  - Club members can learn a bit about how many popular apps work inside 
- What platforms will be supported (i.e. MacOS, Windows, Chromebook, Mobile, Browser, etc)?
  - Browser
- How will you allow Club Leaders to add their own project to the Jam presentation (giving them a sense of ownership over the meeting)?
  - Club leaders can create their own projects, such as a school club directory (they can put their club on it first), alongside club members
  - They can use the project to teach CSS down the line
  - They can connect with club members about their project ideas (many project ideas are based in CRUD)
Any feedback is appreciated!
