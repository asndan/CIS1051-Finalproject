# Proposal

## What will (likely) be the title of your project?

Title : Presence Scanner

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

Detect nearby devices on the same network to notify and alert of a nearby presence and their location

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

My program will first collect data on the connected devices on the network using arp-scan  or known as Resolution Protocol packet scanner that shows every active IPv4 in my local network.
Then using raspberry pi to sort the data and calculate distance from my specific presence radius. Then using Initial state streamer, a python streaming module, I will have Iss use raspberry pi's calculated date into a dashboard.
The dashboard will stream a message if a device comes close to my presence's specific radius and then track the location of all the devices near me. 
## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

N/A

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

N//A

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

The priority goal I hope to accomplish is to mount the arp-scan data onto raspberry pi and make the appropriate calculations to determine presence distance 

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

The goal I hope to reach is to have the data stream a message onto the dashboard to display with the right data calculations when a presence/device comes near me 

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

The best outcome is to have the dashboard pinpoint exact location details of the devices near my presence 

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

My next step is to set up Arduino and the raspberry pi program onto my computer. Then I will focus on my first priority goal by working with Arp-scan and research how to properly integrate it before
having it work with data collection. After properly figuring out the data calculations and have it run properly , I will research into Intial State Streamer. Iss has problems with mac's terminal
so I will have to find a way to effectively use it while troubleshooting. 
