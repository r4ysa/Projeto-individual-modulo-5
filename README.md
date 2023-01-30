# Projeto individual Módulo 5 - Resilia

**O projeto tem como objetivo a criação de uma ferramenta no terminal para auxiliar desenvolvedores no dia a dia com CSS. Desse modo, foi utilizado o Node para montar um código que vai receber uma lista de propriedades de CSS e vai devolver essa lista ordenada de A-Z. Além disso, o usuário terá opções para exibir a lista e excluir uma  propriedade da mesma.**

## Tecnologias:

<ul>
<li>node.js</li>
<li>npm</li>
</ul>

## Configurações:

Para executar este projeto, é necessário realizar as seguintes instalações localmente usando npm:

```
$ npm init -y
$ npm install inquirer
$ npm install chalk
$ npm install prompt-sync
$ npm start
```

<br><br>

## Aplicação


Abaixo consta como funciona o projeto desenvolvido.<br><br>

<b>Menu Inicial:</b><br>
![npm-start-menu-inicial](https://github.com/r4ysa/Projeto-individual-modulo-5/blob/a1ae053d92497be1e14dd02c93696a57a57ec78f/src/menu.png)
<br><br>
<b>Exibir lista de propriedades CSS:</b><br>
![exibir-propriedades](https://github.com/r4ysa/Projeto-individual-modulo-5/blob/a1ae053d92497be1e14dd02c93696a57a57ec78f/src/exibir.png)
<br><br>        
<b>Adicionar propriedade CSS na lista:</b><br>
![adicionar-itens-css](https://github.com/r4ysa/Projeto-individual-modulo-5/blob/a1ae053d92497be1e14dd02c93696a57a57ec78f/src/adicionar.png)
<br><br>
<b>Adicionar propriedade CSS que já esteja na lista:
Note que ao adicionar um item que já esteja na lista, aparece um erro. Ao digitar "sair" aparece uma solicitação para salvar a lista num arquivo que será no formato JSON.
</b><br>
![adicionar-propriedade-repetida](https://user-images.githubusercontent.com/113844035/215296839-c4115af5-ee3e-4a49-8db8-7d4b28d6a6be.png)
<br><br>
<b>Remover propriedade CSS da lista:</b><br>
![remover-itens](https://github.com/r4ysa/Projeto-individual-modulo-5/blob/a1ae053d92497be1e14dd02c93696a57a57ec78f/src/remover.png)
<br><br>
<b>Remover propriedade CSS que já foi removida:</b><br>
![remover-itens2](https://github.com/r4ysa/Projeto-individual-modulo-5/blob/a1ae053d92497be1e14dd02c93696a57a57ec78f/src/remover2.png)
<br><br>
<b>Sair da aplicação:</b><br>[
![sair]](https://user-images.githubusercontent.com/113844035/215296871-016fdd85-196d-44bd-a8ba-014ffc14a5a1.png)
<br><br>
