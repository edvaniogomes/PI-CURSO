# repositorio_do_senac
aula de repositório do senac

Comandos básicos do Git

### Configuração Inicial
- **`git config --global user.name "Seu Nome"`**: Define seu nome de usuário que será associado aos commits.
- **`git config --global user.email "seuemail@example.com"`**: Define seu endereço de e-mail que será associado aos commits.

### Criar um Repositório
- **`git init`**: Inicializa um novo repositório Git no diretório atual.

### Clonar um Repositório
- **`git clone https://github.com/usuario/repo.git`**: Copia um repositório remoto para seu computador, criando uma cópia local.

### Adicionar Mudanças
- **`git add .`**: Adiciona todas as mudanças feitas nos arquivos do diretório atual ao índice para o próximo commit.
- **`git add nome_do_arquivo`**: Adiciona um arquivo específico ao índice.

### Fazer um Commit
- **`git commit -m "Mensagem do commit"`**: Registra as mudanças adicionadas ao índice com uma mensagem descritiva.

### Verificar o Status
- **`git status`**: Exibe o estado atual do repositório, incluindo arquivos modificados, adicionados e não rastreados.

### Ver o Histórico de Commits
- **`git log`**: Mostra um histórico dos commits feitos no repositório, incluindo mensagens e autores.

### Sincronizar com o Repositório Remoto
- **`git pull origin main`**: Puxa (atualiza) as mudanças do repositório remoto para sua branch local.
- **`git push origin main`**: Envia suas mudanças locais para o repositório remoto.

### Criar uma Nova Branch
- **`git branch nome-da-branch`**: Cria uma nova branch para desenvolver novas funcionalidades ou corrigir bugs.

### Mudar para Outra Branch
- **`git checkout nome-da-branch`**: Muda para a branch especificada, permitindo que você trabalhe em outra parte do projeto.

### Mesclar Branches
- **`git merge nome-da-branch`**: Mescla as mudanças da branch especificada na branch atual.

### Remover um Arquivo
- **`git rm nome_do_arquivo`**: Remove um arquivo do diretório e do índice, preparando-o para o próximo commit.

### Reverter Mudanças
- **`git checkout -- nome_do_arquivo`**: Desfaz alterações em um arquivo, retornando à versão mais recente do commit.

Esses comandos ajudam a gerenciar seu código e colaboração em projetos. Se precisar de mais detalhes sobre algum comando específico, é só avisar!

Os principais comandos para criar uma página web html:
1. `<!DOCTYPE html>`: Declaração do tipo de documento.
2. `<html>`: Início do documento HTML.
3. `<head>`: Contém metadados, como título e links para CSS.
4. `<title>`: Define o título da página.
5. `<body>`: Conteúdo visível da página, onde você pode usar elementos como `<h1>`, `<p>`, `<a>`, e `<img>`. 

Para conformação de texto, você pode usar:
<h1> a <h6>: Cabeçalhos.
<p>: Parágrafos.
<strong>: Texto em negrito.
<em>: Texto em itálico.

Para criar links, use:
<a href="URL">Texto do Link</a>.

Para imagens, utilize:
<img src="URL" alt="Descrição">.

E para listas:
<ul> para listas não ordenadas e <ol> para listas ordenadas, com <li> para itens.

