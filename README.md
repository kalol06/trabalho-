<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./styles/reset.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://unpkg.com/swiper@8/swiper-bundle.min.css" />
    <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="./styles/styles.css">
    <title>Formulário de cadastro</title>
</head>

<body>

    <header class="cabeçalho">
        <div class="container">
            <input type="checkbox" id="menu" class="container__botao">
            <label for="menu" class="container__rotulo">
                <span class="cabeçalho__menu-hamburguer container__imagem"></span>
            </label>
            <ul class="lista-menu">
                <li class="lista-menu__titulo">Categorias</li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Programação</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Front-end</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Infraestrutura</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Business</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Design & UX</a>
                </li>
            </ul>
            <img src="data:image/png;base64,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" alt="Logo do Paranabooks" class="container__imagem">
            <h1 class="container__titulo"><b class="container__titulo--negrito">Paraná</b>Books</h1>
        </div>

        <ul class="opções">
            <input type="checkbox" id="opções-menu" class="opções__botão">
            <li class="opções__item"><a href="#" class="opções__link">Categorias</a></li>
            <li class="opções__item"><a href="#" class="opções__link">Favoritos</a></li>
            <li class="opções__item"><a href="#" class="opções__link">Minha estante</a></li>
        </ul>

        <div class="container">
            <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos"
                    class="container__imagem container__imagem-transparente"></a>
            <a href="#" class="container__link">
                <img src="data:image/png;base64,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" alt="Carrinhos de compras" class="container__imagem">
                <p class="container__texto">Minha sacola</p>
            </a>
            <a href="#" class="container__link">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT1BSwhBSxeXGkgesldeADvBRaalu9H2INYAA&usqp=CAU" alt="Meu perfil" class="container__imagem">
                <p class="container__texto">Meu perfil</p>
            </a>
        </div>
    </header>

    <section class="banner">
        <h2 class="banner__titulo">Tela de cadastro</h2>
    </section>

    <main class="principal">
        <h2 class="principal__titulo">Dados do cadastro</h2>

        <form class="principal__formulario" id="formulario" target="_blank"
            onsubmit="location.replace('./cadastro-finalizado.html')">
            <h3 class="principal__subtitulo">Dados pessoais</h3>
            <div class="formulario__campo">
                <label class="campo__etiqueta" for="nome">Nome Completo</label>
                <input name="nome" id="nome" class="campo__escrita" required />
            </div>
            <div class="formulario__dupla">
                <div class="formulario__campo">
                    <label class="campo__etiqueta" for="nascimento">Nascimento</label>
                    <input name="nascimento" id="nascimento" type="date" class="campo__escrita" required />
                </div>
                <div class="formulario__campo">
                    <label class="campo__etiqueta" for="telefone">Contato</label>
                    <input name="telefone" id="telefone" type="tel" placeholder="(XX) XXXXX-XXXX" class="campo__escrita"
                        required />
                </div>
            </div>
            <div class="formulario__campo">
                <label class="campo__etiqueta" for="email">E-mail</label>
                <input name="email" id="email" type="email" class="campo__escrita" required />
            </div>

            <h3 class="principal__subtitulo">Endereço</h3>

            <div class="formulario__campo">
                <label class="campo__etiqueta" for="cep">CEP</label>
                <input name="cep" id="cep" class="campo__escrita" required />
                <div id="erro"></div>
            </div>

            <div class="formulario__campo">
                <label class="campo__etiqueta" for="endereco">Endereço</label>
                <input name="endereco" id="endereco" class="campo__escrita" required />
            </div>
            <div class="formulario__dupla">
                <div class="formulario__campo">
                    <label class="campo__etiqueta" for="numero">Numero</label>
                    <input name="numero" id="numero" class="campo__escrita" required />
                </div>
                <div class="formulario__campo">
                    <label class="campo__etiqueta" for="complemento">Complemento</label>
                    <input name="complemento" id="complemento" class="campo__escrita" />
                </div>
            </div>
            <div class="formulario__campo">
                <label class="campo__etiqueta" for="bairro">Bairro</label>
                <input name="bairro" id="bairro" class="campo__escrita" required />
            </div>
            <div class="formulario__dupla">
                <div class="formulario__campo">
                    <label class="campo__etiqueta" for="cidade">Cidade</label>
                    <input name="cidade" id="cidade" class="campo__escrita" required />
                </div>

                <div class="formulario__campo">
                    <label class="campo__etiqueta" for="estado">UF</label>
                    <select id="estado" name="estado" class="campo__escrita">
                        <option value="AC">Acre</option>
                        <option value="AL">Alagoas</option>
                        <option value="AP">Amapá</option>
                        <option value="AM">Amazonas</option>
                        <option value="BA">Bahia</option>
                        <option value="CE">Ceará</option>
                        <option value="DF">Distrito Federal</option>
                        <option value="ES">Espírito Santo</option>
                        <option value="GO">Goiás</option>
                        <option value="MA">Maranhão</option>
                        <option value="MT">Mato Grosso</option>
                        <option value="MS">Mato Grosso do Sul</option>
                        <option value="MG">Minas Gerais</option>
                        <option value="PA">Pará</option>
                        <option value="PB">Paraíba</option>
                        <option value="PR">Paraná</option>
                        <option value="PE">Pernambuco</option>
                        <option value="PI">Piauí</option>
                        <option value="RJ">Rio de Janeiro</option>
                        <option value="RN">Rio Grande do Norte</option>
                        <option value="RS">Rio Grande do Sul</option>
                        <option value="RO">Rondônia</option>
                        <option value="RR">Roraima</option>
                        <option value="SC">Santa Catarina</option>
                        <option value="SP">São Paulo</option>
                        <option value="SE">Sergipe</option>
                        <option value="TO">Tocantins</option>
                        <option value="EX">Estrangeiro</option>
                    </select>
                </div>

            </div>


            <input type="submit" value="Enviar formulário" class="formulario__botao" id="enviar">
        </form>
    </main>

    <hr>
    <footer class="rodapé">
        <h2 class="rodapé__titulo">Grupo Paraná</h2>
        <ul class="lista-rodapé">
            <li class="lista-rodapé__titulo">Educação</li>
            <li class="lista-rodapé__item">
                <a href="https://redacao.pr.gov.br/login" class="lista-rodapé__link">REDAÇÃO PARANÁ</a>
            </li>
         
                <a href="https://leiaparana.odilo.us/?locale=pt" class="lista-rodapé__link">LEIA PARANÁ</a>
            </li>
        </ul>

        <ul class="lista-rodapé">
            <li class="lista-rodapé__titulo">Educação online</li>
           
                <a href="https://www.alura.com.br/" class="lista-rodapé__link">ALURA</a>
            </li>
            <li class="lista-rodapé__item">
                <a href="https://accounts.google.com/o/saml2/idp?idpid=C03fukzmn&SAMLRequest=rZJNT%2bMwEIb%2fSuR7PklbajVdtUVokVhR0SwHLpXjTIpF4sl6bBb49Tihy8elpz3EUl7Paz%2fvjBckurbnK2cf9C38cUA2eO5aTXzYKJgzmqMgRVyLDohbyXerX9c8ixIuiMBYhZoFVxcF2zcZzCdyeh7WaVWF%2bdQvVZKIcD6p8%2fl8lsisSlhwB4a8p2D%2bCG8kcnClyQptvZRkZ2GahOmsTDOepjydRfl5nufTyT0LLjyc0sKO7gdre%2bJxLKREpy1FB8RDC5HELsZ4gM9iVfc%2f%2fKfqYpOcNe7xtfOol2gkjHkL1oiWYIDY%2bizqCT6UrUGLEtu10rXSh9N9qN6LiP8sy224vdmVLFj9680GNbkOzA7Mk5Lw%2b%2fb6kx0aVYOLqky2eFB6ZD9qqDslDRI2dpTX2WafrvalcWQvjUf4i%2bZxLQjGqH1MhPHHPOTxTvZllP3pDP0xMFsuhmo%2bzsUMzeqEPW0dFFWHzVjKQVtlX9jyf2ZcxF%2bYlu9%2f39%2fs8g0%3d&RelayState=StateProperties%3deyJUSUQiOiJmZGNjM2UwZC02OTNlLTQ5MjctYmZjOS1mOTgxMDE5MTMwYjcifQ&SigAlg=http%3a%2f%2fwww.w3.org%2f2000%2f09%2fxmldsig%23rsa-sha1&Signature=K1wHKYDP1Ncp1OR19LmjshYErlYbeOrqrA9gEXxeo7MedB8uMBuoyTZgdsqT0oz1rZtSAXwYL1ejPumTEIO1%2fi4P%2bcouiTN5kVnhi5LA%2fusX4Rcn9Kp30R0en7wT4ToF7XoW%2fCRQKHosQTSZvetiiX7PDWQMfsnf1GtQ0p6nuKxKA6xhMI9ixZxSKYhtt2YgeI%2bqEZ0tgEPBKNI4Nl2v8HSgjPuE%2fS1Hc8qV0QLyDnUWGj3gqNwYyxwfUhRGpcf8rfwffwIDFndv6xeQzf1hHpQUmxIfdqC8tsgUZHZ1DJU00ISRebPoGdHRDOYDxLzX14clKgP%2fgxCSMirMrnNlgB%2bB7Jf6Ll2KwhJDz%2fOitbskU84esKZhfBuOqFCyzWhP4%2fHlsu%2fM0vn8X3RjkY%2bsYJa2fWYFimvWj%2bLurDdghPV5e75FVqMzicaSygxn4mG%2btxtKP9BLrSAXEY57Ee0ca58510Em3m9ii%2f7agC8zxjmJemS3dzzjStFhZ%2ft9U9TWlK9pFcjxmk%2bqQKTzDWycn9eeSV%2fj5Oh6m6hWUpBnrCt9ZqEZRINIOfWaSwrZbn%2fJvS4cxe3GAxz6%2bcP8g9xn7Y%2bK%2fEDZmL5LCBSOt4FMEIUJ6khdOP1JDQfi1gUq6iTRCpG9JaKPiB3VkQk73wdB8rSU8OoNwjD9goJSiP9yUao%3d" class="lista-rodapé__link">INGLÊS PARANÁ</a>
            </li>
        </ul>

        <ul class="lista-rodapé">
            <li class="lista-rodapé__titulo">Comunidade</li>
            <li class="lista-rodapé__item">
              
            </li>
            <li class="lista-rodapé__item">
                <a href="https://github.com/" class="lista-rodapé__link">GITHUB</a>
            </li>
           
        </ul>
    </footer>

    <script src="script.js"></script>
