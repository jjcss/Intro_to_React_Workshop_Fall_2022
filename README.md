
<!-- # Intro to React -->

<img src="https://i.imgur.com/JybZuXd.png" alt="drawing" width="100"/> <img src="https://i.imgur.com/Bzkqs5I.png" alt="drawing" width="100"/>

# Computer Science Society Club

## Table of Contents
- [Tip Calculator App](#Tip-Calculator-App)
- [Pre Requisites](#Pre-Requisites)
- [React Demo](#React-Demo)
- [Continue Learning About React](#Continue-Learning-About-React)

# Intro to React Workshop 

**Date:** Tuesday, November 22nd, 2022 <br>
**Description**: In this workshop You will learn the basics of **React**. You will get an introduction into the ever evolving programming language React. This meeting will also be our **last meeting of the semester**, where we’ll recap all events and new club members. . For more information on React and other resources talked about during the meeting please continue looking below for all resources and **coding demo** steps. <br>
**Workshop Zoom Recording**: [TBD]() <br>
**Workshop Google Slides**: [TBD]() <br>

---


## Tip Calculator App

**Description**: We will be building a simple one screen Tip Calculator application in Xcode using the power of Swift.
**App Features**: 
- The User will be able to add in an original amount. Let's say the user enters an amount of **$50.00**. After a user enters an amount, they will be able to choose the **tip percentage** that they'd like to calculate an amount for. The three tip choices that they will have is **15%, 20%, and 25%**. Based on a choice, our application will calculate the new total amount with the tip percentate. Let's say the user picks **20%** as the tip percentage. Our application will display the new total amount, with the initial price of $100 + 25% tip, which should be **$120**.
- We will add images to our application (specifically the CSS Club's logo). These images, will be on our **main application screen, the loading screen of our app, and as an icon of our app**.
- We will also stylize our application.

<details>
<summary>Full application gif</summary>
<br>
<img src="https://i.imgur.com/7uDn8uR.gif" alt="drawing" width="150" height="300"/> 
</details>

<details>
<summary>App logo on Loading Screen and App Icon</summary>
<br>
<img src="https://i.imgur.com/bOBa7zR.gif" alt="drawing" width="150" height="300"/> 
</details>

---

## Pre Requisites
- [ ] **Download & Install React**: 
    - [ ] Make sure you have [React](https://developer.apple.com/xcode/) downloaded and installed.
        - Step 1:
            - Head over to the [Node JS website](https://nodejs.org/en/) and downloaded the latest version of React. We recommend you download the `Recommended for most users` version.
                <details>
                    <summary>Example</summary>
                    <img src="https://i.imgur.com/wa6kNWy.png" alt="drawing" width="400" height="200"/>
                </details>
        - Step 2:
            - Located the downloaded packages and open it up. Click continue to install all necessary packeges onto your system. You might get asked to enter your username and password. That's totally fine.
        - Step 3:
            - Once you've downloaded Node & React, let's open up our terminal.
                <details>
                        <summary>Example</summary>
                        <img src="https://i.imgur.com/MX165d1.png" alt="drawing" width="400" height="200"/>
                </details>
        - Step 4:
            - Once in your terminal, let's enter in the command `node -v`. This command, if you've installed everything succesfully, will display the current version of Node that you've just downloaded.
                <details>
                            <summary>Example</summary>
                            <img src="https://i.imgur.com/QH9Phfp.png" alt="drawing" width="500" height="200"/>
                </details>
            - Next, enter in the command `npm -v`. If you installed everything correctly, you'll get the version of npm on your terminal.
                <details>
                            <summary>Example</summary>
                            <img src="https://i.imgur.com/seOiEiG.png" alt="drawing" width="500" height="200"/>
                </details>
        - Step 5:
            - Once you have checked that everything was installed properly, it is now time to create our first React project. To do this, enter the command `npx create-react-app enter-any-name-here`. One you get an output saying "Happy Hacking" in your terminal, this means you've successfully installed React, and created your first project. 
            - > Note: Every time you want to create a new React project, you would just need to enter in the command above to your terminal.
            - > Note: Depending on your system, the installation of React may take a long time. Take this into account when installing.
                <details>
                            <summary>Example</summary>
                            <img src="https://i.imgur.com/ySZcvYX.png" alt="drawing" width="500" height="200"/>
                </details>
        - Step 6:
            - You've succefully installed React and created your project! Now, let's see how we can access our project. In order to begin coding, you will need to cd into the project that you just created. Since I named my project `enter-any-name-here`, I will type in the following command to cd into this project, `cd enter-any-name-here`.
            - > Note: this step is required because in the next step we will be "turning on" our React project. 
                <details>
                            <summary>Example</summary>
                            <img src="https://i.imgur.com/nZIRCPQ.png" alt="drawing" width="500" height="400"/>
                </details>
        - Step 7:
            - Now, in order to get your React project up and running, you will need to type in the command `npm start` in your terminal. This will run your React project on your terminal and on a new browser. If you see the outputs like the screenshots below, then you've done all the steps correclty.
            - > Note: On the browser that opens up when you enter in the command above, that is the inital code that all React projects start with.
                <details>
                            <summary>Terminal Example</summary>
                            <img src="https://i.imgur.com/O72bfsy.png" alt="drawing" width="500" height="200"/>
                </details>
                <details>
                            <summary>Browser Example</summary>
                            <img src="https://i.imgur.com/TOMxHV5.png" alt="drawing" width="500" height="300"/>
                </details>
        - Step 8:
            - Finally, in order to begin coding, you will need to open up your React project on a Coding Editor. We highly recommend you use and download [Visual Studio Code](https://code.visualstudio.com/download) as a coding editor. Once you selected a coding editor, go to where you downloaded/saved your React project and open it up on your editor. That's it. Happy coding!

> Note: Please allocate some time for these steps as they take a long time to get set up/downloaded.
> **Resources**:
> Video on installing [React on Mac](https://www.youtube.com/watch?v=2oA9d93T9Aw)
> Install React [Article](https://www.knowledgehut.com/blog/web-development/install-react-on-mac)

---

# React Demo

**Alternative**: For the sake of time, since downloading React is a lengthy process, an alternative for anyone who'd like to follow along, head over to this [Replit Link](https://replit.com/@replit/React-Javascript) and click on the **Use Template** button. **You will need** an account to click on the button. It shouldn't take more than 2-3 minutes to make an account. Once you made an account and you click "Use Template", you will be directed to an online Coding editor that contains all the React files that you will need to be able to follow along. 

> Note: Although the above action works, and you can run React on the Online Editor, we still recommend you download React and use it in a Coding editor like Visual Studio code, as seen in the **Pre Requisites** steps.

## Step 0 - Look over React Files/Folders (After Installation)

1) Once inside of your coding editor, after having installed React, you now see a bunch of new files/folders. You probably see the **`node_modules`** folder. This folder contains every installed dependency for your project. You don't really need to worry about this folder.
    <details>
    <summary>node_modules folder</summary>
    <img src="https://i.imgur.com/x4ESV5d.png" alt="drawing" width="100" height="300"/>
    </details>

2) Another folder is the **`public`** folder and this contains a bunch of images that comes with all React projects. The most important file on this folder is the **`index.html`** folder. You won't ever need to touch this file, and the only thing you should know about this is that this page allows everything to be rendered through the **`root`** class.
    <details>
    <summary>public folder</summary>
    <img src="https://i.imgur.com/glZenPu.png" alt="drawing" width="80" height="250"/>
    </details>

3) Your final folder should be the **`src`** folder. This folder is where you'll be writing almost all of your code. Here is where you include all your files and components. The most important file in this folder is the **`index.js`** file. This file is what renders all your components.
    <details>
    <summary>src folder</summary>
    <img src="https://i.imgur.com/5poMMSe.png" alt="drawing" width="100" height="300"/>
    </details>

4) Ignore the other files that you see outside of the 3 folders we mentioned as they won't be something we'll be touching over, since this is a beginner demo.

## Step 1 - Creating App Design

**Description**: In this step we will begin designing our application in our `Main Storyboard`.
<details>
    <summary>Finished product for this step</summary>
    <img src="https://i.imgur.com/6SCeUyj.png" alt="drawing" width="170" height="300"/>
    </details>

0) Let's head over to our `Main Storyboard` file, located on the left side of Xcode. This section on the left side is referred as the `Project Navigator`. You should now see an iPhone like screen. Here is where we will design our application. <br>

https://user-images.githubusercontent.com/71786791/197360059-4afba473-5760-4a93-aae9-0d618864383d.mov

1) Let's locate `Xcode's Library Components` button. It should be a `+` at the top right corner of the middle section of our current screen. Click on it, and now you should see a pop-up displaying various components. If you click on a component, you will see a description of what they each do. <br>

https://user-images.githubusercontent.com/71786791/197360120-0d1ccbc9-5e72-43d6-906a-9960c1f22be4.mov
    
2) Now, let's search up `label`, click on it and drag it on to the `View Controller`. Let's try to place it at the top of our screen, directly in the middle. We will be using this label to display the name of our application "Tip Calculator". <br>

https://user-images.githubusercontent.com/71786791/197360165-c0c2dc7c-886c-49a0-948c-f28a95c1e9c1.mov
 
3) Next, let's double click on the label, and let's give it a name of `Tip Calculator`. Make sure you center the text to the middle of the screen again. Let's then go to the right side of our screen, known as the `Inspection Secton`, and let's locate the `Font section`. Click on the `T` button, click on `style` and select the `bold` selection. This will bolden our label. That is all we will do with this label. <br>

https://user-images.githubusercontent.com/71786791/197360202-3b548347-396f-48d1-90fd-f36b25ec8709.mov

4) Next, let's access our component's library again, click `+` button on the top right corner of the middle section. Search up `Image`, and drag the `Image View` onto your screen. Place it right below our `Tip Calculator` label and center it. We will use this component to display the CSS Logo. <br>

https://user-images.githubusercontent.com/71786791/197360231-77f1c8d7-6a58-4ab8-b8d6-0e7064794622.mov
 



## The End
**Summary**: Congratulations on building your first iOS Application on Xcode. We've included videos in almost each step if you ever get lost, and below we've included iOS Development resources if you'd like to continue learning.

---

# Continue Learning About React
- [11 Hour React Free Course](https://scrimba.com/learn/learnreact)
- [React Website: Learn more](https://reactjs.org/community/courses.html)
- [React Youtube Course](https://www.youtube.com/watch?v=bMknfKXIFA8&t=2154s)



> For visual learners, we'd recommend Youtube videos.
