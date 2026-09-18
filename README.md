🎨 SublimStudio Pro
<p align="center">
  <img src="img/01.png" alt="SublimStudio Pro" width="100%">
</p>
<h1 align="center">SublimStudio Pro</h1>
<p align="center">
  <strong>Editor profissional de criação visual, personalização e preparação para sublimação.</strong>
</p>
<p align="center">
  <a href="https://ai-sublimation-studio-pro.ai.studio">🚀 Aplicação Online</a> •
  <a href="https://github.com/ruitobias-eng/AI-Sublimation-Studio-Pro">💻 GitHub</a>
</p>
---
📌 Sobre o projeto
O SublimStudio Pro é uma plataforma de criação visual desenvolvida para profissionais de sublimação, personalização, estamparia, brindes, gráfica rápida e design.
A proposta é reunir em um único ambiente ferramentas de edição 2D, tipografia avançada, geração de elementos gráficos, inteligência artificial, bancos de imagens, mockups 3D e preparação de arquivos para impressão.
O projeto está em desenvolvimento ativo, com foco em uma experiência moderna, responsiva e orientada ao fluxo real de produção.
> **Desenvolvimento:** diBiTech®  
> **Desenvolvedores:** Rui Tobias Carvalho & Rodrigo Carvalho
---
✨ Principais recursos
🎨 Editor de Estampas e Produtos
Área de trabalho visual com canvas.
Camadas e composição de elementos.
Redimensionamento, rotação e posicionamento.
Grade, guias, margem de segurança e sangria.
Produtos e formatos predefinidos.
Suporte a projetos para personalização.
Preparação de artes para sublimação.
🔤 WordArt Studio PRO
Sistema avançado para criação de textos decorativos:
Efeitos 3D.
Arcos e textos circulares.
Neon.
Metalizado.
Dourado.
Retro 3D.
Selos.
Nuvens e composições tipográficas.
Gradientes e paletas voltadas à sublimação.
Gerenciamento de fontes OTF, TTF e WOFF2.
Integração com Google Fonts.
☁️ Word Cloud Generator
Criação de nuvens de palavras para composições personalizadas.
Formas disponíveis incluem:
☕ Caneca
👕 Camiseta
❤️ Coração
⭐ Estrela
⭕ Círculo
👑 Coroa
🔥 Chama
🛡️ Escudo
Também permite controlar frequência, densidade, orientação e composição visual.
🔳 QR Code Art
Criação de QR Codes estilizados e funcionais para:
URLs
Wi-Fi
WhatsApp
E-mail
vCard
Outros conteúdos personalizados
Com opções de:
cores;
molduras;
bordas;
estilos;
logotipo central;
exportação em SVG e PNG.
🖼️ Frames, máscaras e imagens
Ferramentas para trabalhar com fotografias e elementos gráficos:
Molduras estilizadas.
Máscaras.
Composições para retratos.
Elementos com transparência.
Upload de imagens.
Colagem a partir da área de transferência.
Suporte a PNG com alpha.
🤖 AI Studio
Ambiente para geração e preparação de imagens com IA.
Exemplos de categorias:
Floral / Watercolor
Cyberpunk
Anime
Pets
Profissões
Temas personalizados
O fluxo é orientado à criação de artes que possam ser utilizadas em produtos personalizados e projetos de sublimação.
🏞️ Bancos de Imagens HD
O projeto prevê integração com bancos de imagens e fontes de conteúdo visual, incluindo:
Unsplash
Pexels
Pixabay
Wikimedia
A arquitetura permite ampliar futuramente o conjunto de provedores disponíveis.
🧊 Mockup 3D em tempo real
Visualização da arte aplicada em produtos tridimensionais.
Recursos:
Rotação 360°.
Visões frontal, lateral, traseira, superior e isométrica.
Simulação de superfícies.
Produtos cilíndricos e cônicos.
Visualização de canecas, camisetas, almofadas e outros produtos personalizados.
🖨️ Central de Impressão
Módulo destinado à preparação da produção:
Nesting automático.
Aproveitamento da folha.
Repetição de artes.
A4, A3, A3+, Letter e Ofício.
Marcas de corte e registro.
Pré-visualização.
Preparação para fluxo RIP.
Informações relacionadas a cores e consumo estimado.
---
🧩 Fluxo de trabalho
```text
┌───────────────────────┐
│  1. Produto / Formato │
└───────────┬───────────┘
            ↓
┌───────────────────────┐
│  2. Criação da Arte   │
│     Editor 2D         │
└───────────┬───────────┘
            ↓
┌───────────────────────┐
│  3. Elementos / IA    │
│     Imagens / Texto   │
└───────────┬───────────┘
            ↓
┌───────────────────────┐
│  4. Mockup 3D         │
│     Visualização      │
└───────────┬───────────┘
            ↓
┌───────────────────────┐
│  5. Central Impressão │
│     Nesting / RIP     │
└───────────┬───────────┘
            ↓
┌───────────────────────┐
│  6. Produção          │
│     Impressão         │
└───────────────────────┘
```
---
🖼️ Galeria
As imagens da documentação ficam na pasta `img/`.
Interface principal
![Interface principal](img/01.png)
Templates e projetos
![Templates e projetos](img/02.png)
Texto e gerenciamento de fontes
![Texto e fontes](img/03.png)
Word Cloud
![Word Cloud](img/04.png)
WordArt Studio PRO
![WordArt Studio PRO](img/05.png)
Gerador de WordArt
![Gerador de WordArt](img/06.png)
QR Code Art
![QR Code Art](img/07.png)
Frames e edição de fotos
![Frames e edição de fotos](img/08.png)
AI Studio
![AI Studio](img/09.png)
Upload e clipboard
![Upload e clipboard](img/10.png)
Produtos e formatos cônicos
![Produtos](img/11.png)
Bancos de imagens HD
![Bancos de imagens](img/12.png)
Central de Impressão e Nesting
![Central de Impressão](img/13.png)
RIP e estimativa de produção
![RIP e estimativa](img/14.png)
---
🏗️ Arquitetura
```text
                       SUBLIMSTUDIO PRO
                              │
              ┌───────────────┼───────────────┐
              │               │               │
              ▼               ▼               ▼
        ┌──────────┐    ┌──────────┐    ┌──────────┐
        │ Editor   │    │ AI       │    │ Mockup   │
        │ 2D       │    │ Studio   │    │ 3D       │
        └────┬─────┘    └────┬─────┘    └────┬─────┘
             │               │               │
             └───────────────┼───────────────┘
                             ▼
                  ┌─────────────────────┐
                  │ Produção / Pré-press│
                  └──────────┬──────────┘
                             ▼
                  ┌─────────────────────┐
                  │ Central de Impressão│
                  └──────────┬──────────┘
                             ▼
                 ┌──────────────────────┐
                 │ Nesting + RIP/Preview│
                 └──────────────────────┘
```
---
📐 Preparação para sublimação
O projeto foi concebido considerando requisitos comuns de produção gráfica e sublimação, incluindo:
resolução de trabalho em alta qualidade;
referência de 300 DPI para produção;
exportação PNG com transparência;
arquivos preparados para impressão;
espelhamento de artes quando necessário;
sangria;
área segura;
organização por camadas;
composição em formatos de produtos;
preparação para fluxo de impressão.
Exemplo de referência
Para uma arte vertical de proporção 4:5:
```text
Canvas lógico
1080 × 1350 px

Produção a 300 DPI
3240 × 4050 px
```
Os valores podem variar conforme o produto, tamanho físico e fluxo de impressão utilizado.
---
📱 Design responsivo
O SublimStudio Pro foi projetado com foco em desktop, tablet e dispositivos móveis.
Canvas Sempre Visível
A experiência responsiva prioriza manter a área de criação disponível durante a edição.
Desktop
```text
┌─────────────────────────────────────────────────────┐
│                    Top Menu                          │
├───────┬───────────────────────────────┬─────────────┤
│ Tools │                               │ Properties  │
│       │             CANVAS            │             │
│       │                               │             │
├───────┴───────────────────────────────┴─────────────┤
│                    Footer                            │
└─────────────────────────────────────────────────────┘
```
Mobile
```text
┌───────────────────────────┐
│       Top Menu            │
├───────────────────────────┤
│                           │
│          CANVAS           │
│                           │
├───────────────────────────┤
│   Ferramentas / Painéis   │
│                           │
├───────────────────────────┤
│      Bottom Navigation    │
└───────────────────────────┘
```
A interface utiliza conceitos como `100dvh`, áreas de toque maiores e adaptação dos painéis para telas menores.
---
🛠️ Tecnologias
Tecnologia	Utilização
React	Interface
TypeScript	Tipagem e arquitetura
Vite	Build e desenvolvimento
Tailwind CSS	Design system
Zustand	Estado global
Canvas API	Editor 2D
SVG	Elementos vetoriais
Three.js	Visualização 3D
WebGL	Renderização 3D
PWA	Experiência instalável
Web Workers	Processamento em background
---
🚀 Executando localmente
1. Clonar o repositório
```bash
git clone https://github.com/ruitobias-eng/AI-Sublimation-Studio-Pro.git
```
2. Entrar no projeto
```bash
cd AI-Sublimation-Studio-Pro
```
3. Instalar dependências
```bash
npm install
```
4. Executar em desenvolvimento
```bash
npm run dev
```
5. Criar build de produção
```bash
npm run build
```
6. Visualizar a build
```bash
npm run preview
```
---
📦 Estrutura conceitual
```text
src/
├── components/
├── features/
│   ├── editor/
│   ├── wordart/
│   ├── wordcloud/
│   ├── qrcode/
│   ├── ai/
│   ├── frames/
│   ├── mockup3d/
│   └── printing/
├── stores/
├── assets/
├── types.ts
├── App.tsx
├── main.tsx
└── index.css

img/
├── 01.png
├── 02.png
├── 03.png
├── 04.png
├── 05.png
├── 06.png
├── 07.png
├── 08.png
├── 09.png
├── 10.png
├── 11.png
├── 12.png
├── 13.png
└── 14.png
```
> A estrutura acima representa a organização conceitual do projeto. Os nomes das pastas podem evoluir conforme a arquitetura do código.
---
🗺️ Roadmap
Editor
[x] Canvas de criação
[x] Composição visual
[x] Camadas
[x] Produtos predefinidos
[ ] Evolução do sistema de seleção e transformação
[ ] Refinamento de histórico Undo/Redo
WordArt
[x] Efeitos tipográficos
[x] Gradientes
[x] Efeitos 3D
[x] Gerenciamento de fontes
[ ] Expansão de efeitos avançados
AI Studio
[x] Interface de geração
[x] Prompts orientados a categorias
[x] Histórico de sessão
[ ] Ampliação das integrações
Mockup 3D
[x] Visualização 3D
[x] Rotação
[x] Diferentes produtos
[ ] Otimização de deformação cônica
[ ] Refinamento das rotinas 3D
Impressão
[x] Central de impressão
[x] Nesting
[x] Pré-visualização
[ ] Otimização das rotinas RIP
[ ] Evolução da estimativa de consumo
Responsividade
[x] Desktop
[x] Tablet
[x] Mobile
[ ] Refinamentos contínuos de touch e interação
---
🔐 Segurança e privacidade
O projeto deve tratar cuidadosamente:
arquivos enviados pelo usuário;
conteúdo SVG;
imagens externas;
credenciais e tokens de APIs;
conteúdo gerado por IA;
dados persistidos localmente.
Chaves privadas de serviços externos não devem ser expostas no código cliente ou armazenadas de forma insegura.
---
🎯 Público-alvo
O SublimStudio Pro foi pensado principalmente para:
🎨 Designers
🖨️ Gráficas rápidas
☕ Sublimadores
👕 Estúdios de personalização
🎁 Empresas de brindes
🧑‍💻 Freelancers
🏭 Pequenos negócios de produção personalizada
---
🌐 Aplicação
🚀 Demo online
https://ai-sublimation-studio-pro.ai.studio
💻 Repositório
https://github.com/ruitobias-eng/AI-Sublimation-Studio-Pro
---
📸 Documentação visual
As capturas de tela apresentadas neste README fazem parte da documentação visual do projeto e estão organizadas na pasta:
```text
/img
```
O README utiliza exatamente os arquivos:
```text
01.png
02.png
03.png
04.png
05.png
06.png
07.png
08.png
09.png
10.png
11.png
12.png
13.png
14.png
```
---
👨‍💻 Desenvolvimento
diBiTech®
Soluções em Engenharia, Automação e Computação
Desenvolvimento:
Rui Tobias Carvalho  
Rodrigo Carvalho
---
📄 Licença
Defina aqui a licença oficial do projeto antes da publicação, caso o repositório seja disponibilizado como código aberto.
Exemplo:
```text
Copyright © diBiTech®
Todos os direitos reservados.
```
---
<p align="center">
  <strong>🎨 SublimStudio Pro</strong><br>
  Criação visual • Sublimação • Personalização • IA • 3D • Impressão
</p>
<p align="center">
  Desenvolvido por <strong>diBiTech®</strong>
</p>
