# PLANTOPIA
## PROGRAMMING 3D – PROG 7314
## PART 2: README FILE
## TEAM LEAD: Bela Premchund – ST10257468

## CONTENTS:
- Our App
- Members
- Requirements (libs.versions.toml File)
- GitHub Link
- Video link
- Developer Information
- Design Considerations
- Utilisation of GitHub and GitHub Actions
- AI Declaration
- References


## OUR APP:
     
<img width="308" height="683" alt="image" src="https://github.com/user-attachments/assets/6fadd3a9-308d-4014-adfd-a94039ace714" />
<img width="307" height="682" alt="image" src="https://github.com/user-attachments/assets/0ce2b1ac-c7ef-487a-bd26-35b4c4ac50fe" />
<img width="306" height="681" alt="image" src="https://github.com/user-attachments/assets/cc1381bc-1374-4803-8d75-e810571c7eb5" />

Plantopia is designed to be users’ plant buddy. It will allow the user to scan any plant, and they will be provided with the name, Latin name, a description of the plant, and the place of origin. Users would also be able to save these plants to their personal page called ‘My Plants.’ 
They would then be able to create custom reminders for taking care of their plant. Whether it is to water it or to repot it, users would be able to tailor their reminders to the plant.
Users can find any information about any plant they are curious about, through our encyclopaedia. This will allow users to expand their knowledge and feed into their passion. 


<img width="310" height="688" alt="image" src="https://github.com/user-attachments/assets/93cac838-d998-4677-bf2f-a465d2301dea" />
<img width="305" height="678" alt="image" src="https://github.com/user-attachments/assets/6d3ed1de-94a1-40b6-ad05-9f946f7ff9c8" />
<img width="307" height="681" alt="image" src="https://github.com/user-attachments/assets/a056a0d6-9eea-409d-a8a3-12766b2a0c38" />

All user information is protected by a password as users would need to register and login with their own email addresses and passwords. 
Users will also be able to sign in using their Google accounts (SSO).

<img width="352" height="781" alt="image" src="https://github.com/user-attachments/assets/0bef2cce-a38d-4849-af9c-71fb82bd908b" />

Users have the option to change the theme of their app from dark to light. They would also be able to change their account details such as their password. 

When a user logs out, they will be redirected to the welcome page. 

## MEMBERS:
Bela Premchund – ST10257468

Altaf Ally – ST10254661

Ahmed Gangat – ST10247416

Sohum Singh - ST10257909



## REQUIREMENTS:
In order to run this code, users need to have Android Studio, between version: Meerkat 2024.3.1 to Narwhal 2025.1.3
The following is the code for the libs.versions.toml File:
```bash
[versions]
agp = "8.13.0"
kotlin = "2.0.21"
coreKtx = "1.17.0"
junit = "4.13.2"
junitVersion = "1.3.0"
espressoCore = "3.7.0"
lifecycleRuntimeKtx = "2.9.4"
activityCompose = "1.8.0"
composeBom = "2024.09.00"
appcompat = "1.7.1"
constraintlayout = "2.2.1"
recyclerview = "1.4.0"
coordinatorlayout = "1.3.0"
material = "1.13.0"
roomCommonJvm = "2.8.3"
workRuntimeKtx = "2.11.0"

[libraries]
androidx-core-ktx = { group = "androidx.core", name = "core-ktx", version.ref = "coreKtx" }
junit = { group = "junit", name = "junit", version.ref = "junit" }
androidx-junit = { group = "androidx.test.ext", name = "junit", version.ref = "junitVersion" }
androidx-espresso-core = { group = "androidx.test.espresso", name = "espresso-core", version.ref = "espressoCore" }
androidx-lifecycle-runtime-ktx = { group = "androidx.lifecycle", name = "lifecycle-runtime-ktx", version.ref = "lifecycleRuntimeKtx" }
androidx-activity-compose = { group = "androidx.activity", name = "activity-compose", version.ref = "activityCompose" }
androidx-compose-bom = { group = "androidx.compose", name = "compose-bom", version.ref = "composeBom" }
androidx-compose-ui = { group = "androidx.compose.ui", name = "ui" }
androidx-compose-ui-graphics = { group = "androidx.compose.ui", name = "ui-graphics" }
androidx-compose-ui-tooling = { group = "androidx.compose.ui", name = "ui-tooling" }
androidx-compose-ui-tooling-preview = { group = "androidx.compose.ui", name = "ui-tooling-preview" }
androidx-compose-ui-test-manifest = { group = "androidx.compose.ui", name = "ui-test-manifest" }
androidx-compose-ui-test-junit4 = { group = "androidx.compose.ui", name = "ui-test-junit4" }
androidx-compose-material3 = { group = "androidx.compose.material3", name = "material3" }
androidx-appcompat = { group = "androidx.appcompat", name = "appcompat", version.ref = "appcompat" }
androidx-constraintlayout = { group = "androidx.constraintlayout", name = "constraintlayout", version.ref = "constraintlayout" }
androidx-recyclerview = { group = "androidx.recyclerview", name = "recyclerview", version.ref = "recyclerview" }
androidx-coordinatorlayout = { group = "androidx.coordinatorlayout", name = "coordinatorlayout", version.ref = "coordinatorlayout" }
material = { group = "com.google.android.material", name = "material", version.ref = "material" }
androidx-room-common-jvm = { group = "androidx.room", name = "room-common-jvm", version.ref = "roomCommonJvm" }
androidx-work-runtime-ktx = { group = "androidx.work", name = "work-runtime-ktx", version.ref = "workRuntimeKtx" }

[plugins]
android-application = { id = "com.android.application", version.ref = "agp" }
kotlin-android = { id = "org.jetbrains.kotlin.android", version.ref = "kotlin" }
kotlin-compose = { id = "org.jetbrains.kotlin.plugin.compose", version.ref = "kotlin" }


```



