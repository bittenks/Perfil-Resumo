# Meu Resumo 
Algo que eu sempre quis fazer, desde quando qeu entrei nesse mundo de desenvolvimento Web<br/>
Coloquei em prática tudo que eu aprendi, tive desafios que tive que buscar por ajuda mas consegui fazer, no futuro eu pretendo melhorar 
a interface e colocar os meus projetos nele.


# Prévia do projeto <br/>
[Meu resumo](https://bittenks.github.io/Perfil-Resumo/)

# Responsivo

![alt text](https://github.com/bittenks/Perfil-Resumo/blob/main/responsivo-prefil-resumo-.gif)


## Como eu fiz
Background usei o site [Color hunt](https://colorhunt.co/palette/2763)
<br/>
E fiz a animação:
~~~
@keyframes colors {
0% {
 background-position: 0% 50%;
}
50% {
 background-position: 100% 50%;
}
100% {
 background-position: 0% 50%;
}
}
~~~
~~~

.gradient{
 display: flex;
 align-items: center;
 justify-content: center;
 height: 100vh;
 width: 100vw;
 background: linear-gradient(45deg, #222831, #393e46, #00adb5, #eeeeee);
 background-size: 300%, 300%;
 animation: colors 15s ease infinite;

}
~~~


