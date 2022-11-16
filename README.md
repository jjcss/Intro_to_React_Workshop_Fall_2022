
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
**Workshop Zoom Recording**: [Click here](https://jjay-cuny.zoom.us/rec/share/w_WX2fAcJoPI4-4dhcHLG_y_hPCXmjX7NBequkk0QoH06S34hx0b5QGo7FbupUc2.wPWYQlzWqFX792Z-) <br>
**Workshop Google Slides**: [Click here](https://docs.google.com/presentation/d/1viKLdLpINEwy6IiY2uzX_hjU2UOL8sxf_YBFfxtV2xw/edit?usp=sharing) <br>

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
- [ ] **Mac Users**: 
    - [ ] Make sure you have [Xcode](https://developer.apple.com/xcode/) downloaded.
        - Xcode includes everything you need to develop, test, and distribute apps across all Apple platforms. Leverage the simplicity and power of Swift with a new multiplatform app experience and code faster with enhanced editor features. Creating amazing apps has never been easier. In other words, it's an IDE (Integrated Development Environment)
        - Xcode is a bulky application so it might take you a good amount of time to get it to fully download.
- [ ] **Window Users**:
    - [ ] Since Apple only allows iOS Development with Swift and Xcode on MacOS, Window users have to use a virtual machine like **Virtual Box** to be able to use these tools.
        - VirtualBox is a cross-platform virtualization software. It allows users to extend their existing computer to run multiple operating systems including Microsoft Windows, Mac OS X, Linux, and Oracle Solaris, at the same time.
        - [Click here](https://www.wikihow.com/Download-Xcode-on-PC-or-Mac) to learn how to download/install VirtualBox, download Xcode and begin your iOS Development learning.

> Note: Please allocate some time for these steps as they take a long time to get set up/downloaded.

---

# iOS Development Demo

## Step 0 - Open up Xcode & Create a New Project

1) Open up your Xcode Application
    <details>
    <summary>You should see this on your screen</summary>
    <img src="https://i.imgur.com/RCQU2Wp.png" alt="drawing" width="300" height="200"/>
    </details>
2) Click on `Create a New Xcode Project`
    <details>
    <summary>Example</summary>
    <img src="https://i.imgur.com/cU7YmCl.png" alt="drawing" width="400" height="80"/>
    </details>
    
3) You should now see a new screen asking you to choose a template for your project. We want to build and app, so let's select the `iOS Tab` and under `Application` let's select `App`
    <details>
    <summary>Example of configuration for our template</summary>
    <img src="https://i.imgur.com/biYJMqy.png" alt="drawing" width="400" height="200"/>
    </details>
    
4) You should now see options a few options to further configure your project. We will just be focusing on `Product Name`, `Interface` and `Language`. Name your project whatever you'd like. For `Interface` choose, `Storyboard` (we'll get more into what Storyboard is in the following steps). For language, select `Swift`. Then, click `Next`.
    <details>
    <summary>More configuration of project</summary>
    <img src="https://i.imgur.com/7A48vcM.png" alt="drawing" width="400" height="200"/>
    </details>
    
5) You should now see a window asking you to save your project anywhere on your system. One you choose where you want to save your project folder, click on `Create`.

6) You have succesfully created a new Xcode Project File. We can now begin building our application 💻.
1) Open up your Xcode Application
    <details>
    <summary>Newly created project</summary>
    <img src="https://i.imgur.com/BkZxMgU.png" alt="drawing" width="300" height="200"/>
    </details>

>Take some time to look over the various files you now see and all tabs. Also check out video below to see all steps done for `Step 0`.
    
<!-- Step 0
vid1 <br> -->
https://user-images.githubusercontent.com/71786791/196853346-9268941a-7dd0-43d5-a3a5-fbcd96794afc.mov 


<!-- vid2 <br> -->
https://user-images.githubusercontent.com/71786791/196853551-14a9dc55-6aab-435e-9c0f-93a5d5daac18.mov

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
- [Swift Programming Tutorial Video](https://www.youtube.com/watch?v=CwA1VWP0Ldw&ab_channel=SeanAllen)
- [Swift Guide Documentation](https://docs.swift.org/swift-book/GuidedTour/GuidedTour.html)
- [Apple Developer Documentation](https://developer.apple.com/swift/resources/)
- [Build Swift Netflix Clone Programmatically Video](https://www.youtube.com/watch?v=KCgYDCKqato&t=213s&ab_channel=freeCodeCamp.org)
- [Build Programmatic Swift Components](https://github.com/lanqy/swift-programmatically)
- [CodePath Free iOS Development Course](https://www.codepath.org/courses)


> For visual learners, I'd recommend Youtube videos.