## GITHUB LINK:
Bela Premchund (main link with collaborators): https://github.com/VCWVL/prog7314-poe-ST10257468.git 

Altaf Ally: https://github.com/VCWVL/prog7314-poe-Altaf-Ally.git 

Ahmed Gangat: https://github.com/VCWVL/prog7314-poe-AhmedGangat.git 

Sohum Singh: https://github.com/VCWVL/prog7314-poe-Sohum-Singh.git




## VIDEO LINK:

[[Video Link](https://drive.google.com/drive/folders/11L25VLMBt4dvp2LUn5Ofe9YjsGrpgM8G) ](https://drive.google.com/drive/folders/1eXmf0MT_DTSh4hcO5x0ABtdS1Abe8x7x)



## DEVELOPER INFORMATION:
Developer: Altaf Ally 

Student Number: ST10254661

Contact: ST10254661@vcconnect.edu.za 




## UTILISATION OF GITHUB AND GITHUB ACTIONS:
 <img width="940" height="499" alt="image" src="https://github.com/user-attachments/assets/8d4376b7-2a0f-4d29-a004-1df23d79c2c5" />

The image above shows that we posted the code to the app and the API to our GitHub repository. There are over 15 commits, showing what and why we changed the code. 

 <img width="940" height="498" alt="image" src="https://github.com/user-attachments/assets/647224b1-42fe-459d-a925-25469349b3f1" />

With the use of GitHub Actions, we were able to create a new workflow that allowed us to test our app. This test runs each time a new commit is made. This ensures that the app will run on any platform. 




## AI-DECLARATION:
ChatGPT, 2025. Change frame transparency. [Online] 
Available at: https://chatgpt.com/c/68e43a5a-e444-8333-8255-ed693bf4583e 
[Accessed 6 October 2025].

ChatGPT, 2025. Fix Gradle error. [Online]
Available at: https://chatgpt.com/c/691b77b4-0eec-8326-8f38-4774a7b85188
[Accessed 17 October 2025]

We did use ChatGPT in this assignment to assist with the UI. When we coded the UI in Android Studio, you could see the ‘hint’ text on the register and login pages. When we ran the app from our phones, the ‘hint prompts’ were not visible.
The solution was to hardcore the colour of the text to ensure that is visible on any phone. We used ChatGPT to help us get the colour code for the hint text.
This can be seen in the images below:

<img width="940" height="731" alt="image" src="https://github.com/user-attachments/assets/496129fb-9d36-4da0-967f-3de13362e2a9" />

One of the content fixes included this line on code: tools:ignore=”HardcodedText.”  I asked ChatGPT for more details about this.


<img width="800" height="616" alt="image" src="https://github.com/user-attachments/assets/5515acb6-d962-402a-b218-e36cc49c0168" />

Here we asked ChatGPT for a plausible reason for our error.


<img width="793" height="624" alt="image" src="https://github.com/user-attachments/assets/90c6ff2b-8cc8-4c92-ba72-5251e0285ea7" />

Here we asked ChatGPT for the colour code so we could hardcode the colour into the pages. 

We also used it to fix the errors in the gradle and other files in order for the signed APK to be created.
<img width="1364" height="724" alt="image" src="https://github.com/user-attachments/assets/b4abfcbb-700e-4544-afb5-982e06df6c32" />


## REFERENCES:
- ChatGPT, 2025. Change frame transparency. [Online] 
Available at: https://chatgpt.com/c/68e43a5a-e444-8333-8255-ed693bf4583e
[Accessed 6 October 2025].

- ChatGPT, 2025. Fix Gradle error. [Online]
Available at: https://chatgpt.com/c/691b77b4-0eec-8326-8f38-4774a7b85188
[Accessed 17 October 2025]

- Cocca, G., 2023. The REST API Handbook – How to Build, Test, Consume, and Document REST APIs. [Online] 
Available at: https://www.freecodecamp.org/news/build-consume-and-document-a-rest-api/
[Accessed 4 October 2025].

- Fireship, 2021. RESTful APIs in 100 Seconds // Build an API from Scratch with Node.js Express. [Online] 
Available at: https://www.youtube.com/watch?v=-MTSQjw5DrM
[Accessed 2 October 2025].

- Lackner, P., 2021. How to Build a Simple REST API With Ktor + Android App. [Online] 
Available at: https://www.youtube.com/watch?v=c6I3Dw0xDlQ
[Accessed 4 October 2025].

- OpenWeatherMap, 2024. Weather API Documentation. [Online] 
Available at: https://openweathermap.org/api
[Accessed 3 October 2025].

- Plant.id, 2024. Plant Identification API Documentation. [Online] 
Available at: https://web.plant.id/documentation
[Accessed 3 October 2025].

- Trefle API, 2024. Trefle Plant Data API. [Online] 
Available at: https://trefle.io/
[Accessed 3 October 2025].



