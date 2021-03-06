# ![real logo](https://github.com/maisha242/food-vibes/blob/main/misc/logo.png) food-vibes-plus
Have you ever been hungry but you don't know what to eat? 
Let us pick for you! 
Let us listen to what you’re listening to and we'll make suggestions based on your 'vibes'

## Inspiration
Because of COVID-19, hanging out with friends becomes increasingly difficult especially when internet fatigue kicks in. Sometimes we end up hanging out (socially distanced) by doing homework and listening to music together. After a long day of working on our very cool homework, we get hungry but we find it difficult to choose what to eat. That's when realized that sometimes our 'vibes'/moods change based on the music we are listening to. Therefore, we decided why not try making something that would give us food recommendations that would fit the 'vibes' of our hangouts.

## What it does
> *food vibes* takes an audio file and gives you food recommendations based on your 'vibes'/song.

More descriptive:
> *food vibes* takes an audio file and enhances it using the Media Processing API by [https://dolby.io/](dolby.io). 
This is was used for recordings where there might be background noise. 
> Then, the audio file will be put through the Media Recognition API by [https://www.acrcloud.com/](ACRCloud) to recognize the song.
> Using this, the webpage will come up with a couple of different products found at Wegmans using the Products API by [https://dev.wegmans.io/](Wegmans) that would fit the 'vibe'/mood of the song.
The foods and genres are related using our personal opinions/experiences.

## How we built it
We implemented this project using JavaScript, HTML/CSS, Axios, Express.js, Node.js, and APIs.

Click the link below to see our Figma Prototype!
https://www.figma.com/proto/1IrVUulqONiEbKFRm81388/food-vibes?node-id=10%3A5&scaling=contain

First, we broke down our project into a couple of goals: 
- Make a webpage that is able to take in an audio file.
- Enhance the audio file so the song can be more easily recognized.
- Actually, recognize the song and its genre using the API.
- Identify what foods go with what music genres. 
- Use the Wegmans API to get information about the food (ex. name, price, aisle) at their local Wegmans.

Then, we figured out what we would be using:
- Prototype making: [https://www.figma.com/](figma.com) 
- Audio Enhancement: Media Processing API by [https://dolby.io/](dolby.io)
- Song and Genre Recognition: Media Recognition API by [https://www.acrcloud.com/](ACRCloud)
- Food Products: Products API by [https://dev.wegmans.io/](Wegmans)

Finally, we broke it up into three parts that each of us took priority on:
- Audio Enhancement + Prototyping
- Song and Genre Recognition + Webpage
- Food Products + Identifying song to the genre

## Example
![Example GIF](https://github.com/maisha242/food-vibes/blob/main/misc/example.gif)

## Challenges we ran into
- Finding a song and genre recognition API
- How to bring all the individual APIs together
- How to use all the APIs based on their documentation
- Efficiently using time
- Limits of APIs (Especially the song and genre recognizer)

## Accomplishments that we're proud of
- Figuring how to integrate all the APIs
- Using a language not everyone is comfortable with
- Understanding node.js 
- Learning Figma
- Creating a webpage with a logo
- Good Team Work
- Figuring out Time Management

## What we learned
- How to prototype a webpage
- Only one of us had some experience JavaScript before this, so we all got very comfortable with writing in it. 
- How the backend of a webpage can be made
- more HTML/CSS (ex. radial gradients)
- Async and Sync functions
- How to make APIs interact

## What's next for food vibes 
- Connecting the Location API for Wegmans so it can be used in other places
- Meals based on genres
- Generalized categories of foods based on genres (ex. snacks)
