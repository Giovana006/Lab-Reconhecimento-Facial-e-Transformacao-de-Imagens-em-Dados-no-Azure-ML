# Reconhecimento Facial e Transformacão de Imagens em Dados no Azure ML
Este repositório tem como finalidade armazenar o projeto desenvolvido no âmbito do módulo "Reconhecimento facial e transformação de imagens em dados no Azure ML" do Bootcamp "Microsoft Azure AI Fundamentals" da [DIO](https://www.dio.me/users/giovananascimentoferreira1) , sob instrução da professora [Valéria Baptista](https://www.linkedin.com/in/valeriabaptista/) .

O projeto é requisito essencial para a aprovação no módulo “Trabalhando com Visão Computacional”, consolidando o aprendizado prático dos participantes e preparando-os para os desafios subsequentes.

O desenvolvimento deste projeto visa demonstrar como funciona o reconhecimento facial, o reconhecimento de dados em documentos e também o reconhecimento de imagens. Para um melhor entendimento, dividi todo o processo em etapas, desde a criação do grupo de recursos até o resultado final da regressão.

Passo a passo do desafio de projeto "Reconhecimento Facial e transformação de imagens em Dados no Azure ML" da DIO.


### Etapa 1: Criando um Recurso
Primeiro, vamos criar um espaço de trabalho do Azure Machine Learning. Para fazer isso, crie um recurso e pesquise os serviços de IA 
do Azure. Na próxima etapa, configuraremos o Recurso e criaremos um novo Grupo de Recursos, se necessário. Como estamos em um laboratório de aprendizagem, não configuraremos outras abas.

Para criar clicamos em “Revisar + Criar” e depois em “Criar”, como demonstrado no vídeo.

<video src="Passo-a-Passo%20de%20Criar%20um%20Recurso%20no%20Azure%20ML.mp4" controls title="Passo-a-Passo de Criar um Recurso no Azure ML"></video>


### Etapa 2: Acessando o Portal Vision Studio

Após o recurso ter sido criado, acessaremos o [Portal do Vision Studio](https://portal.vision.cognitive.azure.com/demo/image-captioning) . **Acesse com a sua conta Azure** e vá em "View all resorces" e será apresentado o recurso criado na etapa anterior. Marque a opção do seu laboratório (nome) do seu recurso Azure que criamos na etapa anterior de acordo com os passo-a-passos do vídeo a seguir:

<video src="Passo-a-Passo%20no%20Vision%20Studio-1.mp4" controls title="Title"></video>

### Etapa 3: detectar rostos em uma imagem
Na página inicial do Portal Vision Studio, acessei a aba "Face" e cliquei em "Detect faces in an images".

Na próxima página, em "Try it out", precisei informar o recurso criado anteriormente no Portal do Azure para testar (marcando na opção de acordo com o recurso/laboratório que você deseja usar). Sem escolher o recurso, não consegui obter a resposta do teste.

Passo-a-Passo da Etapa no Vídeo a Seguir:

<video src="Passo-a-Passo%20-%20Teste%20Identificar%20o%20Rosto.mp4" controls title="Title"></video>

**Teste de Imagem:**

Ao selecionar a imagem desejada podemos realizar a análise facial.

Imagem utilizada: [01_facial_análise.jpg](https://github.com/Giovana006/Lab-Reconhecimento-Facial-e-Transformacao-de-Imagens-em-Dados-no-Azure-ML/blob/main/01_facial_analysis.jpg)

<img src="Inputs/01_facial_analysis.jpg">

Detecção de atributos:

**Rosto #1** (Mãe)

Máscara facial: sim

Máscara facial cobrindo nariz e boca: sim

**Rosto #2** (Filha)

Máscara facial: sim

Máscara facial cobrindo nariz e boca: sim

**Rosto #3** (cachorro)

Máscara facial: não

É importante destacar a capacidade que a Visão Computacional teve de identificar diferentes rostos, incluindo o rosto de um animal, e também os rostos de pessoas usando máscara.

Você pode conferir os resultados da análise aqui: 01_facial_análise.json

### Etapa 4: Análise de Documentos
Vamos trabalhar com o módulo Extração de texto de imagens do Vision Studio.

Na página inicial do Portal Vision Studio, acessei a aba "Optical Character Recognition" e cliquei em "Extract Text From Images".

Na próxima página, em "Try it out", precisei informar o recurso criado anteriormente no Portal do Azure para testar (marcando na opção de acordo com o recurso/laboratório que você deseja usar). Sem escolher o recurso, não consegui obter a resposta do teste.

De acordo com o Passo-a-Passo do vídeo a seguir:

<video src="Passo-a-Passo%20-%20Teste%20Identificar%20Texto.mp4" controls title="Title"></video>

**Teste de Texto:**

Ao selecionar a imagem desejada podemos realizar a extração de texto.

Imagem utilizada: [Cartão de Crédito.jpg](https://github.com/Giovana006/Lab-Reconhecimento-Facial-e-Transformacao-de-Imagens-em-Dados-no-Azure-ML/blob/main/Cart%C3%A3o%20de%20Cr%C3%A9dito.jpg)

<img src="Inputs/Cartão de Crédito.jpg">

Você pode conferir os resultados da análise aqui: Cartão_de_Crédito.json

### Etapa 5: adicione legendas às imagens
Vamos trabalhar com o módulo Adicionar legendas às imagens do Vision Studio.

Na página inicial do Portal Vision Studio, acessei a aba "Image Analysis" e cliquei em "Add Captions To Images".

Na próxima página, em "Try it out", precisei informar o recurso criado anteriormente no Portal do Azure para testar (marcando na opção de acordo com o recurso/laboratório que você deseja usar). Sem escolher o recurso, não consegui obter a resposta do teste.

De acordo com o Passo-a-Passo do vídeo a seguir:

<video src="Passo-a-Passo%20-%20Teste%20Legenda%20de%20Imagem.mp4" controls title="Title"></video>

**Teste de Legenda de Imagem:**

Ao selecionar a imagem desejada podemos realizar a extração de texto.

**Resultado em Inglês:**

Imagem utilizada: [Foto de Família - Legenda de Imagem - Legenda em Inglês.png](https://github.com/Giovana006/Lab-Reconhecimento-Facial-e-Transformacao-de-Imagens-em-Dados-no-Azure-ML/blob/main/Foto%20de%20Fam%C3%ADlia%20-%20Legenda%20de%20Imagem%20-%20Legenda%20em%20Ingl%C3%AAs.png)

<img src="Inputs/Foto de Família - Legenda de Imagem - Legenda em Inglês.png">

Você pode conferir os resultados da análise aqui: Foto_de_Família/Inglês.json

**Resultado em Português:**

![Família](<Família - Legenda de Imagem - Legenda em Português.png>)

Imagem utilizada: [Família - Legenda de Imagem - Legenda em Português.png](https://github.com/Giovana006/Lab-Reconhecimento-Facial-e-Transformacao-de-Imagens-em-Dados-no-Azure-ML/blob/main/Fam%C3%ADlia%20-%20Legenda%20de%20Imagem%20-%20Legenda%20em%20Portugu%C3%AAs.png)

<img src="Inputs/Família - Legenda de Imagem - Legenda em Português.png">

Você pode conferir os resultados da análise aqui: Foto_de_Família/Português.json

É possível observar que o serviço Azure Vision Studio conseguiu descrever o momento em que a imagem passa de forma assertiva.


### **Links importantes:**

[Detectar Rostos no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)

[Ler Texto no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)

[Analise imagens no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html#learn-more)

### **Tecnologias Utilizadas:**
+ Estúdio de visão de IA do Microsoft Azure

### **Autora:**
Giovana do Nascimento Ferreira.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovana-nascimento-ferreira-947958231/)

