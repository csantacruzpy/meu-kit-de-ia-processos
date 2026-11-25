# Meu Kit de IA

Desafio de Projeto da [DIO](https://dio.me): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

O kit foi criado pelo Expert Bruno Lima com os prompts, templates, checklists e skills usados nas Aulas. Ele não é uma apostila: abra a pasta que resolve o seu problema, copie o modelo, adapte e use.

**Copie → adapte → teste → confira → melhore**

## Como Fazer o Desafio

Você não precisa instalar nada nem saber programar. Tudo acontece no navegador.

1. Clique em **Use this template**, depois em **Create a new repository**. Dê um nome simples, como `meu-kit-de-ia`, deixe **Public** e confirme.
2. Siga os passos abaixo com uma tarefa real da sua semana.
3. Preencha a seção [Minha Entrega](#minha-entrega) da sua cópia e entregue o link dela na DIO.

## Os Passos

1. **Escolha uma tarefa real.** Comece pelo trabalho que se repete na sua semana, como preparar uma reunião ou montar um relatório, e não pela ferramenta.
2. **Pegue um modelo.** Abra a pasta do kit que combina com a sua tarefa. Cada modelo tem um botão de copiar no canto.
3. **Adapte.** Troque o que está entre colchetes pelo seu contexto, objetivo, dados, limites e formato.
4. **Teste.** A primeira resposta é um ponto de partida. Ajuste até funcionar para a sua realidade.
5. **Delegue.** Com o [template de delegação](02-templates/03-delegacao.md), entregue a tarefa à IA. Peça o plano antes de ela começar, acompanhe e valide o resultado.
6. **Confira.** Provável não é o mesmo que verdadeiro. Revise com o [Pare, Confira, Use](03-checklists/01-pare-confira-use.md) antes de usar.

## O Que Tem no Kit

| Pasta | Para que serve |
|---|---|
| [01-prompts](01-prompts) | Pedidos prontos para adaptar: escrita, comunicação, pesquisa, comparação e preparação de reuniões |
| [02-templates](02-templates) | Estruturas para preencher: bom pedido, pesquisa e decisão, e delegação |
| [03-checklists](03-checklists) | Revisão de respostas, de textos e de tarefas delegadas |
| [04-skills](04-skills) | Como criar uma skill, e a Skill Preparador de Reuniões usada nas Aulas |
| [05-delegacao-e-automacao](05-delegacao-e-automacao) | Gatilhos de automação, supervisão e checkpoints |

## Os Frameworks das Aulas

- **Bom pedido:** contexto + instrução + objetivo + formato. Quanto menos a IA precisa adivinhar, melhor você consegue avaliar a resposta.
- **Pesquisa e decisão:** pergunta → pesquisa → critérios → comparação → você. Peça fontes quando precisar de informação externa. A decisão final é sua.
- **Segurança:** pare → confira → use. Valide fatos, números, datas, fontes e contexto.
- **Atalhos reutilizáveis:** criar → testar → ajustar → salvar. Separe as instruções fixas das informações que mudam a cada uso.
- **Delegação:** objetivo + contexto + recursos + limites + sucesso. Autonomia funciona melhor quando o resultado esperado está claro.
- **Supervisão:** definir → delegar → acompanhar → validar. Em tarefas maiores, confira o plano, acompanhe os checkpoints e valide o resultado.

> A IA pode ajudar você a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo sua.

---

## Minha Entrega

### Minha Tarefa Real

Escolhi a estruturação de Procedimentos Operacionais Padrão (POP) e o diagnóstico inicial de melhorias em processos administrativos e operacionais a partir de notas soltas de reuniões de levantamento. Essa tarefa se repete toda semana na minha rotina de consultoria e gestão da qualidade, consome bastante tempo na organização inicial e exige padronização clara (entradas, saídas, responsáveis e riscos) antes da validação com as áreas.

### Meus Atalhos

Adaptei dois modelos da pasta `01-prompts` (escrita/estruturação e análise/comunicação). Deixei **fixo** o papel de especialista em Gestão de Processos e ISO 9001, as regras de não inventar informações e a estrutura padrão de saída (tabelas e tópicos). O que **muda a cada uso** são apenas as notas brutas da reunião ou o desvio operacional específico entre colchetes.

```text
Atue como Especialista Sênior em Gestão de Processos, Qualidade (ISO 9001) e Melhoria Contínua.
Contexto: Receberá notas desordenadas de uma reunião de levantamento operacional.
Objetivo: Transformar essas notas em um Procedimento Operacional Padrão (POP) claro e objetivo.
Formato de saída:
1. Objetivo do processo, entradas, saídas e responsáveis.
2. Fluxo passo a passo numerado.
3. Tabela com pelo menos 3 riscos operacionais ou gargalos identificados e sugestões de controle.
Regras: Não invente etapas que não estejam implícitas no texto. Se faltar alguma informação crítica, liste ao final na seção "Perguntas para validar com a área".

Notas da reunião: [COLE AQUI AS ANOTAÇÕES DA REUNIÃO]
