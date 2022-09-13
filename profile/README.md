# Penn-Pal

![Penn-Pal](https://user-images.githubusercontent.com/70975465/189779387-e3a2b1c8-2391-4e85-acdc-ae0e76d87635.jpg)

### Project summary

We developed a mentor matching software targeted towards online students (mentors and mentees) as well as mentor program administrators. Penn-Pal provides an intuitive and simple portal for mentors and mentees from different locations, time zones, backgrounds, and experiences to sign-up and connect with each other. Mentor program administrators can use the application on a desktop or mobile device to create a new mentoring event, and customize mentor-mentee matches.

Include the link to your Devpost project page here: [Devpost](https://...)

### Authors

We are a group of three UPenn MCIT Online students who are participating in the [MOSA Fall 2022 Hackathon](https://mosa-fall-2022-hackathon.devpost.com/). 

* Kris Stern - Devpost ID: krisstern – Penn email: kastern@seas.upenn.edu – [GitHub](https://github.com/krisstern)
* Dan Fitz - Devpost ID: danfitz – Penn email: danfitz@seas.upenn.edu – [GitHub](https://github.com/danfitz)
* Bonnie Tse - Devpost ID: bonniewt – Penn email: bonniet@seas.upenn.edu – [GitHub](https://github.com/bonniewt)

## Usage

### Prerequisites

* [WebStorm](https://www.jetbrains.com/webstorm/) - JavaScript IDE
* [Node.js](https://nodejs.org/en/download/) - JavaScript Framework
* [yarn](https://yarnpkg.com/getting-started/install) - Yarn package

### Installation for Front-end 

Give a step-by-step rundown of how to **install** your project.

Step 1: Download WebStorm IDE

https://www.jetbrains.com/webstorm/download/#section=mac

Step 2: Download Node.js (version > 16.10)

https://nodejs.org/en/download/

Step 3: Type in your (MacOS) Terminal, to install yarn package
```
sudo npm install --global yarn

```
You can check if yarn is installed.

```
yarn --version
```

### Deployment

Give a step-by-step rundown of how to **use** your project. Including screenshots in this section can be highly effective for highlighting specific features of your project.

Step 1: Download the front-end code from [penn-pal-frontend](https://github.com/UPenn-MOSA-Hackathon-Gang-of-Three/penn-pal-frontend)

Step 2: Load the code into WebStorm https://www.jetbrains.com/help/webstorm/opening-reopening-and-closing-projects.html

Step 3: In the Terminal in WebStorm, make sure you have all the updated yarn packages.
```
yarn install
```
![Screen Shot 2022-09-12 at 4 30 18 PM](https://user-images.githubusercontent.com/70975465/189775746-aaae7521-5329-4542-b6d8-196b5c25021f.png)

Step 4: To run the code. 
```
yarn dev
```
![Screen Shot 2022-09-12 at 4 30 45 PM](https://user-images.githubusercontent.com/70975465/189775774-3eb4878a-8afc-4d8b-a048-9fe885f1d738.png)

Step 5: Program Administrator - Go to http://localhost:3000 with your browser to see the Program Administrator Mentor Program Event creation view. 

Program Administrator - Home Page http://localhost:3000
![Screen Shot 2022-09-12 at 4 31 17 PM](https://user-images.githubusercontent.com/70975465/189775819-a3181e88-34eb-4825-a736-42be793a999a.png)

Program Adminstrator - Create an event http://localhost:3000/event/new

![Screen Shot 2022-09-12 at 4 32 04 PM](https://user-images.githubusercontent.com/70975465/189775884-3b9f4284-59f6-4ec8-b94e-9caaa99faead.png)

Fill out all the required feeds in the Event Creation form and click on the "Create event" button on the bottom of the page http://localhost:3000/event/success?eventName=Mentor+event&uniqueId=12345
 
![Screen Shot 2022-09-12 at 4 38 33 PM](https://user-images.githubusercontent.com/70975465/189776453-f678eaa5-3bde-4afa-951d-0533597cd60b.png)

Step 6: Mentee - Go to http://localhost:3000/event/register with your browser to see the Mentor and Mentee sign-up form. 

![Screen Shot 2022-09-12 at 4 33 49 PM](https://user-images.githubusercontent.com/70975465/189776034-c00e117f-c40e-4882-a128-311510d89a0d.png)

Click on Mentee Icon to get to Mentee Sign-up form (questions customized for mentee) - http://localhost:3000/event/register

![Screen Shot 2022-09-12 at 4 34 19 PM](https://user-images.githubusercontent.com/70975465/189776070-fc345b81-d534-4dae-81ef-5d14f315680a.png)

Fill out the application and then click on "Submit application" button on the bottom of the page. - http://localhost:3000/event/success?participantName=Ben&uniqueId=12345

![Screen Shot 2022-09-12 at 4 35 45 PM](https://user-images.githubusercontent.com/70975465/189776199-b2d6d6e2-af72-4d0f-b197-fb33ddf2bd93.png)

Step 7: Mentor - Go to http://localhost:3000/event/register with your browser to see the Mentor and Mentee sign-up form. 

![Screen Shot 2022-09-12 at 4 33 49 PM](https://user-images.githubusercontent.com/70975465/189776034-c00e117f-c40e-4882-a128-311510d89a0d.png)

Click on Mentor Icon to get to Mentor Sign-up form (questions customized for mentor) - http://localhost:3000/event/register

![Screen Shot 2022-09-12 at 4 36 38 PM](https://user-images.githubusercontent.com/70975465/189776281-0febb0c6-86a0-4659-b5e3-ea5f1968d124.png)

Fill out the application and then click on "Submit application" button on the bottom of the page. - http://localhost:3000/event/success?participantName=Ben&uniqueId=12345

![Screen Shot 2022-09-12 at 4 35 45 PM](https://user-images.githubusercontent.com/70975465/189776199-b2d6d6e2-af72-4d0f-b197-fb33ddf2bd93.png)

Step 8: Found a Match page: Go to http://localhost:3000/event/status/1/yP3tp-C7vOndxThHVpD6o

![Screen Shot 2022-09-12 at 6 35 23 PM](https://user-images.githubusercontent.com/70975465/189788368-1fb0bf97-95d2-4da3-84e9-cc5b1551b781.png)

Step 9: To terminate Penn-Pal, in the Webstorm Terminal type "Command + C"

```
^C
```
![Screen Shot 2022-09-12 at 4 44 49 PM](https://user-images.githubusercontent.com/70975465/189777053-64365e7f-adfa-4a0a-83f1-20bcb63a6f1c.png)

Optional:

To install the backend, please refer to the ReadMe in them [penn-pal-testdatagenerator repository](https://github.com/UPenn-MOSA-Hackathon-Gang-of-Three/penn-pal-backend)

To install the test data generator, please refer to the ReadMe in them [penn-pal-testdatagenerator repository] (https://github.com/UPenn-MOSA-Hackathon-Gang-of-Three/penn-pal-testdatagenerator)

## Additional information

### Tools used

To develop Penn-Pal, we used a host of technologies and tools to enable a feature-complete experience for the user:

Front-end: 

* [Next.js](https://nextjs.org/) - Web Development Framework
* [React.js](https://reactjs.org/) - JavaScript Library
* [Chakra UI](https://chakra-ui.com/) - User Interface Component Library
* [Material UI](https://mui.com/) - User Interface Component Library
* [LottieFiles](https://lottiefiles.com/) - Animations
* [Vercel](https://vercel.com/) - Hosting Platform
* [WebStorm] (https://www.jetbrains.com/webstorm/) - JavaScript IDE

Back-end:

* [Strapi](https://strapi.io/) - Headless Content Management System (CMS)
* [Node.js](https://nodejs.org/en/about/) - Server Environment
* [PostgreSQL](https://www.postgresql.org/) - Object-Relational Database
* [JavaServer Faces Widget Library - JWL](https://www.ibm.com/docs/en/was-nd/8.5.5?topic=files-javaserver-faces-widget-library) - Authentication Widget Library
* [Heroku](https://www.heroku.com/) - Hosting Platform
* [Postman](https://www.postman.com/) - API Testing

Test Dataset Generation: 

* [Python Faker](https://faker.readthedocs.io/en/master/) - Python Package to generate fake data
* [PyCharm](https://www.jetbrains.com/pycharm/) - Python IDE

![Penn-Pal (17)](https://user-images.githubusercontent.com/70975465/189779872-f5e086d9-6902-4466-9c48-33bb4ec7c034.jpg)


### License

MIT License

Copyright (c) 2022 Penn-Pal

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security

