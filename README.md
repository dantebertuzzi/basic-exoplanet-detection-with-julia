# Análise de Curva de Luz de Exoplaneta (K2SFF - Campanha 13)

Este notebook tem como objetivo realizar uma análise exploratória de uma curva de luz do telescópio Kepler/K2, obtida através do projeto K2SFF (K2 Self Flat-Fielding). O experimento foca na detecção e caracterização preliminar de eventos de trânsito de exoplanetas.

## 🪐 Planeta e Estrela

### 🌟 Estrela: EPIC 246 911 830 (também conhecida como K2‑260)

- **Tipo espectral**: F6V (anã amarela mais quente e maior que o Sol), com temperatura na superfície cerca de **6 370 K**  
  Referência: [astro.keele.ac.uk](https://www.astro.keele.ac.uk), [exoplanetkyoto.org](https://www.exoplanetkyoto.org), [arXiv](https://arxiv.org)

- **Massa** ≈ **1,39 M☉**, **Raio** ≈ **1,69 R☉**  
  Referência: [exoplanet.eu](https://exoplanet.eu), [exoplanetkyoto.org](https://www.exoplanetkyoto.org), [arXiv](https://arxiv.org)

- **Magnitude aparente**: ~12,7  
  Referência: [Oxford Academic](https://academic.oup.com), [exoplanetkyoto.org](https://www.exoplanetkyoto.org)

- **Distância**: aproximadamente **2 205 anos‑luz (676 pc)** da Terra  
  Referência: [Wikipédia](https://wikipedia.org), [exoplanetkyoto.org](https://www.exoplanetkyoto.org)

---

### 🪐 Planeta: EPIC 246 911 830 b (também chamado K2‑260 b)

- **Tipo**: *Hot Jupiter*, ou seja, um gigante gasoso próximo da estrela.

- **Período orbital**: ~**2,627 dias** (cerca de 63 horas)  
  Referência: [arXiv](https://arxiv.org), [Wikipédia](https://wikipedia.org)

- **Raio** ≈ **1,55 RJúpiter**, **Massa** ≈ **1,42 MJúpiter**  
  Referência: [Wikipédia](https://wikipedia.org), [arXiv](https://arxiv.org)

- Foi o **primeiro Hot Jupiter detectado na missão K2 com eclipse secundário visível**, usado para estimar a refletividade (**albedo geométrico** ≈ **0,2**)  
  Referência: [arXiv](https://arxiv.org), [Oxford Academic](https://academic.oup.com)


## Objetivos:
1.  **Carregamento de Dados:** Importar e inspecionar a curva de luz de um alvo específico da Campanha 13 do K2.
2.  **Processamento Inicial:** Preparar os dados para análise, identificando e isolando as mínimas de brilho causadas por trânsitos.
3.  **Caracterização de Trânsitos:** Calcular propriedades como o período do trânsito e a variação do fluxo durante o evento.
4.  **Estimativa do Raio Planetário:** Utilizar as informações da curva de luz para estimar o raio do exoplaneta em relação a Júpiter.

  Referência: [Felipe Hime - Usando Python e Data Science em Exoplanetas | Ep1](https://www.youtube.com/watch?v=lgnQdQmB_3o&list=PLgGmq5CrIhxY5j7TXVrIT2RotMdSiO5gN&index=7)

---
