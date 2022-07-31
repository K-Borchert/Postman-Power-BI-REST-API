# Authentication

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
<br>
<p><img src='https://user-images.githubusercontent.com/63601923/182024778-7f6835f0-6a27-4b2b-aef9-fc6268f603bb.gif' alt="Image" height="520" width="780"></p>
<br>
</br>
First we need a methode to authenticate us against the Power BI Service, the easiest methode for the first time is to use the rigths as Power BI Admin. If your no Power BI Admin it's no problem there are also queries which can be send from "normal" Users.
So let's take the code snippiet GET Admin Token and import it into Postman. 

## How to:

<table>
  <tr>
    <th>Description  </th>
    <th>Screenshoot</th>

  </tr>
  <tr>
    <td>You have to options </td>
    <td><img width="299" alt="image" src="https://user-images.githubusercontent.com/63601923/181076141-3df28e18-e3cb-4ceb-9780-199798f51c34.png"></td>
  </tr>
  <tr>
    <td>1.Download the File and Import it</td>
    <td><img width="489" alt="image" src="https://user-images.githubusercontent.com/63601923/181076184-1d9677d8-3afe-45b3-a489-8a724ebd4bda.png"></td>
  </tr>
    <tr>
    <td>2. Copy the Code and fill it into the RAW text </td>
    <td><img width="632" alt="image" src="https://user-images.githubusercontent.com/63601923/181076237-1a882b13-7197-42c8-b514-b04a06044b59.png"></td>
  </tr>
     <tr>
    <td>In both cases you get this navigation frame next </td>
    <td><img width="631" alt="image" src="https://user-images.githubusercontent.com/63601923/181076384-7788550c-063d-495d-8c8f-8ca5cd925739.png"></td>
  </tr>
   <tr>
    <td>Click on Import to import the file into Postman. Now you should have a new entry on the left side</td>
    <td><img width="227" alt="image" src="https://user-images.githubusercontent.com/63601923/181076610-d49f4dda-973d-4fe0-96f7-f9f8881375e3.png"></td>
  </tr>
   <tr>
    <td>Open the folder and click in the first row</td>
    <td><img width="224" alt="image" src="https://user-images.githubusercontent.com/63601923/181076730-0dcd351d-db2c-458f-a3c6-e9377b2a6ec3.png"></td>
  </tr>
     <tr>
    <td>Now you should be able to see a frame in the middle</td>
    <td><img width="929" alt="image" src="https://user-images.githubusercontent.com/63601923/181077289-8bad74ac-b5ac-4269-9ce5-ed5612d4a714.png">
</td>
     <tr>
    <td>Click on body to fill in the needed Information to access the Power BI Service with the REST API</td>
    <td><img width="928" alt="image" src="https://user-images.githubusercontent.com/63601923/181077479-1f5f1c1c-f16c-4168-b546-3e3b32ff8fd8.png">
</td>
  <tr>
    <td>These information you need to fill out:</td>
    <td><img width="524" alt="image" src="https://user-images.githubusercontent.com/63601923/181199056-6d232b55-7022-4cfe-8ed1-9219b815bbd9.png"><br>
<img width="398" alt="image" src="https://user-images.githubusercontent.com/63601923/181199886-f5f6fbce-6d0f-4aa7-b49b-4075f6b74be8.png">
</td>
  <tr>
    <td>The Client ID you can get from your App you have created befor (see Folder: Prerequisites)</td>
    <td><img width="734" alt="image" src="https://user-images.githubusercontent.com/63601923/181199612-dc87a567-4035-48b0-ad49-c0c229f1e799.png">
</td>
  <tr>
    <td>The Tenant ID you can find in the Azure Portal in the Azure Active Directory (https://portal.azure.com/)</td>
    <td><img width="211" alt="image" src="https://user-images.githubusercontent.com/63601923/181200487-4c2a8d7d-ba7b-4379-bad3-b926cd2b50d0.png"><br><img width="659" alt="image" src="https://user-images.githubusercontent.com/63601923/181200335-950debe4-c035-4117-8a7e-51f3f8660d72.png">
</td>
 <tr>
    <td>Now your should be able to fill out the response</td>
    <td><img width="880" alt="image" src="https://user-images.githubusercontent.com/63601923/181201351-019c3edf-00df-4a54-bd2b-2e3a0707f37f.png">
</td>
 <tr>
    <td>Positive response & Token</td>
    <td><img width="1180" alt="image" src="https://user-images.githubusercontent.com/63601923/181201574-d6cda3bc-726d-41f7-a86f-f62adb2a7a64.png">
</td>
</table>
