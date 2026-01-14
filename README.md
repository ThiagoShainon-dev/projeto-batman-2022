# projeto-batman-2022
Site responsivo para adquirir ingressos ao cinema para assistir ao Batman - 2022

index.html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PROJETO BATMAN - FILME 2026 </title>
    <link rel="stylesheet" href="./style.css" />
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Kdam+Thmor+Pro&display=swap');
    </style>
</head>
<body>
    <header>
        <img id="logo" src="./MIDIA/logo 2.jpg" alt="">
            <nav>
                <ul>
                    <a href="./index.html">
                        <li>Home</li>
                    </a>
                    <a href="./contact.html">
                        <li>Contato</li>
                    </a>
                    <a href="./fotos.html">
                        <li>Fotos</li>
                    </a>
                    <a href="./coments.html">
                        <li>Comentários</li>
                    </a>
                </ul>
            </nav>
    </header>
    <div id="banner"> </div>
    <div id="trailer-container">
        <div class="content">
            <video controls class="trailer">
                <source src="./MIDIA/batman video.mp4" type="video/mp4">
                Seu navegador não possui suporte para vídeos
            </video>
            <div id="sinopse">
                <p class="description">
                   Após dois anos espreitando as ruas como Batman, Bruce Wayne se encontra nas profundezas mais sombrias de Gotham City. Com poucos aliados confiáveis, o vigilante solitário se estabelece como a personificação da vingança para a população.
                </p>
                 <button class="button">Comprar Ingresso</button>
            </div>
        </div>
    </div>
    <div class="actor-cards-container">
        <div class="cards-content">
            <div class="card banner-1">Robert Pattinson - Batman</div>
            <div class="card banner-2"> Zoe Kravitz - Mulher Gato</div>
            <div class="card banner-3">Jeffrey Wright - Gordom</div>
        </div>
    </div>
    <footer>
        <img style="object-fit: contain;" id="logo" src="./MIDIA/logo 2.jpg">
        <span>Todos os direitos reservados ©</span>
        <span>Desenvolvido por Thiago Shainon Dev</span>
        <span>https://github.com/ThiagoShainon-dev</span>
        
        <nav class="footer-navigation">
                <ul class="footer-list">
                    <a href="./index.html">
                        <li>Home</li>
                    </a>
                    <a href="./contact.html">
                        <li>Contato</li>
                    </a>
                    <a href="./fotos.html">
                        <li>Fotos</li>
                    </a>
                    <a href="./coments.html">
                        <li>Comentários</li>
                    </a>
                </ul>
            </nav>
    </footer>
