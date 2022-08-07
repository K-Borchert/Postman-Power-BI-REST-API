# POST requests (in Progress)

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
<div id="header" align="center">
  <img src="https://media.giphy.com/media/LHZyixOnHwDDy/giphy.gif" width="100"/>
</div>

<br>
In this section we will learn how to use a POST request and for what you can use a POST request.
⚠️ For this request you need to be Power BI Admin or Global Admin!

<br>

## How to?

<table>
  <tr>
    <th>Description  </th>
    <th>Screenshot</th>

  </tr>
  <tr>
    <td>As before you have two possibilities to do this:<br>
    1. Download File and Import as File<br>
    2. Copy code and fill it into RAW Text </td>
    <td> <img width="403" alt="image" src="https://user-images.githubusercontent.com/63601923/181204322-01e5382b-7c55-411f-9299-ef7445fb070f.png"> </td>
  </tr>
  
<tr>
    <td>In both cases you have to approve the Import</td>
    <td> <img width="627" alt="image" src="https://user-images.githubusercontent.com/63601923/183297925-7d9b4334-516a-4f5b-8d51-967e2921d50a.png"> </td>
</tr>

<tr>
    <td> After you imported the file you get a new Collection on the left site </td>
    <td> <img width="381" alt="image" src="https://user-images.githubusercontent.com/63601923/183297945-f106e858-f56e-427d-be01-5d092f401500.png"> </td>
</tr>
  
<tr>
    <td> Now you can add the  {{TOKEN}} variable to the authorization section (see "Using variables") </td>
    <td> <img width="700" alt="image" src="https://user-images.githubusercontent.com/63601923/183298017-205210a4-06ef-4729-a0c6-8bfc83af477a.png"> </td>
</tr>
  
<tr>
    <td> Next go to the body section and put in the Permission (Admin, Contributor, Member, Viewer) <br> and the EMail adress of the new User </td>
    <td> <img width="309" alt="image" src="https://user-images.githubusercontent.com/63601923/183299975-b57b58f6-85b5-431f-ae55-ccbb4716e30b.png"> </td>
</tr>
  
<tr>
    <td>At last fill out the WorkspaceID you want to put in the new user in the request line above the body </td>
    <td> <img width="458" alt="image" src="https://user-images.githubusercontent.com/63601923/183298165-822d2e9a-1d6a-404e-a00a-c1593a782db9.png"> </td>
</tr>
  
<tr>
    <td>Now you can check If you request works. <br> Before you send the request refresh your Token! <br> If your request is successful the user will appear in the Workspace you choose.<br> You can check it directly in Power BI Service or send another request to pull all users in the Workspace </td>
    <td> <img width="458" alt="image" src="https://user-images.githubusercontent.com/63601923/183298839-a0da1f62-1222-4ae7-86d1-d311b6407492.png">
      <br>
      <br>
      <img width="417" alt="image" src="https://user-images.githubusercontent.com/63601923/183298893-c2bc7732-3a64-4258-8c68-67c1a13bd75c.png"> </td>
</tr>
  
</table>
