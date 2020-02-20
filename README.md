GITHUB INSTRUCTIONS:

1. on the git hub main page, click the clone button and copy that link. 
2. in your terminal enter in the following command `git clone {that link here}`


<!-- our official READ_ME  -->
ABOUT: This is our NUtshell front-end project. Completed by Kurt Krafft, Trinity Terry, and Andrew Green. This project is 
essentially building a website that mimics social media. The user can create an account or login, then they will be taken to the 
home page, afterwards they can use the full range of services we created. Things like an events page, where a user can create 
events. A News page where a user can post news articles. A friends page where the user can add friends and participate in the 
group chat. It also has a personalized task bar to give the user their own to-do list. Have fun, and enjoy TwixBook. 


STARTING THE APP INSTRUCTIONS 

1. Begin by creating an api folding in the root directory and enter in `cd api/` 

2. enter in the following command while in your api folder `touch database.json`

3. open that file and copy and paste the following text 


`{
  "users": [
    {
      "id": 1,
      "username": "Steve",
      "email": "me@me.com",
      "password": "Steve",
      "profPic": "https://media.tenor.com/images/b5abed30c3b61e75907475636efde7df/tenor.gif"
    },
    {
      "id": 2,
      "username": "a",
      "email": "a@a.com",
      "password": "a",
      "profPic": "https://media.tenor.com/images/b5abed30c3b61e75907475636efde7df/tenor.gif"
    },
    {
      "id": 3,
      "username": "b",
      "email": "b@b.com",
      "password": "b",
      "profPic": "https://media.tenor.com/images/b5abed30c3b61e75907475636efde7df/tenor.gif"
    },
    {
      "id": 4,
      "username": "c",
      "email": "c@c.com",
      "password": "c",
      "profPic": "https://media.tenor.com/images/b5abed30c3b61e75907475636efde7df/tenor.gif"
    },
    {
      "id": 5,
      "username": "d",
      "email": "d@d.com",
      "password": "d",
      "profPic": "https://media.tenor.com/images/b5abed30c3b61e75907475636efde7df/tenor.gif"
    },
    {
      "id": 6,
      "username": "e",
      "email": "e@e.com",
      "password": "e",
      "profPic": "https://media.tenor.com/images/b5abed30c3b61e75907475636efde7df/tenor.gif"
    },
    {
      "id": 7,
      "username": "f",
      "email": "f@f.com",
      "password": "f",
      "profPic": "https://media.tenor.com/images/b5abed30c3b61e75907475636efde7df/tenor.gif"
    },
    {
      "username": "as",
      "email": "a@b.com",
      "password": "as",
      "id": 8,
      "profPic": "https://media.tenor.com/images/b5abed30c3b61e75907475636efde7df/tenor.gif"
    },
    {
      "username": "z",
      "email": "z@z.com",
      "password": "z",
      "profPic": "https://media3.giphy.com/media/1d7F9xyq6j7C1ojbC5/giphy.gif",
      "id": 9
    },
    {
      "username": "x",
      "email": "x@x.com",
      "password": "x",
      "profPic": "https://media.giphy.com/media/3gVFmYNIY3A2LroFBD/giphy.gif",
      "id": 10
    },
    {
      "username": "ba",
      "email": "a@a.con",
      "password": "a",
      "profPic": "https://media3.giphy.com/media/1d7F9xyq6j7C1ojbC5/giphy.gif",
      "id": 11
    },
    {
      "username": "abb",
      "email": "a@a.cog",
      "password": "a",
      "profPic": "https://media.giphy.com/media/3gVFmYNIY3A2LroFBD/giphy.gif",
      "id": 12
    },
    {
      "username": "j",
      "email": "j@j.com",
      "password": "j",
      "profPic": "https://media.giphy.com/media/3gVFmYNIY3A2LroFBD/giphy.gif",
      "id": 13
    },
    {
      "username": "w",
      "email": "w@e.com",
      "password": "w",
      "profPic": "https://media.giphy.com/media/3gVFmYNIY3A2LroFBD/giphy.gif",
      "id": 14
    },
    {
      "username": "fr",
      "email": "fr@fr.com",
      "password": "fr",
      "profPic": "https://media.giphy.com/media/3gVFmYNIY3A2LroFBD/giphy.gif",
      "id": 15
    },
    {
      "username": "y",
      "email": "y@y.com",
      "password": "y",
      "profPic": "https://media.giphy.com/media/3gVFmYNIY3A2LroFBD/giphy.gif",
      "id": 16
    }
  ],
  "messages": [
    {
      "userId": 1,
      "message": "What's up? doc",
      "id": 1
    },
    {
      "id": 2,
      "userId": 4,
      "message": "The Sky"
    },
    {
      "userId": 1,
      "message": "hey you!",
      "id": 3
    },
    {
      "id": 4,
      "userId": 6,
      "message": "asd"
    },
    {
      "id": 6,
      "userId": 7,
      "message": "french"
    },
    {
      "id": 7,
      "userId": 2,
      "message": "What's up?"
    },
    {
      "message": "free",
      "userId": 6,
      "id": 8
    },
    {
      "userId": 1,
      "message": "free as a bird",
      "id": 9
    },
    {
      "message": "free",
      "userId": 4,
      "id": 10
    },
    {
      "message": "free",
      "userId": 3,
      "id": 11
    },
    {
      "userId": 1,
      "message": "free as a whale",
      "id": 12
    },
    {
      "message": "no",
      "userId": 3,
      "id": 13
    },
    {
      "message": "yes",
      "userId": 7,
      "id": 15
    },
    {
      "userId": 6,
      "message": "test! yes! whoopee",
      "id": 16
    },
    {
      "message": "here we go",
      "userId": 1,
      "id": 18
    },
    {
      "message": "Lets rock",
      "userId": 1,
      "id": 19
    },
    {
      "message": "LESS",
      "userId": 1,
      "id": 20
    },
    {
      "message": "MORE",
      "userId": 2,
      "id": 21
    },
    {
      "message": "hey",
      "userId": 1,
      "id": 22
    },
    {
      "message": "test",
      "userId": 1,
      "id": 23
    },
    {
      "message": "Lets test this out",
      "userId": 9,
      "id": 24
    },
    {
      "message": "new test",
      "userId": 10,
      "id": 25
    },
    {
      "message": "cheeseing",
      "userId": 16,
      "id": 26
    },
    {
      "message": "yippie",
      "userId": 16,
      "id": 27
    }
  ],
  "events": [
    {
      "userId": 4,
      "name": "3",
      "location": "sldkfjklj",
      "date": "2020-02-13",
      "id": 9
    },
    {
      "userId": 2,
      "name": "1",
      "location": "somewhere",
      "date": "2020-02-21",
      "id": 10
    },
    {
      "userId": 2,
      "name": "2",
      "location": "here",
      "date": "2020-02-29",
      "id": 11
    },
    {
      "userId": 1,
      "name": "this",
      "location": "there",
      "date": "2020-02-28",
      "id": 12
    },
    {
      "userId": 1,
      "name": "that",
      "location": "there",
      "date": "2020-02-21",
      "id": 13
    },
    {
      "userId": 3,
      "name": "party",
      "location": "in here",
      "date": "2020-02-29",
      "id": 14
    },
    {
      "userId": 3,
      "name": "party",
      "location": "over there",
      "date": "2020-02-29",
      "id": 15
    },
    {
      "userId": 2,
      "name": "3",
      "location": "something",
      "date": "2020-02-21",
      "id": 16
    },
    {
      "userId": 3,
      "name": "4",
      "location": "saldk",
      "date": "2020-02-29",
      "id": 17
    },
    {
      "userId": 3,
      "name": "party",
      "location": "everywhere",
      "date": "2020-02-28",
      "id": 18
    }
  ],
  "news": [
    {
      "id": 1,
      "userId": 2,
      "url": "https://www.quantamagazine.org/newfound-wormhole-allows-information-to-escape-black-holes-20171023/",
      "title": "Wormholes Allow Information to Escape Black Holes",
      "synopsis": "Check out this recent discovery about workholes"
    },
    {
      "userId": "1",
      "url": "https://testing.com",
      "title": "whoops",
      "synopsis": "whoops\n2",
      "id": 2
    },
    {
      "userId": "1",
      "url": "https://fun.com",
      "title": "fun",
      "synopsis": "fun",
      "id": 3
    },
    {
      "userId": "2",
      "url": "https://a.com",
      "title": "a",
      "synopsis": "a",
      "id": 4
    }
  ],
  "friends": [
    {
      "friendUserId": 1,
      "userId": 2,
      "nickName": "P-whizzle cool",
      "id": 1
    },
    {
      "friendUserId": 1,
      "userId": 3,
      "nickName": "Broccoli Robert",
      "id": 2
    },
    {
      "friendUserId": 1,
      "userId": 7,
      "nickName": "BUZZY",
      "id": 4
    },
    {
      "friendUserId": 2,
      "userId": 6,
      "nickName": "SNAP",
      "id": 5
    },
    {
      "friendUserId": 2,
      "userId": 4,
      "nickName": "POP",
      "id": 6
    },
    {
      "friendUserId": 2,
      "userId": 6,
      "nickName": "KRACKLE",
      "id": 7
    },
    {
      "friendUserId": 2,
      "userId": 1,
      "nickName": "STEVE-O",
      "id": 8
    },
    {
      "friendUserId": 1,
      "userId": 4,
      "nickName": "Beans",
      "id": 9
    },
    {
      "userId": 7,
      "friendUserId": 16,
      "id": 11
    },
    {
      "userId": 10,
      "friendUserId": 16,
      "id": 12
    },
    {
      "userId": 9,
      "friendUserId": 16,
      "id": 13
    },
    {
      "userId": 14,
      "friendUserId": 16,
      "id": 14
    }
  ],
  "tasks": [
    {
      "id": 1,
      "userId": 3,
      "task": "Take out garbage"
    },
    {
      "userId": 1,
      "complete_on": "",
      "done": true,
      "task_text": "kurt yes",
      "id": 2
    },
    {
      "userId": 1,
      "complete_on": "",
      "done": false,
      "task_text": "new task",
      "id": 3
    }
  ]
}`


4. Now still within the api directory in your terminal enter in the following command `json-server -p 8088 -w database.json`

5. enter in `../`

6. then type `hs -o` within the root directory. On the opening page click the src link and the website will open!

7. enjoy!