# TP1-IHC DETRAN
**DISCIPLINA**: INTERAÇÃO HUMANO COMPUTADOR
**SISTEMA AVALIADO**: Site do Detran-AM

**Integrantes da Equipe**: Felipe Gabriel dos Santos Silva, Jorge Victor Lima de Oliveira, Lúcia Vitória dos Santos Menezes, João Henrique de Souza Barros, Rhuan Felipe Neves Sena

## Sobre o sistema
O site do Detran-AM (Departamento Estadual de Trânsito do Amazonas) é uma plataforma institucional que tem como objetivo disponibilizar informações e serviços relacionados ao trânsito no estado do Amazonas, facilitando o acesso da população aos procedimentos do órgão. Entre suas principais funcionalidades estão o agendamento de atendimentos, a solicitação e renovação da Carteira Nacional de Habilitação (CNH), a consulta de multas e pontuação do condutor, o pagamento de infrações, o licenciamento de veículos, a emissão do Certificado de Registro e Licenciamento de Veículo eletrônico (CRLV-e), além de informações sobre taxas, documentação necessária e legislação de trânsito. Dessa forma, o site busca tornar os serviços mais acessíveis, reduzir a necessidade de deslocamentos presenciais e orientar os cidadãos sobre suas obrigações e seus direitos no trânsito.

## Sumário
### Detran
- [apresentação do sistema]()

### Avaliação de usabilidade
- [Inspeção]()
- [Teste]()
- [Maze]()

### Avaliação UX
- [Experiência de Uso]()

### Avaliação de Acessibilidade
- [Inspeção de Acessibilidade]()

### Avaliação de comunicabilidade
- [mac]()

## Organização do repositório

```
TP1-IHC/
│
├── 00-detran-am/
│   └── apresentacao-do-sistema.md
│
├── 01-avaliacao-usabilidade/
│   ├── 1-inspecao.md
│   ├── 2-teste.md
│   └── 3-maze.md
│
├── 02-avaliacao-ux/
│   └── experiencia-de-uso.md
│
├── 03-avaliacao-acessibilidade/
│   └── inspecao-de-acessibilidade.md
│
├── 04-avaliacao-comunicabilidade/
│   └── mac.md
│
└── README.md
```
## Resumo das avaliações realizadas

### 1. Inspeção de usabilidade (Avaliação Heurística)

Cada integrante da equipe explorou o site do Detran-AM de forma individual e independente, sem roteiro de tarefas, registrando os problemas encontrados com base nas 10 heurísticas de Nielsen. Em seguida, os registros foram reunidos em uma única tabela, com a remoção dos problemas repetidos. A equipe então classificou cada problema como defeito ou falso positivo e, para os defeitos, definiu o grau de severidade e sugestões de melhoria. Todo o processo foi registrado no Notion.

### 2. Teste de usabilidade

O teste foi realizado com [8] participantes externos à equipe, mais um teste piloto, que serviu para ajustar as tarefas e a configuração da ferramenta. Cada sessão seguiu a mesma sequência: assinatura do TCLE, questionário de caracterização, execução das [8] tarefas e questionário pós-teste. As tarefas e os questionários foram aplicados pela ferramenta Maze, e a equipe acompanhou as sessões sem indicar como executar as tarefas. Foram analisados o sucesso, o tempo e os erros de cada participante em cada tarefa.

### 3. Avaliação de experiência de uso (UX)

Após o teste de usabilidade, os participantes responderam ao questionário **UEQ** (User Experience Questionnaire), que mede seis dimensões: atratividade, perspicuidade, eficiência, confiabilidade, estimulação e novidade. Os dados foram inseridos na planilha oficial da ferramenta, que calcula os resultados e gera os gráficos. As respostas às perguntas abertas foram analisadas qualitativamente no **ATLAS.ti**: os comentários foram codificados e os códigos foram associados às dimensões do UEQ por meio de redes, uma para cada dimensão.

### 4. Avaliação de acessibilidade

A equipe inspecionou [telas selecionadas] do site tendo como referência as diretrizes **WCAG 2.2**, combinando verificações manuais e automatizadas: uso de leitor de tela ([nome do leitor]), navegação apenas pelo teclado, análise de estrutura e marcação, verificação de fonte e espaçamento ([ferramenta]) e teste de contraste de cores ([ferramenta]). Os problemas foram reunidos, os registros repetidos foram eliminados e cada achado foi relacionado ao critério da WCAG violado, com sua gravidade e seu impacto.

### 5. Avaliação de comunicabilidade

Foi aplicado o **Método de Avaliação de Comunicabilidade (MAC)** com 2 participantes de perfis diferentes, que não participaram do teste de usabilidade. Cada um assinou o TCLE e executou 10 tarefas ligadas à compreensão das mensagens do site, com tela e áudio gravados. A equipe assistiu aos vídeos e etiquetou cada ruptura de comunicação com expressões como *Cadê?*, *E agora?* e *O que é isto?*, registrando o trecho observado e a interpretação do problema. Por fim, as etiquetas foram contadas e analisadas para identificar quais tarefas e telas concentraram mais rupturas.
