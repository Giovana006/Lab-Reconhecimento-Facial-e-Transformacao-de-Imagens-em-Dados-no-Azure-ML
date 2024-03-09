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

Teste de Imagem:

Ao selecionar a imagem desejada podemos realizar a análise facial.

Imagem usada: 01_facial_análise.jpg

![Mãe, Filha e Cachorro](01_facial_analysis.jpg)

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

Teste de Texto:

Ao selecionar a imagem desejada podemos realizar a extração de texto.

![Cartão de Crétito - Extração de Texto](<Cartão de Crétito - Extração de Texto.png>)

Você pode conferir os resultados da análise aqui: Cartão_de_Crédito.json

### Etapa 5: adicione legendas às imagens
Vamos trabalhar com o módulo Adicionar legendas às imagens do Vision Studio.

Na página inicial do Portal Vision Studio, acessei a aba "Image Analysis" e cliquei em "Add Captions To Images".

Na próxima página, em "Try it out", precisei informar o recurso criado anteriormente no Portal do Azure para testar (marcando na opção de acordo com o recurso/laboratório que você deseja usar). Sem escolher o recurso, não consegui obter a resposta do teste.

De acordo com o Passo-a-Passo do vídeo a seguir:

<video src="Passo-a-Passo%20-%20Teste%20Legenda%20de%20Imagem.mp4" controls title="Title"></video>

Teste de Legenda de Imagem:

Ao selecionar a imagem desejada podemos realizar a extração de texto.

**Resultado em Inglês:**

![Família](<Foto de Família - Legenda de Imagem - Legenda em Inglês.png>)

**Resultado em Português:**

![Alt text](<Família - Legenda de Imagem - Legenda em Português.png>)

É possível observar que o serviço Azure Vision Studio conseguiu descrever o momento em que a imagem passa de forma assertiva.

Você pode verificar os resultados da análise aqui: 03_add_caption_to_image.json

### **Links importantes:**

[Detectar Rostos no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)

[Ler Texto no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)

[Analise imagens no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html#learn-more)

### **Tecnologias Utilizadas:**
+ Estúdio de visão de IA do Microsoft Azure

### **Autora:**
Giovana do Nascimento Ferreira.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovana-nascimento-ferreira-947958231/)

