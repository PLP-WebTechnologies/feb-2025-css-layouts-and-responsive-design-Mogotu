# CSS Layouts and Responsive Design

## Objectives

Implement Flexbox and Grid for layout design.
Make the webpage responsive using media queries.
Ensure proper alignment and spacing.

## Instructions

- use Flexbox or CSS Grid.
- Add a navigation bar and structure the content.
- Use media queries to adjust layout for mobile, tablet, and desktop.

>[!NOTE]
>  - Include at least:
>  - navigation bar
>  - media queries

# Tasks

- Apply Flexbox or Grid for layout.
- Make the page responsive.
- Test across different screen sizes.

Happy Coding! 💻✨


body{
    font-family: 'Times New Roman', Times, serif;
    background-color: azure;
    margin: 0;
    padding: 0;
}

header{
    text-align: center;
    padding: 20px;
    background-color: rgb(160, 95, 151);
    color:rgb(5, 87, 180);
    border-radius: 60px;
}

nav{
    display: flex;
    justify-content: space-around;
    background-color: rgb(100,50,120);
    padding:15px;
    border-radius: 20px;
}

nav a{
    color: aliceblue;
    text-decoration: aqua;
    padding: 10px;
}

nav a:hover{
    background-color: blue;
    border-radius: 5px;
}

h2{
    color: cadetblue;
}

main{
    display:flex;
    flex-wrap: wrap;
    gap:20px;
    justify-content:center;
    margin-top: 20px;
}
ol{
    background-color: rgb(240, 237, 234);
    padding-block:2rem;
    border-radius: 50px;
    margin-inline: auto;
}

img{
    display: block;
    margin: 20px;
    border-radius: 60px;
    max-width: 100%;
    height: auto;
}

table{
    display:grid;
    width:100px;
    border-collapse: collapse;
    margin-top:10px;
    background-color: rgb(177, 153, 153);
}

th,td{
    border:1px;
    padding: 20px;
    text-align:left;
}

form{
    background: rgb(226, 224, 219);
    padding: 40px;
    border-radius: 70px;
    box-shadow:4px 4px 10px royalblue;
}

label{
    font-weight:bold;
    display:inline-block;
    margin-top: 20px;
}

input,select, button{
    width: 120px;
    padding: 8px;
    margin-top:2px;
    border: 10px;
    border-radius: 5px;
}

button{
    background-color: brown;
    color:blue;
    border:10px;
    font-size:smaller;
    cursor:pointer;
}

button:hover{
    background-color: aquamarine;
}

.container{
    width: 80%;
    margin: 0 auto;
}
