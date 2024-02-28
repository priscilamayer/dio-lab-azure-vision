# Desafio Azure Vision
Neste documento explico o passo a passo para realizar o presente projeto do módulo "Trabalhando com Visão Computacional" do curso "Microsoft Azure AI Fundamentals" ministrado pela [DIO](https://web.dio.me). Neste módulo aprendemos os conceitos de Visão Computacional e a utilizar a plataforma [Azure Vision Studio](https://portal.vision.cognitive.azure.com) e três ferramentas disponíveis nesta: Face, Optical Character Recognition e Image Analysis. Neste projeto então realizei a análise de três fotos distintas, cada uma de acordo com a ferramenta utilizada.

💡 Como meu Microsoft Azure está configurado em inglês, utilizo termos e comandos neste idioma no decorrer do texto.

## Primeiros Passos: Microsoft Azure
- Fazer o login no Microsoft Azure e clicar no botão "+Create a resource";
- Clicar em "AI + Machine Learning" e selecionar a opção "Azure AI Services" e clicar em "Create";
- Nesta página há a opção de criar uma nova resource ou utilizar uma já existente, eu selecionei uma que já havia criado para o desafio anterior;
- Dar um nome de acordo com o projeto a realizar;
- Clicar em "Review + create" e aguardar a validação;
- Então clicar em "Create" e esperar sua finalização.

## Azure Vision Studio
- Após a conclusão da criação da resource no Microsoft Azure, abrir a plataforma Azure Vision Studio;
- Na página inicial, clicar em "View all resources";
- Selecionar a que foi criada e clicar em "Select as default resource";
- Nenhuma nova aba ou página abrirá, mas o comando foi realizado adequadamente;
- Então clicar no "X" no canto superior direito para retornar à página inicial;
- Agora começaremos a utilizar as ferramentas mencionadas acima.

### Face ➡ Detect faces in an image
- Na página inicial ainda, clicar na aba "Face" e selecionar "Detect faces in an image";
- Em "Try it out", selecionar a caixinha de estar de acordo com as condições propostas (quando for usar as outras ferramentas ela já estará automaticamente selecionada);
- Existem as amostras de imagens disponíveis na plataforma, mas utilizei a opção "Browse for a file";
- Selecionei a foto *Parc_Jacques_Cartier.jpg* para ser analisada e foi este o resultado mostrado:

### Optical Character Recognition ➡ Extract text from images
- Após retornar à página inicial, clicar na aba "Optical character recognition" e selecionar a opção "Extract text from images";
- Novamente utilizar a opção "Browse for a file";
- Selecionei a foto *Auckland_AlbionBar.jpg* para ser analisada e este foi o resultado gerado:

### Image Analysis ➡ Add captions to images
- Após retornar à página inicial, clicar na aba "Image analysis" e selecionar a opção "Add captions to images";
- Novamente utilizar a opção "Browse for a file";
- Selecionei a foto *Brooklin_park.jpg* para ser analisada e este foi o resultado apresentado:

## Análise dos Resultados
Eu tentei escolher fotos com mais elementos para testar a IA da plataforma, sendo que tive resultados diversos em relação às minhas expectativas com essas ferrramentas. Quanto à foto de reconhecimento de rostos, escolhi uma em que tivesse óculos de sol e óculos + boné para ver como a ferramenta se comportaria, e o resultado foi como o esperado. Quanto à foto para extração de texto, selecionei uma que havia letras impressas e letras escritas à mão. O resultado gerado foi acima do que eu esperava pois, por se tratar de uma foto tirada em uma rua, havia outras letras que eu não havia me dado conta no momento da seleção, mas a IA reconheceu. Já em relação à foto de legendas de imagens, escolhi uma cheia de elementos para ver quais elementos a IA reconheceria. O resultado frustrou um pouco minhas expectativas, pois não considerou nem o fato do gramado ser à beira de um rio, nem os edifícos ao fundo. Isso nos mostra que a IA da plataforma já possui várias funcionalidades e capacidades, mas ainda pode ser aprimorada, para ser capaz de reconhecer mais elementos.

## 💻Programas Utilizados
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
