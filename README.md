# Criação site na Pets Shop 

import { Avatar } from "@opeepsfun/avatar-illustration-system";

const avatar = Avatar({
    circle: { backgroundColor: "brown" },
    size: 600,
    glasses: "Square",
    ear: "Attached",
    eye: "Round",
    shirt: "Crew"
});

const parser = new DOMParser();
const svgDOM = parser.parseFromString(avatar, "image/svg+xml");

document.getElementById("illustration").appendChild(svgDOM.documentElement);

Fiz criação básico site no assunto PetsShop, esse começou aprender programação HTML e CSS. Usa clicar as paginas home, produtos e contatos. 

<h1> Página de home </h1>

<div align="center">
<a href="https://ibb.co/KFNHJT1"><img src="https://i.ibb.co/GczH2gc/Captura-de-tela-2024-10-11-075155.png" alt="image" border="0"></a>
</div>

<div align="center">
<a href="https://ibb.co/KFNHJT1"><img src="https://i.ibb.co/T28Kh3D/1-Captura-de-tela-2024-10-11-084733.png" alt="image" border="0"></a>
</div>

<div align="center">
<a href="https://ibb.co/KFNHJT1"><img src="https://i.ibb.co/25351q0/Captura-de-tela-2024-10-11-084924.png" alt="image" border="0"></a>
</div>

<div align="center">
<a href="https://ibb.co/KFNHJT1"><img src="https://i.ibb.co/48GQVXp/Captura-de-tela-2024-10-11-085246.png" alt="image" border="0"></a>
</div>

<p align="center">
<img src="https://img.shields.io/badge/_-HTML5-grey?logo=html5"/>
<img src="https://img.shields.io/badge/_-CSS3-grey?logo=css3"/>
<img src="https://img.shields.io/badge/_-javascript-grey?logo=javascript"/>
<img src="https://img.shields.io/badge/Imersão Front--End-Alura-blue"/>
<img alt="Static Badge" src="https://img.shields.io/badge/Linkedn-passing?style=flat&logo=linkedin&logoColor=white&color=blue&link=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fmatheus-forstner-larangeiro-2a63901a0%2F">
<img alt="GitHub followers" src="https://img.shields.io/github/followers/MatheusForstner">
</p>
