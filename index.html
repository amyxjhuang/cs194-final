<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link href="stylesheet.css" rel=stylesheet>

    <title>CS194 Final Project</title>
  </head>
  <body>
    <h1>CS194 Final Project</h1>
    <p>Intro to Computer Vision & Computational Photography: <b>Anderson Lam, Amy Huang</b></p>
    <div class="row">
      <button type="button" name="button" ><a href="./index.html">Lightfield Camera</a></button>
      <button type="button" name="button"><a href="./image_quilting.html">Image Quilting</a></button>
      <button type="button" name="button"><a href="./gradient.html">Gradient Domain Fusion</a></button>
    </div>
    <h2>Lightfield Camera</h2>
    <p><b>Overview:</b> In this project we will be using the <a href="http://lightfield.stanford.edu/lfs.html">Stanford Light Field Archive</a>
    to reproduce <em>depth refocusing</em> and <em>aperature adjustments</em> using shifting and averaging. We followed Ren Ng's <a href="http://graphics.stanford.edu/papers/lfcamera/lfcamera-150dpi.pdf"> paper </a> as well.</p>
<hr>
    <h4>Depth Refocusing</h4>

    <center>
    <figure>
      <img src="./lightfield-camera/beans_gif.gif"  height=300/><figcaption>a = [-5, 1]</figcaption>
    </figure>
    </center>
    <p>Faraway objects do not move as much with the different camera angles compared to closer objects- and we are able to utilize this and take into account
    the camera placement to implement the depth refocusing. We first parsed the camera index from the image file names- this was our (x, y) coordinate which we used
    measure from the index of (8, 8), the center image. The amount of shifting is calculated by multiplying by an alpha <code>Δ(x_1, y_1) = a * (x_0, y_0)</code>
    <br><br>Here is the following averaged <b>amethyst</b> photos with a = -1, 0, 1 respectively
  </p>
  <center>
  <div class="row">
    <figure>
      <img src="./lightfield-camera/am-1.jpg" height=300/> <figcaption>a = -1</figcaption>
    </figure>
    <figure>
      <img src="./lightfield-camera/am0.jpg"  height=300/><figcaption>a = 0</figcaption>
    </figure>
    <figure>
      <img src="./lightfield-camera/am1.jpg"  height=300/><figcaption>a = 1</figcaption>
    </figure>
  </div>
  </center>
  <div class="row">
    <p><br><br> On the right shows
    the values of a from -3 to 2. As you can see, increasing the alpha focused the front
      of the object while decreasing it focused on the back. When alpha = 0, that means we
    did not do any additional/scaled shifting- it is just an average of the dataset's images.

   <br><br> Let's also look at the Jellybean and Chess dataset!
  <br><br> Here is the alpha values -5 to 1 on the jellybean image dataset. We shifted our alpha
   value down because of how the jelly beans are pretty far back in the images. </p>
    <img src="./lightfield-camera/am_gif.gif"  height=300/>
  </div>
  <p><b>Jellybean dataset</b></p>
    <center>
    <div class="row">
      <figure>
        <img src="./lightfield-camera/beans-3.jpg" height=110/> <figcaption>a = -3</figcaption>
      </figure>
      <figure>
        <img src="./lightfield-camera/beans-1.jpg"  height=110/><figcaption>a = -1</figcaption>
      </figure>
      <figure>
        <img src="./lightfield-camera/beans1.jpg"  height=110/><figcaption>a =1</figcaption>
      </figure>

    </div>
    </center>

   <p><b>Chess dataset</b></p>
   <center>
   <div class="row">
     <figure>
       <img src="./lightfield-camera/chess-3.jpg" height=120/> <figcaption>a = -3</figcaption>
     </figure>
     <figure>
       <img src="./lightfield-camera/chess0.jpg"  height=120/><figcaption>a = 0</figcaption>
     </figure>
     <figure>
       <img src="./lightfield-camera/chess3.jpg"  height=120/><figcaption>a = 3</figcaption>
     </figure>

   </div>
   </center>
<hr>
   <h4>Aperature Adjustment</h4>
   <center>
   <figure>
     <img src="./lightfield-camera/ap_bean.gif"  height=300/><figcaption>r = [0, 10]</figcaption>
   </figure>
   </center>
   <p>To implement aperature adjustment, we want to average the images perpendicular to the optical axis.
   A bigger aperature is created with more perpendicular images. We use a radius variable to indicate
   a bigger or smaller aperature. By adding images from different angles, we acculumate the rays to a certain
   part of the image, and are able to mimick the opening of aperature in a camera.
   <br> <br> <b>Amethyst Dataset</b>
 </p>

   <center>
   <div class="row">
     <figure>
       <img src="./lightfield-camera/apam0.jpg" height=300/> <figcaption>r = 0</figcaption>
     </figure>
     <figure>
       <img src="./lightfield-camera/apam10.jpg"  height=300/><figcaption>r = 10</figcaption>
     </figure>
     <figure>
       <img src="./lightfield-camera/ap_am.gif"  height=300/><figcaption>r = [0, 10]</figcaption>
     </figure>
   </div>
   </center>
<p><b>Jellybean Dataset</b></p>
<center>
<div class="row">
  <figure>
    <img src="./lightfield-camera/apbeans0.jpg" height=150/> <figcaption>r = 0</figcaption>
  </figure>
  <figure>
    <img src="./lightfield-camera/apbeans10.jpg"  height=150/><figcaption>r = 10</figcaption>
  </figure>
</div>
<figure>
  <img src="./lightfield-camera/ap_bean.gif"  height=310/><figcaption>r = [0, 11]</figcaption>
</figure>
</center>

<p><b>Chess Dataset</b></p>
<center>
<div class="row">
  <figure>
    <img src="./lightfield-camera/apchess0.jpg" height=150/> <figcaption>r = 0</figcaption>
  </figure>
  <figure>
    <img src="./lightfield-camera/apchess10.jpg"  height=150/><figcaption>r = 10</figcaption>
  </figure>
</div>
<figure>
  <img src="./lightfield-camera/ap_chess.gif"  height=310/><figcaption>r = [0, 11]</figcaption>
</figure>
</center>

<p><b>Summary:</b> Through this project we learned how to refocus and adjust an image after looking through already
processed images. The idea is very straightforward and makes a lot of sense, although I never would have known how
this works otherwise. </p>
<div class="row">
  <button type="button" name="button"><a href="./image_quilting.html">Image Quilting</a></button>
  <button type="button" name="button"><a href="./gradient.html">Gradient Domain Fusion</a></button>
</div>
  </body>
</html>