*HTML5*
1. Tags de Estrutura e Layout
<html>: Defina o início e o fim de um documento HTML. Toda página HTML começa com essa tag.
<head>: Contém metadados sobre o documento, como o título e links para arquivos CSS e JavaScript.
<title>: Defina o título da página que aparece na aba do navegador.
<base>: Especifique uma URL base para todos os links e caminhos relacionados à página.
<link>: Conecta o documento HTML a arquivos externos, como folhas de estilo (CSS) ou ícones.
<meta>: Defina metadados da página, como charset, especificamente e palavras-chave para SEO.
<style>: Insira estilos CSS diretamente no documento HTML.
<body>: Contém todo o conteúdo visível da página, como texto, imagens e vídeos.
2. Tags de Cabeçalhos, Parágrafos e Texto
<h1> - <h6>: Representam níveis de diferentes níveis de classificação, onde <h1>é o mais importante e <h6>o menos importante.
<p>: Defina um parágrafo de texto.
<br>: Insira um quebra-linha.
<hr>: Insira uma linha horizontal usada para separar conteúdo.
<pre>: Exibe o texto exatamente como foi escrito no código, preservando espaços e quebras de linha.
<blockquote>: Defina uma citação em bloco.
<ol>: Cria uma lista ordenada (numerada).
<ul>: Crie uma lista não ordenada (com marcadores).
<li>: Define um item dentro de uma lista ( <ol>ou <ul>).
<dl>: Defina uma lista de definições.
<dt>: Representa um termo em uma lista de definições.
<dd>: Defina a definição de um termo em uma lista de definições.
<a>: Crie um link (âncora) para outra página ou parte da mesma página.
<strong>: Define texto com ênfase forte, geralmente exibido em negrito.
<em>: Define texto com ênfase, geralmente exibido em itálico.
<b>: Exibe o texto em negrito sem importância semântica.
<i>: Exibe o texto em itálico sem importância semântica.
<u>: Exibe o texto sublinhado.
<mark>: Destaca o texto, como um marcador de texto.
<small>: Exibe o texto em tamanho menor.
<del>: Defina o texto que foi excluído, geralmente exibido riscado.
<ins>: Define o texto que foi inserido, geralmente traduzido.
<sub>: Exibe texto em subscrito (abaixo da linha de base).
<sup>: Exibe texto em sobrescrito (acima da linha de base).
<abbr>: Defina uma abreviação ou acrônimo.
<cite>: Defina o título de uma obra citada, como o nome de um livro ou artigo.
<code>: Exibe texto como código de programação.
<kbd>: Representa entrada de teclado.
<samp>: Representa uma saída de código ou do sistema.
<var>: Representa uma variável ou uma expressão matemática.
<time>: Defina uma data ou hora.
<dfn>: Defina um termo que está sendo descrito ou explicado.
<q>: Representa uma citação curta em linha.
3. Tags Semânticas e de Layout do HTML5
<header>: Representa o cabeçalho de uma seção ou página, geralmente contendo logotipo, título e menus de navegação.
<nav>: Contém links de navegação.
<section>: Defina uma seção temática de conteúdo.
<article>: Representa um conteúdo independente e autocontido, como um artigo de blog ou uma notícia.
<aside>: Definir conteúdo relacionado ou complementar ao conteúdo principal, como uma barra lateral.
<footer>: Representa o rodapé de uma seção ou página, geralmente contendo informações sobre direitos autorais.
<main>: Defina o conteúdo principal da página.
<figure>: Agrupa conteúdo gráfico, como imagens ou diagramas.
<figcaption>: fornece uma legenda para um elemento <figure>.
<div>: Contêiner genérico para agrupar outros elementos sem significado semântico específico.
<span>: Contêiner genérico para conteúdo em linha.
<details>: Defina detalhes adicionais que o usuário pode visualizar ou ocultar.
<summary>: Resumo de um elemento <details>que é sempre visível.
<dialog>: Defina uma janela de diálogo ou modal.
<data>: Relaciona um conteúdo legível para humanos com dados legíveis por máquina.
4. Tags de Mídia
<img>: Insira uma imagem.
<audio>: Insira o conteúdo do áudio.
<video>: Insira o conteúdo do vídeo.
<source>: Defina uma fonte alternativa para arquivos de áudio ou vídeo.
<track>: Defina faixas de texto, como legendas, para vídeos.
<picture>: Defina diferentes fontes de imagem para dispositivos variados.
<iframe>: Insira uma página da web dentro de outra.
<embed>: Insira conteúdo externo, como um vídeo ou plugin.
<object>: Representa um recurso externo, como uma imagem ou um plugin.
<param>: Define parâmetros para um elemento <object>.
5. Tags de Formulários
<form>: Define um formulário para enviar dados do usuário.
<input>: Defina um campo de entrada (texto, senha, e-mail, etc.).
<textarea>: Área de texto para entrada de várias linhas.
<button>: Cria um botão clicável.
<select>: Cria uma lista suspensa.
<option>: Defina opções dentro de um <select>.
<optgroup>: Grupo de opções dentro de um <select>.
<label>: Associa um rótulo a um elemento de formulário.
<fieldset>: Agrupa elementos relacionados dentro de um formulário.
<legend>: Fornece uma legenda para um <fieldset>.
<datalist>: Defina uma lista de opções predefinidas para um campo <input>.
<output>: Representa o resultado de um cálculo.
<keygen>: Gera um par de chaves para autenticação (obsoleto no HTML5).
<progress>: Exibe o progresso de uma tarefa.
<meter>: Exibe uma medição ou valor escalar dentro de um intervalo.
6. Tags de Tabelas
<table>: Defina uma tabela.
<tr>: Defina uma linha em uma tabela.
<td>: Defina uma célula de dados em uma tabela.
<th>: Defina uma célula de cabeçalho em uma tabela.
<thead>: Grupo o cabeçalho da tabela.
<tbody>: Agrupar o corpo da tabela.
<tfoot>: Agrupar o rodapé da tabela.
<caption>: forneça uma legenda para a tabela.
<col>: Define propriedades de uma coluna.
<colgroup>: Defina um grupo de colunas em uma tabela.
7. Tags de Script e Metadados
<script>: Insira ou faça referência a um script (geralmente JavaScript).
<noscript>: Exibe conteúdo alternativo para navegadores que não suportam JavaScript.
<template>: Defina um modelo de conteúdo que pode ser reutilizado.
<slot>: Define um ponto de inserção em um componente da Web (Web Components).
8. Tags Obsoletas ou Não Recomendadas
Essas tags foram descontinuadas no HTML5 e não são mais recomendadas para uso:


