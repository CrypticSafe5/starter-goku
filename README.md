# Start Goku Project
There's two parts to this project. There's the first step which will entail building the client, and the second building a backend for it.

The purpose of this project is simple. Be able to apply the basic understanding of the client side of an HTML page, and the second to gain exposure to server side code.

## Part 1
Build out an HTML page that has the following components:
- An image of Goku
- Two buttons denoting to "power up" and "power down" below the picture, centered
- A text between the two button denoting the power level
- Upon reaching different levels(going up or down), Goku's form should change according to his level

## Part 2
Build a Nodejs application that serves the client HTML upon request.
- Use npm to install "express"
- Setup a basic server to give the HTML client to the user upon request

## Part 3
This is going to be a more in-depth endeavor. You will be creating a service on the server that does the following:
- Setup a sql-lite database with [this node module][0]
- Create a startup script that is able to request the [csv file][1] from https://gist.github.com/lokesh234/a2ce22ac39f7e36df4305ac07967342d
- Parse the contents of the file downloaded into something more manageable
- Load the parsed data into the sql-lite database
- Create an api that is able to return a list of characters based on "Saga_or_Movie"(this name is able to be changed to something more consumable)
- Create an api that returns a single character and it's power level per "Saga_or_Movie" unless this is also specified in the request
- Create an api that will return the outcome of a fight between the characters based on their "Power_Level" in a specified "Saga_or_Movie"

[0]: https://www.npmjs.com/package/sqlite3
[1]: https://en.wikipedia.org/wiki/Comma-separated_values
