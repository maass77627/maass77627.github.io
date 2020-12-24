---
layout: post
title:      "ReactFinalProject"
date:       2020-12-24 07:58:04 +0000
permalink:  reactfinalproject
---


For my final flat iron project. I created a React/Redux app with a rails API backend. My project is titled JourneyJournal and it acts as a database for a User to store and keep track of all of the citys they have visited/ want to visit as well as get inspiration for where they might want to go next.
This was a difficult project for me but I learned so much in the process and am excited to continue learning and building my skills. 
For me building the back end came pretty naturally by this point with all the practice we have had with rails but being my first experience with react I had to do a lot of further reading and research into concepts like state, props, lifecycle, components, store etc. 
One of the things that caused me a lot of trouble initially was figuring out parts of the component lifecycle as far as when certain things would render in the application. 
Remembering the order that certain methods are called in react really helped in the troubleshooting process.   
For instance it is important to know that when an instance or your component is being created the methods constructor(), static getDerivedStateFromProps(), render(), and componentDidMount() will be called in that specific order. 
 
Besides the component life cycle I probably spent most of my time learning about props state and store, and how to use it and update it throughout your application. 

When connecting your redux store to your components it will be important to remember connect and provide. And how to use them to make your stores state accessible to whichever components you need. 
When changing and updating your state in the reducer function do not forget about the spread operator and object.assign as I found these could really come in handy. 

