# Weekly_Activity_One
Repositório voltado para a publicação dos conhecimentos "ainda existentes" adquiridos em aula sobre Desenvolvimento Web.


**Conceitos HTML:**

1. **HTML**

    - É uma linguagem marcação para a construção de páginas web;

    - HTML (abreviação do inglês HyperText Markup Language, que em português significa Linguagem de Marcação de Hipertexto);

    - Comumente usada na construção de páginas de sites hospedadas na web;

    - Sendo em sua infinidade de browsers(navegadores) tem a capacidade de interpretar páginas HTML.

2. **Tags HTML**

    - As tags são utilizadas para informar ao seu navegador a estrutura do site que está sendo acessado, tendo como principal característica de sempre estarem dentro dos sinais de "maior que" e "menor que", ou seja: < >.

    - São divididas em dois tipos: as que precisam de fechamento e as que não precisam de fechamento. As tags que precisam de fechamento possuem a estrutura "<li></li>" e as que não precisam de fechamento possuem como estrutura a seguinte forma "<br/>".

    - Além disso, uma mesma tag pode receber um ou mais atributos, que possuirá um valor que modifica sua estrutura ou funcionalidade mais conhecido como "estilização".


3. **Estrutura de um documento HTML simples**
    ```
    <!DOCTYPE html>
    <html>
        <head>
            <title>Título da página</title>
            <meta charset="utf-8"/>
        </head>
        <body>
            
        </body>
    </html>
    ```
4. **Exemplos de tags HTML**

    - Tags de texto 
        ```
        <h1></h1>
        <h2></h2>
        <h3></h3>
        <h4></h4>
        <h5></h5>
        <h6></h6>
        ```

    - Tag para parágrafo
        ```
        <p></p>
        ```

    - Tag para quebra de linha
        ```
        <br/>
        ```

    - Tag para criar uma linha horizontal
        ```
        <hr/>
        ```

    - Tag para lista
        ```
        <ul></ul>
        <ol></ol>
        <li></li>
        ```

    - Tag para título
        ```
        <title></title>
        ```

    - Tag para grupo de texto 
        ```
        <hgroup></hgroup>
        ```

    - Tag para criar divisões 
        ```
        <div></div>
        ```

    - Tag para delimitar o rodapé 
        ```
        <footer></footer>
        ```

    - Tag para criar uma sessão na página 
        ```
        <section></section>
        ```

    - Tag para texto em negrito 
        ```
        <b></b>
        ```

    - Tag para texto em itálico 
        ```
        <i></i>
        ```

5. **Estilização de tags HTML**

    - A estilização das tags em HTML se dá por meio do uso de atributos que por sua vez, modificam a estrutura e/ou sua funcionalidade.
        
        **Exemplos:**

        - style=""
        - rel="" 
        - type="" 
        - href=""
        - background-color:
        - color:
        - margin-left:
        - margin-right:
        - margin-center:
        - font-size:
        - padding:
        - float:
        - width:
        - height:
        - background:

**CSS**

- É um mecanismo utlizado para adicionar estilos a um página web, podendo ser aplicado diretamente nas tags no documento HTML, pode ficar contido dentro das tags "<style></style>" ou também, pode-se criar um link local ou externo para um arquivo CSS que contenha os estilos para aquele documento HTML. Logo, quando se quiser alterar a aparência dos documentos vinculados a este arquivo CSS, basta modifica-lo.

    **Exemplos:**
        
    - Mudar a formatação dos textos (cor, tamanho, fonte, etc);

    - Mudar a cor do fundo da página;

    - Criar divisões na página;

    - Modificar a cor das divisões;

    - Adicionar imagens e/ou vídeos;

    - Adicionar conteúdos de outra página HTML.

**Frameworks CSS**

**Bootstrap**

- O Bootstrap é um framework desenvolvido pelo Twitter, que traz consigo características bem definidas de inicialização rápida, ou seja, possuem estilos predefinidos (prontos). Com a utilização do Bootstrap é possível a criação de sites responsivos, que são aqueles que se adaptam ao tamanho da tela que estará sendo utilizada pelo usuário.

- Abaixo segue como deve ser colocado o link externo para o arquivo CSS:
    ```
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    ```
**MaterializeCSS**

- A utilização do MaterializeCSS facilita a criação de interfaces dentro do padrão do material design feito pela Google, que tem como intuito de unificar a experiência do usuário na usabilidade dos seus softwares seja em smartphones, desktops ou tablets.

- Abaixo segue como deve ser colocado o link externo para o arquivo CSS:
    ```
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css"/>
    ```


    