</body>

</html>






















.banner {
    background: var(--azul-degrade);
    color: var(--branco);
    text-align: center;
    padding: 1em;
}

.banner__titulo {
    font-size: 18px;
    font-weight: 700;
}

@media screen and (min-width: 1024px) {
    .banner__titulo {
        font-size: 36px;
    }
}
.cadastro {
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 10px;
    padding: 2em;
}

.cadastro__imagem {
    display: block;
    margin: 1em auto 0 auto;
}

.cadastro__subtitulo {
    margin: 1em 0;
}
.principal {
    width: 50vw;
    margin: 5em auto 6em auto;
}

.principal__titulo {
    font-style: normal;
    font-weight: 700;
    font-size: 26px;
    color: var(--laranja)
}

.principal__subtitulo {
    font-weight: 700;
    font-size: 17px;
    line-height: 26px;
    color: var(--azul);
    margin: 3em 0 2em 0;
}

.campo__etiqueta {
    display: block;
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;
    color: var(--azul);
    margin-left: 1em;
}

.campo__escrita {
    border: 1px solid var(--azul);
    border-radius: 24px;
    padding: 1em;
    width: 100%;
}

.formulario__campo {
    margin: .6em 3em .6em 0;

}

.formulario__dupla {
    display: flex;
}

.formulario__botao {
    background: var(--laranja);
    padding: 1em 4em;
    font-weight: 700;
    font-size: 20px;
    line-height: 30px;
    border: none;
    color: var(--branco);
    cursor: pointer;
    float: right;
}

