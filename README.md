# Imersao-Alura-IA
# ✈️ Assistente de Viagens com Gemini Agents 🏨

Bem-vindo ao seu Assistente de Viagens pessoal, desenvolvido com o poder dos Gemini Agents! Este projeto visa simplificar o planejamento das suas viagens, buscando e organizando informações cruciais sobre hotéis e passagens aéreas de forma rápida e eficiente.

## ✨ Funcionalidades

Este assistente interage com você para coletar informações sobre a sua viagem e, em seguida, utiliza dois agentes especializados do Google ADK para:

1.  **Buscar Hotéis:** Encontra as 5 estadias mais relevantes com base no local de interesse, datas de check-in e check-out, e número de hóspedes, fornecendo detalhes como avaliação, preço, distância do aeroporto e pontos de interesse.
2.  **Buscar Passagens:** Com base nas informações das estadias, busca as 5 passagens aéreas mais relevantes, incluindo detalhes como companhia aérea, preços de ida e volta, horários e duração do voo.

Todas as informações são apresentadas em tabelas estruturadas para facilitar a sua visualização e comparação. Após a apresentação das tabelas, você pode interagir com o assistente para tirar dúvidas sobre as informações fornecidas.

## 🚀 Como Usar

1.  **Configure seu ambiente:** Certifique-se de ter o Google Colaboratory ou Jupyter Notebook configurado e com as bibliotecas necessárias instaladas (`google-genai`, `google-adk`).
2.  **Obtenha sua API Key:** Armazene sua chave de API do Google Gemini de forma segura no Google Colab Secrets (ou outro método seguro em seu ambiente). O código busca esta chave na variável de ambiente `GOOGLE_API_KEY`.
3.  **Execute o código:** Rode as células do notebook.
4.  **Interaja:** O assistente solicitará as informações necessárias para a sua viagem (local de partida, destino, datas, número de hóspedes).
5.  **Visualize os resultados:** As tabelas com as sugestões de hotéis e passagens serão exibidas.
6.  **Tire suas dúvidas:** Após as tabelas, você pode fazer perguntas sobre as informações apresentadas ou digitar "Encerrar" para finalizar a interação.

## 🧠 Arquitetura

O projeto utiliza:

-   **Google Gemini API:** Para gerar conteúdo textual e manter a conversação interativa.
-   **Google ADK (Agent Development Kit):** Para criar agentes especializados (Buscador de Hotéis e Buscador de Passagens).
-   **Ferramenta `google_search`:** Utilizada pelos agentes para realizar pesquisas na web e coletar as informações de hotéis e passagens.
-   **InMemorySessionService:** Para gerenciar a sessão da conversa.

## 🤝 Contribuição

Sinta-se à vontade para explorar o código, sugerir melhorias ou reportar problemas. Contribuições são bem-vindas!

---

📖 Criado por Mateus Ortega Mendes. Imersão IA Alura
