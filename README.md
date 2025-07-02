# Projeto-Analise-de-Sentimentos-por-Inteligencia-Artificial-com-Language-Studio
PROJETO PROPOSTO PELA PLATAFORMA DIGITAL DIO ME, APRENDIZADO DO BOOTCAMP RANDSTAD - ANÁLISE DE DADOS

Análise Verbal: Desvendando o Sentido por Trás das Palavras

Cada frase é um quebra-cabeça, e cada palavra, uma peça essencial. Com o Language Studio da Microsoft Azure AI, você equipa sua aplicação com as ferramentas necessárias para decifrar a verdadeira intenção por trás de uma comunicação.

Seja para:

Identificar o sentimento (positivo, negativo ou neutro)

Extrair tópicos principais e palavras-chave

Compreender a mensagem central do emissor

Demonstração Prática
Olá! Sou Charles Albert e hoje vou mostrar o meu aprendizado do primeiro desafio, vou aprensentar a você pelo Language Studio, focando na análise de sentimentos. Usaremos textos-exemplo para explorar como a ferramenta da Microsoft Azure AI transforma dados brutos em insights valiosos.

Vamos lá!

# Pra criarmos o recurso, vamos entrar em "https://www.portal.azure.com" e clicar em "Criar um recurso".

<div align="center">
<img src="/assets/portal azure.png" width="800px" /></div>

será aberto a parte de Criar recurso, na parte de Marketplace do portal da Azure.

<div align="center">
<img src="/assets/analise de texto.png" width="800px" />
</div>

Clicamos em "Criar", nessa primeira opção que aparece, e "Análise de texto". E logo após vamos em criar

<div align="center">
<img src="/assets/selecionar e criar.png" width="800px" />
</div>

Na caixinha de Grupo de recursos, você seleciona um grupo existente ou cria um novo para ser usado nesse projeto. No meu caso, irei criar um novo e chamar de "LanguageStudioLAB".

<div align="center">
<img src="/assets/studio lab.png" width="800px" />
</div>

Vou deixar o nome do recurso como "LanguageStudioLABDIO", e o tipo de preço em "Free F0".

<div align="center">
<img src="/assets/examinar e criar.png" width="800px" />
</div>

Após isso,  marcamos a caixinha para declarar que aceita os temos de uso do aviso de uso reponsável de inteligência artificial, e clicamos em Examinar + Criar. Como na imagem acima.

Aguarde alguns minutos até terminar a implantação finalizar. Após concluída, vamos para o próximo passo.

<div align="center">
<img src="/assets/proximo passo.png" width="800px" />
</div>

# Parte 2- Análise de Sentimentos (satisfação) no Language Studio.

Agora acessamos "https://language.cognitive.azure.com/".

Aqui você precisará logar com sua conta Microsoft e depois selecionar o grupo de recursos e o recurso que criamos anteriormente.

Na página inicial do Language Studio, você vai na aba "Classify text", e na primeira opção ("Analyze sentiment and mine opinion") você clica em "Try it out".

<div align="center">
<img src="/assets/texto.png" width="800px" />
</div>

Agora voltamos ao Language Studio, selecionamos o idioma do texto (caso peça, você também precisará selecionar o recurso que vocẽ deseja usar) e colamos o texto que desejamos usar a ferramenta para analisar.

Então descemos mais um pouco a página e marcamos a caixinha que confirmamos que temos ciência que esse Demo usará valores incluidos em nosso recurso da Azure, e clicamos em "Run".



<div align="center">
<img src="/assets/text1.png" width="800px" />
</div>

Então, ao terminar de carregar, podemos ver os resultados do nosso experimento:

*A ANÁLISE COMPLETA ESTARÁ NA PASTA "OUTPUT" JUNTAMENTE COM A SAÍDA EM JSON.
