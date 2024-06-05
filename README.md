# FindYourProfessor：A Fluid Navigation Static web-page
By 2252551 Junyi Xu & 2151422 Zhiduo Wu

## 1. Web-page Introduction
This is an indoor navigation web-page of Jishi building in Tongji University specially designed for students of software engineering college, which provides the main functions including the floor guide of the Jishi Building and a quick overview of information (whole map, college faculty, and professors'profiles etc.)
## 2. Specific design
### 2.1 The home page
**1. intro section**
The first section provides an introduction of the web-page and tips on how to use them. 
![](/report/image.png)
Specifically, by clicking the **LAB**/**CLASSROOM**/**MEETINGROOM**/**OFFICE** on the right above part, users can jump to the corresponding section to see specific information about this kind of room such as which rooms fall into this kind.
![](/report/7a41daef59352c29e21399ee930d0ac.png)
**2. search section**
The second section provides a search engine and a selection box for users. Users can select their professors and directly jump into her/his room page. Alternatively, they can input the professor's name or the specific room number and then jump to the corresponding page.
![](/report/image-1.png)
![](/report/image-2.png)
**3. map section**
The third section provides an overview of all the rooms in the Jishi Building where the School of Software is located. Users can click on **red pin** of the corresponding room on the map in the guide interface. Once you have found a room, you can click on it jump to the corresponding room page and to get a brief description of the current location, including the location, opening hours, and contact phone number, etc. 
![](/report/image-3.png)
**4. Room section**
The fourth section provides an overview of all the rooms in different types. We designed four parts which basically covers all kinds of rooms in the fourth floor. Here we designed a small animation, when the mouse is hovering above a certain room, the picture would bouce a bit and indicate you to click on it and jump to the specific page. 
![](/report/image-4.png)
![](/report/image-5.png)
![](/report/image-6.png)
![](/report/image-7.png)
**4. Professors section**
The fifth section provides an overview of some of the professors in software engineering college. Here we designed a small trick, if the user clicks on the mail pattern below every professor then they would jump to the specific profile page of the professor in SSE.
![](/report/image-8.png)
### 2.2 The room page
Every room has a exclusive page including a **GO HOME** button which can lead users back to the home page. In the room page, we provide the specific information about which professors are here and ways to contact them.The pictures are real and up-to-date since they were taken by us in this Monday.
![](/report/image-9.png)
![](/report/image-10.png)
## 3. Presentation
![](/report/1.gif)
## 4. Usage
By downloading the zip file and open it inside VScode or Pycharm, and *Go live* for the **index.html**, you can start this web-page with the home page.
## 5.Fluid Navigation principle description
1. Provide context-aware navigation: By displaying the floor plan of Jishi Building on the homepage and displaying pictures of each room on subsequent pages, users can clearly understand the positional relationship between the rooms.
2. Provide a variety of navigation methods: Users can click on the room icon on the floor plan, enter keywords through the search box, or click on each room image on the homepage to quickly find the room or person they need in various ways.
3. Support users to explore and review: The webpage provides maps, images, and settings buttons, allowing users to return to the homepage and view other rooms at any time. At the same time, the detailed information page displays a list of people in the room, making it convenient for users to view. At the end of the webpage, some photos and personal information pages of college teachers are also displayed for users to refer to.
4. Keep the interface clear: By integrating map icons, room images, settings icons, and search boxes on the homepage, users can clearly view all rooms. In the room detail card, only display information related to the room to avoid distractions.
5. Provide feedback: When the user clicks on the room icon, image or search box, selection box search (not yet implemented), the page will immediately jump to the corresponding room detailed information card. In addition, when the user clicks on the room type, the page will automatically slide to the corresponding room type image. The user clicking on the teacher's email icon will redirect to the teacher's personal information homepage, and clicking on the author's email at the end of the page will automatically redirect to the email address, and so on.
6. Keeping the interface consistent: The top and bottom navigation bars and detail room card are essentially the same and have clear guidelines in the design diagram above. The goal is to ensure that the layout, naming, and appearance of the navigation bars are consistent throughout the application or in order to provide a uniform, clear and unambiguous user experience.

   
With the above design solution and the principle of fluid navigation, we can provide users with a simple and efficient webpage for guiding the 4th floor of the Jishi Building. users can easily visit each room in the webpage and understand the room usage and personnel.
