Download Link: https://assignmentchef.com/product/solved-computer-graphics-alternative-assignment-to-final-exam
<br>
<strong> </strong>




<ol>

 <li>(100 pts) Write a Python program that satisfies the following requirements. Draw an object with</li>

</ol>

PyOpenGL.

<ol>

 <li>(85 pts) Evaluation criteria 1 – Requirements: [Each item is evaluated as satisfied, partially satisfied, or unsatisfied]</li>

 <li>(15 pts) Draw 3 or more 3D objects.

  <ol>

   <li>Draw any shape of objects as you want.</li>

   <li>Each object should be a 3D polygon mesh. It can be drawn using a vertex array</li>

  </ol></li>

</ol>

or glVertex3f(). Do not use 2D plannar meshes.

<ol start="3">

 <li>You can reuse your class assignment 2 (obj viewer) code if you want to use obj files for this requirement. In this case, an obj file path should be specified by a <strong>relative path</strong> and the obj files should be included in the submission zip file. Do not use drag and drop to open obj files. They must be automatically loaded when</li>

</ol>

the program starts.

<ol start="2">

 <li>(15 pts) One of the objects should be “main object”. The user should be able to transform the main object using the mouse or keyboard.

  <ol>

   <li>Specifically, the user should be able to use all of the following transformation on</li>

  </ol></li>

</ol>

the main object: translate, rotate, shear, scale, and reflect the main object.

<ol start="2">

 <li>All these transformations should be performed w.r.t the <strong>local frame of the main </strong></li>

</ol>

<strong>object.</strong>

<ol start="3">

 <li>(15 pts) The rest of the objects should be automatically moved in response to the movement of the main object or other objects around it.</li>

 <li>Examples: Following the main object, pushed away from the main object to keep</li>

</ol>

a certain distance from it, “bounced” when “colliding” with the main object, and

so on.

<ol start="2">

 <li>Each object must move separately. Do not move them identically so that they</li>

</ol>

overlap each other.

<ol start="4">

 <li>(15 pts) Use perspective projection. The camera should be able to be switched between two modes:

  <ol>

   <li>First-person view: Attach the camera to the main object just like FPS games. The camera should be translated &amp; rotated along with the main object. (You don’t neeed to draw a weapon!)</li>

   <li></li>

   <li>Quarter view: The main object is always the target of the camera. The camera</li>

  </ol></li>

</ol>

never rotate, meaning that it always do “panning” when the main object moves.

<ol start="3">

 <li></li>

</ol>

<ol start="5">

 <li>(15 pts) Use OpenGL lighting / shading.

  <ol>

   <li>Use different material colors for each object.</li>

   <li>Use 2 or more light sources. Among them, at least one light should be animated.</li>

   <li>You can use either flat shading or smooth shading for each object.</li>

   <li>If you use obj files, you can just use the normal vector data in the obj files for</li>

  </ol></li>

</ol>

shading.

<ol start="6">

 <li>Extra credit

  <ol>

   <li>(5 pts) Use an animating hierarchical model composed of multiple meshes as an</li>

  </ol></li>

</ol>

object, for all objects.

<ol start="2">

 <li>(5 pts) Use curves to express the movement of at least one object.</li>

 <li>(15 pts) Evaluation criteria 2 – <strong>Completeness</strong> – Overall evaluation of the degree of</li>

</ol>

completeness and difficulty of the program [Evaluated as excellent, moderate, or insufficient]




<ol start="2">

 <li>Report

  <ol>

   <li><strong>You can use either English or Korean for the report. </strong></li>

   <li><strong>Since the program and code will be checked based on the report, you will get 0 pts if </strong></li>

  </ol></li>

</ol>

<strong>you do not submit the report. </strong>

<ol>

 <li><strong>For the same reason, the requirement items that are implemented in the code but not </strong></li>

</ol>

<strong>listed in the report will be evaluated as “unsatisfied”. </strong>

<ol>

 <li><strong>Make sure to make a report using the report form (CG-FinalAssignment-</strong></li>

</ol>

<strong>ReportForm.docx) that is uploaded together with this assignment file.. </strong>E. What should be included:

<ol>

 <li><strong>Introduction to the program, a brief description of how to run it, and how to use </strong></li>

</ol>

<strong>it.</strong>

<ol start="2">

 <li><strong>Description of the implementation of each requirement</strong>

  <ol>

   <li>How you implemented that requirement.</li>

   <li>How TA can verify that the requirement has been implemented, by performing a</li>

  </ol></li>

</ol>

program’s specific feature.




<ol start="3">

 <li>Submission: A <strong>zip</strong> file of the following files. Submit the zip file within the submission deadline through the “Final Assignment” on the Blackboard Lecture Home..

  <ol>

   <li>A Python source file named <strong>py</strong>

    <ol>

     <li>If the program consists of several Python source files, the name of the file to be</li>

    </ol></li>

  </ol></li>

</ol>

executed must be main.py..

<ol>

 <li>A report file (<strong>docx</strong>)</li>

 <li><strong>Obj files (if used in your program).</strong> . Remember that obj file paths MUST be specified by a <strong>relative path, </strong>to be opened in the TA’s computer. Be sure to unzip the submission zip file to another directory and run the program before submitting it to see the program works. <strong>If the obj file fails to load, the assignment will be scored as 0 pts because the </strong></li>

</ol>

<strong>program’s functionality cannot be verified at all. </strong>

<ol>

 <li>The name of the zip file should be <strong>studentID-name.zip</strong></li>

</ol>




<ol start="4">

 <li><strong>Runtime Environment </strong>

  <ol start="3">

   <li><strong>Your program should be able to run on systems only with Python 3.7 or later, NumPy, </strong></li>

  </ol></li>

</ol>

<strong>PyOpenGL, glfw. Do not use any other additional python modules. </strong>

<ol>

 <li>Only <strong>glfw</strong> is allowed for event processing and window &amp; OpenGL context management. <strong>Do not use glut functions for this purpose.</strong></li>

 <li><strong>If your program does not meet this requirement, it will not run on TA’s computer </strong><strong>so </strong></li>

</ol>

<strong>you will not get any score for this assignment </strong>

<ol>

 <li><strong>If a run-time error occurs and interferes with the function check of the program, 0 points are given for the requirement that cannot be checked. </strong></li>

</ol>