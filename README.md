# Vision 360

## Why This Project?
<ul>
<li> During the COVID-19 Pandemic, examination process were forced to move in online form. </li>
<li> While online exams/proctoring had help in cost cutting and helped to reach applicants even in remote area, the one major issue regarding to this system is use of UNFAIR MEANS. </li>
<li> Main Goal: Develop a second feed camera system which could be combined with the already existing laptop webcam and minimize the blind spots which were vastly present with a single camera system.</li>
<li> Online exams which are less costly can thus be conducted instead of the offline exams in the future which can indeed save the money given to the Proctors/Invigilators. </li>
</ul>

## Overview
<ul>
  <li> Hardware: A headband is prototyped via 3D modelling on CREO. It was later 3D printed. Special mount was created to place the camera for a better view. Band is made such that it completed the need of a microphone and a speaker which is a necessity of the online examinations. </li>
<li> This device smartly detects and prevents cheating by using AI combined with 360 degrees view to check if there are some objectionable means in the environment of the examinee. </li>
<li> Software/ ML model: YOLOV4 or You Only Look Once, is a popular real-time object detection algorithm. It is helping us detect diff objects that can be present during the examination.</li>
<li> We have formulated a dataset of 1000 images having objects from 11 different classes here on which the training and testing of the model was done.</li>
<li> During deployment: The webam, micrphone, speaker is connected to the laptop of the examinee. Laptop now has 2 cameras' access. One camera would check only at the front for the authentication of the person. Other camera is mounted on the examinee's head which will check for the unfair means surrounding the examinee and both the cameras together provide complete 360 degree vision of the examinee's surroundings.</li>
</ul>

![4](https://user-images.githubusercontent.com/68558847/183279218-48d763cc-13cc-4abd-8a11-6dea7f65c7eb.png)

## Need Analysis
<ul>
  <li> 73% of students cheat during online exams.</li>
  <li> Survey conducted via the Google form filled by various Institutes' students: more than 75% percent feel that online examinations is more of cheating and less of knowledge but if they won't cheat then others will score more.</li>
  <li> Survey conducted amongst the Thapar University Faculty conclusion: Need of better proctoring to be able to minimise the malicious practices and make the system more efficient via integration of hardware and software technologies.</li>
  <li> From the surveys, we got some solutions like double camera feed, wide angle camera, increasing field of view and advance AI. </li>
</ul>

## Tech used
<ul>
<li>Software: Python, You Only Look Once (YOLO V4), Tensorflow, Google Colab, OPENCV, etc.</li>
<li>Hardware: 3D Modelling via CREO, Stress Analysis on CREO, 3D Printing, Samsung Earphones wth mic, Lenovo Camera, etc.</li>
</ul>

## Testing Phase
![2](https://user-images.githubusercontent.com/68558847/183279758-6d8c0e70-2842-43e1-8276-ea8cb5e6f67f.png)

![1](https://user-images.githubusercontent.com/68558847/183279696-db91da7c-df32-4270-9675-0ef21bb8bda7.png)


## Challenge
<ul>
<li> Earphones which was a necessity to be detected were not detected.</li>
<li> Detetction of the partially hidden objects was difficult.</li>
<li>It can be difficult to design comfortable-fitting headphones. Product design engineers must be able to create products that are comfortable for a large number of people while keeping manufacturing costs low.</li>
<li> The testing was done in a very simple environment. Predicted results could vary if the environmental conditions change such room brightness. This requires further examination.</li>
<li> Funding for the camera</li>
<li> Integration of mech and computer engineering tasks</li>
</ul>

## Conclusion
<ul>
<li> Resultant is a headband which will help in help mitigating use of unfair means by providing secondary view of the examinee's surroundings.</li>
</ul>






