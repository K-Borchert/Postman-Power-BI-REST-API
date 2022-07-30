# Pre-requisites to use the Power BI REST API
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
</br>
<b>Tip 1: If you want to be have a own Sandbox to test this you can go to the Tip Folder and create your own environment</b><p>
<br>
Create Azure App (with permission for Power BI Service: like Dataset.read, Workspace.read<p>
Attention: You need an Admin to grant permissions!<p>
<br>
## How to?

<table>
  <tr>
    <th>Description</th>
    <th>Screenshot</th>
  </tr>
  
  <tr>
    <td>To create the App you can go to Azure Portal and searching for Apps (https://portal.azure.com/):</td>
    <td><img width="507" alt="image" src="https://user-images.githubusercontent.com/63601923/181196138-c4517680-c5e4-4c5f-b946-c367596816f3.png"></td>
 </td>

  <tr>
    <td>In the most companies the Apps are not restircted so you can creat it by yourself:</td>
    <td><img width="198" alt="image" src="https://user-images.githubusercontent.com/63601923/181196392-a0195f14-8d17-4fe5-bd2b-8f3879bb1eeb.png"></td>
 </td>
 
   <tr>
    <td>All you have to do is to register a new App</td>
    <td><img width="402" alt="image" src="https://user-images.githubusercontent.com/63601923/181196632-2f06a93a-2446-423c-81e7-a7cf31e64d58.png"></td>
   </td>
   
  <tr>
    <td>After creating you have to add some settings
1. Allow public client flows (switch toggel to yes)</td>
    <td><img width="760" alt="image" src="https://user-images.githubusercontent.com/63601923/181196782-cb471157-da52-4cea-afea-7204bebaa8cf.png"></td>
   </td>
 
   <tr>
    <td>2. Add some permissions, for example Workspace.read, Dataset.read</td>
    <td><img width="529" alt="image" src="https://user-images.githubusercontent.com/63601923/181197173-47dc2948-5cc3-4d63-9b53-e156e1ba8995.png">

<img width="140" alt="image" src="https://user-images.githubusercontent.com/63601923/181197229-85503d8b-e8e1-485f-9e85-bc2b2ce9cb45.png"><br>

<img width="601" alt="image" src="https://user-images.githubusercontent.com/63601923/181197279-b6ae5698-39c3-44b7-b9a1-c2ca81b61624.png"><br>

<img width="336" alt="image" src="https://user-images.githubusercontent.com/63601923/181197352-daf794b3-1c51-4f36-88d5-316f094c4827.png"><br>

<img width="300" alt="image" src="https://user-images.githubusercontent.com/63601923/181197440-56842609-d5f1-4dee-80c8-e94f76d4a4b3.png"><br></td>
   </td>
   
 <tr>
    <td>3. Important: the Amdin has to consent the permission!</td>
    <td><img width="670" alt="image" src="https://user-images.githubusercontent.com/63601923/181195779-410ee670-f19e-438b-922f-fb3d5cd8841c.png"></td>
   </td>
</table>
<br>

## Attention?
If your Admin don't want to give you the permission you can answer that you don't read any sensitive Data from Reports or User it's only a status check on the Power BI Tenant at one Moment. Sure If you gab the Data and store it in a Data lake or SQL Database you have a history but still no Data from Reports.

After you finished the Set-Up you can go to the next Folder "Authentication" to check how you can get your first Token in Postman.
