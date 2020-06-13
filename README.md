# Projeto-Web-1
Modificações 07/04/2020
- Imagem_covid-19, retirada da div class="artigo"
- Largura da div  class="artigo" alterada para 90 % para o texto se adequar melhor a tela ao ser minimizado
- Adicionado sombreado na div class= "barra"
- Inserido botões de fonte
- Inserido botões de categoria
- Mudança do titulo do artigo para preto
- largura das imagemns modificadas para 100% para ocuparem todo o espaço da tag figura
- Modificação na barra_autor

 Modificações 14/04/2020
 -  animação dos emojis ao passar em cima , não consegui fazer com que eles movam, quando o mouse é passado em cima do botão
 -  botões das reações ficam azuis  quando pressionados, no entanto quando clicado em outra parte da tela ele perde a cor de background novamente (necessita corrigir isso)
 - Largura do figure alterado para 100% e  inserido margin-left;0px, para que o figure se adeque melhor ao texto
 - removido altura da imagem covid-19, para que se adeque  melhor visualmente ao minimizar a tela 
 - alterado o tamanho da fonte do figcaption
 - inserido alt nas imagens
 
 Modificações 16/04/2020
 - imgs de lupa e seta substituídos por icons, o código origianl foi apenas comentado
 - inserção de itens do comentario que estão abaixo dos botões de reações(necesita corrigir implementação)
 - animação dos emojis agora é realizado quando o mouse está sobre o botão e não apenas na imagem
 <!DOCTYPE html>
