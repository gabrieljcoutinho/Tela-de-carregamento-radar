# 🛰️ Radar Scanning Loader

Uma tela de carregamento inspirada em radares de sonar e sistemas de monitoramento de tráfego aéreo. Em vez de apenas esperar, o usuário sente que o sistema está "escaneando" e localizando os arquivos necessários.

## 📡 O Conceito
A animação simula um feixe de luz giratório que varre uma área circular. Sempre que o feixe passa por um "ponto de interesse", ele brilha, indicando que um pacote de dados foi encontrado e carregado.

### 🧩 Componentes do Design
* **O Varredor (Sweep):** Uma linha radial com rastro de gradiente que gira 360°.
* **Círculos Concêntricos:** Grades que dão a sensação de profundidade e escala.
* **Blips (Pontos):** Pequenos sinais que aparecem aleatoriamente para simular a descoberta de dados.

---

## 🛠️ Tecnologias e Performance

Este loader foi construído com foco em ser **leve** e **altamente performático**:

* **CSS Conic-Gradients:** Para criar o efeito de rastro do radar sem precisar de imagens pesadas.
* **SVG Filters:** Para o efeito de "blur" e brilho (glow) nos pontos detectados.
* **Opacity Keyframes:** Para simular o desvanecimento (fade-out) do sinal após a passagem do feixe.

---

## 📊 Anatomia do Radar

| Elemento | Estilo | Movimento |
| :--- | :--- | :--- |
| **Linha de Varredura** | Verde Neon (#00FF00) | Rotação Contínua |
| **Grade de Fundo** | Opacidade Baixa (0.1) | Estático |
| **Alvos (Blips)** | Pulsação de Brilho | Fade-in / Fade-out |

---

<img width="217" height="235" alt="Image" src="https://github.com/user-attachments/assets/18f790fd-e4bd-4913-aa2d-69b7ec1411a9" />