.formulario__erro {
    display: flex;
    margin-top: .5em;
    align-items: center;
}

.erro__imagem {
    width: 10px;
    height: 10px;
    margin: 0 .5em;
    background-image: url('../img/warning.png');
    background-repeat: no-repeat;
    background-size: contain;
}

.erro__texto {
    font-size: 12px;
    line-height: 18px;
    color: var(--vermelho);
}


.container__botao:checked~.container__rotulo>.cabeçalho__menu-hamburguer {
    background-image: url("../img/Menu Aberto.svg");
}

.container__botao:checked~.container__rotulo {
    background: var(--azul-degrade);
}

.cabeçalho {
    background-color: var(--branco);
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
}

.container {
    display: flex;
    align-items: center;
}

.container__imagem {
    padding: 1em;
}

.lista-menu {
    display: none;
    position: absolute;
    top: 100%;
    width: 60vw;
}

.container__botao:checked~.lista-menu {
    display: block;
}

.lista-menu__titulo,
.lista-menu__item {
    padding: 1em;
    background-color: var(--branco);
}

.lista-menu__titulo {
    color: var(--verde);
    font-weight: 800;
}

.lista-menu__link {
    background: var(--azul-degrade);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-transform: uppercase;
}

.container__botao {
    display: none;
}

.container__titulo {
    display: none;
}

