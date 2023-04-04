
#What does this server

This is a local server for the proyect named Agro-Commodities-Investment. This server is used to provide different information to the different views and pages.
It has the following paths:
  http://localhost:3000/blogNews: This path is for the blog and we can see the news there.
  http://localhost:3000/blogNoticias: This path is the same as the previous one but in Spanish.
  http://localhost:3000/Preguntanos : This path contains FAQ for our users, you can see it in the "Customize" page of our proyect.
  http://localhost:3000/askQuestion : This are the FAQ in Spanish.
  http://localhost:3000/reviews     : In this path we have a few reviews that our users have written. We use this in the Home of our website.
  http://localhost:3000/opiniones   : This path has the reviews in Spanish.

(open terminal)

npx json-server --watch db.json
