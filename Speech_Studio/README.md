# 🎙️ [Speech Studio](https://speech.microsoft.com/portal)
Ao acessar o Speech Studio nós encontramos diversos modelos de recognição, transcrição e tradução de falas, utilizando tanto o modelo "Speech to Text" quanto o "Text to Speech"

## 🗣️ ♺ 🔠 [Conversão de fala em texto em tempo real](https://speech.microsoft.com/portal/speechtotexttool) 

Este modelo utiliza o Speech to Text para coverter audios em tempo real para textos, muito utilizado para automatizar a criacao de legendas em videos, filmes e series. Podemos utilizar este modelo no mundo coorporativo traduzindo simultanemente conversas por telefone ou video chamada, mas já fica mais complexo pois precisamos fazer a conversao de Speech to Texte, para obtermos o que o usuário está falando agora em formato de texto para podermos traduzir, e após a tradução utilizaremos o Text to Speech para o outro usuário poder ouvir a tradução.

Gravei um áudio para teste na própria plataforma, e a transcrição é incrivelmente rapida.
![Captura de tela Speech to Text](/Speech_Studio/images/Speech_to_Text.png)


## 🔠 [Legendas](https://speech.microsoft.com/portal/captioning)


Já na página de legendas temos dois exemplos, um com legenda simultânea e outro com legenda que ficam disponíveis para videos offlines.
Na parte central do artigo nós temos um campo nos mostrando como configurar o tipo de legenda atráves de linguagens de programação como mostro na imagem. Onde podemos observar como as configurações podem e devem ser utilizadas
![Captura de tela Legendas](/Speech_Studio/images/Captioning.png)

## 🗣️ [Galeria de Vozes](https://speech.microsoft.com/portal/voicegallery)

Explorando a galeria de vozes pude observar que temos dezenas de idiomas disponíveis, e dentro destes idiomas temos variacoes de falas que vão de faixa etária, sexo, com diferentes tipos de entonação e etc. E claro temos algumas vozes ainda meio robotizadas, mas uma boa diversidade de falas bem naturais.
![Captura de tela Galeria de Vozes](/Speech_Studio/images/Voice_Gallery.png)

# 🔠 [Language playground](https://ai.azure.com/resource/playground/language)

 Já no Language Playground temos diversos modelos de ia voltados para comunicação, modelos treinados para extrair informações de textos como informações de saúde, extrair palavras chaves, entidades nomeadas, já outros para resumir informações e classificar texto.
 ![Captura de tela Language Playground modelos](/Speech_Studio/images/Language_Playground01.png)

## Análise de Sentimentos e Mineração de Opiniões

 Um modelo que me chamou atenção foi o de extrair entidades nominadas como locais, datas, eventos e etc. 

 Utilizei a seguinte frase para teste:
 > Tired hotel with poor service
 The Royal Hotel, London, United Kingdom
 5/6/2018
 This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk.

 E o modelo me retornou com as seguinte informações:
 
 ![Captura de tela do Language Playground](/Speech_Studio/images/Language_Playground.png)

 Onde podemos observar o que o modelo identificou direto no texto que escrevemos e também na barra a direita detalhando melhor cada item

 ## Extração de Frases-Chave
O modeloe de extração de Frases-Chave nos ajuda a identificar pontos chaves do nosso texto, podendo ser utilizada em contratos para facilitar a leitura e a compreensão

Fiz um teste com um texto fornecido na [documentação do Language Playground ](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html#extract-key-phrases-with-azure-ai-language-in-azure-ai-foundry-portal)

>  Good Hotel and staff
 The Royal Hotel, London, UK
 3/2/2018
 Clean rooms, good service, great location near Buckingham Palace and Westminster Abbey, and so on. We thoroughly enjoyed our stay. The courtyard is very peaceful and we went to a restaurant which is part of the same group and is Indian ( West coast so plenty of fish) with a Michelin Star. We had the taster menu which was fabulous. The rooms were very well appointed with a kitchen, lounge, bedroom and enormous bathroom. Thoroughly recommended.

 E o modelo novamente retorna com informacoes, mas dessa vez mais simplificado apenas com as palavras-chaves do nosso texto.
 
 ![Captura de tala frases-chaves](/Speech_Studio/images/Frases_Chaves.png)

# Considerações Finais
Este desafio foi uma excelente oportunidade para aplicar na prática os conceitos de Inteligência Artificial oferecidos pelo Microsoft Azure. A experiência de utilizar o Speech Studio e o Language Studio de forma interativa tornou o aprendizado muito mais concreto e dinâmico.

Achei particularmente impressionante a precisão do serviço de Reconhecimento de Fala em Tempo Real e a naturalidade das vozes neurais na Galeria de Vozes. São ferramentas que abrem um leque de possibilidades para criar aplicações mais acessíveis e interativas.

No Language Studio, a capacidade de extrair Entidades Nomeadas e Frases-Chave com poucos cliques demonstra o quão avançada está a IA para análise de texto. Em um projeto real, eu poderia utilizar esses recursos para automatizar a categorização de tickets de suporte ou para analisar o feedback de clientes em redes sociais, extraindo insights valiosos para o negócio.

Concluo este desafio com um entendimento muito mais claro do potencial dos serviços de IA do Azure e motivado a explorar ainda mais suas capacidades em projetos futuros.