<html lang="pt-br">
<head>
    <link rel="stylesheet" href="styles.css" />
    <title>Aluraflix</title>
</head>

<body>

    <heater>ALURAFLIX</heater>
    <section>
        <div>
            <h1>ATRAVÉS DO ARANHAVERSO SUPERA O PRIMEIRO FILME?</h1>
            <p>#homem-aranha</p>
        </div>

        <div>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/gt_fAE1Eg2Q?si=6mqdjuVn2QWrMm3t"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </section>
 <section class="categoria">
        <h2>Filmes e séries</h2>
        <div class="categoria-videos">
            <a href="https://www.youtube.com/watch?v=cs15QqG6Gjc">
                <img src="https://img.youtube.com/vi/cs15QqG6Gjc/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=nCmIwcycUJ8">
                <img src="https://img.youtube.com/vi/nCmIwcycUJ8/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=FvRmEapoHRc">
                <img src="https://img.youtube.com/vi/FvRmEapoHRc/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=Ipkw_hWW-Hw">
                <img src="https://img.youtube.com/vi/Ipkw_hWW-Hw/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=d4DzMNGoyis">
                <img src="https://img.youtube.com/vi/d4DzMNGoyis/maxresdefault.jpg" />
            </a>
        </div>
    </section>
</body>
</html>
body{
    color:yellow;
background:blue;
margin: 0px;
header {
    border: solid 2px rgb(42, 122, 228);
    border-bottom: solid 2px rgb(42, 122, 228);
    padding: 20px;
    font-size: 32px;
    color: rgb(42, 122, 228);
}
.chamada {
    background: rgb(184, 156, 213);
    padding-bottom: 80px;
    padding-top: 80px;
    display: flex;
    justify-content: center;
}

.chamada-texto {
    margin-right: 5%;
}

h1 {
    font-size: 40px;
}

p {
    font-size: 20px;
}

.categoria-videos {
    display: flex;
    overflow-x: auto;
    gap: 10px;
}

.categoria {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 50px;
}

.categoria-videos img {
    opacity: 0.5;
    height: 200px;
}

.categoria-videos img:hover {
    opacity: 1.0;
    border: 3px solid green;
}

.categoria h2 {
    color: rgb(42, 122, 228);
}
}