.opções {
    display: none;
}

.container__texto {
    display: none;
}

@media screen and (min-width: 1024px) {

    .container__titulo,
    .container__titulo--negrito {
        font-family: var(--fonte-secundario);
        font-size: 30px;
    }

    .container__titulo {
        font-weight: 40;
        display: block;
    }

    .container__titulo--negrito {
        font-weight: 700;
    }

    .opções {
        display: flex;
    }

    .opções__item {
        padding: 0 1em;
        text-transform: uppercase;
    }

    .opções__link {
        text-decoration: none;
        color: var(--preto);
    }

    .container__imagem-transparente {
        display: none;
    }

    .cabeçalho__menu-hamburguer {
        display: none;
    }

    .opções__botão:checked~.lista-menu {
        display: block;
        width: auto;
    }

    .opções__botão {
        display: none;
    }

    .opções__botão:checked~.opções__rotulo>.opções__item {
        background: var(--azul-degrade);
        color: var(--branco);
    }

    .opções__item {
        padding: 2em 1em;
    }

    .lista-menu__item:hover {
        background: var(--azul-degrade);
    }

    .lista-menu__item:hover>.lista-menu__link {
        -webkit-text-fill-color: var(--branco);
        text-decoration: none;
    }

}

@media screen and (min-width: 1728px) {
    .container__link {
        display: flex;
        align-items: center;
        text-decoration: none;
        color: var(--preto);
    }

    .cabeçalho {
        padding: 0 2em;
    }

    .opções {
        margin-right: auto;
    }

    .container__texto {
        display: block;
    }
}
/* http://meyerweb.com/eric/tools/css/reset/
   v2.0 | 20110126
   License: none (public domain)
*/

html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 10%;
    font: inherit;
    vertical-align: baseline;
}

/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
    display: block;
}

body {
    line-height: 1;
}

ol,
ul {
    list-style: none;
}

blockquote,
q {
    quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
    content: '';
    content: none;
}

table {
    border-collapse: collapse;
    border-spacing: 0;
}hr {
    margin: 0;
}

.rodapé {
    background-color: var(--branco);
    padding: 1em;
}

.lista-rodapé {
    display: none;
}

@media screen and (min-width: 1024px) {
    .rodapé {
        display: flex;
        justify-content: space-around;
    }

    .lista-rodapé {
        display: block;
    }

    .lista-rodapé__item {
        display: flex;
        align-items: center;
        margin: 0.6em 0;
    }

    .lista-rodapé__link {
        color: var(--cinza);
        text-decoration: none;
        margin-left: 0.6em;
    }

    .lista-rodapé__titulo {
        font-size: 14px;
        color: var(--cinza-claro);
    }

    .rodapé__titulo {
        font-size: 24px;
    }
}

