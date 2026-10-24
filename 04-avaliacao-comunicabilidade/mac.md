# Avaliação de Comunicabilidade

## Método utilizado

O **Método de Avaliação de Comunicabilidade (MAC)** é baseado na Engenharia Semiótica e entende a interface como uma mensagem enviada pelo designer ao usuário, por meio da qual o designer comunica o que o sistema faz e como utilizá-lo. O método busca identificar **rupturas de comunicação**, que são momentos em que o usuário não interpreta a mensagem do sistema como o designer pretendia.

A avaliação seguiu quatro etapas: preparação, gravação da interação, etiquetagem das rupturas e interpretação dos resultados. Na etiquetagem, cada ruptura recebe uma etiqueta que representa o que o usuário "diria" naquele momento (por exemplo, *Cadê?*, *E agora?*, *O que é isto?*), junto do trecho observado. Cada ruptura também é classificada quanto ao tipo de falha: **temporária** (o usuário supera sozinho), **parcial** (cumpre só parte da tarefa ou por outro caminho) ou **completa** (não consegue concluir).

## Participantes e tarefas

A avaliação do site do Detran-AM (`detran.am.gov.br`) foi realizada com 2 participantes de perfis diferentes, que não participaram do Teste de Usabilidade: [descrever o perfil de P1 e P2].

Foram aplicadas 10 tarefas, que dependem das mensagens do site (menus, rótulos, banners e links). Os participantes receberam apenas o objetivo, sem indicação do caminho.

| Tarefa | Caminho esperado | Critério de sucesso |
|---|---|---|
| **T1** — Ir aos postos de atendimento | Página inicial > menu *Postos de atendimento* (ou *Sobre Serviço* > *Postos de atendimento*) | Chega à lista ou ao mapa de postos de atendimento |
| **T2** — Ir à página de renovação da CNH | Página inicial > menu *Habilitação* > *Renovação de CNH* | Chega à página com orientações, etapas e documentos exigidos |
| **T3** — Ir à página de consulta de multas | Página inicial > menu *Infrações* > *Consulta de Multas* | Chega à página de consulta de infrações do veículo |
| **T4** — Entrar no portal de serviços online | Página inicial > banner ou botão *Portal de Serviços* (ou *Agendamento* / *Detran Digital*) | Chega à tela principal do Portal de Serviços do Detran-AM |
| **T5** — Voltar do portal para o site do Detran | Portal de Serviços > link ou logotipo *Voltar para o site do Detran-AM* (ou *Ir para o Portal Institucional*) | Volta à página inicial do site institucional do Detran-AM |
| **T6** — Aumentar o tamanho do texto do site | Página inicial > barra superior de acessibilidade > botão *Aumentar texto* (ícone *A+*) | As fontes do site aumentam de tamanho na tela |
| **T7** — Consultar a Carta de Serviços ao Cidadão | Página inicial > menu *A Instituição* (ou atalhos rápidos) > *Carta de Serviços* | Chega à página ou ao PDF da Carta de Serviços ao Cidadão |
| **T8** — Acessar a Ouvidoria do Detran | Página inicial > menu *Ouvidoria* | Chega à página do canal oficial da Ouvidoria (E-OUV) |
| **T9** — Chegar à tela do licenciamento do veículo | Página inicial > *Portal de Serviços* > *Veículos* > *Licenciamento Anual (CRLV-e)* | Chega à tela do formulário para inserção de dados ou placa do veículo |
| **T10** — Localizar o endereço da sede e o horário de atendimento | Página inicial > rolar até o rodapé da página | Visualiza o endereço da sede (Av. Mário Ypiranga) e o horário de atendimento presencial (8h às 14h) |

As etiquetas da última coluna são hipóteses feitas no planejamento. As etiquetas realmente atribuídas estão na seção de etiquetagem.

## Registro das sessões

- [Vídeo do participante U1]([link])
- [Vídeo do participante U2]([link])

## Etiquetagem das rupturas

A tabela apresenta cada ruptura de comunicação identificada nos vídeos, com o participante, a tarefa, a tela ou elemento envolvido, a situação observada, o tipo de falha, a etiqueta atribuída e o problema de comunicabilidade correspondente.

[Discutir os resultados observados.]

