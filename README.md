# Roteiro do Pitch — {projectName}

**Entrega:** AB1 — Tech for Peace
**Formato:** vídeo pitch de até 5 min (tolerância: +15s, máx. 5min15s)
**Grupo:** Grupo 1 — UFAL

---

## Estrutura geral

Roteiro cronometrado pra ~5min10s, deixando ~5s de folga dentro do limite do professor (5min15s). Dá pra gravar com uma voz só ou dividir entre integrantes do grupo.

| Bloco | Slides | Tempo | Duração |
|---|---|---|---|
| Abertura | 1 | 0:00 – 0:15 | 15s |
| Contexto do problema | 2–3 | 0:15 – 0:45 | 30s |
| Recorte (Ishikawa) | 4–5 | 0:45 – 1:10 | 25s |
| Problema específico | 6–7 | 1:10 – 1:40 | 30s |
| Solução | 8–9 | 1:40 – 2:25 | 45s |
| Funcionalidades | 10–11 | 2:25 – 2:45 | 20s |
| UI Preview | 12 | 2:45 – 3:05 | 20s |
| Usuários / personas | 13 | 3:05 – 3:30 | 25s |
| Modelo de dados | 14 | 3:30 – 3:55 | 25s |
| Inovação | 15 | 3:55 – 4:30 | 35s |
| Impacto / MVP | 16 | 4:30 – 4:50 | 20s |
| Fechamento | 17 | 4:50 – 5:10 | 20s |

---

## Roteiro

### [Slide 1 — Capa | 0:00–0:15]

> "Quando um desastre acontece, a ajuda chega. Mas chega *certo*? Na hora *certa*? No lugar *certo*? A gente é o Grupo 1, da UFAL, e passou a AB1 inteira investigando uma pergunta que parece simples — mas não é."

### [Slides 2–3 — Contexto do problema | 0:15–0:45]

> "Durante uma crise humanitária — enchente, incêndio, deslizamento — centenas de abrigos abrem em poucas horas. Cada um com uma necessidade diferente: um precisa de água, outro de fralda, outro já está com comida sobrando e precisando de colchão. E essa necessidade *muda a cada hora*. O problema é que ninguém sabe, em tempo real, o que cada abrigo realmente precisa agora."

### [Slides 4–5 — Ishikawa / recorte | 0:45–1:10]

> "A gente aplicou uma análise de Ishikawa e mapeou as causas: falta de método, falta de máquina, falta de gente capacitada, falta de processo. Podia atacar tudo, mas seria raso. Então a gente fez um recorte honesto: vamos resolver *método e máquina* — ou seja, o **workflow** e a **ferramenta** que sustenta esse workflow."

### [Slides 6–7 — Problema específico | 1:10–1:40]

> "O problema específico é esse: hoje, não existe um fluxo confiável pra atualizar as necessidades dos abrigos durante o desastre. O que existe são planilhas paralelas, grupos de WhatsApp, ligações, e-mails. Ninguém sabe qual versão é a atualizada. A informação chega com 3, 4 dias de atraso. E no meio do caos, quem paga o preço é quem mais precisa."

### [Slides 8–9 — Solução | 1:40–2:25]

> "A nossa proposta é o **{projectName}** — uma plataforma de *governança da informação* pra resposta humanitária. Não é mais uma ferramenta de doação. Não é um marketplace. É o lugar onde a necessidade do abrigo vira um dado confiável, carimbado, com hora e responsável. Abrigos verificados publicam o que precisam; atualizam em tempo real; e qualquer pessoa — doador, ONG, Defesa Civil — vê a mesma verdade, ao mesmo tempo."

### [Slides 10–11 — Funcionalidades | 2:25–2:45]

> "Seis funcionalidades-chave: **gestão de crises**, **contas verificadas**, **dashboard em tempo real**, **prioridades** — urgente, necessário, suficiente — com código de cor, **lembretes de expiração** e **mapa georreferenciado**. Tudo pensado pra baixa conectividade."

### [Slide 12 — UI Preview | 2:45–3:05]

