<p align="center">
  <img src="design/banner.png" alt="Capa do Projeto CAF Next" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-prototype-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/IA-integrado-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/automação-n8n-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/segurança-ISO%2FIEC%2027001-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/stack-Metabase%20%7C%20Chatwoot%20%7C%20Docker-lightgrey?style=for-the-badge" />
</p>

# Projeto AutoCAF – Pós-venda Inteligente e Automatizado

> "Transformar o caos em processos, os processos em dados e os dados em automações.”

---

## Visão Geral

O **AutoCAF** é um ecossistema de **automação e inteligência artificial** criado para modernizar o **pós-venda da CAF Máquinas**, integrando sistemas internos (ERP, CRM e canais de atendimento) em uma única operação fluida, eficiente e inteligente.  

O projeto foi desenvolvido para o **Hackathon CAF x SECCOMP 2025**, com foco em **viabilidade prática**, **impacto comercial** e **inovação aplicada com IA**, atendendo diretamente aos desafios e critérios propostos pela empresa.

---

## Contexto e Desafios

Foram nos apresentados 5 principais desafios:

1. **Poucos indicadores e processos estruturados no pós-venda**  
   - Falta de padronização e automação nos fluxos de atendimento.  

2. **Ausência de indicadores em tempo real**  
   - Dificuldade em acompanhar o desempenho e gargalos operacionais.  

3. **Desalinhamento entre produção, vendas e planejamento**  
   - Comunicação deficiente entre diferentes áreas e processos comerciais.  

4. **Planejamento de estoque ineficiente**  
   - Falta de previsibilidade nas reposições e perda de vendas por falta de peças.  

5. **Processos manuais e baixa integração de dados**  
   - Dependência de tarefas repetitivas e retrabalho entre setores.  

---

## Soluções Propostas

| Área | Solução | Tecnologias / Conceitos |
|------|----------|------------------------|
| **Atendimento ao cliente** | Chatbot inteligente com IA no WhatsApp e e-mail, capaz de responder dúvidas, emitir boletos e encaminhar solicitações automaticamente | Chatwoot • N8N • APIs • IA Operacional |
| **Indicadores e relatórios** | Painel de métricas em tempo real e relatórios preditivos automáticos | Metabase • IA Analítica |
| **Integração de sistemas** | Conexão entre ERP (SAP Business One), CRM (Ploome) e automações de processos | APIs REST • N8N • Webhooks |
| **Planejamento de estoque** | IA preditiva para alertas automáticos e previsões de demanda | Modelos Preditivos • Data Sync |
| **Infraestrutura segura e escalável** | VPS com certificação ISO/IEC 27001, Docker Swarm e backups automáticos | Cloud • Docker • Lets Encrypt |

---

## Arquitetura Simplificada

```text
Cliente → Chatbot IA → N8N Automations → ERP / CRM → Metabase Dashboard
````

📊 *Todos os sistemas se comunicam via APIs e automações seguras, garantindo fluidez, escalabilidade e centralização de dados.*

---

## 🧱 Organização do Repositório

| Pasta             | Conteúdo                                                                         |
| ----------------- | -------------------------------------------------------------------------------- |
| `/docs`           | Documentação detalhada do projeto (diagnóstico, proposta e plano de implantação) |
| `/design`         | Diagramas de arquitetura, fluxos de automação e mockups de interface             |
| `/presentation`   | Material visual entregue no Hackathon (PDF / slides)                             |

---

## Estratégia de Implantação

1. **Mapeamento de Processos**
   Estruturar fluxos e pontos de automação — transformar o caos em processos.

2. **Treinamentos Segmentados**
   Capacitar equipes para o uso das novas ferramentas.

3. **Implementação Modular**
   Implantar automações simples e escalar gradualmente para módulos mais complexos.

4. **Monitoramento Contínuo**
   Acompanhar métricas, coletar feedbacks e otimizar fluxos periodicamente.

---

## Aderência aos Critérios do Hackathon

| Critério                      | Como o AutoCAF atende                                              |
| ----------------------------- | ------------------------------------------------------------------- |
| **Viabilidade técnica**       | Soluções simples e compatíveis com a infraestrutura atual da CAF    |
| **Impacto comercial**         | Reduz tempo de atendimento e aumenta capacidade operacional         |
| **Inovação no uso de IA**     | Aplicação prática e personalizada em automação e relatórios         |
| **Facilidade de implantação** | Modular, intuitivo e com baixo custo de implementação               |
| **Interfaces amigáveis**      | Metabase, Chatwoot e Evolution possuem UI acessível                 |
| **Solução escalável**         | Docker Swarm e VPS permitem expansão gradual                        |
| **Grau de inovação**          | Conecta IA, automação e integração de dados em um único ecossistema |

---

## Próximos Passos

* Finalizar protótipos visuais e fluxos simulados de automação.
* Validar integração com SAP Business One e CRM Ploome.
* Testar chatbot com FAQs reais de clientes.
* Preparar ambiente piloto com base em métricas reais de pós-venda.

---

## Equipe

**Gabriel Severo** – Product Owner / Analista de Soluções
**Otto Jacometo** - Engenheiro de Dados / Analista de BI

---

## Conclusão

O **AutoCAF** representa o próximo passo da transformação digital da CAF Máquinas.
Mais do que uma proposta técnica, ele é uma **estratégia de crescimento**, que permite à CAF:

* Atender mais clientes com o mesmo time,
* Tomar decisões baseadas em dados,
* E consolidar uma operação de **#marCAForte, inteligente e integrada.**
