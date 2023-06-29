# WebGL Shaders: Drawing fractals with JavaScript

### Details:
* __Outcome__: Build your very own fractal renderer capable of drawing and zooming into fractals in *real time*
* __Requirements__: Any computer with a text editor and browser
* __Language Used__: HTML, Javascript, GLSL
* __Customization opportunity__: There are hundreds of different types of fractals that can be implemented in the Jam, and people can add their own colors and gradients to the app
* __Time Estimation__: 1 Hour

---
<p align=center>
<img width="300" alt="fractal" src="https://github.com/NalinPlad/Jams/assets/43052612/54b85359-07ee-4f4f-bd5a-cf99ebb57c7b">
<img width="300" alt="Screenshot 2023-03-09 at 6 10 39 PM" src="https://github.com/NalinPlad/Jams/assets/43052612/df4e62eb-a65e-413b-bb3b-ef38f03bbe89">
<img width="300" alt="Screenshot 2023-03-09 at 10 40 05 AM" src="https://github.com/NalinPlad/Jams/assets/43052612/592be5d1-a93d-4aaa-86c1-5ad8576b8392">

<h6 align=center>All these images were made <a href="https://github.com/NalinPlad/gpu_fractals">by me</a> with the method in the Jam</h6></p>


---


### Breakdown
###### Each point is a chapter, or section of the Jam
1) Learn about the imaginary plane and how fractals are formed (Mathematical Overview)
2) Here you can choose a specific fractal to use for your project
3) What is WebGL, and why are we using it instead of just Javascript and Canvas elements?
4) Rendering fractals
    1) Setting up WebGL code ★
    3) What are Vertex and Fragment Shaders
    2) Drawing a square ★
    3) Rendering our scene ★
    4) What are Uniform variables
    5) Implementing Uniform variables ★
    6) Simplifying the complex plane to real numbers
    7) Adding color ★
    8) Camera controls ★
5) Where to go from here, further optimizations like perturbation theory, and trade offs from using GPU


### Additional Information
* __Why should Hack Clubbers care about this project__: Graphics programming is one of the most under appreciated technologies that we use for almost everything on the web, and on our computers. This jam will give a beginner - intermediate(depending on how you follow the Jam after its over) view into how this process actually works.
* __What club members will walk away with__: Following the completion of the Jam, members will have a low level understanding of the GPU rendering pipeline, in addition to this, they will also understand the complex math behind fractals, for which many elegant explanations exist.
* __What makes the Jam fun for members__: When I first made this project by myself for fun, it wa the most rewarding experience to actually be interfacing with the GPU directly from my code. Really getting this loe level view of GPU code is very rewarding when you see your hard work pay off.
* __What platforms are supported__: [Everyone](https://caniuse.com/webgl), replit can be used to complete the project as well
* __How will you allow Club Leaders to add their own project to the Jam presentation__: Leaders can finish the Jam and create the web app. They can then serve it on a local web server so that students on the same wifi network can view it and see the end product before they start. If they are not on the same network the Lleader can always [tunnel the connection](https://theboroer.github.io/localtunnel-www/) to quickly show it to them


- **General outline of a club meet doing the Jam**
  - **3 minutes:** Quick intro to graphics programming
  - **50 minutes:** Going through the breakdown above, the sections that are marked with ★ are live coding that students can follow along with
  - **5 minutes:** Members can show off renders they made or different things they discover in the fractals
  - **2 minutes:** Quickly go over where to go from here (step 5 on the breakdown)

