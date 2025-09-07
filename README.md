# Speech Studio

Transcreve a fala em texto e o texto em fala audível.

## Passo a passo

Aceda ao [Speech Studio](https://speech.microsoft.com/portal) e faça login com as suas credênciais do portal Azure.

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img0.png)  

Clique no botão de configuação.

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img1.png)  

Em seguida clique em **Cria novo recurso**.

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img2.png) 

Preencha a seguinte informação:

	. Nome do novo recurso
	. Assinatura
	. Região
	. Tipo de preço: Padrão S0
	. Grupo de recurso

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img3.png)  

Selecione **Criar um recurso** para confirmar. Aguarde até que conclua a criação.

De seguida selecione o recusro criado, clique em **Usar o recurso** e volte para a página inicial.

Selecione a opção **Conversão de fala em texto**  e escolha o módulo **Conversão de fala em texto em tempo real**.

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img4.png) 

Selecione o recurso criado anteriormente e escolha o idioma do áudio.

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img5.png) 

Faça o upload do [ficheiro audio](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/WhatAICanDo.m4a) 

Reproduza o áudio. O áudio será transcrito simultaneamente com a reprodução:

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img6.png) 

# Language Studio

Análise semântica de Texto, com funcionalidades como reconhecimento de entidades, extração de frases-chave, sumarização e análise de sentimentos.


## Passo 1 - Criar um recurso

Aceda ao [portal Azure](https://portal.azure.com) e faça login com as suas credênciais.

Selecione a o menu **Create a resource** e procure por **Language Services**.

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img7.png) 

Selecione os recursos adicionais.

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img8.png) 

É necessário preencher a seguinte informação:

	. Subscription
	. Resource group
	. Region 
	. Name 
	. Pricing tier: Standard S0

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img9.png) 


Selecione **Criar** para confirmar. Aguarde até que conclua a criação.

# Passo 2 - Iniciar o Language Studio

Aceda ao portal [Language Studio](https://language.cognitive.azure.com)e selecione um novo resource.

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img10.png) 

A seguir deverá selecionar a opção **Classify text** e selecionar o módulo **Analyze sentiment and mine opinions**

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img12.png) 

Deverá selecionar o idioma do texto e o resource.

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img13.png) 

Inseria o [texto](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/Texto.txt) a analisar.

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img14.png) 

Marque a opção **I acknowledge that running this demo will incur usage and may incur costs to my Azure resource.** e clique no **Run** para iniciar a análise.

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img15.png) 

Depois de analisado o texto serão gerados os seguintes dados: 

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img16.png) 

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img17.png) 

![](https://github.com/vicalmeida/MLearnAI900Lab3/blob/main/images/img18.png) 
