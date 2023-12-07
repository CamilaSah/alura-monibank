![Front-end-JavaScript-form](https://github.com/CamilaSah/alura-monibank/assets/128820692/27f7b483-8eeb-4297-95c2-8e54ff335e5a)
![Static Badge](https://img.shields.io/badge/Status-Conclu%C3%ADdo-%2391DCFF)

<h1>Validação de formulário - Monibank</h1>
Este projeto foi desenvolvido com o curso JavaScript: validando formulários, no qual foi proposto implementar validações nos campos do formulário de cadastro do banco virtual Monibank e implementar a página de reconhecimento facial do nosso formulário, ou seja, a pessoa usuária seria capaz de capturar uma imagem sua com a câmera. O código do projeto já veio com o HTML e o CSS prontos, para focarmos no desenvolvimento do JavaScript.

## :hammer: Funcionalidades do projeto
- `Validar campos do formulário`: quando o usuário não preencher o campo ou preencher de forma incorreta, aparecerá uma mensagem de erro embaixo do campo, impossibilitando a finalização do cadastro.
- `Capturar a sua foto`: quando o usuário clicar no "rostinho sorridente", permitir o acesso à câmera e clicar no botão "Tirar foto", a sua foto será capturada e aparecerá a mensagem "Prontinho, imagem capturada!".
- `Criar conta`: quando o usuário preencher todos os campos do formulário corretamente e clicar no botão "avançar", tirar uma foto e clicar no botão "Quero abrir minha conta", a conta será criada.

## 📁 Acesso ao projeto

## ✔️ Técnicas e tecnologias utilizadas

Técnicas utilizadas:
- ``Atributo required``: torna o campo obrigatório.
- ``Atributo type``: define o tipo de input.
- ``Atributo min-length e atributo max-length``: controlam a quantidade de caracteres do input.
- ``pattern``: utilizado para que o CPF seguisse um padrão.
- ``Método forEach()``: foi aplicado para verificar cada campo do formulário.
- ``Método includes()``: foi utilizado para verificar se o CPF estava na lista de números repetidos.
- ``Método checkValidity()``: foi utilizado para checar se o campo é válido ou não.
- ``Método setCustomValidity()``: foi utilizado para definir uma mensagem de validade personalizada para o campo.
- ``Método navigator.mediaDevices()``: foi utilizado para pedir para o navegador iniciar a câmera.
- ``Método JSON.stringify()``: transforma objetos, arrays e listas em string.
- ``addEventListener``: detecta interações da pessoa usuária com o cadastro;
- ``Evento blur``: foi acionado quando o usuário tira o foco do input.
- ``Evento invalid``: foi acionado quando um elemento que pode ser enviado foi verificado quanto à validade e não satisfaz suas restrições.
- ``Evento submit``: foi acionado quando o formulário foi enviado.
- ``Evento click``: foi acionado quando o botão para tirar foto foi clicado.
- ``if``: foi utilizado para fazer validações do CPF.
- ``ValidityState``: verifica os erros que ocorrem no preenchimento do elemento.
- ``Node.parentNode``: foi utilizado para retornar o input mais próximo.
- ``Propriedade textContent``: foi utilizado para imprimir a mensagem de erro caso o campo não seja válido.
- ``Data attributes``: foi utilizado para selecionar o formulário.
- ``Função querySelector()``: faz a seleção dos elementos para captura de foto.
- ``Manipulação de DOM``: para imprimir mensagens de erro.
- ``localStorage``: para salvar os dados.
- ``localStorage.setItem``: foi utilizado para criar um elemento no Local Storage.

Tecnologias e ferramentas utilizadas:
- ``Visual Studio Code``: editor de código.
- ``Extensão Live Server``: é uma extensão para o Visual Studio Code que cria um servidor local para hospedar seu projeto e atualizar automaticamente a página quando você faz alterações no código. 
- ``Chrome``: navegador utilizado para teste.
- ``HTML``: fazer a estrutura semântica da página.
- ``CSS``: fazer os estilos da página.
- ``JavaScript``: adicionar o dinamismo e as atualizações de programação, a lógica na página.
- ``DevTools``: utilizamos a aba “Console”, no qual podemos executar qualquer código JavaScript, além de nos ajudar a desenvolver, a entender o nosso código e ver como os erros são apresentados.
- ``Git``: ferramenta de controle de versão de seu arquivo, projeto ou código. 
- ``GitHub``: plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs (permite compartilhamento de código através da criação de repositórios), utilizando o Git como sistema de controle.
- ``Vercel``: colocar o projeto no ar e compartilhar com o mundo.

## 📚 Mais informações do curso
Gostou do projeto e quer conhecer mais? Você pode acessar o curso que me ajudou a desenvolver o projeto desde o começo! 
Busque na plataforma da Alura o curso da escola Front-end:
- [JavaScript: validando formulários](https://cursos.alura.com.br/course/javascript-validando-formularios).

Esse curso faz parte da formação [Desenvolva aplicações Web com JavaScript](https://cursos.alura.com.br/formacao-javascript-front-end) da Alura
<br>
<br>
# Autores

| <img src="https://github.com/CamilaSah/site-pessoal/assets/128820692/bed790ab-3722-4503-8fed-c786e774661b" width="100"><br>[<sub>Camila Sayuri Tokubo</sub>](https://www.linkedin.com/in/camila-tokubo/)|
| :---: |
