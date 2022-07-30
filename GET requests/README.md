# GET requests

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
<table>
  <tr>
    <th>Request</th>
    <th>Code Link</th>
    <th> Description - How to?</th>

  </tr>
  <tr>
    <td>GET Workspaces as User</td>
      <td><a href="https://github.com/K-Borchert/Postman-Power-BI-REST-API/blob/main/GET%20requests/GET%20Workspace%20as%20User">Code</a></td>
    <td><a href="https://github.com/K-Borchert/Postman-Power-BI-REST-API/edit/main/GET%20requests/README.md#get-request-get-workspaces-as-user">How to?</a></td>
  </tr>
  
  <tr>
    <td>GET Workspaces as User (with filter on Premium Capacity</td>
    <td><a href="https://github.com/K-Borchert/Postman-Power-BI-REST-API/blob/main/GET%20requests/GET%20Workspaces%20as%20User%20(with%20filter%20on%20Premium%20Capacity)">Code</a></td>
    <td><a href="https://github.com/K-Borchert/Postman-Power-BI-REST-API/blob/main/GET%20requests/README.md#get-workspaces-as-user-with-filter-in-premium-capacity">How to?</a></td>
</tr>
</table>
<br>
</br>

# GET request (GET Workspaces as User)
To create your first GET request you need to Import the <b>GET Workspaces</b> File.<p>

## How to:

<table>
  <tr>
    <th>Description  </th>
    <th>Screenshoot</th>

  </tr>
  <tr>
    <td>As before you have two possibilities to do this:<br>
    1. Download File and Import as File<br>
    2. Copy code and fill it into RAW Text</td>
    <td><img width="403" alt="image" src="https://user-images.githubusercontent.com/63601923/181204322-01e5382b-7c55-411f-9299-ef7445fb070f.png"></td>
  </tr>
  
  <tr>
    <td>In both cases you have to approve the Import</td>
    <td><img width="630" alt="image" src="https://user-images.githubusercontent.com/63601923/181204510-7ed2182f-fabd-4d71-ab68-eba5a3a4847e.png"></td>
</tr>

  <tr>
    <td>After this you get a new Collection the left site</td>
    <td><img width="223" alt="image" src="https://user-images.githubusercontent.com/63601923/181204653-1e9af7b9-081c-4374-a075-e12ce424be75.png"></td>
</tr>

  <tr>
    <td>Open the folder and click on the request, now you have to put in your TOKEN which you generated before (Folder: Authentication) only the Token without ""</td>
    <td><img width="785" alt="image" src="https://user-images.githubusercontent.com/63601923/181204935-509d342c-5f2a-41a1-b5df-391fddd6c5ac.png"><p></td>
</tr>

  <tr>
    <td>After you put in the Token you can send the request, If you set all permissions from the Folder: Authentication and if the permsionss are granted from the
Admin you should be able to get back your first request</td>
    <td><img width="991" alt="image" src="https://user-images.githubusercontent.com/63601923/181205868-2b213f90-6761-4dad-b215-fa7623dceca8.png"><p></td>
</tr>

</table>
<br>
</br>

# GET Workspaces as User (with filter in Premium Capacity)
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

If you now want to add a filter for example in our case in Premmium Capacity you can do this very easy.</b> File.<p>

## How to:

<table>
  <tr>
    <th>Description  </th>
    <th>Screenshoot</th>
  </tr>
  
  <tr>
    <td>Follow the Instruction on "GET Workspace as User" but with the File "Get Workspace as User (with filter on Premium Capacity)</td>
    <td><img width="788" alt="image" src="https://user-images.githubusercontent.com/63601923/181906218-53bcd712-90e1-4fa8-9117-c10e6c026871.png"></td>
  </tr>
  
 <tr>
    <td>After Importing the new file above you will find an extra Parameter in your request</td>
    <td><img width="893" alt="image" src="https://user-images.githubusercontent.com/63601923/181906341-d7cc5ccd-99e7-496c-bf7a-6aaed70f362f.png"></td>
 </tr>  
  
 <tr>
    <td>With this Parameter it will be possible to read out all Workspaces in a Premium Capacity. You can test it directly after putting in the TOKEN in the Authroization Area</td>
    <td><img width="781" alt="image" src="https://user-images.githubusercontent.com/63601923/181906390-0db039c2-6164-4755-8b76-0e6d3edc0aa9.png"><br>
      <img width="801" alt="image" src="https://user-images.githubusercontent.com/63601923/181906434-d462992b-9307-44bc-9b1f-10453b5fa312.png"></td>      
</tr>
    </table>
  
