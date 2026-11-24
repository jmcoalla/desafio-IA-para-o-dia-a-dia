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

Na sua cópia, abra este README, clique no lápis (**Edit this file**) e role até aqui. Troque cada frase em itálico pelo que você fez e cole o texto dentro dos blocos já prontos. Para pôr um print, é só colar a imagem com Ctrl+V. No fim, clique em **Commit changes**.

Nada de e-mail, nome de cliente, dado da empresa, senha ou informação pessoal nos textos e nos prints.

### Minha Tarefa Real

Lista de transmissão diária no WhatsApp para chamada e validação de jogos, com foco em futebol.

### Meus Atalhos

Montei dois atalhos: um para gerar a mensagem diária da lista de transmissão (com foco em futebol) e outro para organizar meus estudos noturnos de tecnologia. O que fica fixo são as regras que não mudam (como tom de voz, limite de tamanho, divisão do tempo de estudo e cuidados de segurança), e o que muda a cada uso são os dados do dia ou da noite, como jogos, horários e tema de estudo.

```text
Atue como um especialista em comunicação direta e clara para atendimento via WhatsApp.

Tarefa: Crie uma mensagem curta e atrativa para minha lista de transmissão diária, convidando clientes a validarem palpites nos jogos do dia.

Regras fixas:
- Foco principal em futebol (outros esportes entram apenas se eu informar como exceção).
- Linguagem simples, amigável, energética e direta ao ponto.
- Use emojis com moderação para destacar os jogos e horários.
- Inclua uma chamada para ação (CTA) clara no final para enviarem seus jogos para validação.
- Texto curto, ideal para leitura rápida no celular (máximo de 10 linhas).
- Não faça promessas de ganho garantido e não peça nem exponha dados sensíveis.

Dados de hoje (o que muda):
- Principais jogos de futebol e horários: [INSERIR JOGOS E HORÁRIOS DE HOJE]
- Horário limite para validação: [INSERIR HORÁRIO]
- Destaque ou observação do dia: [INSERIR SE HOUVER, OU "NENHUM"]
```

```text
Atue como um mentor de tecnologia didático e objetivo, focado em quem está construindo base sólida na área.

Tarefa: Organize minha sessão de estudos de hoje à noite de forma prática e sem enrolação.

Regras fixas:
- Linguagem simples, como se estivesse explicando para um iniciante dedicado.
- Divida o tempo disponível em: 1) Resumo teórico direto (30%), 2) Exemplo prático do dia a dia (40%) e 3) Exercício rápido de fixação (30%).
- Evite textos longos demais; use tópicos curtos.

Dados da noite (o que muda):
- Assunto/tema de tecnologia de hoje: [INSERIR TEMA]
- Tempo disponível hoje à noite: [INSERIR TEMPO, EX: 1H30]
- Meu nível atual no assunto: [EX: DO ZERO / JÁ VI O BÁSICO]
```

### Minha Delegação

```text
Preciso delegar uma tarefa recorrente para você, mas quero que você me apresente o PLANO antes de executar qualquer coisa. Espere minha aprovação do plano para gerar o resultado final.

- Objetivo: Criar um fluxo simples e reutilizável para montar a mensagem diária da lista de transmissão no WhatsApp, convidando clientes a validarem palpites nos jogos do dia.
- Contexto: Atuo de forma autônoma no atendimento diário de validação de jogos e preciso de mensagens rápidas, claras e diretas para enviar todos os dias antes do fechamento.
- Recursos: Meu modelo de atalho da mensagem diária, a fonte de dados informada e os jogos e horários do dia.
- Limites: Foco principal em futebol (outros esportes entram apenas se eu informar como exceção); não inventar jogos, horários ou informações; não prometer ganho garantido; manter a mensagem curta (até 10 linhas) para leitura fácil no celular; não incluir nem pedir dados sensíveis.
- Critério de sucesso: Ter um passo a passo prático de uso diário + um rascunho pronto da mensagem de futebol, revisado e validado por mim antes de usar.

Primeiro, mostre apenas o seu PLANO de execução e aguarde minha confirmação antes de prosseguir.
```

### O Plano da IA

<img width="1264" height="711" alt="image" src="https://github.com/user-attachments/assets/8b696f26-0eb1-45ce-ac51-7c6b37e9e0c3" />
Além de acrescentar o horário de validação, eu indiquei o site para fonte de dados.

### O Resultado

<img width="1318" height="960" alt="image" src="https://github.com/user-attachments/assets/c93ed06f-73e3-4636-ab83-943507d56d6a" />
Conferi cada trecho do resultado gerado e validei se o horário limite, a fonte de dados e as regras do atalho foram cumpridos antes de usar.

### Como Foi para Você

Com os atalhos e a delegação com plano, ficou mais rápido montar a mensagem diária com foco em futebol sem perder tempo do zero, mantendo o controle de revisar tudo antes de enviar; o atalho de estudos noturnos de tecnologia já ficou pronto para eu usar nas próximas noites.