> "E na prática, é isso que todo mundo enxerga: um mapa com os abrigos marcados por prioridade — vermelho pra urgente, laranja pra necessário, verde pra suficiente — e um feed que atualiza em tempo real, mostrando quem publicou, quando publicou, e o quê."

### [Slide 13 — Usuários / personas | 3:05–3:30]

> "Quem usa? A gente modela três papéis. **Master**, a Defesa Civil, abre e fecha as crises. **Admin**, ONGs e responsáveis por abrigos, cadastram seu abrigo e atualizam o estoque. **Leitor**, que é o doador, o logístico e — o nosso diferencial — **órgãos de controle**: Ministério Público, TCU, CGU. Toda atualização fica registrada, com autor e carimbo de tempo — porque governança da informação só funciona se for auditável."

### [Slide 14 — Modelo de dados | 3:30–3:55]

> "E como isso se organiza por trás? Três entidades, uma hierarquia simples. **Crises** — só o Master abre, com tipo, área afetada e ciclo de vida. Dentro de uma crise vivem os **Abrigos**, verificados em dois minutos, com capacidade, ocupação e infraestrutura. E dentro de cada abrigo, os **Recursos** — gerais, como comida e água, que o sistema monitora automaticamente; e específicos, como medicamento e item especial, que o abrigo pede sob demanda, com prioridade."

### [Slide 15 — Inovação | 3:55–4:30]

> "Duas coisas nos tornam diferentes. Primeiro, a gente muda o paradigma: de *coleta de dados* pra *governança da informação* — workflow auditável, verificado em dois minutos, uma única fonte de verdade. Segundo, e esse é o pulo do gato pra contexto de crise: **funciona offline**. A gente construiu como PWA, então o voluntário atualiza a necessidade do abrigo mesmo sem sinal, e o app sincroniza sozinho quando a conexão volta. Sem app store, sem instalação — o link vira ícone no celular. É a diferença entre o caminhão chegar no abrigo certo ou girar três dias procurando quem precisa."

### [Slide 16 — Impacto / MVP | 4:30–4:50]

> "Nosso escopo pros próximos meses é entregar um MVP funcional: cadastro e verificação de abrigos, publicação de necessidades em tempo real, dashboard público e mapa. Stack leve, offline-first, pensada pra rodar em qualquer lugar — inclusive em prefeitura de cidade pequena."

### [Slide 17 — Fechamento | 4:50–5:10]

> "Desastre vai continuar acontecendo. A gente não pode mudar isso. Mas a gente pode mudar a chance de a ajuda chegar na hora certa, no lugar certo, pra quem realmente precisa. Esse é o {projectName}. Obrigada."

---

## Dicas de execução

- **Ensaiem com cronômetro** antes de gravar. Se bater acima de 5:00, o primeiro corte deve ser no bloco Ishikawa (slides 4–5) — dá pra resumir em uma frase só. O segundo corte vai no Modelo de dados (slide 14): dá pra tirar o detalhe de "geral vs específico" e deixar só o "três entidades, uma hierarquia".
- **Não corram na abertura e no fechamento.** São os blocos de maior impacto.
- **Áudio > vídeo.** Se puderem, gravem o áudio separado com fone/microfone decente. Áudio de notebook fica ruim.
- **Luz natural** de janela, de dia, é melhor do que qualquer iluminação artificial improvisada.
- **Fundo limpo.** Parede lisa ou algo neutro. Evitem bagunça atrás.
- **Uma pessoa ou várias?** Se dividirem, definam quem fala cada bloco antes e não troquem no meio de uma frase. Transições entre pessoas ficam melhores em trocas de slide.

## Critérios de avaliação (pra lembrar)

1. **Definição do Problema e Escopo** — clareza, relevância, escopo realista
2. **Proposta de Solução** — qualidade, criatividade, alinhamento com o problema
3. **Inovação e Impacto** — grau de inovação e potencial de impacto

O roteiro já foi estruturado pra bater nesses três pontos na ordem.

## Deadline

**24/04 (sexta-feira)** — Google Classroom.
