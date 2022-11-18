
<!-- # Intro to React -->

<img src="https://i.imgur.com/JybZuXd.png" alt="drawing" width="100"/> <img src="https://i.imgur.com/Bzkqs5I.png" alt="drawing" width="100"/>

# Computer Science Society Club

## Table of Contents
- [Pre Demo Introduction](#Pre-Demo-Introduction)
- [Pre Requisites](#Pre-Requisites)
- [React Demo](#React-Demo)
- [Continue Learning About React](#Continue-Learning-About-React)

# Intro to React Workshop 

**Date:** Tuesday, November 22nd, 2022 <br>
**Description**: In this workshop You will learn the basics of **React**. You will get an introduction into the ever evolving programming language React. This meeting will also be our **last meeting of the semester**, where we’ll recap all events and new club members. . For more information on React and other resources talked about during the meeting please continue looking below for all resources and **coding demo** steps. <br>
**Workshop Zoom Recording**: [TBD]() <br>
**Workshop Google Slides**: [TBD]() <br>

---


## Pre Demo Introduction

**Description**: We will be learning the vary basics of React.
**We will be going over**: 
- Understanding the **index.js** file code & displaying "Hello World!"
- JSX elements
- Functional Components
- Parameters and embedding JavaScript in JSX
- Using CSS In React

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

## Look over React Files/Folders (After Installation)

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

## Hello World

**Description**: In this part of the demo we will start off by learning the fundemental react code that allows us to display and render elements.

0) Let's head over to our `index.js` file, located in the **`src`** folder. The **`index.js`** file is important as this is where we are redering our React code that displaye in the **root** class element in the `index.html` file in the **`public`** folder. Once in this file, delete everything on this file and copy & paste the code below.

    ```JSX
    import React from "react";
    import ReactDOM from "react-dom/client";

    const htmlContainer = document.getElementById("root");
    const root = ReactDOM.createRoot(htmlContainer);

    root.render(<h1>Hello World!</h1>)
    ```
    This code will display **`Hello World!`** in your browser.
    <details>
        <summary>Hello World in Browser</summary>
        <img src="https://i.imgur.com/7dO5ZGo.png" alt="drawing" width="500" height="200"/>
    </details>

1) Let's look at the first line of code: **`import React from "react";`**. This Line isn't really necessary, but it's good practice to include to let your code editor to import the React library into this file. 

    
2) In the next line: **`import ReactDOM from "react-dom/client";`**, we are importing the **ReactDOM** library, which will allow us to create a **Root** and allow us to **render** a React element into the **Dom**. In simplified terms, this line allows us to render an **HTML** file.

3) Next up, we have the following line: **`const htmlContainer = document.getElementById("root");`**. 
    
    Going from left ----> right: 
    1) we first have `const htmlContainer`. We are creating a constant variable, meaning we can't update this variable to anything else. 
    2) After that we have `= document.getElementById("root")`. For those familiar with HTML, we are basically saying, select an HTML file (**index.html** in this case) and locate the element that has the **"root"** class name. 
    3) If you go back to your **index.html** file, try to locate the root file. To sum up, this line is creating a variable that is accessing the **index.html** file that has the **root** class name.

4) Next up, we have the following line: **`const root = ReactDOM.createRoot(htmlContainer);`**. 

    Going from left ----> right: 
    1) we first have `const root`. We are creating a constant variable named root, meaning we can't update this variable to anything else. 
    2) After that we have `= ReactDOM.createRoot(htmlContainer);`. Here we are using the ReactDOM Module we imported in the second line of this file. Then, we access the function **createRoot()**, which takes in **htmlContainer** that we initialized in the previous line. In simple terms we are using **ReactDOM** to create a root (or connection) to the HTML file (htmlContainer).

5) Finally, we have this line: **`root.render(<h1>Hello World!</h1>)`**.
    
    Using the **root** variable we defined earlier we are using the **render** function to render what are known as **JSX** elements, and what looks basically the same as **HTML** elements.
 
## JSX (Not the same as HTML elements)

1) JSX means **JavaScript Syntax Extension** or **JavaScript XML** as some like to put it. In other words, JSX is an HTML-like syntax that you can use in React.

    For example, in the **`root.render(<h1>Hello World!</h1>)`**, we are endering what looks very similar to a **h1** HTML tag. They have the same name but aren't really the same thing. 
    
    Let's try another example of JSX. Copy the code below inside of **root.render()**:
    
    ```
    root.render(
        <div>
          <h1>Hello World!</h1>
          <h1>Hi Again</h1>
        </div>
    )
    ```
    <details>
        <summary>Example in Browser</summary>
        <img src="https://i.imgur.com/NEvEnhq.png" alt="drawing" width="500" height="200"/>
    </details>
    Here we have a **div** JSX element (container),  and a pair of **h1** JSX elements. They have the same functionality as regular HTML elements but are not to be mistaken of being the same.
    
    Let's try another example of JSX code. Enter this line of code:
    
    ```
    root.render(
        <>
          <h3>Hello World!</h3>
          <h3>Hi Again</h3>
        </>

    )
    ```
    <details>
        <summary>Example in Browser</summary>
        <img src="https://i.imgur.com/uFP8m0X.png" alt="drawing" width="500" height="200"/>
    </details>
    
    The only difference here is the **<>** and **</>** tag. This tag is known as a **fragment tag**. When rendering JSX elements, you must always include your code inside a **fragment tag** because without it, you won't be able to render more than one tag in **React**. Try to test this out by removing the fragment tag from your code. Your terminal will give you an error saying *"Adjacent elements must be wrapped...."*. 
    
