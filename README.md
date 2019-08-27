<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title> Início | Exotic Pets</title>
    <!-- o primeiro link é o responsável pela folha de estilo feita pelo grupo -->
    <link rel="stylesheet" href="css/estilo.css">
    <!-- o segundo link é o responsável por trazer a folha de estilo de um framework de js -->
    <link rel="stylesheet" href="https://unpkg.com/flickity@2/dist/flickity.min.css">

</head>

<body>
    <header>
        <!-- Logotipo clicável da empresa -->
        <a href="index.html">
            <img src="detalhes/lotipo.png" class="logo" alt="logotipo da empresa">
        </a>
        <!-- a classe push leva o menu para direita -->
        <nav class="menu push">
            <!-- menu -->
            <a href="login.html"> Usuário </a>
            <a href="contato.html"> Fale Conosco</a>
            <a href="sobre.html"> Quem Somos</a>
            <a href="produto.html"> Produtos</a>
            <a href="adote.html"> Adote um Pet </a>

            <!-- fim do menu -->
        </nav>
    </header>

    <main>
        <section>
            <!-- carrosel -->
            <!-- imagem da maletinha: Não é permitida a compra de medicamentos sem prescrição do médico veterinário. -->
            <div class="carousel" data-flickity='{ "imagesLoaded": true, "percentPosition": false }'>
                <img src="imagens/imagens_index/aniversario1_.jpg" alt="Banner de aniversário da empresa Exotic Pets" />
                <img src="imagens/imagens_index/adote_sphynyxx.jpg" alt="Banner contendo anúncio sobre adoção" />
                <img src="imagens/imagens_index/gratuito.jpg" alt="Banner contendo anúncio sobre a empresa" />

            </div>


            <div>
                <!-- tag <hr> esquerda -->
                <hr class="hr-e">
                <!-- tag <hr> da direita -->
                <hr class="hr-d">
                <!-- texto que fica no meio das <hr> -->
                <div class="favorito">
                    <h1>Destaques</h1>
                </div>
            </div>
            <!-- limpa os floats -->
            <div class="clear"></div>

            <div class="item">
                <!-- classe item responsavel pelo posicionamento, dentro dela há a classe imagem 
                responsável pelo espaçamento entre as imagens-->
                <div class="imagem">
                    <a href="adote.html">
                        <img src="imagens/imagens_index/arara.jpg" alt="Foto de uma Arara Canindé">
                        <p>
                            <!-- tag <strong para deixar em negrito> -->
                            <strong>Aves</strong>
                        </p>
                    </a>

                </div>

                <div class="imagem">
                    <a href="adote.html">
                        <img src="imagens/imagens_index/reptil.jpg" alt="Foto de um réptil">
                        <p>
                            <strong>Répteis</strong>
                        </p>
                    </a>

                </div>

                <div class="imagem">
                    <a href="adote.html">
                        <img src="imagens/imagens_index/cavalo_marinho.jpg" alt="Foto de um cavalo marinho branco">
                        <p>
                            <strong>Aquáticos</strong>
                        </p>
                    </a>

                </div>
            </div>

            <div class="form">
                <!-- formulário de novidades -->
                <h2>
                    <img src="detalhes/promo.png" alt="icone de etiqueta">
                    Hey! Fique por dentro das novidades da Exotic Pets!</h2>
                <p>Preencha os campos abaixo com seu nome e endereço de e-mail para receber novidades, promoções
                    e
                    descontos. </p>
                <form id="news">
                    <div class="info">
                        <input type="text" id="nome" placeholder="Digite seu nome.">
                        <input type="email" id="email" placeholder="Digite seu e-mail."> <br>
                        <button type="submit"> Cadastrar</button><br>
                        <p id="resultado"></p>
                    </div>
                </form>
            </div>

        </section>
    </main>

    <footer>
        <!-- Começo do rodapé -->
        <div class="footer">
            <div class="itens-rodape">
                <h2> A Empresa</h2>
                <!-- Links que levam para a página sobre -->
                <a href="sobre.html">Cupom de Desconto</a>
                <br> <a href="sobre.html">Trabalhe conosco</a>
                <br> <a href="sobre.html">Projetos</a>
                <br> <a href="sobre.html">Eventos</a>
                <br> <a href="sobre.html">Sede</a>
                <br> <a href="sobre.html">CNPJ</a>


            </div>

            <div class="itens-rodape">
                <h2> Ajuda e Suporte</h2>
                <!-- Links que levam para a página de contato -->
                <a href="contato.html">Central de Atendimento</a>
                <br> <a href="contato.html">Política de Promoção</a>
                <br> <a href="contato.html">Trocas e Devoluções</a>
                <br> <a href="contato.html">Sistema de Adoções</a>
                <br> <a href="contato.html">Sistema de Compras</a>
                <br> <a href="contato.html">Como comprar</a>
            </div>

            <div class="itens-rodape">
                <h2> Sac Exotics Pets</h2>
                <!-- Links que levam para a página sobre -->
                <a href="sobre.html">(16)66666-6666 - Ribeirão Preto-SP </a>
                <br> <a href="sobre.html">(16)66666-6666- Taquaritinga-SP</a>
                <br> <a href="sobre.html">(16)66666-6666 - Araraquara-SP </a>
                <br> <a href="sobre.html">(11)66666-6666 - Osasco-SP</a>
                <br> <a href="sobre.html">sac@exoticpets.com.br</a>
                <br> De segunda à sábado das 9h00 às 21h00
            </div>

            <div class="itens-rodape center">
                <h2> Meios de Pagamento</h2>
                <!-- ícones dos meios de pagamento -->
                <img src="detalhes/mastercartao.png" alt="ícone do cartão Master Card">
                <img src="detalhes/visacartao.png" alt="ícone do cartão Visa">
                <img src="detalhes/pay.png" alt="ícone do Paypal">
            </div>

            <!-- ícones das redes sociais -->
            <div class="icones">
                <a href="https://facebook.com" target="blamk"><img src="detalhes/facebook.png"
                        alt="ícone do facebook"></a>
                <a href="https://www.instagram.com" target="blamk"><img src="detalhes/instagram.png"
                        alt="ícone do instagram"></a>
                <a href="https://twitter.com/" target="blamk"><img src="detalhes/twitter.png"
                        alt="ícone do twitter"></a>
                <a href="https://www.google.com.br/maps/@-21.42715,-48.5134158,15z" target="blamk"><img
                        src="detalhes/gmaps.png" alt="ícone do google maps"></a>
            </div>
        </div>
        <!-- fim do rodapé -->
    </footer>
    <!-- script do framework -->
    <script src="https://unpkg.com/flickity@2/dist/flickity.pkgd.min.js"></script>
    <!-- link do javascript feito pelo grupo -->
    <script src="JavaScript/function.js"></script>
</body>

</html>
