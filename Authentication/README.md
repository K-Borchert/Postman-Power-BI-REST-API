First we need a methode to authenticate us against the Power BI Service, the easiest methode for the first time is to use the rigths as Power BI Admin. If your no Power BI Admin it's no problem there are also queries which can be send from "normal" Users.
So let's take the code snippiet GET Admin Token and import it into Postman. 
You have to options:

<img width="299" alt="image" src="https://user-images.githubusercontent.com/63601923/181076141-3df28e18-e3cb-4ceb-9780-199798f51c34.png">

1. Download the File and Import it
<img width="489" alt="image" src="https://user-images.githubusercontent.com/63601923/181076184-1d9677d8-3afe-45b3-a489-8a724ebd4bda.png">

2. Copy the Code and fill it into the RAW text
<img width="632" alt="image" src="https://user-images.githubusercontent.com/63601923/181076237-1a882b13-7197-42c8-b514-b04a06044b59.png">

In both cases you get this navigation frame next

<img width="631" alt="image" src="https://user-images.githubusercontent.com/63601923/181076384-7788550c-063d-495d-8c8f-8ca5cd925739.png">

Click on Import to import the file into Postman

Now you should have a new entry on the left side

<img width="227" alt="image" src="https://user-images.githubusercontent.com/63601923/181076610-d49f4dda-973d-4fe0-96f7-f9f8881375e3.png">

Open the folder and click in the first row

<img width="224" alt="image" src="https://user-images.githubusercontent.com/63601923/181076730-0dcd351d-db2c-458f-a3c6-e9377b2a6ec3.png">

Now you should be able to see a frame in the middle

<img width="929" alt="image" src="https://user-images.githubusercontent.com/63601923/181077289-8bad74ac-b5ac-4269-9ce5-ed5612d4a714.png">

Click on body to fill in the needed Information to access the Power BI Service with the REAT API

<img width="928" alt="image" src="https://user-images.githubusercontent.com/63601923/181077479-1f5f1c1c-f16c-4168-b546-3e3b32ff8fd8.png">

These information you need to fill out:

<img width="524" alt="image" src="https://user-images.githubusercontent.com/63601923/181199056-6d232b55-7022-4cfe-8ed1-9219b815bbd9.png">
<img width="398" alt="image" src="https://user-images.githubusercontent.com/63601923/181199886-f5f6fbce-6d0f-4aa7-b49b-4075f6b74be8.png">


The Client ID you can get from your App you have created befor (see Folder: Prerequisites)

<img width="734" alt="image" src="https://user-images.githubusercontent.com/63601923/181199612-dc87a567-4035-48b0-ad49-c0c229f1e799.png">


The Tenant ID you can find in the Azure Portal in the Azure Active Directory (https://portal.azure.com/)

<img width="211" alt="image" src="https://user-images.githubusercontent.com/63601923/181200487-4c2a8d7d-ba7b-4379-bad3-b926cd2b50d0.png">


<img width="659" alt="image" src="https://user-images.githubusercontent.com/63601923/181200335-950debe4-c035-4117-8a7e-51f3f8660d72.png">

Now your should be able to fill out the response

<img width="880" alt="image" src="https://user-images.githubusercontent.com/63601923/181201351-019c3edf-00df-4a54-bd2b-2e3a0707f37f.png">


Positive response & Token

<img width="217" alt="image" src="https://user-images.githubusercontent.com/63601923/181195931-0e48eb30-a21e-452c-a5f8-8f3b81ad4182.png">