## Functional Components
The point of a component based system is to create reusable componenets. Let's make the following changes to our code (index.js):

```JSX
import React from "react";
import ReactDOM from "react-dom/client";

function ClassList() {
  return (
    <div>
      <h1>Welcome to the Computer Science Society Club</h1>
      <p>List of Club Members</p>
    </div>
  );
}

const htmlContainer = document.getElementById("root");
const root = ReactDOM.createRoot(htmlContainer);
root.render(<ClassList />);
```
<details>
    <summary>Example in Browser</summary>
    <img src="https://i.imgur.com/ufId5LQ.png" alt="drawing" width="500" height="200"/>
</details>
    
What did we just do?

- components should begin with capital letters
- notice the `( )` in the return
- Try <ClassList></ClassList>, did it work?
- is <ClassList> a standard HTML tag?
    
Now, let's try adding multiple **`<ClassList/>`** into our code:
    
```
import React from "react";
import ReactDOM from "react-dom/client";

function ClassList() {
    return (
        <div>
          <h1>Welcome to the Computer Science Society Club</h1>
          <p>List of Club Members</p>
        </div>
    );
}

const htmlContainer = document.getElementById("root");
const root = ReactDOM.createRoot(htmlContainer);
root.render(
    <>
        <ClassList />
        <ClassList />
        <ClassList />
        <ClassList />
        <ClassList />
    </>
);
```
    
<details>
    <summary>Example in Browser</summary>
    <img src="https://i.imgur.com/IQVBWxK.png" alt="drawing" width="500" height="200"/>
</details>

    
Do you see how reusable these components are and how useful creating a functional component is?
    
Let's do another more realistic example. Copy this code below:
    
```
import React from "react";
import ReactDOM from "react-dom/client";

function ClassList() {
  return (
    <div>
      <h1>Welcome to the Computer Science Society Club</h1>
      <p>List of Club Members</p>
    </div>
  );
}

function StudentInfo() {
  return (
    <div>
      <div>
        Gamarra, Leandro
      </div>
      <ul>
        <li>
          <strong>ID:</strong> 212121
        </li>
        <li>
          <strong>School:</strong> John Jay College
        </li>
        <li>
          <strong>Major:</strong> Computer Science / Information Security
        </li>
      </ul>
    </div>
  );
}

const htmlContainer = document.getElementById("root");
const root = ReactDOM.createRoot(htmlContainer);
root.render(
  <>
    <ClassList />
    <StudentInfo/>
  </>
);
```
<details>
    <summary>Example in Browser</summary>
    <img src="https://i.imgur.com/wU9h4Yg.png" alt="drawing" width="500" height="200"/>
</details>

Here we are creating another functional component (**StudentInfo**) to display the info of a club member. Now, how do we make this more realistic to display multiple club members?

## Parameters and embedding JavaScript in JSX

Here we will be learning how to pass in **parameters** to a **functional component** to be able to display different information to mutiple club members. Copy the code below:

```
import React from "react";
import ReactDOM from "react-dom/client";

function StudentInfo(item) {
  return (
    <div>
      <div>
        {item.lastName}, {item.firstName}
      </div>
      <ul>
        <li>
          <strong>ID:</strong> {item.sId}
        </li>
        <li>
          <strong>School:</strong> {item.school}
        </li>
        <li>
          <strong>Major:</strong> {item.major}
        </li>
      </ul>
    </div>
  );
}

function ClassList() {
  return (
    <div>
      <h1>Welcome to the Computer Science Society Club</h1>
      <p>List of Club Members</p>
      <StudentInfo firstName="Leandro" lastName="Gamarra" sId="212121" school="John Jay College" major="John Jay College" />
      <StudentInfo />
      <StudentInfo />
    </div>
  );
}

const htmlContainer = document.getElementById("root");
const root = ReactDOM.createRoot(htmlContainer);
root.render(
  <>
    <ClassList />
    <StudentInfo/>
  </>
);
```

<details>
    <summary>Example in Browser</summary>
    <img src="https://i.imgur.com/b4rnNPr.png" alt="drawing" width="500" height="200"/>
</details>

**What's new here:**
1) We passed in an **item** parameter to the **StudentInfo** component. You can name the parameter anything you'd like, but you must use the same name inside the component.
2) After passing in a parameter, we included code like **`{item.lastName}`** where we'd like to have different data for. Opening up the **{}** let's React know that you'd like to pass in data, but you have to follow the same format of brackets ---> parameter name ---> what data you want to Pass in = `**{item.lastName}**``. We did the same thing for **firstName**, **sID**, **school**, and **major**. Make sure you keep track of the data you'd like to pass in.
3) Inside of the **ClassList** function, where the first **StudentInfo** element is written, we now have, what appears to be the name of the data that we want to pass it (from our **StudentInfo** function). The format is **`lastName="Leandro"`**. Do you see how we are using the **lastName** that we defined in **StudentInfo** (they must always be the same lettering). After the equal operator we define what data we want to be displayed.
4) Practice some more by passing in separate data. Make sure you first define what data you want to pass in **StudentInfo** first, before you pass in the data in the **StudentInfo** tag in **ClassList** function.

## Using CSS In React

## The End
**Summary**: Congratulations on learning the basics of **React**. Knowing these basics you can now go on and build out a bit larger projects of your own. Below we've included React resources if you'd like to continue learning.

---

# Continue Learning About React
- [11 Hour React Free Course](https://scrimba.com/learn/learnreact)
- [React Website: Learn more](https://reactjs.org/community/courses.html)
- [React Youtube Course](https://www.youtube.com/watch?v=bMknfKXIFA8&t=2154s)



> For visual learners, we'd recommend Youtube videos.
