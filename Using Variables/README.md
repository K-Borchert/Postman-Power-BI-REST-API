# Using Variables in Postman
<div id="badges">
  <a href="https://www.linkedin.com/in/k-borchert/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://www.youtube.com/channel/UC6nEaIKn3ffJG6otCqNSMlA">
    <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
  <a href="https://twitter.com/Mirrortears">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>
<br>
After we created a Token we don't want to put it everytime after refreshing it in the Authorization field, rigth? So we need to define a variable to use our dynamic Token in every Request.
<br>
<br>
<table>
  <tr>
    <th>Description</th>
    <th>Screenshot</th>
  </tr>
  
  <tr>
    <td>Useful Links to learn <br> about Variable in Postman</td>
    <td>https://www.youtube.com/watch?v=HHASdmCR1bE = Great video to practice using Variables<br>
    https://learning.postman.com/docs/sending-requests/variables/ = Postman Docs "Understanding Variables"<br>
    https://jsonpathfinder.com/ = To find the rigth value in you path</td>
 </td>

  <tr>
    <td>In this step we will learn how to turn our Authorization Token into a variable <br> First we need to go to our "Power BI GET User Token" request in Postman<br> and open the Tests section</td>
    <td><img width="639" alt="image" src="https://user-images.githubusercontent.com/63601923/182020270-865c85de-e3c1-4e3a-b43f-658cf620a64e.png"></td>
 </tr>
 
 <tr>
    <td>Next we put in the <a href="https://github.com/K-Borchert/Postman-Power-BI-REST-API/blob/main/Using%20Variables/Code%20for%20Tests%20in%20Postman">"Code for Tests in Postman"</a></td>
    <td><img width="207" alt="image" src="https://user-images.githubusercontent.com/63601923/182020684-f37a638e-8a36-4a39-947e-3fbf4dcb9e5a.png"></td>
 </tr>
 
  <tr>
    <td>If you like to prove If the Token is now a variable<br> you can look into the Environment Quick Look</td>
    <td><img width="718" alt="image" src="https://user-images.githubusercontent.com/63601923/182020504-128781b2-f447-40fe-9996-92e11b2bc6a3.png"></td>
 </tr>
 
   <tr>
    <td>The Line "console.log(value)" make <br>it possible to check your request headers in the console.<br> You can find the consol in the lower left corner</td>
    <td><img width="140" alt="image" src="https://user-images.githubusercontent.com/63601923/182020839-0579f03a-3b85-43dd-a901-f2ff57cfea24.png">
</td>
 </tr>
 
   <tr>
    <td>At last you can put in the Token variable in our "GET Workspace" request <br> in the Authorization section.<br> You can use variables if you us the {{}}</td>
    <td><img width="990" alt="image" src="https://user-images.githubusercontent.com/63601923/182021045-0ce87df4-ab02-47f3-b221-ccea5ded4e2c.png">
</td>
 </tr>
 
</table>