*CSS*
1. Propriedades de Fonte e Texto
<color:> Define a cor do texto.
<font-family: Define a família de fontes.
<font-size: Define o tamanho da fonte.
<font-weight: Define a espessura da fonte.
<font-style: Define o estilo da fonte (normal, itálico).
<text-align: Alinha o texto.
<text-decoration: Decoração do texto (sublinhado, linha sobre o texto).
<letter-spacing: Define o espaçamento entre as letras.
<line-height: Define a altura da linha do texto.
<text-transform: Transforma o texto em maiúsculas, minúsculas, etc.
<word-spacing: Define o espaçamento entre as palavras.
2. Propriedades de Fundo
<background: Define todas as propriedades de fundo.
<background-color: Define a cor de fundo.
<background-image: Define a imagem de fundo.
<background-position: Define a posição da imagem de fundo.
<background-size: Define o tamanho da imagem de fundo.
<background-repeat: Define se a imagem de fundo será repetida.
<background-clip: Define a área onde o fundo será aplicado (content-box, padding-box, border-box).
<background-origin: Define a origem do posicionamento da imagem de fundo.
3. Propriedades de Espaçamento
<margin: Define a margem externa.
<margin-top: Define a margem superior.
<margin-right: Define a margem direita.
<margin-bottom: Define a margem inferior.
<margin-left: Define a margem esquerda.
<padding: Define o preenchimento interno.
<padding-top: Define o preenchimento superior.
<padding-right: Define o preenchimento direito.
<padding-bottom: Define o preenchimento inferior.
<padding-left: Define o preenchimento esquerdo.
4. Propriedades de Bordas
<border: Define a borda (largura, estilo e cor).
<border-width: Define a largura da borda.
<border-style: Define o estilo da borda (solid, dotted, dashed).
<border-color: Define a cor da borda.
<border-radius: Define o arredondamento das bordas.
<border-top: Define a borda superior.
<border-right: Define a borda direita.
<border-bottom: Define a borda inferior.
<border-left: Define a borda esquerda.
5. Propriedades de Tamanho e Dimensões
<width: Define a largura de um elemento.
<height: Define a altura de um elemento.
<min-width: Define a largura mínima.
<max-width: Define a largura máxima.
<min-height: Define a altura mínima.
<max-height: Define a altura máxima.
<6. Propriedades de Posição e Layout
<position: Define o tipo de posicionamento (static, relative, absolute, fixed).
<top: Define a posição superior.
<right: Define a posição à direita.
<bottom: Define a posição inferior.
<left: Define a posição à esquerda.
<z-index: Define a ordem de empilhamento.
<display: Define o tipo de exibição (block, inline, flex, grid, etc.).
<float: Alinha um elemento à esquerda ou direita.
<clear: Controla o comportamento de elementos flutuantes.
<overflow: Define o que acontece com o conteúdo que ultrapassa o tamanho do elemento (scroll, hidden, auto).
<visibility: Define se o elemento será visível ou não.
7. Propriedades de Flexbox
<display: flex: Define um contêiner flexível.
<flex-direction: Define a direção dos itens flexíveis (linha ou coluna).
<justify-content: Alinha os itens no eixo principal.
<align-items: Alinha os itens no eixo transversal.
<flex-wrap: Define se os itens devem quebrar linha ou não.
<flex-grow: Define a capacidade de um item de crescer.
<flex-shrink: Define a capacidade de um item de encolher.
<flex-basis: Define a base de tamanho do item flexível.
8. Propriedades de Grid Layout
<display: grid: Define um contêiner de grid.
<grid-template-columns: Define a estrutura das colunas.
<grid-template-rows: Define a estrutura das linhas.
<grid-column: Define o início e fim de uma coluna.
<grid-row: Define o início e fim de uma linha.
<grid-gap: Define o espaçamento entre colunas e linhas.
9. Propriedades de Transições e Animações
<transition: Define a transição suave entre estados de um elemento.
<transition-duration: Define a duração da transição.
<transition-property: Define a propriedade a ser animada.
<transition-timing-function: Define a curva de aceleração da transição (ease, linear).
<animation: Define uma animação.
<animation-duration: Define a duração da animação.
<animation-timing-function: Define a curva de aceleração da animação.
10. Propriedades de Transformação
<transform: Aplica transformações como rotação, escala, translação.
<transform-origin: Define a origem da transformação.
<scale(): Redimensiona o elemento.
<rotate(): Rotaciona o elemento.
<translate(): Move o elemento.
<skew(): Inclina o elemento.
11. Outras Propriedades Úteis
<box-shadow: Aplica sombra ao elemento.
<text-shadow: Aplica sombra ao texto.
<cursor: Define o estilo do cursor (pointer, default, move, etc.).
<opacity: Define a opacidade do elemento.
<<clip-path: Aplica uma máscara de recorte a um elemento.
12. Propriedades Avançadas (Responsive e Outras)
media queries: Para tornar o layout responsivo.
css
Copiar código
@media (max-width: 768px) {
    /* estilos para telas menores que 768px */
}