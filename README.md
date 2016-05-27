## Applicant Test

This test is intended to go over a broad array of topics ­ without paying too much attention to each detail. It should also demonstrate learning new things quickly.

### Front End
Your client is a huge Chuck Norris Fan and thinks that having Chuck Norris Jokes all over its website will really make it snap!

You’ve been asked to build a simple site, and handed a wireframe:

![Wireframe](/images/wireframe.png/)

Your client’s 14-year-old child said that React is the best framework; therefore, you must use React for this single page application. 

#### API Interaction
Make use of http://www.icndb.com/api/ to dynamically get a different joke each time the user clicks a button.

Because a 14-year-old is in the mix, you should have a filter for explicit content.

### Devops!
Your team uses different operating systems and you need to share the project with them easily.
Use [docker](https://docs.docker.com/) and [docker-compose](https://docs.docker.com/compose/) to run the application. The web server, database, and anything else needed is up to you. The goal is that when someone receives the program they can run it easily without having to set up anything besides docker/compose. Check out the [django example](https://docs.docker.com/compose/django/) and notice how once compose is installed I can just type `docker-compose up` and it works.

After doing this briefly explain what you like and/or dislike about using Docker.

### The Deliverable
Push your work up to a private gitlab repo. We should be able to run `docker-compose up`, maybe run any extra commands you give us, then go to a web browser and see the finished site. Include a `notes.md` file with your answers/notes for the above questions.
