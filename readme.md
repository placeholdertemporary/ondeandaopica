# 🚇 Onde anda o pica?

> O passe pesa na carteira — e a multa ainda mais.

"Onde Anda o Pica?" é uma web app que mostra avistamentos recentes de revisores nos transportes públicos em Portugal (começando pelos Metros de Lisboa e Porto).

Os relatos de avistamentos são submetidos por passageiros anónimos e apresentados em tempo quase real.

A página mostra apenas avistamentos das últimas 24 horas, organizados por linha, direção e hora. 

---

## 💻 Stack

Este projeto foi construído com uma filosofia de custo zero e complexidade mínima, utilizando apenas ferramentas estáticas e serviços gratuitos.

**Arquitetura:** Google Form → Google Sheets → HTML + JavaScript → GitHub Pages


| Componente     | Ferramenta        | Função                                                         |
|---------------|-------------------|----------------------------------------------------------------|
| Recolha       | Google Forms      | Submissão anónima de relatos de avistamentos                   |
| Base de Dados | Google Sheets     | Armazenamento de dados e filtragem lógica   |
| Frontend      | Vanilla JS        | Parsing de TSV, agrupamento de dados e renderização dinâmica           |
| Hosting       | GitHub Pages      | Distribuição sob domínio próprio             |

---

## 🛠 Roadmap

Ideias em aberto:

- Versão PWA: Tornar o site instalável no telemóvel.
- Notificações Push: Sistema experimental de alertas por linha.
- Heatmap: Visualização gráfica de estações com mais fiscalização.
- Redes Ferroviárias: Inclusão da CP e Fertagus.

---

## 🤝 Contribuir

Contribuições são muito bem-vindas:

- 💻 Código: Melhorar o código via pull request.
- 🎨 UX/UI: Sugerir formas de melhorar a apresentação mobile.
- ✍️ Copy: Melhorar as mensagens de erro e instruções.
- 📌 Expansão: Ajudar a mapear direções/estações de outras redes.

---

## 📬 Contacto

Tens dúvidas, queres dar feedback ou sugerir uma parceria?

📩 info@ondeandaopica.pt

---
## ⚠️ Disclaimer

Este projeto é independente, feito por um humano e mantido pela comunidade.

É uma ferramenta experimental e sem fins lucrativos, criada para partilha informal de informação entre passageiros, sem qualquer afiliação a operadores de transportes públicos ou privados.

---
