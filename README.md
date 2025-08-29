---
# Projeto DIO - Análise de Sentimentos com Language Studio no Azure AI aplicado em site de hospedagem 🎙️

## 📌 Descrição
Este projeto foi desenvolvido como parte do desafio da [Digital Innovation One](https://www.dio.me/), com foco em aplicar os recursos do **Azure Speech Studio** e **Language Studio**.  
O cenário escolhido foi a **avaliação de um site de hospedagem**, onde comentários de clientes são processados para obter **transcrição automática de voz** e **análise de sentimentos**.

---

## 🎯 Objetivos de Aprendizagem
- Explorar o **Speech Studio** para conversão de fala em texto.
- Utilizar o **Language Studio** para análise de sentimentos e extração de insights.
- Simular um **processo de avaliação de clientes** em um site de hospedagem.
- Documentar todo o processo em um repositório GitHub.

---

## 🛠️ Ferramentas Utilizadas
- [Azure Speech Studio](https://speech.microsoft.com/) – Transcrição de fala.
- [Azure Language Studio](https://language.cognitive.azure.com/) – Análise de texto e sentimentos.
- [GitHub](https://github.com/) – Organização e compartilhamento do projeto.
- Markdown – Criação deste README.md.

---

## 🚀 Etapas do Projeto

### 1. **Speech Studio – Transcrição de Fala**
- Simulei comentários de clientes (áudios gravados).
- Apliquei o serviço de **Speech to Text** para gerar transcrições.
- Exemplo de entrada: 🎙️ *“O quarto era confortável, mas o ar-condicionado estava barulhento.”*  
- Saída (texto): *“O quarto era confortável, mas o ar-condicionado estava barulhento.”*

---

### 2. **Language Studio – Análise de Sentimentos**
- Peguei as transcrições do Speech Studio.
- Analisei com **Text Analytics for Sentiment Analysis**.
- Resultados obtidos:
  - **Sentimento geral:** Misto.
  - **Opiniões detectadas:** 
    - Quarto → Positivo
    - Ar-condicionado → Negativo

---

### 3. **Possíveis Aplicações no Site de Hospedagem**
- Automatizar análise de feedbacks de clientes.
- Gerar relatórios de satisfação por área (quarto, limpeza, alimentação etc.).
- Apoiar decisões estratégicas (ex: melhorar café da manhã se muitos comentários forem negativos).

---

## 🧠 Aprendizados
- O **Speech Studio** é eficiente para transcrever áudios em diferentes idiomas.
- O **Language Studio** consegue detectar nuances nos sentimentos, indo além de positivo/negativo.
- Projetos simples já mostram como **IA pode transformar experiências do cliente**.

---

## 📊 Resultados e Insights
- A transcrição automática facilita o registro de feedbacks em áudio.
- A análise de sentimentos ajuda a entender rapidamente **pontos fortes e fracos** do serviço.
- Essa abordagem poderia ser integrada em tempo real em plataformas de hospedagem.

---

## 📜 Referências
- [Documentação Speech Studio](https://learn.microsoft.com/azure/cognitive-services/speech-service/)
- [Documentação Language Studio](https://learn.microsoft.com/azure/cognitive-services/language-service/)
- [Guia Markdown GitHub](https://www.markdownguide.org/basic-syntax/)