@media screen and (min-width: 1728px) {
    .lista-rodapé {
        border-left: 1px solid var(--cinza-claro);
        padding-left: 1em;
    }

    .rodapé {
        padding: 3em 0;
    }
}
@import url("header.css");
@import url("banner.css");
@import url("formulario.css");
@import url("rodape.css");
@import url("cadastro.css");

:root {
    --cor-de-fundo: #EBECEE;
    --branco: #FFFFFF;
    --laranja: #EB9B00;
    --azul-degrade: linear-gradient(97.54deg, #002F52 35.49%, #326589 165.37%);
    --fonte-principal: "Poppins";
    --azul: #002F52;
    --fonte-secundario: "Josefin Sans";
    --preto: #000000;
    --cinza: #474646;
    --cinza-claro: #858585;
    --vermelho: #D94937;
}

body {
    background-color: var(--branco);
    font-family: var(--fonte-principal);
    font-size: 16px;
    font-weight: 400;
}.banner {
    background: var(--azul-degrade);
    color: var(--branco);
    text-align: center;
    padding: 1em;
}

.banner__titulo {
    font-size: 18px;
    font-weight: 700;
}

@media screen and (min-width: 1024px) {
    .banner__titulo {
        font-size: 36px;
    }
}
.cadastro {
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 10px;
    padding: 2em;
}

.cadastro__imagem {
    display: block;
    margin: 3em auto 0 auto;
}

.cadastro__subtitulo {
    margin: 1em 0;
}
.principal {
    width: 50vw;
    margin: 5em auto 6em auto;
}

.principal__titulo {
    font-style: normal;
    font-weight: 700;
    font-size: 26px;
    color: var(--laranja)
}

.principal__subtitulo {
    font-weight: 700;
    font-size: 17px;
    line-height: 26px;
    color: var(--azul);
    margin: 3em 0 2em 0;
}

.campo__etiqueta {
    display: block;
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;
    color: var(--azul);
    margin-left: 1em;
}

.campo__escrita {
    border: 1px solid var(--azul);
    border-radius: 24px;
    padding: 1em;
    width: 100%;
}

.formulario__campo {
    margin: .6em 3em .6em 0;

}

.formulario__dupla {
    display: flex;
}

.formulario__botao {
    background: var(--laranja);
    padding: 1em 4em;
    font-weight: 700;
    font-size: 20px;
    line-height: 30px;
    border: none;
    color: var(--branco);
    cursor: pointer;
    float: right;
}

.formulario__erro {
    display: flex;
    margin-top: .5em;
    align-items: center;
}

.erro__imagem {
    width: 10px;
    height: 16px;
    margin: 0 .5em;
    background-image: url('../img/warning.png');
    background-repeat: no-repeat;
    background-size: contain;
}

.erro__texto {
    font-size: 12px;
    line-height: 18px;
    color: var(--vermelho);
}


.container__botao:checked~.container__rotulo {
    background: var(--azul-degrade);
}

.cabeçalho {
    background-color: var(--branco);
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
}

.container {
    display: flex;
    align-items: center;
}

.container__imagem {
    padding: 1em;
}

.lista-menu {
    display: none;
    position: absolute;
    top: 100%;
    width: 60vw;
}

.container__botao:checked~.lista-menu {
    display: block;
}

.lista-menu__titulo,
.lista-menu__item {
    padding: 1em;
    background-color: var(--branco);
}

.lista-menu__titulo {
    color: var(--azul);
    font-weight: 700;
}

.lista-menu__link {
    background: var(--azul-degrade);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-transform: uppercase;
}

.container__botao {
    display: none;
}

.container__titulo {
    display: none;
}

.opções {
    display: none;
}

.container__texto {
    display: none;
}

@media screen and (min-width: 1024px) {

    .container__titulo,
    .container__titulo--negrito {
        font-family: var(--fonte-secundario);
        font-size: 30px;
    }

    .container__titulo {
        font-weight: 400;
        display: block;
    }

    .container__titulo--negrito {
        font-weight: 700;
    }

    .opções {
        display: flex;
    }

    .opções__item {
        padding: 0 1em;
        text-transform: uppercase;
    }

    .opções__link {
        text-decoration: none;
        color: var(--preto);
    }

    .container__imagem-transparente {
        display: none;
    }

    .cabeçalho__menu-hamburguer {
        display: none;
    }

    .opções__botão:checked~.lista-menu {
        display: block;
        width: auto;
    }

    .opções__botão {
        display: none;
    }

    .opções__botão:checked~.opções__rotulo>.opções__item {
        background: var(--azul-degrade);
        color: var(--branco);
    }

    .opções__item {
        padding: 2em 1em;
    }

    .lista-menu__item:hover {
        background: var(--azul-degrade);
    }

    .lista-menu__item:hover>.lista-menu__link {
        -webkit-text-fill-color: var(--branco);
        text-decoration: none;
    }

}

@media screen and (min-width: 178px) {
    .container__link {
        display: flex;
        align-items: center;
        text-decoration: none;
        color: var(--preto);
    }

    .cabeçalho {
        padding: 0 2em;
    }

    .opções {
        margin-right: auto;
    }

    .container__texto {
        display: block;
    }
}
/* http://meyerweb.com/eric/tools/css/reset/
   v2.0 | 20110126
   License: none (public domain)
*/

html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}

