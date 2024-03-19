# Tinder For Spotify
Find music you love by swiping on songs. Like Tinder, but for Spotify. 

# Introduction
The purpose of this project is to develop an app that enables users to discover new music they enjoy by swiping on songs presented to them. This concept is inspired by the dating app Tinder, where users swipe right on individuals they like and swipe left on those they don't.

Finding new music I enjoy has always been a challenge for me. After learning about various techniques in supervised and unsupervised machine learning, I decided this was something I wanted to pursue. Although there are other implementations available online, none have met my standards for ease of use and UI/UX experience. Therefore, I decided to create my own.


# Development Notes
**March 18, 2024**   
I have researched the Spotify API a bit now. I suspect that the main endpoints I'll need to use are:

- Create Playlist
- Add Items to Playlist
- Remove Playlist Items
- Start/Resume Playback
- Seek To Position
- Get Track
- Get Track's Audio Features
- Get Track's Audio Analysis
- Get Recommendations
- Get User's Top Items

Another important thing I came across is that Spotify states that developers can't use their content to train machine learning algorithms. I think I'll be okay, because I won't train my machine learning models on their content but rather the users' reaction to it (whether they swipe left or right). I'm not sure what the extent of Spotify's wishes here is, but I'll try to research more and contact them. Worst case, I'll have to use another music provider API, but again, Spotify's documentation is vague and unclear on this, so I'll have to do more research on this part too.  



**March 18, 2024**   
I'll be using this README for my notes, research, and the dev process. First up, I need to dive into the Spotify API. My initial aim is to craft a site that feels intuitive and offers a great user experience, focusing especially on making swiping smooth and the design both clean and appealing. Once I nail that, including the swipe functionality, I’ll explore machine learning techniques for the recommendation algorithm. I'm thinking of starting with a user getting a playlist after some swipes, but ideally, I want the playlist to form instantly and refine with each swipe for better accuracy. This sounds resource-heavy, though, so more research is needed.
