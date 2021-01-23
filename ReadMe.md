# Lesson 1 Practice Hands-On

# Directions

For your Lesson 1 Practice Hands-On, you will be rendering the below information by using Handlebars and the res.render() method. This Hands-On will not be graded, but we encourage you to complete it. The best way to become a great programmer is to practice! Once you have submitted your project, you will be able to access the solution on the next page.

Setup
Open up your terminal/command prompt.

Navigate to your desktop in your terminal:

cd Desktop
Then, navigate to the Express-Course directory in your terminal:

cd Express-Course
Requirements
Step 1
To begin, generate a new project (within the Express-Course directory) using the Express/Handlebar generator.

Call this app L01HandsOn
Don't forget to run npm install
Install and run Nodemon
Step 2
Within your res.render() method's object, you should have two fields: title and cities. The field title should have the value of "Amazing US Cities". The field cities will be an array of objects, as shown below. Be sure to add the below array into the res.render() method:

[
      {
        name: 'San Francisco',
        state: 'CA',
        population: 864816
      },
      {
        name: 'Denver',
        state: 'CO',
        population: 682545
      },
      {
        name: 'Seattle',
        state: 'WA',
        population: 704352
      },
      {
        name: 'Portland',
        state: 'OR',
        population: 639863
      },
      {
        name: 'New York City',
        state: 'NY',
        population: 8.538
      },
      {
        name: 'Charlotte',
        state: 'NC',
        population: 842051
      },
      {
        name: 'Pittsburgh',
        state: 'PA',
        population: 303625
      }
]
Step 3
Given the above array of objects, write the needed code within the index.hbs file to create a table that lists out each of these objects and their key/value pairs. Also be sure to use the title key/value pair within your index.hbs to title your page. Use a Handlebar each loop.