/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
    display: block;
}

body {
    line-height: 1;
}

ol,
ul {
    list-style: none;
}

blockquote,
q {
    quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
    content: '';
    content: none;
}

table {
    border-collapse: collapse;
    border-spacing: 0;
}hr {
    margin: 0;
}

.rodapé {
    background-color: var(--branco);
    padding: 1em;
}

.lista-rodapé {
    display: none;
}

@media screen and (min-width: 1024px) {
    .rodapé {
        display: flex;
        justify-content: space-around;
    }

    .lista-rodapé {
        display: block;
    }

    .lista-rodapé__item {
        display: flex;
        align-items: center;
        margin: 0.6em 0;
    }

    .lista-rodapé__link {
        color: var(--cinza);
        text-decoration: none;
        margin-left: 0.6em;
    }

    .lista-rodapé__titulo {
        font-size: 14px;
        color: var(--cinza-claro);
    }

    .rodapé__titulo {
        font-size: 24px;
    }
}

@media screen and (min-width: 1728px) {
    .lista-rodapé {
        border-left: 1px solid var(--cinza-claro);
        padding-left: 1em;
    }

    .rodapé {
        padding: 3em 0;
    }
}
@import url("header.css");
@import url("banner.css");
@import url("formulario.css");
@import url("rodape.css");
@import url("cadastro.css");

:root {
    --cor-de-fundo: #EBECEE;
    --branco: #FFFFFF;
    --laranja: #EB9B00;
    --azul-degrade: linear-gradient(97.54deg, #002F52 35.49%, #326589 165.37%);
    --fonte-principal: "Poppins";
    --azul: #002F52;
    --fonte-secundario: "Josefin Sans";
    --preto: #000000;
    --cinza: #474646;
    --cinza-claro: #858585;
    --vermelho: #D94937;
}

body {
    background-color: var(--branco);
    font-family: var(--fonte-principal);
    font-size: 16px;
    font-weight: 400;
}




















async function buscaEndereco(cep) {
    var mensagemErro = document.getElementById('erro');
    mensagemErro.innerHTML = "";
    try {
        var consultaCEP = await fetch(`https://viacep.com.br/ws/${cep}/json/`);
        var consultaCEPConvertida = await consultaCEP.json();
        if (consultaCEPConvertida.erro) {
            throw Error('CEP não existente!');
        }
        var cidade = document.getElementById('cidade');
        var logradouro = document.getElementById('endereco');
        var estado = document.getElementById('estado');

        cidade.value = consultaCEPConvertida.localidade;
        logradouro.value = consultaCEPConvertida.logradouro;
        estado.value = consultaCEPConvertida.uf;

        console.log(consultaCEPConvertida);
        return consultaCEPConvertida;
    } catch (erro) {
        mensagemErro.innerHTML = `<p>CEP inválido. Tente novamente!</p>`
        console.log(erro);
    }
}

var cep = document.getElementById('cep');
cep.addEventListener("focusout", () => buscaEndereco(cep.value));
