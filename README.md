#Savvy Suit Technical interview

Savvy Assignment
Working at a startup is a whole new environment compared to the big corporate world. We are a small team attempting to do something that has never been done before! It’s not about what you know, but how willing you are to learn new things and go the extra mile to help shape the company into something awesome.
Because this is so crucial, we want to test you on it. We want (and encourage!) you to use as many resources as you need to get it done - because that’s what we do on the job every day! But we caution you not to use other people’s code, this is still a test of your skills.
Polymer, Socket.io, and Node.js are three very important pieces of our product. This homework assignment is broken down into three smaller parts for each technology.
####Polymer (1.0) ..
***Background:***
Polymer is a framework used to make beautiful UI that  brings an implementation of Google’s “material design” to the web. Polymer is our frontend.
Polymer is used by importing different pre-styled “elements” to your project. For example, in Polymer there is an element called  paper-button . This element is the fancier looking version of a regular button in HTML.
Task:
We would like you to create a web page in Polymer! Don’t worry - it will be very basic. It needs to contain the following items:
- An input field in the form of a Polymer p  aper-input-decorator,  and
- A button in the form of a Polymer p  aper-button.
Resources:
Remember, we really really really really  encourage you to look things up! Here are some helpful resources:
- [Polymer site](https://www.polymer-project.org/0.5/)
- [Paper docs](https://www.polymer-project.org/0.5/docs/elements/paper-button.html)
- [Paper decorator](https://www.polymer-project.org/0.5/docs/elements/paper-input-decorator.html)

    
####Socket.io (latest) ..
***Background:***
Socket.io is a framework built for sending messages between a client and server. We deal with a lot of data, so this kind of functionality is a must.
The first part of passing data from a client to a server is for the client to actually send the server a message. In the next part, we will look at how the server will interact with this message, but for now, let’s focus on the client.
Task:
Wewanttosendamessagetotheserverwhenweclickthep aper-button .To do this, we want you to use socket.io. We would like you to add the following to your Polymer web page:
- Set the variable  myMsg  to the text that is in your input, and
- Send a message using  socket.emit(‘myMessage’, myMsg) when the
paper-button  is clicked.
*Resources:*
Remember, we really really really really  encourage you to look things up! Here are some helpful resources:
 - [Socket.io site](http://socket.io/)
 - [Socket docs](http://socket.io/docs/)
   
####Node.js (latest) ..

***Background:***
Node.js is difficult to describe as it does just about anything you'd like! For our purposes, it's a Javascript framework that allows Javascript to run on a server that the client can talk to. (  You might want to read up on client-server if this sounds a bit too crazy.) If you're with us so far, we would like to have a client (your Polymer web page) talk to (using socket.io) our server (Node.js).
*Task:*
It's time to add the last piece of the puzzle! This is the most complex part. Here is what we need:
- We would like you to make a local server using Node.js,
- We need it to use socket.io,
- With socket.io included, we need to listen for m  yMessage   (remember where this
is from?), and
- When we receive a message, log to the console that we received a
message and what message we received.
*Resources:*
Here are some more resources:
- [Node Site](https://nodejs.org/)
- [Beginner's Guide to Node](http://blog.modulus.io/absolute-beginners-guide-to-nodejs/)
- [Socket.io Docs](http://socket.io/docs/)

**Conclusion ..**

While we do expect you to know a little bit about web development, we also expect there to be a learning curve - and that’s okay! This assignment was intended for you to go out, research, and learn how to work with the three main technologies we use. In addition to this, we would love to see you go the extra mile! If you have an interesting idea that you would like to add on to this assignment, it will definitely be taken into consideration. ;) As a startup, innovation and creative thinking is a must, so these are qualities we are also looking for during this process.
If you have any questions, feel free to ask! We can't wait to see what you create! Good luck and happy coding!
