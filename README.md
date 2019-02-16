<h1>Criando uma aplicação com Anuglar</h1>

<p>Angular é um framework para construção de aplicações web mobile e deskop</p>
<p>SPA(Single Page Application)</p>
<p>Mantido pela Google</p>
<p>Código Aberto</p>
<p>Baseado em TypeScript - É um superconjunto Javascript desenvolvido pela Microsoft</p>
<h3>Instalando o Angular</h3>
<p>Para o angular funcionar é necessário ter o NodeJS e o NPM instalados</p>
<p>No Linux segue comandos abaixo:</p>
<p><strong>sudo apt update == atualiza o gerenciador de pacotes do Linux</strong></p>
<p><strong>sudo apt install nodejs == instala o NodeJS</strong></p>
<p><strong>sudo apt install npm == instala o gerenciador de pacotes do Node</strong></p>
<p><strong>sudo npm install -g @angular/cli  == instala o Angular</strong></p>
<p><strong>ng --version == mostra versão do Angular instalado</strong></p>
<h2>Criando Projeto</h2>
<p><strong>ng new nome_projeto == cria novo projeto Angular</strong></p>
<p><strong>sudo npm install -g @angular/cli  == instala o Angular</strong></p>
<h2>Iniciando Angular</h2>
<p>ng serve --o == inicia o Angular, abre o navegador com uma página de boas-vinda do Angular</p>
p><strong>ng g c nome_componente == cria novo componente ( g=generate c=component)</strong></p>
<h2>Adicionando Bootstrap e o Material Angular ao projeto</h2>
<p>No arquivo index.html na pasta src será copiado o CDN do Bootstrap</p>
<p>Para adicionar o Material é executado a instalção via terminal:</p>
<p>ng add @angular/material</p>
<h2>Criar componente formulario</h2>
<p>ng g c contato-form</p>
<p>No app.modules.ts é preciso importar o componente</p>
<h2>Enviando dados do formulário para o console</h2>
<p>O arquivo contanto-form.component.ts tem a lógica do objeto</p>
<p>Primeiro é criado uma classe Contato com seus atributos.</p>
<p>Depois será criado um novo objeto Contato</p>
<p>No metódo ngOnInit deve ser instaciado o novo objeto</p>
<p>Finalizando será criado o metódo onSubmit que irá sair com os dados para o console.</p>
