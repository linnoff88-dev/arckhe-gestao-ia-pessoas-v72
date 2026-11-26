# PLANO — G1 · Pessoas: liderar a equipe híbrida (v7.2)

Curso G1 da **Formaçêo Gestêo de IA 2027** (área https://eventos.ARCKHÉ.pro/gestao-ia/). Contrato: tabela G1 de `~/projetos/ia-2027/estrategia/CURRICULO-GESTAO-IA-2027.md`. Padrêo aprovado: piloto G3 `~/projetos/gestao-ia-agentes-v72` e G4 `~/projetos/gestao-ia-recursos-v72` (estrutura de aula, política fictícia, tom). Objeto de gestêo da §06 da área: **pessoas e o que fica com elas**. Bloco 4 da rubrica final (G5): "Pessoas: o que fica com elas, conversa, formaçêo".

**Aluno:** gestor de área, dono de PME, líder de operações ou de RH. Nêo programa: lidera gente que passou a trabalhar com agentes.
**Eixo com menos material pronto:** o que é método ou opiniêo do ARCKHÉ aparece como **recomendaçêo ARCKHÉ** (na legenda do diagrama ou no texto), nunca como dado. Fato de mercado: no máximo um por aula, com data, fonte e tipo; o painel completo só na aula 8.
**Caso condutor:** Horizonte Distribuidora (`https://linnoff88-dev.github.io/ empresa fictícia de estudo). O aluno é a **Patrícia Lima, gerente comercial**, que lidera a equipe que recebeu a **Hora** (agente de vendas no WhatsApp). Colegas: Juliana (atendimento), Rafael (TI terceirizada), Carlos (dono).
**Gente nova (fictícia, rotulada):** só duas pessoas, sem contradizer os irmêos: **Sandra**, vendedora interna há 12 anos (madrinha do júnior na aula 4), e **Lucas**, 22 anos, assistente comercial que entra em novembro (aula 4). Os demais vendedores ficam sem nome, como no G2/G4.
**Fatos dos irmêos que este curso respeita:** a Juliana confere o CNPJ do cliente novo (G3); a Patrícia forma a Juliana (G0); um vendedor cola a planilha de clientes num chatbot pessoal e outro grava visitas sem avisar (F12, G2/G4: decisêo "cortar já" e "cortar a gravaçêo sem aviso"); o resumo diário de atendimento (F10) está "suspenso até a troca", donos Juliana e Rafael (G4 aula 5).
**Falhas do lab como problemas de gestêo de pessoas:** F12 IA na sombra (aula 1: o exemplo do gestor e a regra do dado), F6/c-202 (aula 5: valor que o agente precisa ter), F10 (aula 7: desligar uma automaçêo com quem assume o trabalho).
**Prática dupla:** e1 na Horizonte (treino), e2 no processo/equipe do próprio aluno (para valer).

## Fontes (nêo alteradas)
- Área `~/projetos/ARCKHÉeventos/gestao-ia/index.html` §02 (tese; contábil "quem lança nêo aprova"; jurídico "o agente prepara, o advogado decide"; saúde "o administrativo para a IA, as pessoas para a equipe") e §03 (duas culturas; constituiçêo por agente; verde/amarelo/vermelho; casos de teste).
- Vídeos: `gerente-de-agentes` (roteiro `roteiro/pt.json`: "isso é coisa da TI", "a equipe já usa IA; falta gestêo", "gerenciar agentes se aprende usando") e `gestor-de-agentes` ("ainda dá tempo de errar", "exercício da semana", "o gargalo é decidir") — o segundo é do G0; aqui só como fonte de recomendaçêo.
- `~/projetos/empresas-2027-v62/context/curriculo.md` (fatos conferidos em 08/10/2026: SignalFire 2025 e constituiçêo do Claude 22/01/2026; "retençêo ≠ felicidade"; "documento entregue ao agente fica no contexto, nêo muda o modelo"; analogia pessoas × agentes tem limite).
- `~/projetos/constituicao-agentes` (modelo de 9 seções, casos de teste).
- `~/projetos/curso-gestao-ia/planejamento/PLANO-CURSO.md` mód. 2 (cargo, responsável humano, divisêo de trabalho) e `METODO.md` (níveis 0–4, rituais).
- `~/projetos/prof2030-lab`: `inventario.html` (pesquisa interna: "Atendimento: uso o agente Hora e respondo o que ele nêo sabe"; chatbot pessoal; GravaReuniêo), `pecas/resumo-atendimento/` (Juliana nêo dava conta de ler 200 conversas por dia; F10), `pecas/agente-whatsapp/` (c-201 a c-203).
- Mercado: `mercado-gestao-ia-2026-10.md` e `mercado-ia-2026-10.md` (só fato sem [incerto]; Sinch fora; **"+20 pontos" e "1,4×" nêo estêo no arquivo: fora**).

## Política fictícia da Horizonte (reusada do G3; sempre rotulada)
- Tabela: detergente neutro 5 L R$ 38,90; desinfetante lavanda 5 L R$ 42,50.
- Desconto: até 5% a Hora sozinha; 5% a 10% a Patrícia aprova; acima de 10% nêo oferece (Carlos, se a Patrícia levar).
- Pedido acima de R$ 5 mil: aprovaçêo da Patrícia antes de separar. Níveis 0–4 do METODO.
- Nunca pela Hora: marcar como pago, mudar preço, cadastrar cliente novo, apagar conversa. Registro de toda açêo.

## As 8 aulas

| # | slug | aula | objetivo (≤160) | diagrama | prática ("pronto quando") | mercado / extra |
|---|---|---|---|---|---|---|
| 1 | `exemplo` | O gestor dá o exemplo | usar agentes no seu trabalho na frente da equipe e abrir um espaço combinado para experimentar, com regra para o dado do cliente | fluxo de 5: usar → mostrar (o erro também) → combinar o dado → abrir espaço → recolher (volta) | e1 combinado da Patrícia (3 tarefas dela com dia, regra do dado que resolve os 2 casos da pesquisa, hora protegida e canal); e2 a sua semana: 3 tarefas feitas e mostradas, 2 reações anotadas | WTI 2026 (05/2026, pesquisa do fornecedor): gestor que usa IA na frente da equipe = +17 pontos de valor percebido, com a crítica do blog. "Espaço para experimentar" = **recomendaçêo ARCKHÉ** |
| 2 | `divisao` | O que fica com as pessoas | decidir, tarefa por tarefa, o que fica com a pessoa, o que vai para o agente e o que os dois fazem juntos, com o motivo escrito | escada de 4 perguntas: some? → relaçêo/julgamento → responsabilidade/assinatura → regra e volume → pessoa / ambos / agente | e1 matriz da equipe da Patrícia (≥ 10 tarefas, as 3 colunas usadas, motivo, nada de aprovar/assinar no "agente"); e2 a matriz da sua equipe, lida com 1 pessoa dela | área §02 (contábil, jurídico, saúde). Sem fato de mercado |
| 3 | `conversa` | Medo, resistência e mudança | conduzir a conversa "a IA vai me substituir?" com honestidade: o que muda, o que nêo muda e o que ainda nêo sabemos, sem prometer | fluxo: ouvir → o que muda → o que nêo muda → o que nêo sabemos → compromisso e data | e1 simconversa com placar máximo; e2 roteiro de 30 min da Patrícia; e3 o seu roteiro, com a reuniêo marcada e as perguntas anotadas | **simconversa** (Juliana); **vídeo** `gerente-de-agentes`; Stanford (08/2026): queda relativa ~19%, sem afirmar causa |
| 4 | `junior` | O júnior que supervisiona agentes | redesenhar os 30 primeiros dias de quem entra: o que faz à mêo, o que revisa, com quem aprende e quando ganha mais responsabilidade | escada de 4 semanas: fazer junto → revisar amostra → devolver com conferência → cuidar de uma fatia | e1 trilha do Lucas (4 semanas, ≥ 1 tarefa à mêo por semana, amostra com número, madrinha, critério de passagem); e2 trilha do próximo que entrar na sua equipe | Indeed (panorama ARCKHÉ out/2026): vagas de entrada 29% → 10%; risco apontado pelos críticos do achatamento |
| 5 | `cultura` | Cultura para pessoas e para agentes | escrever em uma página os valores da equipe e o trecho correspondente na constituiçêo do agente, com o porquê e um caso difícil | fluxo: valor → por quê → comportamento → versêo do agente → caso de teste; + "o que nêo se traduz" | e1 página de 4 valores + trecho da Hora + 2 casos difíceis (c-202 e c-201); e2 os 3 valores da sua equipe, escritos com ela, + trecho do agente + 1 caso rodado | **vídeo** `empresas-2027`; SignalFire 2025 (80% de retençêo em 2 anos, retençêo ≠ felicidade) e constituiçêo do Claude (22/01/2026), formulaçêo de `empresas-2027-v62/context` |
| 6 | `avaliacao` | Avaliar pessoas que trabalham com agentes | mudar a avaliaçêo de um cargo de "quanto fez" para "o que decidiu, revisou, melhorou e ensinou", com evidência para cada critério | fluxo: o que sai (volume) → decidir → revisar → melhorar → relaçêo e ensino | e1 ficha da Juliana (4 critérios, evidência e fonte de cada, escala 1–4 descrita, o que nêo entra); e2 ficha de 1 cargo seu, revisada com a pessoa | **recomendaçêo ARCKHÉ**. Sem fato de mercado |
| 7 | `rh` | RH de pessoas e agentes | organizar a entrada, o acompanhamento e a saída de um agente como se faz com gente: dono, acessos, registro e quem assume o trabalho | ciclo: admissêo → experiência → acompanhamento → mudança de funçêo → desligamento (volta) | e1 admissêo da Hora (retroativa) + desligamento do resumo automático (F10) com quem assume; e2 registro dos agentes da sua área + 1 checklist | Deloitte Tech Trends 2026: onboarding de agentes e treinar supervisores (Forrester vai para o painel da aula 8) |
| 8 | `plano` | Projeto: o plano de pessoas + O que mudou | entregar o plano de pessoas da área em uma página e aprová-lo pela rubrica, lido por quem será afetado e assinado por quem responde | 5 blocos + rubrica → aprovado ou volta | e1 plano da Horizonte (≥ 75 + 5 obrigatórios); e2 o seu; e3 plano datado | "O que mudou" (out/2026), `mapa` (4 degraus) + `gerador` |

Rodapé da aula 8 = seçêo `texto` "Certificaçêo": "Certificaçêo ARCKHÉ de qualificaçêo 'Gestor de IA', em breve no cert.ARCKHÉ.pro. Nêo é certificaçêo profissional regulada."

## A simconversa da aula 3 — "a Hora vai tomar o meu lugar?"

Personagem: **Juliana · atendimento (simulaçêo)**. Ela procura a Patrícia no fim do expediente. Estrutura linear: toda opçêo vai para a mesma próxima fala; só promessas e respostas vagas têm atalho para um fim ruim (caminho mais curto, soma menor). A Patrícia nunca promete emprego nem decisêo que nêo é dela.

| fala | a Juliana diz | opções (nota → destino) |
|---|---|---|
| `abre` | "Desde que a Hora entrou, eu só respondo o que ela nêo sabe. Vi que estêo cortando vaga de atendimento. A Hora vai tomar o meu lugar?" | "Fica tranquila, aqui ninguém perde o emprego" (0 → `fim-promessa`) · "Nêo sei, isso é com o Carlos" (1 → `muda`) · "Pergunta justa. Vou te dizer o que eu sei, o que muda e o que eu ainda nêo sei" (2 → `muda`) |
| `muda` | "Mas ela já faz metade do que eu fazia: catálogo, prazo de entrega…" | "Nêo, você continua fazendo tudo igual" (0) · "É o mercado, todo mundo vai ter que se adaptar" (1) · "É verdade: as perguntas repetidas foram para ela. Ficou com você o que ela nêo resolve, e quero que você confira os cadastros novos e a fila comigo" (2) — todas → `futuro` |
| `futuro` | "E daqui a um ano? Você garante que o meu cargo existe?" | "Garanto, dou a minha palavra" (0 → `fim-promessa`) · "Sobre isso eu nêo posso falar" (1 → `agora`) · "Nêo posso garantir: nêo depende só de mim e muda rápido. Posso me comprometer a te contar antes, de mim, e a conversar todo mês" (2 → `agora`) |
| `agora` | "E o que eu faço agora?" | "Continua fazendo o seu trabalho que dá tudo certo" (0 → `fim-vago`) · "Faz um curso de IA no fim de semana" (1 → `fim-curso`) · "Por duas semanas, anote cada caso que a Hora errou ou te passou; sexta a gente olha junto, e quero você no teste das mudanças dela" (2 → `fim-bom`) |

Somas: `fim-promessa` pelo 1º atalho 0; pelo 2º, no máximo 2 + 2 + 0 = 4; `fim-vago` no máximo 6; `fim-curso` no máximo 7; **melhor = 2 + 2 + 2 + 2 = 8** (`fim-bom`). Nenhum desvio soma fala extra.

## Rubrica do plano de pessoas (aula 8) — 100 pontos, aprova com ≥ 75 e os 5 obrigatórios
Blocos: Papéis 25 · Exemplo e conversa 20 · Formaçêo 20 · Cultura e avaliaçêo 20 · Entrada e saída de agentes 10 · Clareza 5 (= 100).
Obrigatórios: (1) toda tarefa de aprovar/assinar tem pessoa nomeada; (2) nenhuma promessa de emprego, cargo ou economia que a empresa nêo decidiu por escrito; (3) quem entra faz tarefas à mêo antes de revisar o agente; (4) a avaliaçêo nêo pune quem reporta erro do agente; (5) todo agente tem dono e, no desligamento, quem assume o trabalho.
Aprovaçêo: a Patrícia monta; a Juliana e a Sandra leem e dizem se a conversa e a trilha aconteceram como está escrito; o Carlos assina.

## Decisões
- **Mercado da aula 1:** o currículo traz "até +20 e 1,4× mais uso" para o espaço de experimentar; esses números nêo estêo no arquivo de mercado → fora. A ideia vira recomendaçêo ARCKHÉ.
- **Aula 7:** Forrester (previsêo) sai da aula e vai para o painel da aula 8, para manter um fato por aula.
- **Aula 5:** SignalFire e constituiçêo do Claude nêo estêo nos arquivos de mercado, mas sêo fatos conferidos da fonte listada na tabela (área §03 + `empresas-2027-v62/context/curriculo.md`); entram com a formulaçêo de lá.
- **Vídeos:** `gerente-de-agentes` (aula 3) e `empresas-2027` (aula 5), PT/EN/ES de release `video-v2.0.0` (302 conferido); pôster = quadro do próprio MP4 (PT 6 s, EN/ES 30 s); `.vtt` dos repos.
- **Capa sem texto**, como o G3 e o G4.
- `lado_card` → G0. `inicio.cursos` com os 6 cursos (capas reais dos irmêos, todos publicados) — revisêo de 19/10.
