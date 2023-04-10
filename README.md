# dio-desafio-github-primeiro-repositorio
Desafio de Projeto sobre Git/GitHub

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página - Módulo I - Primeiros Passos com Html</title>
</head>
<body>
    <h1>Módulo 1 - Primeiros Passos com HTML</h1>
    <hr />

    <h2 id="Índice"</h2>
    <ul>
        <li><a href="#Historiadoscomputadores">Historia dos computadores</a></li>
        <li><a href="#O que são clients">O que são <i>Clients</i>?</a></li>
        <li><a href="#O que são Servers">O que são <i>Servers</i>?</a></li>
        <li><a href="#Como é uma estrutura básica de um HTML?">Como é uma estrutura básica de um HTML?</a></li>
        <li><a href="#Entendendo a diferença entre listas ordenadas e não ordenadas">Entendendo a diferença entre listas ordenadas e não ordenadas</a></li>
        <li><a href="#">Links de referências</a></li>
    </ul>

    <h2 id="Historiadoscomputadores"</h2>

    <center><img src="https://www.ime.usp.br/~macmulti/figuras/z-1_machine.jpg" alt="Image" height="400" width="500"></center>
    <center><sub>Na imagem aparece Konrad Zuse ao lado de uma máquina, acredito ser o Z1</sub></center>

    <p style="font-family: Tahoma"> O primeiro computador eletromecânico foi construído por <strong>Konrad Zuse (1910–1995).</strong>
        Em 1936, esse engenheiro alemão construiu, a partir de relês que executavam os cálculos e dados lidos em fitas 
        perfuradas, o Z1. Zuse tentou vender o computador ao governo alemão, que desprezou a oferta, já que não poderia 
        auxiliar no esforço de guerra. Os projetos de Zuse ficariam parados durante a guerra, dando a chance aos americanos 
        de desenvolver seus computadores.</p>

    <p style="font-family: Tahoma"> Foi na Segunda Guerra Mundial que realmente nasceram os computadores atuais. 
        A Marinha dos Estados Unidos, em conjunto com a Universidade de Harvard, desenvolveu o computador Harvard <i>Mark I</i>,
        projetado pelo professor Howard Aiken, com base no calculador analítico de Babbage. O Mark I ocupava 120 m³ aproximadamente, 
        conseguindo multiplicar dois números de dez dígitos em três segundos.</p>
        
    <p style="font-family: Tahoma"> Simultaneamente, e em segredo, o Exército dos Estados Unidos desenvolvia um projeto semelhante, 
        chefiado pelos engenheiros J. Presper Eckert e John Mauchly, cujo resultado foi o primeiro computador a válvulas, 
        o Eletronic Numeric Integrator And Calculator (ENIAC),[5] capaz de fazer quinhentas multiplicações por segundo. 
        Tendo sido projetado para calcular trajetórias balísticas, o ENIAC foi mantido em segredo pelo governo americano 
        até o final da guerra, quando foi anunciado ao mundo. </p>
    <br/>
    <h2 id="O que são clients"</h2>
    <center><img src="https://techenter.com.br/wp-content/uploads/2019/01/cliente-servidor.png" alt="Image" height="400" width="500"></center>
    <center><sub>Imagem ilustrativa</sub></center>
    <p style="font-family: Tahoma"><strong><i>"Cliente"</i></strong> é um termo empregado em computação e representa uma 
        entidade que consome os serviços de uma outra entidade servidora, em geral através do uso de uma rede de computadores 
        numa arquitetura cliente-servidor</p>
    <br/>
    <h2 id="O que são Servers"</h2>
    <center><img src="https://www.redeszone.net/app/uploads-redeszone.net/2019/10/servidores_rack-930x487.jpg" alt="Image" height="400" width="500"></center>
    <center><sub>Imagem de um servidor moderno</sub></center>
    <p style="font-family: Tahoma"><strong><i>"Servidor"</i></strong> é um programa de computador funcionando para atender demandas 
        de outros programas, os clientes. Exemplos de servidores incluem servidores da web, servidores de e-mail e servidores de 
        arquivos, servidores de banco de dados, entre outros.</p>  

    <h2 id="Como é uma estrutura básica de um HTML?"</h2>
    <p style="font-family: Tahoma"</p>A estrutura básica de uma página HTML pode ser vista na Listagem 1, na qual podemos ver as 
        principais tags que são necessárias para que o documento seja corretamente interpretado pelos browsers.

    <ol></ol>
    <li><*!DOCTYPE html></li>
    <li><*html></li>
    <li><*head></li>
    <li><*meta charset="UTF-8"/></li>
    <li><*title>Document<*/title></li>
    <li><*/head></li>
    <li><*body></li>
    <li><*!-- Conteúdo --></li>
    <li><*/body></li>
    <li><*/html></li>
    <br/>
    <strong><i>1. Estrutura básica de uma página HTML</i></strong>
    <ol>
        <br/>
    <li>Linha 1: a instrução DOCTYPE deve ser sempre a primeira a aparecer em uma página HTML para indicar ao browser qual versão da 
    linguagem usada. Nesse caso, estamos trabalhando com a HTML5, versão na qual a declaração do DOCTYPE é bastante simples, 
    como podemos ver na listagem;</li>
    <br/>
    <li>Linhas 2 e 10: abertura e fechamento da tag html, que delimita o documento. Sendo assim, todas as demais tags da página 
    devem estar nesse espaço;</li>
    <br/>
    <li>Linhas 3 e 6: abertura e fechamento da tag head, que define o cabeçalho do documento. O conteúdo nesse espaço não é visível 
    no browser, mas contém instruções sobre seu conteúdo e comportamento. Dentro dessa tag, por exemplo, podem ser inseridas folhas 
    de estilo e scripts;</li>
    <br/>
    <li>Linha 4: a tag meta, nesse caso, especifica qual conjunto de caracteres (character set ou charset) será usado para renderizar 
    o texto da página. O UTF-8 contém todos os caracteres dos padrões Unicode e ASCII, sendo, portanto, o mais utilizado em páginas web. 
    A mesma tag meta, porém com outros atributos, pode ser utilizada para outros fins, como na SEO (Search Engine Optimization);</li>
    <br/>
    <li>Linha 5: a tag title define o título da página, aquele que aparece na janela/aba do navegador;</li>
    <br/>
    <li>Linhas 7 e 9: abertura e fechamento da tag body, marcando o espaço no qual deve estar contido o conteúdo visual da página. 
    As demais tags que representam texto, botões etc. devem ser adicionadas nesse intervalo;</li>
    <br/>
    <li>Linha 8: nessa linha podemos observar a sintaxe para adição de comentários em HTML. Esse trecho não é renderizado pelo browser.</li>
    </ol>
    <h2 id="Entendendo a diferença entre listas ordenadas e não ordenadas"></h2>
    <p style="font-family: Tahoma"</p>A principal diferença entre a <strong>Linhas ordenada e a lista não-ordenada</strong> está na maneira com que os itens de cada lista são apresentados
    a lista ordenada enumera os elementos; a lista não-ordenada coloca marcadores antes de cada elemento.</p>

    <a href="#Índice">(Voltar ao Índice)</a>

    <h2>Links de referências</h2>
    <p><strong><u>INSTRUÇÕES:</u> </strong>Coloque links para outras páginas que falam sobre estes assuntos. Não esquece de que precisa abrir em outra aba/janela do navegador.</p>
    <ul>
        <li><a href="http://dio.me">dio.me</a></li>
        <li><a href="#">http://w3c.org</a></li>
    </ul>

</body>
</html>
