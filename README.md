# 🕶️ Atividade 2: Cubo Mágico em Realidade Aumentada (WebAR)

<p align="center">
  <img src="https://img.shields.io/badge/A--Frame-1.3.0-EF2D5E?style=for-the-badge&logo=a-frame&logoColor=white" alt="A-Frame Version">
  <img src="https://img.shields.io/badge/AR.js-3.4.8-4caf50?style=for-the-badge" alt="AR.js Version">

Este projeto é uma aplicação de **Realidade Aumentada baseada na Web (WebAR)** 

A aplicação projeta um modelo 3D, modelado via Fusion 360, de um **Cubo Mágico** sobre o clássico marcador **Hiro**, permitindo interações dinâmicas diretamente no navegador.

---

## ✨ Funcionalidades

*   **Tumbling 3D Orbital (Visualização Fluida):** O cubo possui uma animação contínua e rica nos eixos X, Y e Z (usando funções trigonométricas de seno e cosseno), garantindo que o usuário consiga visualizar todas as faces coloridas do modelo de forma elegante.
*   **Interações de Toque Inteligentes:**
    *   **Clique Rápido (<250ms):** Dispara uma animação de giro local elástico de 360° (efeito de rebote `easeOutBack`) combinado com um "pulso/pop" de escala temporário.
    *   **Toque Longo (Hold):** Aumenta suavemente a escala do cubo usando interpolação linear (**LERP**), permitindo aproximar e inspecionar detalhes do modelo. Ao soltar, o cubo retorna suavemente ao tamanho padrão de forma amortecida.
*   **Console de Desenvolvedor Portátil (Eruda):** Integração direta com ferramentas de depuração (DevTools móvel) na tela do smartphone, facilitando a inspeção de logs e requisições de rede em tempo real no dispositivo físico.
*   **Segurança de Integridade 3D:** Equipado com regras Git robustas (`.gitattributes`) para prevenir corrupções de bytes (conversões de quebra de linha CRLF/LF) em modelos binários complexos.

---

## 📸 Como Testar a Realidade Aumentada

Para vivenciar a experiência do Cubo Mágico em 3D, siga os passos abaixo:

### 1. Obtenha o Marcador
Imprima ou exiba em outra tela o marcador padrão **Hiro**:

<p align="center">
  <img src="https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/HIRO.jpg" width="250" alt="Marcador Hiro" style="border: 20px solid white; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.15);">
</p>

### 2. Acesse a Aplicação
Abra o link publicado do **GitHub Pages** no navegador do seu celular:
👉 **[Acesse o Projeto Aqui!](https://nicolasraf.github.io/Atividade2-ImersaoRA/)**

### 3. Aponte a Câmera
Autorize o uso da câmera do celular no navegador e aponte para o marcador **Hiro** exibido. O Cubo Mágico 3D carregará instantaneamente sobre ele!

---

## 🛠️ Tecnologias Utilizadas

*   **[A-Frame (v1.3.0)](https://aframe.io/):** Framework web para a criação de experiências de Realidade Virtual e Aumentada utilizando entidade-componente sobre HTML.
*   **[AR.js (v3.4.8)](https://github.com/AR-js-org/AR.js):** Biblioteca ultra-leve e de altíssima performance para detecção e rastreamento de marcadores via câmera em tempo real.
*   **[Eruda DevTools](https://github.com/liriliri/eruda):** Console de desenvolvedor portátil para monitoramento e depuração no ecossistema mobile.
*   **glTF / bin:** Padrão de modelo 3D de alta fidelidade e eficiência de transmissão web, modelado e exportado via Windows 3D Builder.

---

## 🧑‍💻 Autoria e Desenvolvimento

*   **Desenvolvedor:** Nicolas Rafael

