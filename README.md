# Estrutura-de-dados-e-algoritmos-com-javascript

Exemplos do livro da Loiane Groner -2ª Edição

## Prefácio

* [Exemplos online](https://javascript-ds-algorithms-book.firebaseapp.com/)

 ## Capítulo 1 - JavaScript - Uma visão geral rápida

 * Neste [link](https://githut.info/) encontramos dados sobre os repositórios no Github. Podemos ver que JavaScript é responsável pela maioria dos repositórios ativos atualmente. Neste [link](https://madnight.github.io/githut/) temos dados atualizados.
 * O JavaScript pode ser utilizado:
    * No Backend com o NodeJs - o número de módulos do [NPM](https://www.npmjs.com/) têm crescido exponencialmente;
    * Para desenvolvimento para dispositivos móveis - com o [Apache Cordova](https://cordova.apache.org/) ou [React Native](https://reactnative.dev/)
    * Aplicações desktop para Linux, Mac OS e Windows com o framawork JavaScript [Electron](https://www.electronjs.org/)
    * Aplicações para dispositivos embarcados e dispositivos para IoT (Internet of Things).

### Estrutura de dados e altoritmos em JavaScript

* *Por que utilizar JavaScript para aprender estrutura de dados?* Além de muito popular, a linguagem JavaScript é apropriada para conhecer as estruturas de dados por ser uma linguagem funcional. 
* *Por que é importante conhecer estrutura de dados?* 
    * Primeiro motivo é o fato de as estruturas de dados e os algoritmos serem capazes de resolver os problemas mais comuns de modo eficiente. Isso fará diferença na qualidade do código-fonte que você escreverá no futuro (inclusive no desempenho; se você escolher a estrutura de dados ou o algoritmo incorreto, conforme o cenário, poderá ter alguns problemas de desempenho). 
    * Em segundo lugar, os algoritmos são estudados nas faculdades, junto com os conceitos introdutórios de ciência da computação. 
    * Por fim, se você planeja conseguir um emprego em uma das maiores empresas de **TI** - como Google, Amazon, Microsoft, eBay e outras -, as estruturas de dados e os algoritmos serão assuntos das pergurnas nas entrevistas.

### Configurando o ambiente

* Um navegador (Chrome ou Firefox);
* um editor de texto (VSCode)
* Um servidor web (XAMPP) - Opcional

### Configuração mínima para trabalhar com JavaScript

### Usando servidores Web

* Uma opção é usar uma extensão do Chrome chmada [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en)

### http-server do Node.js

* A terceira opção é ter um ambiente 100% JavaScript!
    * Instale o [Node.js](https://nodejs.org/en/)
    * Instale o http-server a partir do comando: ```npm install http-server -g``` (Windows) ou ```sudo npm install http-server -g``` (Linux e Mac)
* O comando instalará o * http-server*, um servidor JavaScript. Para iniciar um servidor e executar os exemplos deste livro na aplicação do Terminal, mude o diretório para a pasta que contém o código-fonte do livro e digite *http-server*. Para executar os exemplos, abra o navegador e acesse o localhost na porta especificada pelo comando *http-server*.

### Básico sobre o JavaScript

[01-HelloWorld.html](Capítulo 1/01-HelloWorld.html)
[01-HelloWorld.js](Capítulo 1/01-HelloWorld.js)
[01-HelloWorld.html](Capítulo 1/01-HelloWorld2.html)

* Você poderá encontrar instruções *include* de JavaScript ou código JavaScript na tag *head* em alguns exemplos na internet. Seguindo a melhor prática, incluiremos qualquer código JavaScript no final da tag *body*. Desse modo, o navegador fará o parse do HTML, e ele será exibido antes de os scripts serem carregados. Com isso, a página terá um melhor desempenho.