| Part. | Tarefa | Tela/Elemento | Timestamp | Situação observada | Tipo de falha | Etiqueta | Problema de comunicabilidade |
|---|---|---|---|---|---|---|---|
| P1 | T1 | Página inicial → menu *Postos de atendimento* | | Não encontrou a opção e permaneceu na página inicial até o fim da tarefa: “difícil...” | Completa | Cadê? | A opção de postos de atendimento não foi percebida na página inicial, e o usuário não identificou onde ela estava. |
| P1 | T1 | Página inicial | | Pediu para encerrar a tarefa: “pode desistir?...” | Completa | Desisto | Sem encontrar o caminho, o usuário abandonou a tarefa, e o site não deu pistas para ele continuar. |
| P1 | T2 | Páginas diversas do site | | Navegou por vários campos do site sem localizar a página de renovação da CNH | Temporária | Cadê? | O caminho *Habilitação* → *Renovação de CNH* não foi percebido como o lugar onde essa informação está. |
| P1 | T2 | Portal de Serviços → serviço de renovação | | Chegou ao serviço pelo Portal de Serviços, mas ele estava bloqueado por falta de login: “deve ser aqui...”, “tá aqui só q tá bloqueado” | Parcial | Por que não funciona? | O serviço aparece, mas o site não explica antes que é preciso estar logado, e o usuário só descobre ao tentar acessá-lo. |
| P1 | T4 | Página inicial → banner/botão *Portal de Serviços* | | Ficou confuso por um tempo até encontrar o Portal de Serviços, que reconheceu por já ter passado por ele na T2 | Temporária | Cadê? | O acesso ao Portal de Serviços não foi imediatamente reconhecido, e o usuário só o encontrou por já conhecê-lo de antes. |
| P1 | T5 | Portal de Serviços → link de retorno ao site | | Teve dificuldade em voltar ao site sem usar o botão voltar do navegador: “que site horrível...” | Temporária | Assim não dá | O portal não deixa claro como voltar ao site institucional, e o usuário se sente preso nesse ambiente. |
| P1 | T6 | Barra superior de acessibilidade → botão *Aumentar texto* (A+) | | Clicou várias vezes no botão para aumentar o texto, mas o tamanho não mudou | Completa | Por que não funciona? | O botão aparece na tela como funcional, mas não tem efeito, e o site não informa que o recurso está indisponível. |
| P1 | T9 | Menu *Veículos* | | Demorou procurando a opção de licenciamento anual dentro do campo de veículos: “licenciamento de veículo...” | Temporária | Cadê? | A opção de licenciamento demorou a ser localizada e o usuário a procurou em outro lugar que não o caminho previsto. |
| P2 | T1 | Página inicial → menu principal | | Levou alguns segundos procurando a opção de postos de atendimento no menu principal: “onde é q fica isso?” | Temporária | Cadê? | A opção de postos de atendimento não foi percebida de imediato no menu principal. |
| P2 | T1 | Barra de pesquisa → resultados | | Desistiu de procurar no menu, usou a barra de pesquisa e demorou até selecionar a opção correta | Temporária | Vai de outro jeito | Como não encontrou o caminho pelo menu, o usuário recorreu à busca, e os resultados não deixaram claro qual era a opção correta. |
| P2 | T2 | Barra de pesquisa → resultados | | Pesquisou por renovação de CNH, ficou confuso, escolheu a opção errada e achou que tinha concluído a tarefa | Temporária | Pra mim está bom... | Os resultados da busca não distinguem claramente a página de renovação de outros conteúdos, e o usuário não percebeu que estava no lugar errado. |
| P2 | T2 | Página inicial → barra de pesquisa | | Voltou à tela inicial e pesquisou novamente por CNH, até encontrar a página correta | Temporária | Vai de outro jeito | O usuário só percebeu o erro depois e precisou refazer a busca com outro termo para chegar à página certa. |
| P2 | T6 | Barra superior de acessibilidade → botão *Aumentar texto* (A+) | | Clicou várias vezes no botão para aumentar o texto, mas a fonte continuou normal: “não tá aumentando...” | Completa | Por que não funciona? | O botão aparece na tela como funcional, mas não tem efeito, e o site não informa que o recurso está indisponível. |
| P2 | T9 | Menu *Veículos* | | Acessou *Veículos* e procurou a opção de licenciamento anual, mas não a encontrou na primeira tentativa | Temporária | Cadê? | A opção de licenciamento anual não foi percebida de imediato dentro do menu de veículos. |
| P2 | T9 | Barra de pesquisa → resultados | | Pesquisou na barra de pesquisa, não encontrou, voltou à tela inicial e entrou de novo em *Veículos*, onde achou a opção: “tá aqui RM veículos mesmo” | Temporária | Vai de outro jeito | A busca não retornou o serviço, e o usuário só o encontrou voltando ao caminho do menu, que já tinha percorrido. |
| P2 | T10 | Página inicial → menu *Acesso à informação* | | Foi ao menu *Acesso à informação* em busca do endereço e do horário e não encontrou: “eu acho q n é aqui”. Depois desceu até o rodapé e localizou as informações | Temporária | Cadê? | O endereço e o horário não estavam onde o usuário esperava, e ele só os achou ao rolar até o rodapé. |

## Consolidação das etiquetas

A tabela apresenta quantas vezes cada etiqueta foi atribuída a cada participante, o total e as tarefas mais afetadas.

[Discutir os resultados observados. Apresentar os principais resultados da avaliação, destacando quais etiquetas apareceram com maior frequência, quais tarefas apresentaram mais rupturas e o que esses resultados indicam sobre a comunicação entre o sistema e os usuários.]

| Etiqueta | Ocorrências (P1) | Ocorrências (P2) | Total | Tarefas mais afetadas |
|---|---|---|---|---|
| Cadê? | 4 | 3 | 7 | T1, T9 |
| E agora? | 0 | 0 | 0 | — |
| O que é isto? | 0 | 0 | 0 | — |
| Epa! | 0 | 0 | 0 | — |
| Onde estou? | 0 | 0 | 0 | — |
| Assim não dá | 1 | 0 | 1 | T5 |
| Por que não funciona? | 2 | 1 | 3 | T6 |
| Ué, o que houve? | 0 | 0 | 0 | — |
| Pra mim está bom... | 0 | 1 | 1 | T2 |
| Desisto! | 1 | 0 | 1 | T1 |
| Vai de outro jeito | 0 | 3 | 3 | T1, T2, T9 |
| Não, obrigado | 0 | 0 | 0 | — |
| Socorro! | 0 | 0 | 0 | — |
| **Total** | **8** | **8** | **16** | |
