# Projetos Front-End para Computação Gráfica

Este repositório contém uma coleção de projetos interativos desenvolvidos com foco na **Computação Gráfica** utilizando **Front-End**. Os projetos abrangem uma variedade de técnicas gráficas aplicadas em interfaces web, desde conceitos de **teoria da cor** até **transformações 3D** e **animações complexas**. Utilizando principalmente **JavaScript**, **HTML**, **CSS** e **WebGL**, os projetos permitem a exploração e visualização de diversos conceitos da computação gráfica.

## O Que Você Vai Aprender

Os projetos deste repositório são uma maneira prática de aprender e explorar conceitos fundamentais da computação gráfica e como aplicá-los em páginas web. Entre os tópicos abordados estão:

- **Teoria da Cor em Computação Gráfica**: Conversões de espaço de cor, acessibilidade visual, harmonia cromática e manipulação de paletas de cores.
- **Processamento de Imagens**: Filtros espaciais, detecção de bordas, equalização de histograma, segmentação e análise de imagens.
- **Primitivas 2D e 3D**: Desenho de formas, implementações de algoritmos de rasterização, transformações, clipping e projeção 3D.
- **Animação e Física**: Animação por interpolação, animação hierárquica, física simples, animação esquelética, entre outros.
- **Materiais e Texturas**: Aplicação de texturas, normal maps, mapeamento UV, reflexões e refrações.

## Lista de Projetos

### Teoria da Cor em Computação Gráfica

- **Color Picker Customizado (RGB, HSL e Hex)**
  - **Objetivo**: Demonstrar a relação entre diferentes espaços de cor (RGB, HSL, Hexadecimal).
  - **Ensina**: Conversão entre espaços de cor, noções de matiz, saturação e luminosidade.
  
- **Simulador de Cegueira de Cores**
  - **Objetivo**: Mostrar como as cores são percebidas por pessoas com diferentes tipos de daltonismo.
  - **Ensina**: Componentes de cor, contraste e teoria aplicada à acessibilidade.
  
- **Criador de Paleta Harmônica**
  - **Objetivo**: Gerar paletas harmônicas com base em teorias de cores (análoga, complementar, triádica).
  - **Ensina**: Círculo cromático e ângulos de combinação de cores.
  
- **Gradiente Interativo**
  - **Objetivo**: Explorar transições suaves entre cores.
  - **Ensina**: Interpolação de cores e blending (mistura de cores).
  
- **Analisador de Contraste (WCAG Compliance)**
  - **Objetivo**: Verificar se o contraste entre cor de fundo e texto atende aos padrões WCAG.
  - **Ensina**: Percepção visual, luminância relativa e acessibilidade.

- **Recriando Obras Famosas com Cores Básicas**
  - **Objetivo**: Analisar como artistas usam teoria da cor.
  - **Ensina**: Limitação de paleta, mistura de cores e composição estética.

- **Aplicação de Filtros (Tint, Sepia, Grayscale, Invert)**
  - **Objetivo**: Manipular canais de cor e aplicar filtros digitais em imagens.
  - **Ensina**: Operações pixel a pixel com a API Canvas.

### Processamento, Análise e Síntese de Imagens

- **Filtros Espaciais (Suavização e Realce)**
  - **Objetivo**: Aplicar filtros como Gaussian Blur, sharpen e emboss.
  - **Ensina**: Convolução 2D e operações locais em imagens.

- **Detecção de Bordas (Sobel, Prewitt, Canny Simplificado)**
  - **Objetivo**: Detectar bordas em imagens utilizando algoritmos de gradiente.
  - **Ensina**: Derivadas discretas, gradiente de intensidade e thresholding.

- **Equalização de Histograma**
  - **Objetivo**: Ajustar o contraste global de uma imagem.
  - **Ensina**: Distribuição de tons e manipulação de intensidades.

- **Segmentação Simples (Thresholding e K-means)**
  - **Objetivo**: Separar objetos do fundo em uma imagem.
  - **Ensina**: Agrupamento de pixels e métricas de similaridade.

- **Analisador de Formas e Contornos (Bounding Box & Área)**
  - **Objetivo**: Detectar formas e calcular áreas e perímetros.
  - **Ensina**: Identificação de regiões conectadas e análise de contornos.

- **Heatmap de Frequência de Cores**
  - **Objetivo**: Visualizar quais áreas têm maior incidência de cor ou brilho.
  - **Ensina**: Análise estatística e percepção visual.

- **Geração Procedural de Texturas**
  - **Objetivo**: Criar texturas como mármore, madeira ou nuvens.
  - **Ensina**: Uso de ruído para gerar padrões aleatórios.

- **Fractais Visuais (Mandelbrot, Julia Set)**
  - **Objetivo**: Gerar imagens fractais interativas com zoom.
  - **Ensina**: Recursão visual e conceitos de complexidade emergente.

