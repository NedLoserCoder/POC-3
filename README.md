# POC-3- Media Queries
## Sistemas de Informação, 02J L12
### Andreas Caycedo Martinez 10435302
###Caio Takehiro Magnoli Igari 10437809
-- Este código é uma prova de conceito focada em aplicar media queries em uma página HTML, isso siginifica que dependendo do tamanho da tela(computador, tablet e celular) o site terá um layout diferente e também serão apresentadas outras formas de utilizar essa ferramenta.

- Código HTML

O arquivo abaixo contém uma estrutura simples com um header que exibe o título da página, um menu com links e algumas imagens. As media queries são responsáveis por mudar o layout desses elementos de acordo com o tamanho do dispositivo de visualização.

![370463764-600b9c04-6028-466f-940c-d6726420a86b](https://github.com/user-attachments/assets/3103d87e-a12f-4e05-9182-1b8b73cd3ff5)

- Código CSS

-- O CSS utiliza principalmente o flexbox para organizar o layout, e as media queries ajustam o flexbox de diferentes maneiras dependendo do tamanho da tela.

A estrutura CSS abaixo é uma estrutura básica para dar formato ao site, como ja foi dito anteriormente ela utiliza o flexbox para uma melhor disposição dos elementos do site, essa estrutura também é o estilo inicial do site, ela define um layout flexível que faz com que a galeria de imagens se adaptem aos espaços disponíveis.

![370464148-b5d9c267-eef8-463d-84ab-e9b25f33f806](https://github.com/user-attachments/assets/e32b5797-57b9-4324-a721-989e81076ab0)

- Aplicação das Media Queries
  
-- Nesse projeto abordamos o media queries para celulares, tablets e desktops, entretanto também utilizamos algumas funções interessantes como print, landscape e portrait.

- Media Query para Telas Pequenas (smartphones)
  
Quando a largura da tela é menor que 600px, o layout muda . Os itens do menu de navegação passam a ser exibidos em uma única coluna, e a galeria de imagens é reorganizada para se adequar ao espaço reduzido de um smartphone.

![370470211-bade223b-813b-4d00-aca4-247961f16d23](https://github.com/user-attachments/assets/91618cca-31c5-43c2-858a-5e55f3a950d1)

- Media Query para Telas Médias (tablets)

Essa media query entra em ação quando a largura da tela tem o tamanho entre 601px e 1024px. Aqui, o layout da galeria é ajustado para que os elementos ocupem mais espaço verticalmente, facilitando a visualização em tablets ou laptops menores, e diferente do celular os elementos escritos ficam em sequencia de forma horizontal.

![370470876-1b882d7a-1f11-4c80-8be5-1487478de039](https://github.com/user-attachments/assets/e49f0890-db86-4536-a011-4e2e9fbd33be)

- Media Query para Telas Grandes (Desktop)
  
Dessa vez o media query entra em ação apenas quando a largura da tela tem mais de 1024px. Aqui, diferente dos outros casos, as imagens se organizam de forma horizontal (lado a lado), e só quando acaba o espaço horizontal as imagens vão para próxima linha.

![370472322-ff1413ef-c331-4190-8f9f-78dd6465a726](https://github.com/user-attachments/assets/7403ccfd-059a-400e-b11e-f13e815650d6)

- Media Query Print

O print é usada para definir estilos que serão aplicados apenas quando o usuário  for imprimir a página, nesse caso ele esconderá alguns elementos não tão importantes da página, economizando recursos como papel e tinta.

![370473873-2c2825fc-2599-406a-9f68-1a497a943cb1](https://github.com/user-attachments/assets/a3c9df39-c0c2-4652-b376-ae51e1f6b533)

-- Os próximos dois casos servem para controlar o layout de uma página web com base na orientação da tela (portrait ou landscape)

- Media Query Landscape e Portrait
- Landscape (Paisagem)

Esse modo é ativado quando a largura da tela é maior do que a altura, então nessa situação as imagens na galeria serão redimensionadas para ocupar 25% da largura da tela, menos 10px para espaçamento entre elas e também o conteúdo em textp é dividido em 4 colunas.

- Portrait (Retrato)

Esse modo é ativado quando a largura da tela é menor do que a altura, então nessa situação as imagens na galeria ocupam 100% da largura da tela, fazendo com que as imagens fiquem maiores e centralizadas, e as colunas de texto serão divididas em 2.

![370475382-4ba61229-e1f0-4882-ae63-f8e890995816](https://github.com/user-attachments/assets/4b66e527-dd75-4b6b-8dd3-46e096236618)

--Resultados

-Tela para PC (Landscape)

Em uma tela de computador, o layout é exibido com um menu de navegação horizontal e a galeria de imagens disposta lado a lado, assim como já era previsto tanto pelo código de desktop quanto de landscape.

![370477243-c51d942c-8ac2-4be1-ada1-7a5f6f0f954d](https://github.com/user-attachments/assets/3ad28b2c-2542-4c2e-9395-17b13e5de462)


-Tela Tablets (Portrait)

Quando a tela é reduzida para o tamanho de um tablet, o menu de navegação passa a ser exibido em formato de coluna, e a galeria de imagens ocupa mais espaço verticalmente, a principal diferença entre esse formato e o de celular é a parte escrita superior do site, na forma como ela é organizada, e também assim como na de celular eles são organizados na forma portrait (Retrato).

![370478145-aaa1a346-b3fa-457c-ae57-47a257728ae5](https://github.com/user-attachments/assets/ce496502-5b3e-45cf-a06e-0d5ae6015d76)

-Tela de Smartphone (Portrait)

Para telas de smartphones, o layout é ainda mais compacto: o menu de navegação é exibido verticalmente, e a galeria de imagens é empilhada para facilitar a visualização em uma tela pequena, assim como o tablet o texto abaixo das imagens é apresentado por 2 colunas pois permance com os comandos definidos pelo portrait.

![370480282-06d841c6-a8c4-43fa-9c85-1047a1e417eb](https://github.com/user-attachments/assets/58548550-2f7d-454b-a39c-7cadd728970c)
![370480969-0e352337-ce48-4df5-a8ec-f6a293413d7f](https://github.com/user-attachments/assets/bbe67829-4b02-4fa4-b36f-f86cb86fb987)

Este projeto demonstra como o uso de media queries no CSS é fundamental para criar layouts responsivos, ajustando o design de forma adequada para diferentes dispositivos, desde telas grandes de PCs até smartphones compactos.
