# π± Su_Profile

### π©βπ λλ§μ νλ‘ν λ§ν¬ λ§λ€κΈ° 
> ##### spartacodingclub

### Stack 

         HTML, CSS

---

### 1. νλ‘ν λ§λ€κΈ° 

```HTML
<body>
    <div class="profile"></div>
    <h1 class="main">Su Kyung</h1>
    <p class="sub">ENFJ</p>
</body>
```

```CSS
<style>
            body {
                background-color: #44398A;
            }
            .profile {
                width: 100px;
                height: 100px;

                background-color: yellow;
                border-radius: 100%;

                border : 2px solid white;

                background-image: url(./λ΄μ¬μ§2.PNG);
                background-position: center;
                background-size: cover;
            }
            .main {
                color: white;
                font-size: 20px;
            }
            .sub {
                color: white;
                font-size: 14px;
            }
        </style>
```

---


### 2. λ§ν¬ λ§λ€κΈ° 

```html
<body>
    <div class="wrap">
        <div class="profile"></div>
        <h1 class="main">Su Kyung</h1>
        <p class="sub">π Full Stack Developer</p>
        <a target="_blank" href="https://github.com/oiosu">GITHUB</a>
        <a target="_blank" href="#">β areuready@kakao.com</a>
        <a target="_blank" href="https://areuready.tistory.com/">Blog</a>
        <a target="_blank" href="#">About</a>
    </div>
</body>
```

```css
<style>
            @import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');
            * {
                font-family: "Pretendard",serif;
            }
            body {
                background-color: #FF5D5D;
            }
            .profile {
                width: 100px;
                height: 100px;
                border-radius: 100%;
                border : 2px solid white;
                background-image: url(./λ΄μ¬μ§2.PNG);
                background-position: center;
                background-size: cover;
            }
            .main {
                color: #FFE3A9;
                font-size: 20px;
            }
            .sub {
                color: #FFE3A9;
                font-size: 14px;
                font-weight: bold;

                margin-top: 0;
            }
            .wrap{
                width: 300px;
                margin: 30px auto 0px auto;

                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
            }
            .wrap > a {
                font-size: 14px;
                font-weight: bold;
                color: white;

                background-color: #FF8C8C;
                border-radius: 8px;

                /* κ·Έλ¦Όμ */
                box-shadow: 3px 3px 5px 0px black; 

                width: 300px;
                height: 50px;

                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;

                margin-bottom: 10px;
                text-decoration: none;
            }
            .wrap > a:hover {
                background-color: #FFC3C3;
            }
        </style>
```

---
 
 
 

### 3. [Su_Profile](https://oiosu.github.io/Su_Profile/)

      

![image](https://user-images.githubusercontent.com/99783474/195984567-07ffbbda-1c62-46d4-a618-f1c14fde9a55.png)



---