- **Morphing Entre Duas Imagens**
  - **Objetivo**: Interpolar entre duas imagens progressivamente.
  - **Ensina**: Interpolação linear e correspondência de pontos.

### Primitivas 2D e 3D

- **Editor de Desenho Vetorial Básico (SVG ou Canvas)**
  - **Objetivo**: Criar primitivas 2D e aplicar transformações.
  - **Ensina**: Algoritmo de rasterização e transformações geométricas.

- **Implementação Manual do Algoritmo de Bresenham**
  - **Objetivo**: Desenhar linhas pixel a pixel.
  - **Ensina**: Algoritmo de rasterização eficiente.

- **Visualizador de Clipping (Cohen-Sutherland ou Liang-Barsky)**
  - **Objetivo**: Visualizar como objetos são recortados na viewport.
  - **Ensina**: Algoritmos clássicos de clipping e eficiência no pipeline gráfico.

- **Aplicação de Transformações 2D (Matrizes)**
  - **Objetivo**: Aplicar transformações como rotação e escala em 2D.
  - **Ensina**: Matrizes 2D e não-comutatividade das transformações.

- **Visualizador de Primitivas 3D Básicas (WebGL ou Three.js)**
  - **Objetivo**: Exibir formas 3D e permitir interação com rotação e zoom.
  - **Ensina**: Controle de câmera e projeção 3D.

- **Construção Manual de um Cubo Wireframe**
  - **Objetivo**: Criar um cubo 3D e aplicar projeção perspectiva.
  - **Ensina**: Matrizes 3D e conceitos de pipeline gráfico.

- **Gerador Procedural de Prismas e Poliedros**
  - **Objetivo**: Gerar prismas e poliedros com controle de parâmetros.
  - **Ensina**: Geometria algorítmica e topologia 3D.

### Animação e Física

- **Animação de Transformações 3D**
  - **Objetivo**: Criar animações contínuas de rotação 3D.
  - **Ensina**: Matrizes compostas e sistemas de coordenadas.

- **Explorador de Luzes e Materiais (Phong, Gouraud básico)**
  - **Objetivo**: Visualizar efeitos de luz em primitivas 3D.
  - **Ensina**: Modelos de sombreamento e propriedades de materiais.

- **Textura Animada ou Dinâmica (GIF ou Sprite Sheet sobre Objeto)**
  - **Objetivo**: Aplicar texturas animadas em malhas 3D.
  - **Ensina**: Manipulação de texturas em tempo real.

- **Animação por Interpolação Linear e Não-Linear**
  - **Objetivo**: Criar animações com curvas de interpolação.
  - **Ensina**: Conceitos de interpolação e animações suaves.

- **Animação Hierárquica (Cinemática Direta)**
  - **Objetivo**: Montar figuras compostas com animações hierárquicas.
  - **Ensina**: Transformações compostas e cinemática direta.

- **Física Básica e Simulação (Gravidade, Colisão Simples)**
  - **Objetivo**: Implementar animações com física simples (gravidade, colisões).
  - **Ensina**: Movimento, aceleração e controle de tempo.

## Tecnologias Utilizadas

- **HTML5**, **CSS3**, **JavaScript**: Estruturação de interfaces e manipulação de gráficos.
- **Canvas API**: Para renderizar gráficos 2D e manipular pixels.
- **WebGL**, **Three.js**: Para gráficos 3D e animações.
- **Perlin Noise**, **Simplex Noise**: Para geração procedural de texturas.

## Como Rodar os Projetos

1. Clone o repositório:
    ```bash
    git clone https://github.com/Jvms04/projetoComputacaoGrafica.git
    ```

2. Abra o diretório do projeto e inicie um servidor local (por exemplo, usando `Live Server` no VSCode ou Python):
    ```bash
    python -m http.server
    ```

3. Acesse o projeto no navegador: `http://localhost:8000`.

## Contribuições

Sinta-se à vontade para contribuir com novos projetos ou melhorias! Abra uma **issue** ou envie um **pull request** com suas sugestões.

---

### Explicação do README:

- **Introdução sobre a área**: Explica o que é computação gráfica e como ela se aplica ao front-end.
- **Lista de projetos**: Cada projeto é descrito brevemente, com foco no que ele ensina e os conceitos envolvidos.
- **Tecnologias**: Explica as tecnologias usadas nos projetos, como HTML, CSS, JavaScript, e WebGL.
- **Instruções de execução**: Um guia simples de como rodar os projetos localmente.
- **Licença e contribuições**: Instruções de como contribuir e informações sobre a licença.

Esse formato de **README.md** proporciona um resumo claro e organizado dos projetos e também ajuda outros desenvolvedores a entenderem rapidamente o que o repositório oferece.

**Desenvolvido por Gustavo Pereira, João Vitor e Miguel Migailides**.
