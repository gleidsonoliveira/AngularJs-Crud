1 - Para instalar o angular na máquina globol
$ npm i -g @angular/cli

2 - Para criar um projeto com angular
$ ng new frontend --minimal
  Yes - para criar o arquiovo de rotas( Wouldyou like to add Angular routing ?) 
  Not - para não criar o processador do sass (Which stylesheet fromat wouldyoulike touse ? )

3 - Para Rodar a aplicação 
npm start

4 - Alterado o arquivo angular.json.
"schematics": 
{
  "inlineTemplate":false,
  "inlineStyle":false,
  "skipTests":true
},

5 - Instalação do Material designer
ng add @angular/material

6 - Criando o primeiro componentente do angular 
ng g c components/template/header

7 - Criando o componente nav
ng g c components/template/nav

Obs:. Configurando os dois componentes " sidenav, list"
import { MatSidenavModule } from '@angular/material/sidenav';
import { MatListModule } from '@angular/material/list';

8 - Criando as views 
ng g c views/home
ng g c views/product-crud 


--------------------------------------------------------------------------------------------------------


Pontos interessantes 
1 - Criação das directivas 
ng g d directives/red




















