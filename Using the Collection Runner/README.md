# In Progress

<div id="badges"  align="center">
  <a href="https://www.linkedin.com/in/k-borchert/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://www.youtube.com/channel/UC6nEaIKn3ffJG6otCqNSMlA">
    <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
  <a href="https://twitter.com/Mirrortears">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
    </a></div>
    <br>
    <br>
<div id="header" align="center">
  <img src="https://media.giphy.com/media/LHZyixOnHwDDy/giphy.gif" width="100"/>
</div>

## Why should we use Collection Runner?
The Collection Runner is perfect for automation processes. For example you need to add a specific Security Group into every new Workspace. Now you can use the Collection Runner to do that. In the first step you need the authentication process. After that you can grad with "Get Workspaces" every new Workspace with some filters. And at last you can use a Post request to push the Security Group into the new Workspaces. Of course you need to do some adjustments to my Demo here to archieve this but it will safe you a lot of time 😉


<br>

## How to?


<table>
  <tr>
    <th>Desciption</th>
    <th>Snapshot</th>
   </tr>
   
  <tr>
    <td> In the first step we need to create a new collection. We will call this new Collection "Collection Runner"</td>
      <td><img width="204" alt="image" src="https://user-images.githubusercontent.com/63601923/183253402-5faff8f8-9735-4952-9c3c-ea7b5d7331a0.png"><br>
      <img width="209" alt="image" src="https://user-images.githubusercontent.com/63601923/183253414-ee6dfff0-b114-461d-8510-f20b49c5e0f7.png"></td>
  </tr>
 
  <tr>
    <td> Next we create import our "Get User Token" and our "Get Workspaces" in our collection</td>
      <td><img width="260" alt="image" src="https://user-images.githubusercontent.com/63601923/183253492-55fb209f-c996-4f2c-a970-504573ad7b71.png"></td>      
  </tr>
   
  <tr>
    <td> Now we put the "Test Script" into the Test section of our "Get User Token" request.<br> This time I use an enviromental variable.<br> To create an environmental Variable you need to create a environment first.<br> To create an environment click the 3 icon on the left side bar.</td>
      <td> <img width="485" alt="image" src="https://user-images.githubusercontent.com/63601923/183253586-9ba27d71-8ab4-4a9b-bdcc-cc92b6c2e858.png">
      <br>
      <img width="72" alt="image" src="https://user-images.githubusercontent.com/63601923/183253718-4002ac54-cb13-4f0b-9a78-5280782128c1.png">
      <br>
      <img width="162" alt="image" src="https://user-images.githubusercontent.com/63601923/183253729-3c029250-6736-4feb-81b6-cd6b00f1dd43.png">
      </td>      
  </tr>
  
 <tr>
    <td> To see if the variable was retrieved correctly, click on the eye icon in the upper right corner. </td>
    <td> <img width="t503" alt="image" src=https://user-images.githubusercontent.com/63601923/183253919-6d99bae8-f757-4169-a5b0-b2f568bf4820.png> </td>      
  </tr>
  
  <tr>
    <td> If the variable retrieved correctly we can change the "Get Workspace" request.<br> I found out that If you like to use the Collection Runner you have to put the Token (in our case) we get from the "Get User Token" into the Body.<br> So let's put in the Token into our Body section. Click on "Body" and on "from-data".<br> Put in the KEY = Token and in Value= {{TOKEN}}</td>
      <td><img width="503" alt="image" src="https://user-images.githubusercontent.com/63601923/183254144-b139c556-94ac-493d-bcca-be61b93a35d7.png"></td>      
  </tr>
  
  <tr>
    <td> Next we can put another Code into our Test section into "Get Workspaces", for example we can grab the WorkspaceIDs.<b> And this Workspace ID we extract can be used in another request. And so on. </td>
      <td> <img width="282" alt="image" src="https://user-images.githubusercontent.com/63601923/183254262-e2f0a1c4-e1c8-4867-b1e8-0f6d8cfb82b1.png"></td>      
  </tr>
  
  <tr>
    <td> At least the best part. Check if you Collection runner works.<br> Click in the 3 dots beside the "Collection Runner" Name on the left side bar and choose "Run collection".</td>
      <td> <img width="216" alt="image" src="https://user-images.githubusercontent.com/63601923/183254317-c3534374-c626-4ba1-a07e-c31be20b573d.png"></td>      
  </tr>
  
 <tr>
    <td>Set Iteration on 1, Delay on 100ms, and the rest can be as it is.<br> If you are ready click "Run Collection Runner". You can check your result in the Consol below.</td>
      <td> <img width="1312" alt="image" src="https://user-images.githubusercontent.com/63601923/183254383-3f2245e9-2e06-4262-84ae-a4a8bffbef3a.png">
      <br>
      <img width="1312" alt="image" src=https://user-images.githubusercontent.com/63601923/183254591-251431b2-692d-4ec3-a335-d0e199b3e012.png></td>      
  </tr>
  </table>
  