<html lang="pt-br">
    <head>
        
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial scale">
        <title>
          Vírus alienígena e arma biológica: as teorias conspiratórias da Covid-19 - Tecmundo
        </title>
        <link rel="shortcut icon" href="img/log.jpg" sizes= "64x64">
        <link rel="stylesheet" href="Style/layout.css">
        
        <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
        <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
        <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css" rel="stylesheet">
        
    </head>

    <input type="checkbox" id="night-mode"class="in">
    <body>
	    <div class="page">
	        <div class= "barra2">
                <div class= "barra2_filho">
                    Vírus alienígena e arma biológica: as teorias conspiratórias da Covid-19
                </div>
                <div class="alinhar modo-noturno">
                     <button class="noturno color-bar">
                        <label for="night-mode">
                            <div class="alinhar night-mode-text"> MODO NOTURNO? </div>
                           <i class="fa fa-moon-o alinhar"></i>
                        </label>
                     </button>
                </div>
      
                <div class="sb save_image">  
                    <i class="fa fa-bookmark-o"></i>
                </div>

                <div class="sb img_share"> 
                    <i class="fa fa-share-alt" ></i>
                </div>
  
            </div>

            <div class="delimeter">
                <div class="barra" >
                    <a href="https://m.tecmundo.com.br/" alt="TecMundo">
                        <div class="tec1" title="TecMundo" >
                            <img class= "logo" src= "img/log.png">
                            <img class= "logo_act" src= "img/log2.jpg"></img>
              
                            tec<span style="font-weight: bold;">mundo</span>
                        </div>
                    </a>
                    <div class="voltar">
                        <a class="button_back back" href="https://m.tecmundo.com.br/">
                            <i class="fa fa-angle-left" style="font-size:30px; color:#1087ff"></i>
                        </a>
                    </div>
                    <div class="search">
                        <a  href="pesquisar.html">
                            <i class="material-icons lupa" style="font-size:30px;color:#1087ff;">search</i>
                        </a>
                    </div>
                </div>
            
       
                <img  class="imagem"src="img/imagem_covid-19.jpg"  alt="Imagem de:Vírus alienígena e arma biológica: as teorias conspiratórias da Covid-19" >
            </div>
            <div class= "artigo">
                <div class="barra_autor"><!--Incompleto , necessita inserir outros componemtes e corrigir o posicionamneto e tamanho da imagem, perfil do autor-->
                    <div class="perfil_autor">
            
                        <div class= perfil_autor_image>
                            <a href="https://www.tecmundo.com.br/autor/788-diego-denck-via-nexperts">
                                <img src="img/avatar-editor.svg" alt="Avatar">
                            </a>
                        </div>
                        <div class="perfil_autor_text"> 
                            <a href="https://www.tecmundo.com.br/autor/788-diego-denck-via-nexperts">
							    <p class="text"style="font-weight: bold;"> Diego Denck </p>
						    </a>
                            <p class="text link">via 
							    <a href="https://nexperts.co/" target="blank">nexperts</a> 
							</p>
                        </div>
                    </div>
                    <div class="comment">
                        <a href="#comments" >
                            <button type="button" >
                                <div class= comment_image>  
                                    <i class="material-icons"  style="font-size:21px;">chat_bubble_outline</i>
                                </div>
                                <div class="comment_text">
                                    0 Comentários
                                </div>                                            
                            </button> 
                        </a>
                    </div>
                    <div class="share"> 
                        <button type="button">
                            <div class= "share_image">  
                                <i class="fa fa-share-alt" style="font-size:20px;"></i>
                            </div>
                            <div class="share_text">
                                0 Compartilharam 
                            </div>
                        </button>  
                    </div>
					<!--modificado-->
                </div>
                <h1>Vírus alienígena e arma biológica: as teorias conspiratórias da Covid-19</h1>
                <div class="data">
                    <p ><b>20/03/2020</b> às 22:00  •  <b>3 mim</b> de leitura </p> 
                </div>
         
        
                <p>
				    A pandemia de coronavírus tem levado pânico à população mundial. Como a  doença surgiu e se espalhou muito
                    rapidamente, diversas teorias da conspiração tentaram explicar a origem da Covid-19. Uma das que 
                    mais circulou nas <a href="https://www.tecmundo.com.br/redes-sociais/"target ="blank" title="Redes sociais">redes sociais</a> 
                    – e no <a href="https://www.tecmundo.com.br/whatsapp/" target="blank" title="WhatsApp">WhatsApp</a>,
                    claro – foi a de que a doença seria uma arma
                    alienígena para destruir a humanidade.
				</p>
                <p>
				    Quem começou essa história foi o astrônomo e astrobiólogo Chandra Wickamasinghe.
                    Nascido no Sri Lanka, em 1939, o cara jura que a Covid-19 chegou à Terra em      outubro de 2019 junto a
                    um asteroide que teria caído justamente na China. Essa não seria a primeira vez
                    que um evento desses teria ocorrido, com outras
                    pandemias supostamente tendo origem extraterrestre.
		    
                </p>
                <figure>
                    <img src="img/image_Chandra_Wickmasinge.jpg" width="100%" alt="Astrobiólogo Chandra Wickamasinghe acredita em origem extraterrestre">
                    <figcaption><!--Legenda da imagem-->
                        <p>Astrobiólogo Chandra Wickamasinghe acredita em origem extraterrestre</p>
                        <p>Fonte:  <a href="https://en.wikipedia.org/wiki/Chandra_Wickramasinghe#/media/File:Chandra-Wickramasinghe.jpg" target="blank">Wikimedia</a> </p>
                    </figcaption>

                </figure>
      
                <p>
		            A síndrome respiratória aguda grave (SARS), de 2002, também surgiu na China e, de acordo com Wickamasinghe, veio de
                    fora da Terra. Ele tem uma certa fascinação nessa crença, tanto que nos anos 1970 escreveu um livro chamado
                    “Doenças do Espaço”, tentando provar como algumas das mais mortais enfermidades, como a gripe, vieram de regiões
                     distantes no Universo.
                </p>
                <p>
                    O astrobiólogo, no entretanto, não sabe explicar como o vírus teria sobrevivido à radiação sofrida durante toda a
                    sua jornada até aqui e nem como teria infectado os humanos após o choque com a Terra. Por conta disso, ele é bastante
                    desacreditado dentro da comunidade científica internacional, mas faz sucesso     entre os fanáticos por teorias de conspiração.
                </p>
                <p>
                    A teoria de Wickamasinghe se baseia na ideia de que toda a vida terrestre, na verdade, é extraterrestre.
                    Isto é: a vida por aqui teria surgido através de micro-organismos provenientes do espaço. Muitos 
                    cientistas tentam provar essa teoria, chamada de panspermia. Até agora, não obtiveram sucesso.
                </p>
                <figure>
                    <img src="img/image_terra_asteroide.jpg" width="100%" alt="Covid-19 teria vindo junto com asteroide? Improvável!">
                    <figcaption><!--Legenda da imagem-->
                        <p>Covid-19 teria vindo junto com asteroide? Improvável!</p>
                        <p>Fonte:  <a href="https://pixabay.com/pt/photos/aster%C3%B3ide-cometa-meteorito-3628185/" target="blank">Pixabay</a> </p>
                    </figcaption>
                </figure> 
      
                <h2>Arma bioquímica</h2>
                <p> 
		            Outra teoria conspiratória muito popular referente ao <a href="https://www.tecmundo.com.br/coronavirus/" target="blank" title="Coronavírus">coronavírus</a> é de que ele teria sido criado em laboratório para
                    ser uma arma bioquímica. Estados Unidos e China acusaram um ao outro de ter criado o vírus que causou a pandemia.
                    Até mesmo gente importante entrou nessa briga, como o senador norte-americano Tom Cotton, que publicou um tweet em
                    que diz que Wuhan, onde a Covid-19 surgiu, é o único lugar do país que possui um superlaboratório de biossegurança,
                    tentando correlacionar os fatos.
                </p>
                <p>
                    De fato, esse lugar existe, mas sua segurança é tão 
                    grande que o vazamento de qualquer patógeno seria impossível. Outras instalações parecidas, de segurança máxima,
                    existem em vários lugares do mundo, inclusive nos Estados Unidos.
                </p>
                <p>
                    Já alguns representantes da China acusam o país de Trump de deliberadamente ter criado a Covid-19 em laboratório e soltado em seu território. Faria sentido os Estados Unidos 
                    soltarem um vírus tão contagioso em solo chinês sendo que rapidamente ele voltaria ao território norte-americano? Não faria,
                    mas tem gente que acredita piamente nisso.
                </p>
                <figure>
                    <img src="img/covid-19_2.jpg" width="100%" alt="Alguns acreditam que a Covid-19 é uma arma biológica norte-americana soltada deliberadamente na China">
                    <figcaption><!--Legenda da imagem-->
                        <p>Alguns acreditam que a Covid-19 é uma arma biológica norte-americana soltada deliberadamente na China</p>
                        <p>Fonte:  <a href="https://pixabay.com/pt/photos/coronav%C3%ADrus-v%C3%ADrus-pandemia-china-4810201"target="blank">Pixabay</a> </p>
                    </figcaption>
                </figure>
        
                <h2>Afinal, qual a origem?</h2>
                <p>
		            De acordo com pesquisadores da revista Nature Medicine, a Covid-19 surgiu através da evolução. Ou seja, um evento extremamente terrestre e natural.
                    Através do mapeamento genético do vírus, foi possível determinar que ele não tem nenhum traço de manipulação laboratorial e muito menos alienígena.
               </p>
               <p>
		            <span style="font-weight:bold" >Veja também: </span> <!--Deixa em negrito, css interno-->
                    <a href="https://www.tecmundo.com.br/ciencia/151215-estudo-revela-coronavirus-nao-feito-laboratorio.htm" 
                    target="blank" title="Estudo revela: coronavírus não foi feito em laboratório">
                        Estudo revela: coronavírus não foi feito em laboratório
                    </a>
                </p>

                <p>
                    Os coronavírus fazem parte de uma família de vírus que podem gerar doenças com diferentes graus de gravidade.
                    A SARS, por exemplo, foi causada por um tipo de coronavírus e infectou 8 mil pessoas, matando 800 delas.
                    Acredita-se que esta tenha surgido em mutações dentro de civetas-africanas – uma espécie de gato
                    selvagem – infectadas por morcegos. Posteriormente, ao serem comercializadas em mercados,
                    acabaram infectando o homem.
                </p>
                <p>
                    Como os primeiros doentes pela Covid-19 frequentaram o mesmo mercado de Wuhan,
                    é mais provável que a sua origem seja semelhante à da SARS. Não se sabe, entretanto, 
                    quais seriam os hospedeiros não humanos que originalmente causaram a mutação que acabou 
                    atingindo os humanos. O mais provável é que novamente tenha vindo dos morcegos, já que o mapeamento
                    genético da Covid-19 é bastante similar aos coronavírus encontrados nesses mamíferos voadores.
      
                </p>
                <p>
                    Outra possibilidade é que o coronavírus tenha saltado de um hospedeiro animal para os humanos
                    para daí sofrer a mutação que o tornou tão contagioso. Ainda será preciso mais algumas pesquisas 
                    científicas para determinar se uma dessas duas teorias está correta, mas dificilmente será algo 
                    diferente disso.
                </p>
                <p>
		            <span style="font-weight:bold" >Leia também:</span>
                    <a href="https://www.tecmundo.com.br/ciencia/151189-quantos-morrer-coronavirus-brasil-cientistas-respondem.htm"
                    target="blank" title=" Quantos podem morrer pelo coronavírus no Brasil? Cientistas respondem!">
                    <!-- target ="blank", faz com que o link seja aberto em outra aba-->
                    Quantos podem morrer pelo coronavírus no Brasil? Cientistas respondem!</a> 
                </p>
                <p>
                    Cupons de desconto TecMundo:
                </p>
                <ul>
                    <li><a title="Cupom Americanas" href="https://www.tecmundo.com.br/cupons/lojas/americanas">Cupom Americanas App com R$20 OFF </a></li>
                    <li><a title="Cupom Casas Bahia" href="https://www.tecmundo.com.br/cupons/lojas/casas-bahia">Cupom Casas Bahia: Até R$100 OFF em Smartphones</a></li>
                    <li><a title="Cupom AliExpress" href="https://www.tecmundo.com.br/cupons/lojas/ali-express">Cupom AliExpress Primeira compra com R$10 de desconto</a></li>
                    <li><a title="Cupom de desconto Carrefour" href="https://www.tecmundo.com.br/cupons/lojas/carrefour">Desconto Carrefour Smart TVs: até 35% OFF</a></li>
                    <li><a title="Cupom KaBuM" href="https://www.tecmundo.com.br/cupons/lojas/kabum">Cupom KaBuM! primeira compra 5% de desconto</a></li>
                </ul>
                <div class="fonte"> 
                    <p>Fonte</p>
                    <a  title="Ir para: Space.com" class ="link_button" href="https://www.space.com/coronavirus-not-from-outer-space.html" target="blank">
                        Space.com
                    </a>
                    <a  title="Ir para: Science Dayle" class ="link_button" href="https://www.sciencedaily.com/releases/2020/03/200317175442.htm" target="blank">
                        Science Dayle
                    </a> 
                    <a title="Spiegel" class ="link_button" href="https://www.spiegel.de/consent-a-?targetUrl=https%3A%2F%2Fwww.spiegel.de%2Finternational%2Fgermany%2Fconspiracy-theories-in-the-age-of-covid-19-a-86ed07e7-7009-405c-a1c7-58e83f6ab790&ref=https%3A%2F%2Fm.tecmundo.com.br%2Fciencia%2F151284-virus-alienigena-arma-biologica-teorias-conspiratorias-covid-19.htm" target="blank">
                        Spiegel
                    </a>
                    <a  title ="Ir para: Forbes" class ="link_button" href="https://www.forbes.com/sites/brucelee/2020/03/17/covid-19-coronavirus-did-not-come-from-a-lab-study-shows-natural-origins/#72a17ee83728https://www.forbes.com/sites/brucelee/2020/03/17/covid-19-coronavirus-did-not-come-from-a-lab-study-shows-natural-origins/#72a17ee83728" target="blank" >
                        Forbes
                    </a> 
                </div>
                <div class="categoria">
                    <p>Categoria</p>
                    <a title="Ir para:Ciência" class ="link_button" href= "https://m.tecmundo.com.br/ciencia" >
                        Ciência
                    </a>
                    <a title="Ir para: Coronavírus" class ="link_button" href="https://m.tecmundo.com.br/coronavirus">
                        Coronavírus
                    </a> 
                    <a  title="Ir para:Conspirações" class ="link_button" href="https://m.tecmundo.com.br/conspiracoes">
                        Conspirações
                    </a>
                    <a  title ="Ir para: Curiosidades" class ="link_button" href="https://m.tecmundo.com.br/curiosidades">
                        Curiosidades
                    </a> 
                </div>

                <div class= "rel_vej_nov">
                    <p class="rvj">Relacionados</p>
                    <div class="relat">
                        <div class="text1">
                            <a class="link_tex" href="https://m.tecmundo.com.br/mercado/151283-senado-aprova-estado-calamidade-publica-videoconferencia.htm">
                                Senado aprova estado de calamidade pública por videoconferência
                            </a>
                        </div>
                      
                        <p class="date_rel">20/3/2020</p>
                        <ul class="days">
                            <li>há 27 dias</li>
                        </ul>
                        <div class="save">
                            <i class="fa fa-bookmark-o" style="font-size:14px;"></i>
                        </div>
                        <div class= "redirect">
                            <a  href="https://m.tecmundo.com.br/mercado/151283-senado-aprova-estado-calamidade-publica-videoconferencia.htm">
                                <img title="Ir para: Senado aprova estado de calamidade pública por videoconferência" src="img/relac/1_img.jpg">
                            </a>
                        </div>
                    </div>
    
                    <div class="relat">
                        <div class="text1">
                            <a class="link_tex" href="https://www.minhaserie.com.br/novidades/51151-chicago-fire-atriz-deixa-o-elenco-da-serie-apos-duas-temporadas">
                               Chicago Fire: atriz deixa o elenco da série após duas temporadas
                            </a>
                        </div>
              
                        <div class= "redirect">
                            <a  href="https://www.minhaserie.com.br/novidades/51151-chicago-fire-atriz-deixa-o-elenco-da-serie-apos-duas-temporadas">
                                <img title="Ir para: Chicago Fire: atriz deixa o elenco da série após duas temporadas" src="img/relac/2_img.jpg">
                            </a>
                        </div>
                    </div>
          
                    <div class="relat">
            
                        <div class="text1">
                            <a class="link_tex" href="https://m.tecmundo.com.br/cultura-geek/151280-the-mandalorian-serie-tera-rosario-dawson-ahsoka-tano.htm">
                                The Mandalorian: série terá Rosario Dawson como Ahsoka Tano
                            </a>
                        </div>
            
                        <p class="date_rel">20/3/2020</p>
                        <ul class="days">
                            <li>há 27 dias</li>
                        </ul>
                        <div class="save">
                            <i class="fa fa-bookmark-o" style="font-size:14px;"></i>
                        </div>
                        <div class= "redirect">
                            <a  href="https://m.tecmundo.com.br/cultura-geek/151280-the-mandalorian-serie-tera-rosario-dawson-ahsoka-tano.htm">
                            <img title="Ir para: The Mandalorian: série terá Rosario Dawson como Ahsoka Tano" src="img/relac/3_img.jpg">
                            </a>
                        </div>
                    </div>

                    <div class="relat">
                        <div class="text1">
                            <a class="link_tex" href="https://m.tecmundo.com.br/redes-sociais/151277-tinder-libera-passaporte-graca-durante-quarentena.htm">
                                Tinder libera Passaporte de graça para todos durante a quarentena
                            </a>
                        </div>
            
                        <p class="date_rel">20/3/2020</p>
                        <ul class="days">
                            <li>há 27 dias</li>
                        </ul>
                        <div class="save">
                            <i class="fa fa-bookmark-o" style="font-size:14px;"></i>
                        </div>
                        <div class= "redirect">
                            <a  href="https://m.tecmundo.com.br/redes-sociais/151277-tinder-libera-passaporte-graca-durante-quarentena.htm">
                                <img title="Ir para: Tinder libera Passaporte de graça para todos durante a quarentena" src="img/relac/4_img.jpg">
                            </a>
                        </div>
                    </div>

                    <div class="relat">
                        <div class="text1">
                            <a class="link_tex" href="https://m.tecmundo.com.br/ciencia/151273-quarentena-homem-leva-cao-passear-drone.htm">
                                Em quarentena, homem leva cão para passear de drone
                            </a>
                        </div>
            
                        <p class="date_rel">20/3/2020</p>
                        <ul class="days">
                            <li>há 27 dias</li>
                        </ul>
                        <div class="save">
                            <i class="fa fa-bookmark-o" style="font-size:14px;"></i>
                        </div>
                        <div class= "redirect">
                            <a  href="https://m.tecmundo.com.br/ciencia/151273-quarentena-homem-leva-cao-passear-drone.htm">
                                <img title="Ir para: Em quarentena, homem leva cão para passear de drone" src="img/relac/5_img.jpg">
                            </a>
                        </div>
                    </div>

                    <p class="rvj">Veja também</p>
                    <div class="veja" title="O segredo para comprar na Amazon que as pessoas não sabem">
                        <a  href="https://www.cuponomia.com.br/lpage/dincriveis_amazon?utm_source=taboola&utm_medium=Display&utm_campaign=INST_Ampla_D&utm_term=gruponzn-tecmundo&utm_content=tecmundo.com.br">
                            <div class="text2" >
                                <p class="ti">O segredo para comprar na Amazon que as pessoas não sabem</p>
                        
                            </div>
						</a>
                        <p class="pat">PATROCINADO</p>
                        <ul class="list">
                            <li>Cuponomia</li>
                        </ul>
                        <div class= "redirect">
                            <img  src="img/veja/1_img.png">
                        </div>
                        
                    </div>

                    <div class="veja" title="Poliglota de 22 anos ensina inglês em 8 semanas e vira febre na internet">
                        <a  href="https://www.metodoinglesrapido.com.br/ingles-tab-7/?src=TabdarkvicDesk_011119|gruponzn-tecmundo|Poliglota+de+22+anos+ensina+ingl%C3%AAs+em+8+semanas+e+vira+febre+na+internet|http%3A%2F%2Fcdn.taboola.com%2Flibtrc%2Fstatic%2Fthumbnails%2F3ff7a188d10814c888320231f31d4c54.jpeg">
                            <div class="text2">
                                <p class="ti">Poliglota de 22 anos ensina inglês em 8 semanas e vira febre na internet</p>
                        
                            </div>
						</a>
                        <p class="pat">PATROCINADO</p>
                        <ul class="list">
                            <li>Método Inglês Rápido</li>
                        </ul>
                        <div class= "redirect">
                            <img  src="img/veja/2_img.png">
                        </div>
                        
                    </div>


                    <div class="veja" title="Adeus dor nas juntas! Anvisa desenvolve pílula alemã que 'engrossa' cartilagem">
                        <a  href="https://blog2.noticia-agora.com/articaps-capsula-da-cartilagem-mae-sub/?p=tab&cep=ClskO76w6DYvjqzZHvvTFKAmJwA2MUv0we9uZgzGaow-bEOSkwCuRcI596M1Nn3nSe1zFT4tiHHTtP-N2GYtGXl_KkmbCFkezKFpMyhWerGeh2XnuBW08WLlVyi2AqBzpI20brHHgBnK-3VlI4go4sZAUD6Ji3xnwE9qDgfWhM9id15Q6ZDSlwyeparYVSrntRVgpSTPM5VlC0VV2wd4TBVpT8X14hZLCjip0XS2le8geFaBoX2mm_JLmLKc4FKJ4yup1t5_OdyMd8hQzrtxfpC4UsIpqbVj2o8obAJ4hNbQy-AW_7C5Q2HtWJ6e70DGIGXTYvNjySEJcg0yTVUpRgWHrQnjHm494OCLWlOSNUeFv9orA3NXrfmwzKdLw-CyBUOrKEqgiylR5Q3gfC13wzE6oSaX7P3slW2XvYvLO-slQFpOjVtJXCJr_7KN4tk9GhEWqtn4tFoqu1mD1cI568rBpzrt1qb6Lnsb3kWKBKYYkpubqB79EPbhaoPGMl-5NTdCec4Pqw9g3stU_tysZuye6Dht_6TrrrYYZUNtzv8GVfeweRCdwMAoGL96ZyU_8q_1HM7sKvR7hYQbzGGpvQ&lptoken=15d587d5698643c9330b&img=108&h=34&utm_source=taboola&utm_medium=gruponzn-tecmundo&utm_campaign=3616096&utm_content=Adeus%20dor%20nas%20juntas!%20Anvisa%20libera%20p%C3%ADlula%20alem%C3%A3%20que%20%22engrossa%22%20cartilagem">
                            <div class="text2" >
                                <p class="ti">Adeus dor nas juntas! Anvisa desenvolve pílula alemã que "engrossa" cartilagem</p>
                        
                            </div>
						</a>
                        <p class="pat">PATROCINADO</p>
                        <ul class="list">
                            <li>Articaps</li>
                        </ul>
                         <div class= "redirect">
                            <img  src="img/veja/3_img.png">
                        </div>
                        
                    </div>


                    <div class="veja" title="Cabelo pode crescer nas entradas: Anvisa libera tônico para calvice e queda">
                        <a  href="https://ciencia-hoje.com/cabelo-entradas/?utm_source=taboola&utm_medium=HAIR-MAN-DESK-1&utm_campaign=gruponzn-tecmundo">
                            <div class="text2" >
                                <p class="ti">Cabelo pode crescer nas entradas: Anvisa libera tônico para calvice e queda</p>
                        
                            </div>
						</a>
                        <p class="pat">PATROCINADO</p>
                        <ul class="list">
                            <li>Hair Power</li>
                        </ul>
                        <div class= "redirect">
                            <img  src="img/veja/4_img.png">
                        </div>
                        
                    </div>
                </div>
        
        

                <p class="rvj">Novidades</p>
                <div class="relat">
            
                    <div class="text1">
                        <a class="link_tex" href="https://m.tecmundo.com.br/seguranca/152219-sharenting-brasileiros-expoem-filhos-web-entender-riscos.htm">
                            Sharenting: brasileiros expõem filhos na web entender riscos
                        </a>
                    </div>
                    <p class="date_rel">19/4/2020</p>
                    <ul class="days">
                        <li>há 11 minutos</li>
                    </ul>
                    <div class="save">
                        <i class="fa fa-bookmark-o" style="font-size:14px;"></i>
                    </div>
                    <div class= "redirect">
                        <a  href="https://m.tecmundo.com.br/seguranca/152219-sharenting-brasileiros-expoem-filhos-web-entender-riscos.htm">
                            <img title="Ir para: Sharenting: brasileiros expõem filhos na web entender riscos" src="img/nov/1_img.jpg">
                        </a>
                    </div>
                </div>
        
                <div class="relat">
                    <div class="text1">
                        <a class="link_tex" href="https://m.tecmundo.com.br/mercado/152208-youtube-paga-mil-100-mil-1-milhao-visualizacoes.htm">
                            Quanto o YouTube paga por mil, 100 mil e 1 milhão de visualizações?
                        </a>
                    </div>
                    <p class="date_rel">19/4/2020</p>
                    <ul class="days">
                        <li>há 2 horas</li>
                    </ul>
                    <div class="save">
                        <i class="fa fa-bookmark-o" style="font-size:14px;"></i>
                    </div>
                    <div class= "redirect">
                        <a  href="https://m.tecmundo.com.br/mercado/152208-youtube-paga-mil-100-mil-1-milhao-visualizacoes.htm">
                            <img title="Ir para: Quanto o YouTube paga por mil, 100 mil e 1 milhão de visualizações?" src="img/nov/2_img.jpg">
                       </a>
                    </div>
                </div>

                <div class="relat">
                    <div class="text1">
                        <a class="link_tex" href="https://m.tecmundo.com.br/redes-sociais/152198-salvar-video-rascunho-tiktok.htm">
                            Como salvar vídeo rascunho no TikTok
                        </a>
                    </div>
          
                    <p class="date_rel">19/4/2020</p>
                    <ul class="days">
                        <li>há 4 horas</li>
                    </ul>
                    <div class="save">
                        <i class="fa fa-bookmark-o" style="font-size:14px;"></i>
                    </div>
                    <div class= "redirect ">
                        <a  href="https://m.tecmundo.com.br/redes-sociais/152198-salvar-video-rascunho-tiktok.htm">
                            <img title="Ir para: Como salvar vídeo rascunho no TikTok" src="img/nov/3_img.jpg">
                        </a>
                    </div>
                </div>

                <div class="relat">
       
                    <div class="text1">
                        <a class="link_tex" href="https://m.tecmundo.com.br/software/152196-deep-learning-ajudar-autoridades-durante-pandemia.htm">
                            Como o deeping learning pode ajudar autoridades durante a pandemia?
                        </a>
                    </div>
          
                    <p class="date_rel">20/3/2020</p>
                    <ul class="days">
                        <li>há 27 dias</li>
                    </ul>
                    <div class="save">
                        <i class="fa fa-bookmark-o" style="font-size:14px;"></i>
                    </div>
                    <div class= "redirect">
                         <a  href="https://m.tecmundo.com.br/software/152196-deep-learning-ajudar-autoridades-durante-pandemia.htm">
                            <img title="Ir para: Como o deeping learning pode ajudar autoridades durante a pandemia?" src="img/nov/4_img.jpg">
                        </a>
                    </div>
                </div>


        

                <div id="comments">
                    <p class="comentario"> Coméntarios</p>
                    <p class="comments_text" style=" font-weight: 600;"> O que você achou ?</p>
                    <p class="comments_text"> 61 respostas</p>
                    <div class="reactions">
                        <input type="radio"  id="upvote-radio" name="reactions-buttons" class="in">
                        <div class=" reaction upvote">
                            <button type="button" class=" btn-secondary">
                                <label for="upvote-radio">
                                    <div class=" reaction upvote_image">
                                        <img src="img/upvote-512x512.png">
                                    </div>
                                    <div class=" reaction reaction_text"> 
                                        Curtir
                                    </div>                                 
                                </label>
                            </button>
                            <div>28</div>
                        </div>
                        <input type="radio"  id="funny-radio" name="reactions-buttons" class="in">
                        <div class=" reaction funny">
                            <button type="button" class=" btn-secondary">
                                <label for="funny-radio">
                                    <div class=" reaction funny_image">
                                        <img src="img/funny-512x512.png">
                                    </div>
                                    <div class=" reaction reaction_text"> 
                                        Engraçado
                                    </div>

                                </label>
                                
                            </button>
                        
                            <div>5</div>
                        </div>
                        <input type="radio"  id="love-radio" name="reactions-buttons" class="in">
                        <div class=" reaction love">
                            <button type="button" class=" btn-secondary">
                                <label for="love-radio">
                                    <div class="reaction love_image">
                                        <img src="img/love-512x512.png" >
                                    </div>
                                    <div class="reaction reaction_text"> 
                                        Amei
                                    </div>

                                </label>
                               
                            </button>
                            <div>2</div>
                        </div>
                        <input type="radio"  id="surprised-radio" name="reactions-buttons" class="in">
                        <div class="reaction surprised">
                            <button type="button" class=" btn-secondary">
                                <label for="surprised-radio">
                                    <div class="reaction surprised_image">
                                        <img src="img/surprised-512x512.png.">
                                    </div>
                                    <div class=" reaction reaction_text"> 
                                        Surpreso
                                    </div>
                                </label>
                            </button>
                            <div>6</div>
           
                        </div> 
                        <input type="radio"  id="angry-radio" name="reactions-buttons" class="in">       
                        <div class=" reaction angry">
                            <button type="button" class=" btn-secondary">
                                <label for="angry-radio">
                                    <div class="reaction angry_image">
                                        <img src="img/angry-512x512.png" >
                                    </div>
                                    <div class="reaction reaction_text"> 
                                        Irritado
                                    </div>
                                </label>
                            </button>
                            <div>4</div>
                        </div>
                        <input type="radio"  id="sad-radio" name="reactions-buttons" class="in">        
                        <div class="reaction sad">
                            <button type="button" class=" btn-secondary">
                                <label for="sad-radio">
                                    <div class="reaction sad_image">
                                        <img src="img/sad-512x512.png">
                                    </div>
                                    <div class="reaction reaction_text"> 
                                        Triste
                                    </div>
                                </label>

                            </button>
                            <div>16</div>
                        </div>       
                                
                               
                           
                    </div>
                    <div  class=" comentarios"><!--itens de comentário1-->
                        <div  class=" comentarios-tecmundo quantidade-de-comentarios">
                            <div class="alinhar omitir">0</div>
                            <div class="alinhar"> COMENTÁRIOS</div>
                        </div>
                        <div class="comentarios-tecmundo omitir">
                            <a href="https://disqus.com/home/forums/tecmundo/" target="_blank">TecMundo</a>
             
                        </div>
                        <div class="comentarios-tecmundo ">
                            <a href="https://help.disqus.com/en/articles/1717103-disqus-privacy-policy" target="_blank" title="Disqus's Privacy Policy">
                                <div class="alinhar"><i class="fa fa-lock"> </i></div> 
								<div class=" alinhar omitir">Política de privacidade </div>  
                            </a>
                        </div>
                       <div class="comentarios-tecmundo iniciar-sessao">
                            <div class="dropdown"> 
                                <button>Iniciar sessão <i class="fa fa-caret-down"></i></button>
                                <div class="dropdown-content">
                                    <a target="_blank" href="https://disqus.com/next/login/?forum=tecmundo&evs=bmV0d29ya19kZWZhdWx0X2hpZGRlbjpmYWxsdGhyb3VnaDpkeW5hbWlj#!auth%3Astart">Disqus</a>
                                    <a target="_blank" href="https://disqus.com/_ax/facebook/begin/?forum=tecmundo&ctkn=qyvr7BxXekWdC4fxFnf3OADIXKI4gshi&evs=bmV0d29ya19kZWZhdWx0X2hpZGRlbjpmYWxsdGhyb3VnaDpkeW5hbWlj">Facebook</a>
                                    <a target="_blank" href="https://api.twitter.com/oauth/authenticate?oauth_signature_method=HMAC-SHA1&oauth_signature=%2FwhJxbabgHyB9fuKIV7QyLu2%2Bto%3D&oauth_token=LkOqFgAAAAAAAAsqAAABcYWwnqg&oauth_callback=https%3A%2F%2Fdisqus.com%2F_ax%2Ftwitter%2Fcomplete%2F%3Fstate%3Dqyvr7BxXekWdC4fxFnf3OADIXKI4gshi%26evs%3DbmV0d29ya19kZWZhdWx0X2hpZGRlbjpmYWxsdGhyb3VnaDpkeW5hbWlj%26forum%3Dtecmundo&lang=en_US">Twitter</a>
                                    <a target="_blank" href="https://accounts.google.com/signin/oauth?client_id=508198334196-bgmagrg0a2rub674g0shidj8fnd50dji.apps.googleusercontent.com&state=%7B%22ctkn%22:%22qyvr7BxXekWdC4fxFnf3OADIXKI4gshi%22%7D&redirect_uri=https://disqus.com/_ax/google/complete/&response_type=code&hl=en_US&scope=openid+email+profile&o2v=2&as=gpF46e3S2Vc6JeN46FOF9Q">Google</a>
                                </div>
                            </div> 
                        </div>
                    </div>
                    <div class=" itens"><!--itens de comentário 2-->
                        <div class=" item recomendar" title="Recomendar este debate">
                            <div class="item recomendar-img">
                                <i class="fa fa-heart-o"></i>
                            </div>
                            <div class="item recomendar-text mudar-cor">
                                Recomendar
                            </div>
                        </div>
                        <div class=" item remover-efeito twitter omitir">
                            <a href="https://twitter.com/intent/tweet?url=http%3A%2F%2Fdisq.us%2Ft%2F3n2wnga&text=V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19" 
                            target="_blank">
                                <button >
                                    <div class="item item-text">
                                        <i class="fa fa-twitter" style="font-size:15px"></i>
                                    </div>
                                    <div class="item item-text">
                                        Tweet
                                    </div>
               
                                </button>
                            </a>
                        </div>
                        <div class=" item remover-efeito facebook omitir">
                            <a href="https://web.facebook.com/login.php?skip_api_login=1&api_key=966242223397117&signed_next=1&next=https%3A%2F%2Fweb.facebook.com%2Fsharer.php%3Fu%3Dhttp%253A%252F%252Fdisq.us%252Ft%252F3n2wnga&cancel_url=https%3A%2F%2Fweb.facebook.com%2Fdialog%2Fclose_window%2F%3Fapp_id%3D966242223397117%26connect%3D0%23_%3D_&display=popup&locale=pt_BR"
                            target="_blank">
                                <button>
                                    <div class="item item-text">
                                        <i class="fa fa-facebook"></i>
                                    </div>
                                    <div class="item item-text">
                                        Partilhar
                                    </div>
                                </button>
                            </a>
                        </div>
                        <div class=" item ordem-comentarios mudar-cor">
                        <!--  <label for="order-comments"> Mostrar primeiro os </label>
                        <select class="item mudar-cor" name="ordem dos comentarios" id="order-comments" >
                            <option  class= "opcao" value="mais votados"> mais votados</option>
                            <option  class= "opcao" value=" mais recentes"> mais recentes</option>
                            <option class= "opcao" value="mais atigos"> mais antigos</option>
                        </select>-->
                            <div class="dropdown">
                                <button>Mostrar primeiro os mais votados <i class="fa fa-caret-down"></i></button>
                                <div class="dropdown-content comments-order">
                                    <a  target="_parent" href="https://disqus.com/embed/comments/?base=default&f=tecmundo&t_u=https%3A%2F%2Fwww.tecmundo.com.br%2Fciencia%2F151284-virus-alienigena-arma-biologica-teorias-conspiratorias-covid-19.htm&t_e=V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%20-%20TecMundo&t_d=%0A%20%20%20%20%20%20V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%0A%20%20%20%20&t_t=V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%20-%20TecMundo&s_o=asc&l=pt#">Mais votados</a>
                                    <a  target="_parent" href="https://disqus.com/embed/comments/?base=default&f=tecmundo&t_u=https%3A%2F%2Fwww.tecmundo.com.br%2Fciencia%2F151284-virus-alienigena-arma-biologica-teorias-conspiratorias-covid-19.htm&t_e=V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%20-%20TecMundo&t_d=%0A%20%20%20%20%20%20V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%0A%20%20%20%20&t_t=V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%20-%20TecMundo&s_o=asc&l=pt#">Mais recentes</a>
                                    <a  target="_parent" href="https://disqus.com/embed/comments/?base=default&f=tecmundo&t_u=https%3A%2F%2Fwww.tecmundo.com.br%2Fciencia%2F151284-virus-alienigena-arma-biologica-teorias-conspiratorias-covid-19.htm&t_e=V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%20-%20TecMundo&t_d=%0A%20%20%20%20%20%20V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%0A%20%20%20%20&t_t=V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%20-%20TecMundo&s_o=asc&l=pt#">Mais antigos</a>
                                </div>
                            </div> 

                        </div>
            
                    </div> 
                    <div class="comment-textarea">
                        <img src="img/noavatar92.png" alt="avatar">
                        <div class="text-area">
                            <div class="text-area-textarea"  >
                                <textarea id="comment-text-area" name="comment-text-area" placeholder="Escreva o seu comentário... " rows="2"></textarea>
                                <div class="text-area-icons">
                                    <div class=" icon-gif">
                                        <div  title="GIF"class=" icon gif">
                                            <p> GIF</p> 
                     
                                        </div>
                                        <div class="new" >
                                            <i  title="New"class="material-icons">stars</i>
                                        </div>
                                    </div>
                  
                                    <div class=" icon image">
                                        <i title="Carregar imagem" class="fa fa-image"></i>
                                    </div>
                                    <div class="divisor"></div>
                                    <div class="icon format-text">
                                        <i title="Bold" class="material-icons">format_bold</i>
                                    </div>
                                    <div class="icon format-text">
                                        <i   title="Italic"class="material-icons" >format_italic</i>
                                    </div>
                                    <div class="icon format-text">
                                        <i title="Underline" class="material-icons" >format_underlined</i>
                                    </div>
                                    <div class="icon format-text">
                                        <i title="Strikethrough" class="material-icons" >strikethrough_s</i>
                                    </div>
                                    <div title="Ligação" class="icon icon-link">
                                        <div class="link1">
                                            C
									    </div>
                                        <div class="link2">
                                           C
                                        </div >

                                    </div>
                                    <div class="icon spoiler">
                                        <i title="Spoiler" class="material-icons">visibility_off</i>
                                    </div>
                                    <div class="icon code">
                                        <i title="Code" class="fa fa-code"></i>
                                    </div>
                                    <div class =" icon quote">
                                        <i title="Quote" class="fa fa-quote-left" ></i>
                                    </div>

                                    <button class="publish">
                                        Publicar como Usuário
                                    </button>

                                </div>
                
                            </div>
               
                        </div>
            
                    </div>
                    <div class="begin-session">
                        <p> INICIE A SESSÃO COM O</p>
                
                        <a target="_blank" href="https://disqus.com/next/login/?forum=tecmundo&evs=bmV0d29ya19kZWZhdWx0X2hpZGRlbjpmYWxsdGhyb3VnaDpkeW5hbWlj">
                            <button class="discus-button">
                                <div title ="Discus"class= "session iniciar-com-discus">
                                    <img width ="36px" height="35px" class="discus-dark" src= "img/icon_discus_dark.png" alt="discus">
                                    <img width ="36px" height="35px" class="discus-hover" src= "img/icon_discus_hover_0.png" alt="discus">
                                    <img width ="36px" height="35px" class="discus"src="img/icon_discus_0.1.png" alt="discus">
                                </div>
                           </button>
                        </a>
                 
               
                
                        <a target="_blank">
                            <button class="facebook-button">
                                <div title ="Facebook"class="session iniciar-com-facebook"> 
                                    <i class="fa fa-facebook" style="font-size:20px"></i>
                                </div>
                            </button>
                        </a>
              
              
           
                        <a target="_blank" href="https://disqus.com/_ax/twitter/begin/?forum=tecmundo&ctkn=qyvr7BxXekWdC4fxFnf3OADIXKI4gshi&evs=bmV0d29ya19kZWZhdWx0X2hpZGRlbjpmYWxsdGhyb3VnaDpkeW5hbWlj">
                            <button class= "twitter-button">
                                <div title="Twitter" class="session iniciar-com-twitter">
                                    <i class="fa fa-twitter" style="font-size:20px"></i>
                                </div>
                            </button>
                        </a>
            
                        <a target="_blank" href="https://disqus.com/_ax/google/begin/?forum=tecmundo&ctkn=qyvr7BxXekWdC4fxFnf3OADIXKI4gshi&evs=bmV0d29ya19kZWZhdWx0X2hpZGRlbjpmYWxsdGhyb3VnaDpkeW5hbWlj">
                            <button class="google-button">
                                <div title="Google" class="session iniciar-com-google">
                                    G
                                </div>
                            </button>
                        </a>
                    </div>
                    <div class="form">
                      
                        
                            <div class=" alinhar discus-text">
                                OU REGISTRE-SE NO DISCUS</div> <div class=" alinhar action"> <button class="information"><span>?</span></button>
                                <div class="discus-information">
                                    <p>O Discus é uma rede de debates</p>
                                    <ul>
                                       <li>O Disqus não modera nem censura comentários. As regras desta comunidade são criadas por ela própria.</li>
                                        <li>Não seja mal educado, nem infrinja a lei, e verá que tudo será melhor!</li>
    
                                    </ul>
                                    <a href="https://docs.disqus.com/kb/terms-and-policies/" target="_blank">
                                        <button class="button-style">Leia os termos e condições</button>
                                    </a>
    
                                </div>
               
                            </div>
           
                      
           

           
                        <form class="form_pren">
              
                            <input type="text" placeholder="Nome" >
                            <input type="email" placeholder="E-mail" >
                            <input type="password" placeholder="Palavra-passe">
                            <div class="form-text">
                                Please access our 
                                <a href="https://help.disqus.com/customer/portal/articles/466259-privacy-policy" target="_blank">
                                    Política de privacidade
                                </a> 
							    to
                                learn what personal data Disqus collects 
                                and your choices about how it is used.
                                All users of our service are also subject to our 
                                <a target="_blank" href="https://help.disqus.com/customer/portal/articles/466260-terms-of-service"> 
                                    Termos de utilização
							    </a>.
                            </div>
                            <button type="submit" class="button-style">
                                <i class="fa fa-long-arrow-right" style="font-size:24px"></i>
                            </button>
                        </form>

                    </div>


                </div>
                <div class="sob-comentario">
                    <a title="Subscreva e receba as atualizaçãoes deste debate por e-mail" target="_blank" href="https://disqus.com/embed/comments/?base=default&f=tecmundo&t_u=https%3A%2F%2Fwww.tecmundo.com.br%2Fciencia%2F151284-virus-alienigena-arma-biologica-teorias-conspiratorias-covid-19.htm&t_e=V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%20-%20TecMundo&t_d=%0A%20%20%20%20%20%20V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%0A%20%20%20%20&t_t=V%C3%ADrus%20alien%C3%ADgena%20e%20arma%20biol%C3%B3gica%3A%20as%20teorias%20conspirat%C3%B3rias%20da%20Covid-19%20-%20TecMundo&s_o=asc&l=pt#">
                        <i class="fa fa-envelope-o" style="font-size: 18px"></i> Subscrever
                    </a>
                    <a target= "_blank" href="https://disqus.com/data-sharing-settings/">
                        <i class="fa fa-exclamation-triangle" ></i> Do Not Sell My Data
                    </a>

                </div>
            </div>

            <nav class="inst_sites">
                <div class="inst">
                    <input type="checkbox" id="ckeck1">
                    <label for="ckeck1">
                    <p>Institucional </p>
                    <i class="fa fa-angle-left" style="font-size:22px;"></i>
                    </label>
                    <ul>
                        <li>
                            <a href="https://nzn.io/index#about">
                                Sobre
                            </a>
                        </li>
                        <li>  
                            <a href="https://nzn.io/contato">
                                Contato
                            </a>
                        </li>
                        <li>
                            <a href="https://nzn.io/jobs">
                               Jobs
                            </a>
                        </li>
                        <li>
                            <a href="https://nzn.io/termos-de-privacidade">
                                Política de Privacidade
                            </a>
                        </li>
                        <li>
                            <a href="https://mailchi.mp/gruponzn/licenciamento-editorial">
                                Licenciamento de Conteúdo
                            </a>
                        </li>
                        <li>
                            <a href="https://m.tecmundo.com.br/stories">
                                Stories
                            </a>
                        </li>
                    </ul>
                </div>


                <div class="inst">
                    <input type="checkbox" id="ckeck2">
                    <label for="ckeck2">
                        <p>Nossos Sites</p>
                        <i class="fa fa-angle-left" style="font-size:22px;"></i>
                    </label>
                    <ul>
                        <li>
                            <a href="https://www.tecmundo.com.br/">
                                Tecmundo
                            </a>
                        </li>
                        <li>  
                            <a href="https://www.megacurioso.com.br/">
                                Mega Curioso
                            </a>
                        </li>
                        <li>
                            <a href="https://www.minhaserie.com.br/">
                                Minha Série
                            </a>
                        </li>
                        <li>
                            <a href="https://www.clickjogos.com.br/">
                                Click Jogos
                            </a>
                        </li>
                        <li>
                            <a href="https://www.thebrief.com.br/">
                                The Brief
                            </a>
                        </li>
                        <li>
                            <a href="https://www.voxel.com.br/">
                                Voxel
                            </a>
                        </li>
                        <li>
                            <a href="https://www.baixaki.com.br/">
                                Baixaki
                             </a>
                        </li>
                        <li>
                            <a href="https://www.facebook.com/fikadikaoficial/">
                                Fika Dika
                            </a>
                        </li>
                        <li>
                            <a href="https://savecoins.app/">
                                Save Coins
                            </a>
                        </li>
                    </ul>
                </div>
                <div class="nzn inst">
                    <a target="_blank" href="https://nzn.io/"> 
                        <img src="img/black_nzn.png" alt="NZN"class="logo_nzn_noturno">
                        <img src="img/nzn.png" alt="NZN"  class="logo_nzn" >
                        
                    </a>
                    <P>&copy; COPYRIGHT 2020 - NO ZEBRA NETWOORK S.A<br>
                    TODOS OS DIREITOS RESERVADOS.</p>
   
               </div>
            </nav>
	  
       </div>
    
	</body>

