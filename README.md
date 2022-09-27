# GoTime


## GoTime was our 2021 Hackathon Project  
Created by Eesa Aamar, Abdus Shaikh, Maisey Perelonia, and Daniel Liu [me :)]

### Demo Can Be Found Here:
https://www.youtube.com/watch?v=CMCRJt5JhBM


# Inspiration
As commuter students, we always plan to get some school work done after getting home, but we are always far too tired to actually focus and be productive. This exhaustion was made worse by all the walking that must be done to get across campus to the various different buildings. We wanted to minimize this walking distance throughout the day so students can maintain their energy and be more productive throughout their day. Thus, GoTime was born.

# What it does
GoTime takes in a user's classes and their locations as inputs then uses Dijkstra's pathfinding algorithm to find the shortest path between them all. After getting this shortest path, the route the user must travel is displayed on an interactive map powered by the google maps API.

# How we built it
GoTime frontend is built using the Electron framework, leveraging JavaScript, HTML/CSS, and Node.js to create a native app. The back-end path finding algorithm is built primarily in C++. We transferred data across languages by reading and writing to several intermediate text files.

# Challenges we ran into
Implementing Dijkstra's pathfinding was a big challenge. Our team had to create a weighted graph of all the class buildings from scratch, then run the algorithm on that graph to find the shortest path. We also struggled with embedding an interactive map into our app, but the google maps API made this process much easier.

# Accomplishments that we're proud of
We are happy to say that we have a fully functioning app for the domain we set out for. Our app finds the true shortest path that students should take, so we achieved our main goal. We also built a great user interface that requires minimal user interaction to achieve its goal. Finally, we built a strong foundation for our application that allows us to easily expand in the future.

# What we learned
We learned how to collaborate in a team and how to integrate different languages with each other. Particularly, we learned how to effectively transfer data collected in one language to another language for processing. We also learned how to read API documentation better, as well as how to leverage APIs.

# What's next for GoTime
We plan to expand GoTime to universities and colleges across the world, implementing our features to their campuses. Aside from expansion, we plan to introduce a set of premium features that will boost the capabilities of the application for a small subscription fee.

# Built with
* c++
* css
* electron
* google-maps
* javascript
* node.js
* python

## Source Code
https://github.com/AbdusShaikh/GoTime

### Some images
![image](https://user-images.githubusercontent.com/70533174/192608951-4380232d-c9b8-479d-bd7a-5088f087770b.png)
![image](https://user-images.githubusercontent.com/70533174/192609007-aa51b320-c411-46d8-b669-506389684e93.png)
![image](https://user-images.githubusercontent.com/70533174/192609042-b9499452-7dce-47bb-b6ae-07bb12412f7b.png)
![image](https://user-images.githubusercontent.com/70533174/192608972-a37f464e-13ef-49fd-9624-79c7f332d3b7.png)
