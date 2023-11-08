# Zemnitsky Dmitry  

## My contact information:  
__Location:__ Brest, Belarus  
__Phone:__ +375(29) 796-97-77  
__E-mail:__ g.fredex@gmail.com  
__Telegram:__ @gfredex  
__GitHub:__ gfredex 

***

## About me:  
Love my family, love the sun, the sea and warmth. Like to help people. I plan my day and try to do everything in time or earlier. Like to constantly develop and get a new skill. I enjoy the result. I like cars and like to swim.

*** 

## Education:  
* Brest State Technical University, systems engineering engineer; 
* courses: 
  * Educational center "Success", WEB-designer (2016); 
  * Educational center "Success", WEB-coder (2019); 
  * The Rolling Scopes School вЂњJS/FE Pre-School 2022Q4вЂќ. 
  
*** 

## Example my code:  

* html

```
<header class="header">
        <div class="container">
            <nav class="nav">
                <div>
                    <a class="logo_link" href="#">
                        <img class="logo_img" src="./images/logo_vector.svg" alt="Logo">
                        <span class="logo_text">Plants</span>
                    </a>
                </div>
                <button class="burger__menu">
                    <div class="menu__line"></div>
                    <div class="menu__line"></div>
                    <div class="menu__line"></div>
                    <div class="menu__line"></div>
                </button>
                <ul class="menu_list">
                    <li class="list-item">
                        <a class="menu_link" href="#home">Home</a>
                    </li>
                    <li class="list_item">
                        <a class="menu_link" href="#about_us">About us</a>
                    </li>
                    <li class="list_item">
                        <a class="menu_link" href="#service">Service</a>
                    </li>
                    <li class="list_item">
                        <a class="menu_link" href="#price">Price</a>
                    </li>
                    <li class="list_item">
                        <a class="menu_link" href="#contacts">Contacts</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
```  

* css 

```
html {
    scroll-behavior: smooth;
}

body {
    font-size: 16px;
    color: #636060;
    --bg-section: #EDF2EC;
    --color-text: #636060;
    --color-greenText: #499A18;
    --color-orange: #E06733;
    margin: 0 auto;
}

a {
    color: inherit;
    text-decoration: none;
}

h2 {
    font-size: 40px;
    line-height: 52px;
    font-weight: 400;

}

h3 {
    font-weight: 700;
    font-size: 20px;
    line-height: 20px;
    color: var(--color-orange);
}

.burger__menu {
    display: none;
}

.header,
.welcome,
.service,
.contacts {
    background-color: var(--bg-section);
}

.container {
    max-width: 1240px;
    margin: 0 auto;
    padding: 0 10px;
}

.nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 134px;
    font-family: 'Inika';
}

.logo_img {
    width: 20px;
    height: 20px;
}

.menu_list {
    display: flex;
    gap: 0 36px;
    list-style: none;
}

.logo_link,
.menu_link {
    color: #010201;
}

.menu_link {
    padding: 5px;
}

.logo_text:hover,
.menu_link:hover {
    color: var(--color-orange);
    font-weight: 700;
}
``` 

* JS 

```
 const serviceItem = document.querySelectorAll(".service_item");
    const blurGarden = document.querySelectorAll(".garden");
    const blurPlant = document.querySelectorAll(".plant");
    const blurLawn = document.querySelectorAll(".lawn");
    const gardenB = document.querySelector(".gardens-button");
    const lawnB = document.querySelector(".lawn-button");
    const plantB = document.querySelector(".plant-button");

    gardenB.addEventListener("click", function () {
        if (!(gardenB.classList.contains("activ_button")) && (lawnB.classList.contains("activ_button")) && (plantB.classList.contains("activ_button"))) {
            gardenB.classList.add("activ_button");
            lawnB.classList.remove("activ_button");
            plantB.classList.remove("activ_button");
            blurGarden.forEach(blurIt => {
                blurIt.classList.remove("blur_item");
            });
            blurPlant.forEach(blurIt => {
                blurIt.classList.add("blur_item");
            });
            blurLawn.forEach(blurIt => {
                blurIt.classList.add("blur_item");
            });
        } 
    });
``` 
*** 

## Skills:  
* HTML5/ CSS3; 
* JavaScript Basics; 
* Version Control/Git; 
* Browser Developer tools; 
* WebStorm;
* VSCode; 
* Figma; 
* Adobe Photoshop. 

*** 

## Languages  
* Russian (native); 
* English (A2). 

*** 