# Projeto de aula-pet
 
html {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 18px;
}

body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color: #999999;
    color: #232323;
}

/* Classes */
.container {
    width: 80%;
    margin: auto;
    background-color: #f9f9f9;
}

.banner {
    height: 200px;
}

.banner img {
    width: 100%;
    height: 100%;
}

.menu {
    background-color: #da2b65;
    /* padding-top: 10px;
    padding-right: 15px;
    padding-bottom: 25px;
    padding-left: 35px; */
    /* padding: 10px 15px 25px 35px; */
    /* padding: 10px 25px; */
    padding: 10px;
    text-align: center;
    color: #f9f9f9;
    /* font-size: 1.4rem; */
    font-size: 24px;
    font-weight: bold;
}

/* Retira o sublinhado de todos os links */
a {
    text-decoration: none;
}

/* Os link dentro do Menu */
.menu a:link, a:visited {
    color: #f9f9f9;
    padding: 10px 25px;
    transition: 0.8s;
}

.menu a:hover {
    background-color: #b8184d;
    transition: 0.5s;
}

.corpo {
    /* background-color: burlywood; */
    /* height: 350px; */
    min-height: 350px;
    padding: 35px;
    text-align: justify;
}

.rodape {
    background-color: #232323;
    color: #999999;
    height: 150px;
    font-size: 0.8rem;
    padding: 35px;
}
/* Classe mais genêrica */
.btn {
    margin-top: 25px;
    padding: 10px 18px;
    font-size: 1rem;
    font-weight: 700; /* o mesmo que bold (negrito) */
}

/* Classe especializada */
.btn-success {
    background-color: #3bbb1b;
    color: #f9f9f9;
}

.btn-danger {
    background-color: #fa4c2e;
    color: #f9f9f9;
}

.btn-success:hover {
    background-color: #208a06;
}

.btn-danger:hover {
    background-color: #c83015;
}

.links {
    /* border: solid 1px #adff2f; */
    display: inline-block;
    width: 25%;
    vertical-align: top;
}

.links ul {
    list-style: none;
}