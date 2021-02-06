<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">Café Teórico TV - SpaceShip</h3>

  <p align="center">
    :brazil: Código para aprendizado de Orientação a Objetos! <br>
    :uk: Game coding for OOP learning.
    <br />
    <br />
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## About The Project

:brazil:<br>
Este é um projeto que comecei porque eu estava querendo praticar um pouco do Orientação a Objetos. Tentei implementar alguns testes automatizados mas ainda não domino bem a prática de usar Mocks.<br>
:uk:<br>
This is an attemptive to turn the OOP learning a bit more interesting. I tried to code in the simplest way I could, but I hope you can notice the OOP techniques.<br>

[![Vídeo de apresentação de projeto](http://img.youtube.com/vi/ZwciHye3W5A/0.jpg)](http://www.youtube.com/watch?v=ZwciHye3W5A "Vídeo de apresentação de projeto.")

### Built With

:brazil:<br>
O código está em java e utilizei o NetBeans como IDE. Não há nada mais de extraordinário do que isso.<br>
:uk:<br>
The language is Java. There is no extraordinary tools but the Java coding. You shouldn't have great expectations about the game. It's just coding. :-P <br>
* [Java](https://getbootstrap.com)
* [NetBeans](https://https://netbeans.org/)



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
:brazil:<br>
É necessário entender como é o ESQUELETO deste projeto. As classes possuem 03 métodos principais que são disparados na respectiva ordem: 
<ol>
    <li>
      recebeComando()<br>
<p align="center">
    <img align="center" src="images/sequencia_01.jpg" alt="Logo">
 </p> 
     </li> 
  <li>
 executaCiclo()<br>
<p align="center">
    <img align="center" src="images/sequencia_02.jpg" alt="Logo">
   </p>  
  </li> 
    <li>
desenha()<br>   
<p align="center">
    <img align="center" src="images/sequencia_03.jpg" alt="Logo">
   </p> 
        </li> 
      <li>
tocaAudio()<br>   
<p align="center">
    <img align="center" src="images/sequencia_04.jpg" alt="Logo">
 </p> 
        </li>   

Também foi utilizado o padrão de projeto State para implementar a classe Jogo. Para a passagem de estados eu utilizei PERGUNTAS (métodos que retornam um valor boolean).<br><br>
    <p align="center"><img align="center" src="images/estados_01.jpg" alt="Logo">  </p> 
Por fim achei interessante utilizar um Builder para construir as fases, pois ficamos livres para aumentar a dificuldade e outras coisinhas também. Cada fase é inserida no jogo atravês do método jogo.addFase(FaseGenerica fase) e são percorridas na ordem que são inseridas.<br><br>
    <p align="center"><img align="center" src="images/builder_01.JPG" alt="Logo">  </p> 
<br>  
:uk:<br>
I'll write here the books from where I learned the coding techniques I applied in this project. <br>


### Installation

:brazil:<br>
Faça o download do NetBeans e o instale. [https://netbeans.org](https://netbeans.org)<br>
:uk:<br>
Download and install NetBeans IDE. [https://netbeans.org](https://netbeans.org)<br>


<!-- CONTRIBUTING -->
## Contributing

:brazil:<br>
Vocês podem copiar o código à vontade. Aceito críticas e sugestões de melhorias. <br>
Tem umas partes do código que podem ser melhoradas (refatoradas), por exemplo a interface MovimentoGenerico, acredito que uma classe abstrata com os métodos principais já implementados e apenas alguns métodos abstratos sejam a melhor escolha. Mas no momento vou deixar como está e vou começar outro projeto. Deixo esse homework para quem quiser praticar um pouco de OOP. :-P <br>
:uk:<br>
You can download the code at will. Feel free to make suggestions about the techniques. <br>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Heribeto Pedroso - [linkedin](https://linkedin.com/in/heripedroso) - heri.pedroso@gmail.com <br>
Café Teórico TV - [@cafeteorico.tv](https://instagram.com/cafeteorico.tv) - cafeteorico.tv@gmail.com <br>
Project Link: [https://github.com/heripedroso/CafeTeoricoTV_SpaceShip](https://github.com/heripedroso/CafeTeoricoTV_SpaceShip) <br>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/heripedroso/CafeTeoricoTV_SpaceShip/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/heripedroso/CafeTeoricoTV_SpaceShip/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/heripedroso/CafeTeoricoTV_SpaceShip/stargazers
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/heripedroso/CafeTeoricoTV_SpaceShip/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/heripedroso
[product-screenshot]: images/screenshot.png