</html>

 Modificações 18/04/2020
 - Removido das @médias as div{100%}, pois modificam a estrutura dos botões de reações ao minimizar a tela 
 - inseridos itens de coméntário 2
 - corrigidos posicionamento dos itens de coméntario 1, para que apresente de forma semelhate ao minimizar a tela
 
Modificações 20/04/2020 
 -Removido o: .reactions buttom:active do arquivo style.css, pois não estava fazendo efeito nemhum
- Removido as bordas outiline dos botões de reações
- Mudado a cor do texto e borda dos botões para um tom um pouco mais escuro: #2e87e7
- Inserido textarea

Modificações 22/04/2020
- Inserido itens do textarea
- Mudado a cor do backgaround color do a (link), ao passar o mouse para branco;
- Inserido border radius de 5px para arredondar os cantos, portanto mais parecida com a original, das classes: .save-image:active e img-share: active
- alteardo a cor de borda do save-image:active, de para #1087ff  para rgba(52,144,220,0.5) e aumentado espessura da borda de 1px para 3px
- Alterado cor de borda do share-buttom :active, de rgb(82,144,220,.5 )para rgba(52,144,220,0.5)  e aumentado espessura da borda de 1px para 3px
- removido box-sozing:borderbox do save-image e img-share e adicionado padding de 3px;
- alteardo a cor de borda do share-buttom:active, de para #1087ff  para rgba(52,144,220,0.5) e aumentado espessura da borda de 1px para 3px
- Aumentado a espessura da borda de de 1px para 3px e inserido cor de borda rgba(52,144,220,0.5) do comment-buttom:active
- Estilização da classe .voltar  removida, pois não estava causando efeito nenhum;

Modificações 23/04/2020
- Feito o ajuste no Veja também
- Adicionado um botão de Publicar no text area com hover e active 

Modificações 24/04/2020
 - Inseridos icons de inciar sessão (ainda não implementados)
 
 Modificaçãoes 26/04/2020
 - implementação dos icons de iniciar sessão
 - iniciado form do resgistre=se no discus;

 
 
