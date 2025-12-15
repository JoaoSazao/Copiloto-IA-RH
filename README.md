# 🤖 Copiloto de Comunicação Interna com IA Generativa

Este projeto consiste no desenvolvimento de um **copiloto de comunicação interna**, utilizando **Inteligência Artificial Generativa** integrada a um fluxo de automação. A solução tem como objetivo automatizar a criação de textos corporativos a partir de informações simples fornecidas pelos colaboradores, tornando o processo mais ágil, padronizado e eficiente.

---

## 🎯 Objetivo do Projeto

- Automatizar a geração de textos corporativos (avisos, comunicados e mensagens institucionais)
- Reduzir retrabalho em áreas como Recursos Humanos e Comunicação Interna
- Garantir padronização no tom e na estrutura das mensagens
- Disponibilizar os textos gerados por múltiplos canais
- Criar um histórico organizado das comunicações produzidas

---

## 🧠 Tecnologias e Conceitos Utilizados

- **Automação de processos com n8n**
- **Inteligência Artificial Generativa**
- **Modelo de Linguagem de Grande Escala (LLM)**
- **Prompt Engineering**
- **Google Sheets** (entrada e armazenamento)
- **Gmail** (envio automático de mensagens)

---

## 🔄 Funcionamento do Fluxo

O fluxo automatizado funciona da seguinte forma:

1. O colaborador preenche um formulário com informações sobre o texto desejado.
2. Cada envio gera uma nova linha em uma planilha, acionando automaticamente o fluxo no n8n.
3. Os dados são estruturados e validados para garantir consistência.
4. Caso o registro seja válido, cada item é processado individualmente.
5. Um modelo de linguagem de grande escala é acionado para gerar o texto corporativo.
6. O texto gerado é enviado por e-mail ao solicitante.
7. O conteúdo também é armazenado em uma planilha, criando um histórico acessível.

---

## 📤 Canais de Saída

- **E-mail (Gmail):** entrega imediata do texto gerado ao usuário  
- **Google Sheets:** armazenamento e consulta dos textos gerados  

Essa abordagem garante acesso rápido ao conteúdo e rastreabilidade das mensagens.

---

## ✅ Benefícios da Solução

- Agilidade na criação de textos institucionais  
- Padronização da comunicação interna  
- Facilidade de uso por colaboradores não técnicos  
- Histórico automatizado das mensagens geradas  
- Arquitetura modular e escalável  

---

## ⚠️ Considerações Importantes

- Os textos gerados devem ser revisados antes de uso oficial.
- A solução atua como ferramenta de apoio, não substituindo a decisão humana.
- Não devem ser inseridos dados sensíveis ou confidenciais no formulário.

---

## 🚀 Possíveis Evoluções

- Integração com outros canais de comunicação corporativa
- Criação de templates específicos por tipo de mensagem
- Processamento em lote de mensagens
- Implementação de métricas de uso e feedback

---

## 📄 Contexto Acadêmico

Este projeto foi desenvolvido para fins acadêmicos, com foco na aplicação prática de **Inteligência Artificial Generativa** e **automação de processos** no ambiente corporativo.

---
