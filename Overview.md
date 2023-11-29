# Exploration Activity 2

# Question 1

   For my exploration activity I chose the three.js 3D animation JavaScript library[1].

# Question 2

   ## What is the purpose of this package
   
   It's purpose is to provide programmers with various tools to create and display GPU-accelerated 3D animations in a web browser using WebGL[2].
   The features that it provides are, Effects, Scenes (ex add and remove objects on runtime and fog), Cameras (perspective, fps, etc..), 
   Animation (forward kinematics, morph, etc...), Lights (ambient, direction, etc...), Materials (Lambert, Phong, etc...), Shaders (GLSL capabilities),
   Objects (meshes, particles, etc...), Geometry (plane, cube, etc...), Import/Export (native serialization/deserialization), 
   Utilities (3D math functions like frustum, matrix....), Support, Debugging (three.js inspector), virtual and augmented reality via webXR.
   
   ## How do you use it
   
   First thing you have to do to use this package is install from the npm package regestry via your terminal, there are two things that need to be downloaded 
   in order to use the library. Firstly, you must install the three.js library, to do this simply write into your terminal npm install --save three. Secondly, 
   you must install a build tool, you can download any one of them but vite is recommended, to install it all you have to do is write into your terminal 
   npm install --save-dev vite [3]. Alternatively, you can also import from a CDN, so you would install without build tools This process is much longer
   you would have to put the imports directly into the html code script, you would also need to run a local server to host the files at an URL with the npx serve function written in terminal[3].
   Now you can start using the library, but before you start writing the main JavaScript code you must use a html code encasing (it should be wrapped in the body and script tags) 
   so that the website part works, and if you want the website to have like a different background or more front end features then you just have to ad to the
   html code. Then at the start of the JavaScript code you should write import * as THREE from 'three'; (you can replace 'three' with a link to the libraries you want to use). 
   
# Question 3
   
   This library has many functionalities used to create the 3D animations, the ones I utilized were the geometry functions and the animate functions,
   like rotate. 
   
   ## some sample code and output for a rotating circle:
   <img width="734" alt="Screenshot 2023-11-29 at 6 43 51 PM" src="https://github.com/CS2613-FA23/explorationactivity2-cookedbee/assets/118692386/97d0a67a-490f-4b68-a651-d19b8bdf6d1d">
   
   <img width="1440" alt="Screenshot 2023-11-29 at 6 42 03 PM" src="https://github.com/CS2613-FA23/explorationactivity2-cookedbee/assets/118692386/b3ac3a15-878d-4a33-b057-e3e282fdcbb1">
   
   <img width="1440" alt="Screenshot 2023-11-29 at 6 42 07 PM" src="https://github.com/CS2613-FA23/explorationactivity2-cookedbee/assets/118692386/bd7ac613-db18-4c16-b9c3-3d3895220f29">
   
   <img width="1440" alt="Screenshot 2023-11-29 at 6 42 09 PM" src="https://github.com/CS2613-FA23/explorationactivity2-cookedbee/assets/118692386/c51bb07d-fdbd-4a25-ba9d-6ce2d48a86dd">


# References:
[1] https://threejs.org/
[2] https://en.wikipedia.org/wiki/Three.js
[3] https://threejs.org/docs/#manual/en/introduction/Installation
