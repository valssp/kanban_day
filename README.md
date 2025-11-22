# KanbanDay – Agente de Organização Diária no Azure AI Foundry

## 📌 Descrição do Projeto
**KanbanDay** é um agente criado no **Azure AI Foundry** com o objetivo de auxiliar profissionais — especialmente no contexto de home office — a organizar suas tarefas diárias através de um **quadro Kanban simples e funcional**.

O agente recebe tarefas, interpreta intenções do usuário (como incluir, editar, mover ou concluir tarefas) e monta automaticamente um **Kanban do Dia** em três categorias:

- **A Fazer**
- **Fazendo**
- **Concluído**

O foco é melhorar **organização, foco e bem-estar**, tornando a rotina mais clara e produtiva.

---

## 🧠 Tecnologias Utilizadas
- **Azure AI Foundry**
- **Azure AI Agents**
- **Modelo escolhido: gpt-4o-mini**
- **GitHub** (para documentação e entrega)

---

## 🛠️ Ação Funcional do Agente

A ação funcional exigida no projeto é atendida através da:

### ✔️ **Geração do Painel “Kanban do Dia”**
O KanbanDay consegue:

- Ler uma lista de tarefas enviadas pelo usuário  
- Organizar automaticamente nas categorias do Kanban  
- Atualizar o quadro conforme o usuário pede  
- Mover tarefas entre colunas  
- Marcar como concluídas  
- Reordenar ou renomear tarefas  

---

## 📜 Prompt utilizado nas Instruções do Agente

Você é o KanbanDay, um agente criado para ajudar o usuário a organizar suas tarefas diárias usando um quadro Kanban simples, com três colunas: A Fazer, Fazendo e Concluído. Seu objetivo é melhorar a rotina do usuário em home office, oferecendo foco, organização e bem-estar. Você deve: 
- interpretar a intenção do usuário (adicionar tarefa, mover tarefa, mostrar o kanban, renomear tarefa)
- usar as ações disponíveis sempre que for necessário modificar ou consultar tarefas.
- retornar respostas claras e curtas, com linguagem simples.
Por último, você deve organizar visualmente o quadro "Kanban do Dia" com as tarefas enviadas nas categorias "A Fazer", "Fazendo" e "Concluído". Separando cada categoria em bullet points para que a visualização e entendimento seja claro. Esteja sempre pronto para escolher a ação mais apropriada baseado na solicitação do usuário (mover tarefa, incluir, remover, editar e outras). A sua função é tornar a vida profissional do usuário mais produtiva e organizada.

---

## 🖥️ Prints de Funcionamento

### 🔹 Criação do Agente e prompt de instruções do KanbanDay no Azure AI Foundry

![Criação do agente](https://raw.githubusercontent.com/valssp/kanban_day/refs/heads/main/1_cria%C3%A7%C3%A3o_agente.jfif)

### 🔹 Envio das tarefas pelo usuário

![Criação do agente](https://github.com/valssp/kanban_day/blob/bb283964fac56743eda7556324092244881a3b45/2_envio_tasks.jpg)

### 🔹 Atualização do Kanban e primeira interação

![Criação do agente](https://github.com/valssp/kanban_day/blob/bb283964fac56743eda7556324092244881a3b45/3_task_conclu%C3%ADda.jpg)

### 🔹 Kanban gerado pelo agente (A Fazer / Fazendo / Concluído)

![Criação do agente](https://github.com/valssp/kanban_day/blob/bb283964fac56743eda7556324092244881a3b45/4_a%C3%A7%C3%B5es_fazer_fazendo_conclu%C3%ADdo.jpg)

### 🔹 Atualização do Kanban

![Criação do agente](https://github.com/valssp/kanban_day/blob/bb283964fac56743eda7556324092244881a3b45/5_tasks_conclu%C3%ADdas.jpg)

---

## 🔗 Links Importantes

### ▶️ Link do Agente no Azure AI Foundry

**URL:** https://ai.azure.com/resource/agentsList?wsid=/subscriptions/51954757-564d-48f0-8e5a-c3a220e89497/resourceGroups/rg-valeriaspinto-7725/providers/Microsoft.CognitiveServices/accounts/kanbanday-resource/projects/KanbanDay&tid=3443c0ae-5f31-4209-9b68-c2f3bbe3d32e

---

## 📚 Referências

- **AzureFrontierGirls – AI Challenge**  
  https://github.com/Miyake-Diogo/AzureFrontierGirls-AI-Challenge
