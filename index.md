## Organizers
<p style="text-align: center;"> Sean Fanello, Christoph Rhemann, Jonathan Taylor, Sofien Bouaziz, Adarsh Kowdle, Rohit Pandey, Sergio Orts-Escolano, Paul Debevec, Shahram Izadi
</p>
<p style="text-align: center;"> <b> Google </b> </p>
<p style="text-align:center"><img src="http://www.seanfanello.it/wp-content/uploads/2020/04/cvpr20_tutorial_image.png"/></p>

## Description
3D Capture and Rendering of humans has shown incredible progress in the last few years reaching a level of quality that is getting closer to Image Based Renderings (IBR) approaches. These systems usually rely on multiview capture setups and sophisticated pipelines to build a consistent, parameterized mesh of the performer with reflectance properties. The final goal of these approaches is to render high quality, photo-realistic humans that can match the quality of Hollywood productions, without any manual intervention or post-processing.

However, despite steady progress and encouraging results obtained by these 3D capture systems, they still face important challenges and limitations. For example, translucent and transparent objects cannot be easily captured; reconstructing thin structures (e.g. hair) is still very challenging even with high resolution depth sensors. At the same time, the computer vision community has focused its attention towards deep learning techniques to overcome the limitations of geometric approaches. 

In this tutorial, we will show how to combine geometric pipelines with recent advances in neural rendering to construct disentangled 3D representations for photo-realistic renderings of humans in novel viewpoints and desired lighting conditions. We will walk the audience through the current state-of-the-art for 3D performance capture, highlighting the pros and cons of the various techniques. 

In particular, in the first part of the tutorial we will focus on the capture system, that is the foundation for any machine learning methods that rely on supervised ground truth data. We will consider the hardware design choices for cameras, sensors, lighting, and depth estimation algorithms.  We will then describe all the steps needed to select and design the right depth sensing technology for a given application.

In the second part we will then detail state-of-the-art methods to reconstruct humans with high fidelity. We will focus on topics such as 3D reconstruction, parametric and non-parametric tracking, mesh parameterization and compression. We will also detail traditional methods to compute reflectance and material properties of arbitrary objects.

In the third part of the tutorial we will show how deep learning can be applied to overcome the limitations of the traditional capture and rendering pipelines. We will detail recent trends in disentangled representations for human capture, with particular emphasis on pose, viewpoint and lighting. Finally we will discuss multiple applications enabled by performance capture systems and machine learning.


## When and Where
June 14th - 9.10 am PDT - Virtual, hosted on the official <a href="http://fry.vast.uccs.edu/disentangled-3d-representations"> CVPR Website</a>.
<br>
Talks are pre-recorded and attendees can watch them asychronously. 
<br>
Organizers will periodically check the comments to answer questions.

## Program

<table style="width:100%">
  <tr>
    <th><div align="center"> Time</div> </th>
    <th><div align="center"> Title</div> </th> 
    <th><div align="center"> Speaker</div> </th>
  </tr>
  <tr>
    <td></td>
    <td><div align="center"> <b> Morning Session: <br/>3D Capture Systems for Groundtruth Generation </b> </div> </td> 
    <td></td>
  </tr>
     <tr>
    <td><div align="center"> 9:10 - 9:30 </div> </td>
    <td><div align="center"> Learned Disentangled Representations for Perception Tasks</div> </td> 
    <td><div align="center"> Sean Fanello <br/> Google </div> </td> 
  </tr>     
  <tr>
    <td><div align="center"> 9:30 - 10:00 </div> </td>
    <td><div align="center"> High Quality Depth Sensors for Volumetric Capture </div> </td> 
    <td><div align="center"> Adarsh Kowdle<br/> Google </div> </td> 
  </tr>  
  <tr>
    <td><div align="center"> 10:00 - 10:30 </div> </td>
    <td><div align="center"> The Light Stage Hardware </div> </td> 
    <td><div align="center"> Christoph Rhemann <br/> Google </div> </td> 
  </tr>      
  <tr>
    <td><div align="center"> 10:30 - 10:45 </div> </td>
    <td><div align="center"> Coffee Break </div> </td> 
    <td></td> 
  </tr>      
  <tr>
    <td><div align="center"> 10:45 - 11:30 </div> </td>
    <td><div align="center"> Detect, Reconstruct, Track and Parameterize Humans </div> </td> 
    <td><div align="center"> Kaiwen Guo <br/> Google </div> </td> 
  </tr>      
  <tr>
    <td><div align="center"> 11:30 - 12:10 </div> </td>
    <td><div align="center"> Reflectance Estimation in Images, Videos and 3D Content </div> </td> 
    <td><div align="center"> Alex Ma <br/> Google </div> </td> 
  </tr> 
  <tr>
    <td><div align="center"> 12:10 - 13:30 </div> </td>
    <td><div align="center"> Lunch Break </div> </td> 
    <td></td> 
  </tr>   
  <tr>
    <td></td>
    <td><div align="center"> <b> Afternoon Session: <br/>Deep Learning meets Light Stage
 </b> </div> </td> 
    <td></td>
  </tr>  
   <tr>
    <td><div align="center"> 13:30 - 14:00 </div> </td>
    <td><div align="center"> [Keynote] A Light Stage for (almost) Every Application </div> </td> 
    <td><div align="center"> Paul Debevec <br/> Google </div> </td> 
  </tr>    
  <tr>
    <td><div align="center"> 14:00 - 14:20 </div> </td>
    <td><div align="center"> Learning to Predict Depth for Computational Photography </div> </td> 
    <td><div align="center"> Yinda Zhang <br/> Google </div> </td> 
  </tr>    
  <tr>
    <td><div align="center"> 14:20 - 14:40 </div> </td>
    <td><div align="center"> Multi-view Pose Estimation and Tracking </div> </td> 
    <td><div align="center"> Anastasia Tkach <br/> Google </div> </td> 
  </tr>  
    <tr>
    <td><div align="center"> 14:40 - 15:00 </div> </td>
    <td><div align="center"> Accurate Alpha Matting for Performance Capture </div> </td> 
    <td><div align="center"> Sergio Orts-Escolano <br/> Google </div> </td> 
  </tr> 
   <tr>
    <td><div align="center"> 15:00 - 15:20 </div> </td>
    <td><div align="center"> Learning to Estimate Environmental Lighting </div> </td> 
    <td><div align="center"> Chloe LeGendre <br/> Google </div> </td> 
  </tr>   
<tr>
    <td><div align="center"> 15:20 - 15:40 </div> </td>
    <td><div align="center"> Deep Implicit Compression </div> </td> 
    <td><div align="center"> Danhang Tang <br/> Google </div> </td> 
  </tr>     
    <td><div align="center"> 15:40 - 16:00 </div> </td>
    <td><div align="center"> Coffee Break </div> </td> 
    <td></td> 
  <tr>
    <td><div align="center"> 16:00 - 16:20 </div> </td>
    <td><div align="center"> 3D Disentanglement of Lighting, Appearance, Viewpoint </div> </td> 
    <td><div align="center">  Abhimitra Meka <br/> Google </div> </td> 
  </tr>   
<tr>
    <td><div align="center"> 16:20 - 16:40 </div> </td>
    <td><div align="center"> Neural Rendering for Performance Capture </div> </td> 
    <td><div align="center"> Rohit Pandey <br/> Google </div> </td> 
  </tr> 


    
</table>

Please contact [Shahram Izadi](mailto:shahrami@google.com) or [Sean Fanello](mailto:seanfa@google.com) if you have any questions.