</body>
</html>
----------------------------------------------------------------------------------------------
fotos.html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fotos | Projeto Batman</title>
    <link rel="stylesheet" href="./style.css" />
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Kdam+Thmor+Pro&display=swap');

        .gallery {
            width: 90%;
            margin: 50px auto;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
        }

        .gallery img {
            width: 100%;
            height: 350px;
            object-fit: cover;
            border-radius: 5px;
            transition: 0.8s;
            cursor: pointer;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>

<header>
    <img id="logo" src="./MIDIA/logo 2.jpg" alt="">
    <nav>
        <ul>
            <a href="./index.html"><li>Home</li></a>
            <a href="./contact.html"><li>Contato</li></a>
            <a href="./fotos.html"><li>Fotos</li></a>
            <a href="./Coments.html"><li>Comentários</li></a>
        </ul>
    </nav>
</header>

<div class="gallery">
    <img src="https://m.media-amazon.com/images/M/MV5BMmU5NGJlMzAtMGNmOC00YjJjLTgyMzUtNjAyYmE4Njg5YWMyXkEyXkFqcGc@._V1_.jpg">
    <img src="https://static.wikia.nocookie.net/universo-batman/images/a/ac/P%C3%B4ster_de_%27Batman%27.jpg/revision/latest/scale-to-width-down/1200?cb=20220307110904&path-prefix=pt-br">
    <img src="https://preview.redd.it/my-the-batman-part-ii-teaser-poster-ft-hush-who-do-you-want-v0-71scs78j3u1e1.jpeg?auto=webp&s=7c744ff15c64f350c67ae68c86e95a9f02e9b9ea">
    <img src="https://i.redd.it/the-batman-2022-skin-for-arkham-knight-hd-upscale-v0-kcf8trf5kuwb1.jpg?width=3226&format=pjpg&auto=webp&s=865fd5ab537561f19175b676df00930a28950032">
    <img src="https://i.pinimg.com/736x/ab/80/1f/ab801f600efb13c0eb82b4710ba673b0.jpg">
    <img src="https://www.clubecinema.com.br/wp-content/uploads/2022/03/poster-de-The-Batman.jpg">
</div>

<footer>
    <img id="logo" src="./MIDIA/logo 2.jpg">
    <span>Todos os direitos reservados ©</span>
    <span>Desenvolvido por Thiago Shainon Dev</span>
    <span>https://github.com/ThiagoShainon-dev</span>
</footer>

</body>
</html>

--------------------------------------------------------------------------------
coments.html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comentários | Projeto Batman</title>
    <link rel="stylesheet" href="./style.css" />
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Kdam+Thmor+Pro&display=swap');

        .comments-container {
            width: 100%;
            min-height: 500px;
            display: flex;
            justify-content: center;
            margin-top: 50px;
        }

        .comments-content {
            width: 60%;
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .comment {
            background-color: #111;
            padding: 15px;
            border-radius: 5px;
            color: #fff;
            font-family: "Kdam Thmor Pro", serif;
        }
    </style>
</head>
<body>

<header>
    <img id="logo" src="./MIDIA/logo 2.jpg" alt="">
    <nav>
        <ul>
            <a href="./index.html"><li>Home</li></a>
            <a href="./contact.html"><li>Contato</li></a>
            <a href="./fotos.html"><li>Fotos</li></a>
            <a href="./Coments.html"><li>Comentários</li></a>
        </ul>
    </nav>
</header>

<div class="comments-container">
    <div class="comments-content">
        <div class="comment" >🔥 "Filme incrível, visual sensacional!"</div>
        <div class="comment">🦇 "Robert Pattinson mandou muito bem como Batman."</div>
        <div class="comment">🎬 "Gotham nunca esteve tão sombria."</div>
    </div>
</div>

<footer>
    <img id="logo" src="./MIDIA/logo 2.jpg">
    <span>Todos os direitos reservados ©</span>
    <span>Desenvolvido por Thiago Shainon Dev</span>
    <span>https://github.com/ThiagoShainon-dev</span>
</footer>

</body>
</html>
-------------------------------------------------------------------------------------------------
contact.html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contato | Projeto Batman</title>
    <link rel="stylesheet" href="./style.css"/>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Kdam+Thmor+Pro&display=swap');

        .contact-container {
            width: 100%;
            height: 600px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .contact-content {
            width: 50%;
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        input, textarea {
            padding: 12px;
            font-size: 16px;
            border-radius: 5px;
            border: none;
            font-family: "Kdam Thmor Pro", serif;
        }

        textarea {
            resize: none;
            height: 150px;
        }
    </style>
</head>
<body>

<header>
    <img id="logo" src="./MIDIA/logo 2.jpg" alt="">
    <nav>
        <ul>
            <a href="./index.html"><li>Home</li></a>
            <a href="./contact.html"><li>Contato</li></a>
            <a href="./fotos.html"><li>Fotos</li></a>
            <a href="./Coments.html"><li>Comentários</li></a>
        </ul>
    </nav>
</header>

<div class="contact-container">
    <div class="contact-content">
        <input style="color: #fff; font-size: 19px; font-family: Kdam Thmor Pro, serif"; type="text" placeholder="Seu nome">
        <input style="color: #fff; font-size: 19px; font-family: Kdam Thmor Pro, serif"; type="email" placeholder="Seu e-mail">
        <textarea style="color: #fff; font-size: 19px; font-family: Kdam Thmor Pro, serif"; placeholder="Digite sua mensagem"></textarea>
        <button class="button">Enviar</button>
        <p style="color: #fff; font-size: 19px; font-family: Kdam Thmor Pro, serif";>Para maiores informações:</p>
        <p style="color: #fff; font-size: 19px; font-family: Kdam Thmor Pro, serif";> 0800 286 0909  ou  4004-0909 </p>

    </div>

</div>

<footer>
    <img id="logo" src="./MIDIA/logo 2.jpg">
    <span>Todos os direitos reservados ©</span>
    <span>Desenvolvido por Thiago Shainon Dev</span>
    <span>https://github.com/ThiagoShainon-dev</span>
</footer>

</body>
</html>
-----------------------------------------------------------------------------------------
style.css

* {
    margin: 0;
    padding: 0;
    background-color: black;
    list-style: none;
    text-decoration: none;

}

header {
    background-color: black;
    height: 90px;
    display: flex;
    justify-content: space-around;
    align-items: center;

}

nav {
    width: 60%;
    
}

ul {
    display: flex;
    width: 100%;
    justify-content: space-between;
}

li {
    list-style: none;
    color: aliceblue;
    cursor: pointer;
    font-size: 19px;
    transition: .5s;
    font-family: "Kdam Thmor Pro", serif;
}

li:hover {
    color: #D21617;
}

#logo {
    width: 160px;
    height: auto;
}

#banner {
    background-image: url("https://cdn.europosters.eu/image/hp/66923.jpg");
    background-position: 50% 50%;
    background-size: cover;
    width: 100%;
    height: 600px;
}

#trailer-container {
    width: 100%;
    height: 400px;
    display: flex;
    justify-content: center;

}

.content {
    width: 60%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

#sinopse {
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin-left: 30px;
}

.description {
    color: #fff;
    font-size: 19px;
    font-family: "Kdam Thmor Pro", serif;
    width: 70%;
}

.button {
    width: 200px;
    height: 60px;
    background-color: #D21617;
    color: #FFF;
    padding: 8px 10px;
    border-radius: 5px;
    cursor: pointer;
    transition: .8s;
    font-size: 18px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
    border: none;
    outline: none;
    margin-top: 25px;

}

.button:hover {
    background-color: #fff;
    color: #000;

}

.actor-cards-container {
    width: 100%;
    display: flex;
    justify-content: center;
    margin-top: 50px;

}

.cards-content {
    width: 90%;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    row-gap: 20px;
    column-gap: 40px;
}

.card {
    width: 100%;
    height: 600px;
    background-size: cover;
    background-position: 50% 50%;
    border-radius: 5px;
    cursor: pointer;
    transition: 1s;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    padding: 0 0 20px 10px;
    color: #fff;
    font-size: 17px;
    font-family: "Kdam Thmor Pro", serif;

}

.card:hover {
    transform: scale(1.02);
}

.banner-1 {
    background-image: url("https://ovicio.com.br/wp-content/uploads/2019/10/20191020-cropped-jarold-sng-jsd-batman-2021-01-1.jpg");
}

.banner-2 {
    background-image: url("https://i.pinimg.com/originals/3c/a6/28/3ca6282ac5440b49f0008981ad151512.png");
}

.banner-3 {
    background-image: url("https://i.redd.it/l617izc155sb1.png");
}

footer {
    height: 150px;
    margin-top: 50px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;

}

span {
    color: #fff;
    font-family: "Kdam Thmor Pro", serif;
}

.footer-navigation {
    display: none;

}

.footer-list {
    display: flex;
    flex-direction: column;
    align-items: center;

}


@media(max-widht:768px) {
    .footer-navigation {
        display: block;
    }
    nav {
        display: none;
    }
    #banner {
        background-position: 40%;
    }
    #trailer-container {
        width: 100%;
        height: 400px;
        display: flex;
        flex-direction: column;
    }
    .content {
        width: 95%;
        display: flex;
        flex-direction: column;
    }

    .trailer {
        width: 100%;
    }

    #sinopse {
        width: 95%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;

    }
    
    .description {
        width: 100%;
    }

    .button {
        width: 100%;
        margin-top: 30px;
    }

    .cards-content {
        grid-template-columns: 1fr;
        margin-top: 150px;
    }
    
    

}
