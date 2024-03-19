# Bem-vindo ao meu projetinho

Esse é meu projeto tentando recriar a aba inicial do Google, eu pensei em criar esse projeto pra aprender e desenvolver habilidades com HTML e CSS, aprender novos atributos e configurações utilizando e atualizando tags.

Espero que ele sirva de inspiração, modelo ou até mesmo aprendizagem para outras pessoas.
# Atributos utilizados (HTML)
➤lang <br>
➤charset  <br>
➤name  <br>
➤class  <br>
➤content  <br>
➤rel  <br>
➤href  <br>
➤src  <br>
➤action  <br>
➤method  <br>
➤placeholder  <br>
➤required  <br>

# Elementos utilizados (CSS)

➤align-items  <br>
➤border  <br>
➤border-radius  <br>
➤background-color  <br>
➤background-image  <br>
➤background-size  <br>
➤background-repeat  <br>
➤background-position  <br>
➤box-shadow  <br>
➤color  <br>
➤cursor  <br>
➤display  <br>
➤font-size  <br>
➤font-family  <br>
➤height  <br>
➤justify-content  <br>
➤margin  <br>
➤margin-left  <br>
➤margin-top  <br>
➤margin-right  <br>
➤margin-bottom  <br>
➤outline  <br>
➤padding  <br>
➤padding-top  <br>
➤position  <br>
➤pseudo-seletor  <br>
➤pointer-events  <br>
➤text-align  <br>
➤textarea:focus,input:focus  <br>
➤text-decoration  <br>
➤user-select  <br>
➤width  <br>
➤z-index  <br>
# Tags utilizadas (HTML)
➤html  <br>
➤head  <br>
➤meta  <br>
➤title  <br>
➤body  <br>
➤form  <br>
➤input  <br>
➤a <br>
➤img  <br>
➤div  <br>
➤link <br>
# Organização
Foi utilizado css externo, assim como imagens externas, tudo foi jogado dentro de uma pasta SCR, e a partir de lá são retirados as informações e personalização do HTML, tudo isso foi linkado na região da tag <Head> .
# Explicando o código ( ou pelo menos tentando)

Primeira coisa que eu tentei fazer foi a barra de pesquisa, então fui examinar o codigo fonte do google, para me basear e saber como funciona, e depois utilizei a tag form, para criar um input dentro dela que recebesse informações, e depois eu utilizei os atributos action e method para receber essas informações, utilizei o placeholder para deixar uma frase de fundo, o atributo name= "q" para se adequar aos meio utilizados pelo google, depois só coloquei uma class para acessar a tag do input no CSS, e assim eu fiz o input, depois coloquei uma imagem acima e usei uma medidas vh nessa região, para trabalhar com o tamanho dos dipositivo.

Depois eu fui tentar colocar uma lupa, camera e microfone, mas quando eu tentava colocar junto ao input utilizadno background imagem, ficava sem conseguir acessar o input, ai não dava pra pesquisar, então fiz uma barra invísvel, nela ia contar essas imagens, depois de estilizar tudo bonitinho pra que o input e a barra invísivel fiquem 'alinhados' fui tentar pesquisar, mas não dava, percebi então que a barra invísvel estava sobreposta ao input, então utilizei o elemento z-index, para definir o nível de importância daquele algorítmo no site, assim consegui fazer com que a pesquisa funcionasse normalmente. Sei que cos icone da camera e microfone possuem funções e utilizam Javascript ou algo assim, mas com ainda não sei como usar, vai ficar como imagem de fundo mesmo.

Após tudo isso, claro que estilizando parte por parte utilizadno MUITO margins e paddings, fui criar um div assim como em todas as outras regiões que eu desejava acessar especificadamente, e nele utilizei o atributo class, para acessar aquela área no CSS, e nela coloquei dois links e uma foto assim como do GOOGLE tradicional, como não sei Javascript, ficou sem ação ou função, os links eu peguei do código fonte do GOOGLE mesmo, e utilizei a medida vw para tentar adaptar e trabalhar de acordo com os diveros dispositivos.

Esse trabalho pode ter falhas e pode não ser tão prático, mas me ajudou bastante a entender alguns conceitos das linguagens de HTML e CSS, e me fez me correr atrás e pesquisar atrás de diversos recursos que eu não fazia ideia do quão úteis poderiam ser, em diversas fontes e locais, foi até que bem divertido quebrar minha cabeça fazendo isso e provavelmente eu vou aprimorar esse projeto depois...

Alguns elementos como textarea e box shadow foi o método que eu usei para tirar as bordas ao clicar no input sem usar Javascript e position foi o que eu usei para conseguir alinhar algumas tags ao centro.


# Instruções
Serve como fonte de pesquisa ou como um navegador padrão, basta clicar na barra de pesquisa depois clicar Enter assim como os demais navegadores, após isso o usuário é direcionado para um local com aquilo que foi digitado na barra de pesquisa.

Atualmente algumas imagens que são semelhante a botões não esttão atribuidos a nenhuma função, ou seja, eles não funcionam, pelo menos não ainda, afinal esse projeto se trata de um protótipo em desenvolvimento.
