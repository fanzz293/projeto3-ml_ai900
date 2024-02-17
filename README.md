![r](https://github.com/fanzz293/projeto3-ml_ai900/blob/main/assets/dio.jpeg?raw=true)

### DESAFIO DE PROJETO DIO #3 - ANÁLISE DE SENTIMENTOS COM LANGUAGE STUDIO NO AZURE AI

**Logo abaixo, será descrito um passo a passo das seguintes ferramentas:** 

* Estúdio de fala (Speech Studio)

* Analise de texto 

#### Objetivo: Mostrar na prática ferramentas utilizadas para transcrição de fala em texto e vice versa, além de análise de texto para extração de informações baseadas nas perguntas de entrada, que geram saídas atreladas ao contexto da questão passada. 

#### Como proceder?

#### Criando recurso AI Speech no Estúdio de fala (Speech Studio)

1. Visite o site https://speech.microsoft.com/portal e faça o login de sua conta. 
2. É necessário criar um recurso para utilizar a ferramenta. Caso seja necessário, siga as instruções aqui https://microsoftlearning.github.io/mslearn-ai fundamentals/Instructions/Labs/09-speech.html na parte de "criar um recurso de fala do Azure AI">

Explorando a fala em texto no Speech Studio

1. Na página inicial, vá em fala em tempo real para texto
2. Define a linguagem do arquivo
3. Você pode utilizar o arquivo de sua preferência ou o que está disponível nesse endereço (https://aka.ms/mslearning-speech-studio), WhataiCanDo.m4a, insira o arquivo na área de transferência. 
4. Lembre-se de ajustar a linguagem a ser testada a do arquivo!
No teste feito com o arquivo WhatCanIDo.m4a, o resultado foi esse:

![f](https://github.com/fanzz293/projeto3-ml_ai900/blob/main/assets/figura%201.png?raw=true)

Pronto!

##### Criando recurso Language Studio

1. Siga os passos 1 e 2 referente ao tópico "criando recurso AI Speech no Estúdio de fala (Speech Studio)".

##### Configurando o recurso no Azure AI Language Studio

1. Clique aqui para [visualizar o site.](https://language.cognitive.azure.com)
2. Preencha o formulário "selecione um recurso do Azure"

![d](https://github.com/fanzz293/projeto3-ml_ai900/blob/main/assets/figura3.jpg?raw=true)

#### Para saber mais [veja aqui](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html).

##### Obs.: No caso será necessário criar um recurso específico de idioma, que precisará ser implantado no sistema. 

#### Analisando avaliações no Language Studio

##### Através do recurso "analisar sentimento e extrair opiniões", você pode escrever a sentença que preferir ou carregar um arquivo contendo texto relacionado a linguagem selecionada. Segue a seguinte entrada em inglês: 

![d]()

##### A mensagem contém 3 sentenças, que serão analisadas de forma separada. Clicando em executar (run), os resultados do exame de análise de sentimento estão logo abaixo

![d](https://github.com/fanzz293/projeto3-ml_ai900/blob/main/assets/figura%205.jpg?raw=true)

![d](https://github.com/fanzz293/projeto3-ml_ai900/blob/main/assets/figura%206.jpg?raw=true)

![d](https://github.com/fanzz293/projeto3-ml_ai900/blob/main/assets/figura%207.jpg?raw=true)

#### As análises acima são retornos baseados em parâmetros sentimentais que mostram como foi a experiência de usuário em determinado evento. Como mostra o exemplar, o resultado gerado foi ruim.

#### Você pode ficar a vontade para testar o recurso com outras entradas, seja diretamente por texto ou por arquivo documentado. 

Referências:

[Explorando o Estudo de Fala](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)
&nbsp;

[Análise de texto com Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)
