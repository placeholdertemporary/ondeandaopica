# 🚇 Onde anda o pica?

[ondeandaopica.pt](https://ondeandaopica.pt) é uma web app que mapeia avistamentos de revisores nos transportes públicos em Portugal.

Atualmente cobre o metro de Lisboa e o metro do Porto, com relatos anónimos submetidos por passageiros.

## ✨ Funcionalidades

- Avistamentos das últimas 24 horas, por cidade
- Atualização em tempo real via WebSocket
- Agrupamento de avistamentos próximos na mesma linha e direção
- Alertas push por linha e direção (instalação PWA não necessária)
- Interface otimizada para mobile

## 💻 Stack

Este projeto foi construído com uma filosofia de baixo custo e simplicidade estrutural.

**Arquitetura:** Site estático → REST API + WebSocket

| Camada        | Tecnologia              | Função                                              |
|---------------|-------------------------|-----------------------------------------------------|
| Frontend      | HTML + JavaScript       | UI, fetch de dados e renderização                   |
| Backend       | Supabase (Postgres)     | Armazenamento estruturado com RLS                   |
| Realtime      | Supabase Realtime       | Atualizações em tempo real via WebSocket            |
| Notificações  | Supabase Edge Functions | Notificações push via Web Push API (VAPID)          |
| Hosting       | GitHub Pages            | Distribuição sob domínio próprio                    |

## 🤝 Contribuir

Se quiseres ajudar, abre um issue, manda um PR, ou escreve para info@ondeandaopica.pt.

- 💻 Código: Pull requests são bem-vindos, sejam correções ou novas funcionalidades.
- 🎨 UX/UI: Sugestões para tornar a interface mais fluida, especialmente em mobile.
- 🗺️ Expansão: Ajudar a mapear e validar as linhas e direções ferroviárias.

## ⚠️ Disclaimer

Projeto experimental e sem fins lucrativos, criado para partilha informal de informação entre passageiros.

Não tem qualquer afiliação a operadores de transportes públicos ou privados.

_Desenvolvido por um humano, mantido pela comunidade._
