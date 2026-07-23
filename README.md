 {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.8;
}


header{
    background: linear-gradient(to right, #0057B8, white, #D71920);
    color: black;
    text-align: center;
    padding: 20px;
}
header p {
    font-size: 1.2em;
    text-align: center;
}

header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2em;
}


main {
    width: 90%;
    max-width: 1000px;
    margin: 30px auto;
}

section {
    background-color: white;
    padding: 25px;
    margin-bottom: 25px;
    border-radius: 10px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.1);
}

section h2 {
    color: #0057B8;
    margin-bottom: 15px;
    border-left: 6px solid #D71920;
    padding-left: 10px;
}

p {
    margin-bottom: 15px;
    text-align: justify;
}

img {
    display: block;
    width: 100%;
    max-width: 650px;
    margin: 20px auto;
    border-radius: 10px;
    box-shadow: 0 3px 8px rgba(0,0,0,0.2);
}

ul,
ol {
    margin-left: 25px;
    margin-top: 10px;
}

li {
    margin-bottom: 8px;
}
hr {
    border: none;
    height: 2px;
    background-color: #0057B8;
    margin: 30px auto;
    width: 80%;
}

footer {
    background-color: #0057B8;
    color: white;
    text-align: center;
    padding: 30px 20px;
}

footer h3 {
    margin-bottom: 15px;
}

footer ul {
    list-style: none;
}

footer li {
    margin: 10px 0;
}

footer a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

footer a:hover {
    color: #FFD700;
    text-decoration: underline;
}

@media (max-width: 768px) {
    header h1 {
        font-size: 2em;
    }

    section {
        padding: 18px;
    }

    img {
        width: 100%;
    }
}
