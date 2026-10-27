# Avaliação de Acessibilidade

A avaliação de acessibilidade tem como objetivo identificar barreiras que possam dificultar ou impedir o acesso e a utilização do site por pessoas com deficiência ou com diferentes necessidades de navegação. A análise foi realizada com base nas diretrizes WCAG (Web Content Accessibility Guidelines), buscando verificar se o conteúdo e as funcionalidades do site são acessíveis, compreensíveis e utilizáveis.

## Escopo da avaliação

Foram selecionadas as seguintes telas para inspeção:
<img width="1122" height="791" alt="acessibilidade1" src="https://github.com/user-attachments/assets/8493d89d-a159-4599-8fb0-e23331ef6ca4" />
<img width="1120" height="791" alt="acessibilidade2" src="https://github.com/user-attachments/assets/57fcefb4-b15f-4a29-94b8-e053c8f8d221" />
<img width="1122" height="790" alt="acessibilidade3" src="https://github.com/user-attachments/assets/b3caacf6-0d13-469c-ba7c-49f29057a905" />
<img width="1123" height="792" alt="acessibilidade4" src="https://github.com/user-attachments/assets/15d2241f-0651-4779-bfa4-a7ef3b22ab26" />
<img width="1122" height="794" alt="acessibilidade5" src="https://github.com/user-attachments/assets/3d650d20-89d5-4998-a811-52b6a4250156" />
<img width="1123" height="790" alt="acessibilidade6" src="https://github.com/user-attachments/assets/4e2f1cad-a4b3-4462-966c-5ed19b7374ee" />

## Processo utilizado

O processo de avaliação foi dividido em três etapas: detecção, coleta e discriminação dos problemas encontrados.

- **Detecção:** foram inspecionadas as páginas selecionadas para identificar possíveis barreiras de acessibilidade, considerando critérios das diretrizes WCAG, como contraste de cores, textos alternativos para imagens, identificação de campos de formulário, estrutura de títulos e navegação por teclado.

- **Coleta:** os problemas identificados foram registrados, relacionando cada ocorrência à página em que foi encontrada e ao critério de acessibilidade correspondente. Também foi considerada a frequência com que cada problema apareceu durante a inspeção.

- **Discriminação:** os problemas foram classificados de acordo com sua natureza e seu possível impacto na experiência dos usuários. Essa etapa permitiu organizar as falhas encontradas e relacioná-las às recomendações da WCAG, facilitando a compreensão dos problemas e a identificação de possíveis melhorias.

A partir desse processo, foi possível organizar os resultados da inspeção e identificar aspectos do site que podem ser aprimorados para proporcionar uma navegação mais acessível e inclusiva.

## Resultados da inspeção

A inspeção de acessibilidade do site do Detran-AM identificou problemas relacionados à percepção, operação, compreensão e compatibilidade com tecnologias assistivas. Foram analisadas diferentes páginas e funcionalidades, incluindo a página inicial, a apresentação institucional, o acesso à informação, a agenda e o agendamento de serviços. Os problemas encontrados foram relacionados aos critérios das Diretrizes de Acessibilidade para Conteúdo Web (WCAG 2.2).

## Síntese dos problemas encontrados

A tabela a seguir apresenta os problemas identificados durante a inspeção, os respectivos critérios WCAG, as páginas em que ocorrem e a frequência registrada.

| Problema | Critério WCAG | Tela/Página | Frequência |
|---|---|:-:|:--:|
| O botão para fechar o banner sobre queimadas na Amazônia é inacessível por teclado. | 2.1.1 — Teclado | Página inicial, apresentação da instituição, acesso à informação e agenda | 1 |
| Elementos gráficos, como logotipo, banners e ícones de acesso a serviços, não possuem descrição textual adequada. | 1.1.1 — Conteúdo não textual | Página inicial | 16 |
| Textos apresentam contraste insuficiente em relação ao fundo, como na lista de links úteis. | 1.4.3 — Contraste mínimo | Página inicial | 12 |
| Elementos gráficos de data e local e o botão de continuar apresentam baixo contraste. | 1.4.3 — Contraste mínimo | Tela de agendamento | 3 |
| O sistema não informa adequadamente o motivo do erro ao inserir dados incorretos, como CPF, nome, celular ou e-mail. | 3.3.1 — Identificação de erros | Tela de agendamento | 1 |
| Banners e ícones de acesso a serviços não apresentam descrição textual. | 1.1.1 — Conteúdo não textual | Apresentação da instituição | 5 |
| O texto e o botão “ver no mapa” apresentam baixo contraste em relação ao fundo. | 1.4.3 — Contraste mínimo | Apresentação da instituição | 2 |
| O menu lateral apresenta graves problemas de contraste entre texto e fundo. | 1.4.3 — Contraste mínimo | Acesso à informação | 26 |
| O filtro de categorias da agenda não possui rótulos reconhecidos pelo leitor de tela WAVE. | 1.3.1 — Informações e relações | Agenda | 4 |
| O calendário e o menu lateral da agenda apresentam problemas de contraste. | 1.4.3 — Contraste mínimo | Agenda | 145 |
| O contraste não atende às exigências da WCAG em diferentes páginas e componentes. | 1.4.3 — Contraste mínimo | Portal de serviços, agenda e acesso à informação | 186 |
| Links de navegação não possuem textos alternativos ou descrições suficientes para identificar sua finalidade. | 2.4.4 — Finalidade do link (em contexto) | Portal de serviços e agenda | 23 |
| Campos de formulário não possuem rótulos associados que identifiquem sua finalidade. | 1.3.1 — Informações e relações | Agendamento e agenda | 6 |
| Botões e links estão vazios ou não possuem texto descritivo. | 2.4.4 — Finalidade do link (em contexto) | Página inicial, agenda e filtros | 4 |
| Menus ARIA apresentam erros estruturais ou estão quebrados, prejudicando a navegação por tecnologias assistivas. | 4.1.2 — Nome, função e valor | Página inicial e agenda | 2 |
| A estrutura apresenta níveis de cabeçalho omitidos ou fora de ordem, dificultando a orientação dos usuários. | 1.3.1 — Informações e relações | Agendamento e acesso à informação | 31 |
| Há contraste abaixo do recomendado em diversas áreas do site, incluindo páginas de serviços e agendamento. | 1.4.3 — Contraste mínimo | Página inicial, habilitação e veículo, apresentação institucional, acesso à informação e agendamento | 189 |
| Imagens clicáveis e ícones utilizados na interação não apresentam texto alternativo adequado. | 1.1.1 — Conteúdo não textual | Página inicial, habilitação e veículo, apresentação institucional e acesso à informação | 52 |
| Ao preencher dados incorretamente ou deixar campos em branco, o sistema não informa precisamente a localização ou o motivo do erro. | 3.3.1 — Identificação de erros | Agendamento de habilitação e veículo | 1 |
| O botão “validar” do formulário não pode ser selecionado apenas pelo teclado. | 2.1.3 — Teclado (sem exceção) | Agendamento de habilitação e veículo | 1 |
### Critérios WCAG violados

A tabela apresenta os princípios, as diretrizes e os critérios de sucesso da WCAG 2.2 identificados durante a avaliação do site do Detran-AM, assim como os respectivos níveis de conformidade.

| Princípio | Diretriz | Critério violado | Nível |
|:-:|---|---|:-:|
| Operável | 2.1 — Acessível por teclado | 2.1.1 — Teclado | A |
| Perceptível | 1.1 — Alternativas em texto | 1.1.1 — Conteúdo não textual | A |
| Compreensível | 3.3 — Assistência de entrada | 3.3.1 — Identificação de erros | A |
| Perceptível | 1.3 — Adaptável | 1.3.1 — Informações e relações | A |
| Perceptível | 1.4 — Discernível | 1.4.3 — Contraste mínimo | AA |

## Considerações sobre os resultados

A avaliação identificou problemas de acessibilidade em diferentes páginas e funcionalidades do portal do Detran-AM. Entre os aspectos mais relevantes estão o contraste insuficiente, a ausência de alternativas textuais para imagens e ícones, as dificuldades de navegação por teclado e as falhas na identificação de campos e na comunicação de erros.

Esses problemas podem comprometer a autonomia dos usuários, principalmente daqueles que utilizam leitores de tela, navegam exclusivamente pelo teclado ou possuem baixa visão. As falhas também podem dificultar o acesso a informações institucionais e a conclusão de procedimentos importantes, como agendamentos de serviços.

Recomenda-se priorizar a correção dos problemas de contraste, a inclusão de textos alternativos adequados, a associação de rótulos aos campos de formulário e a garantia de que todos os controles interativos possam ser utilizados por teclado. Também é importante revisar a estrutura dos cabeçalhos, os nomes acessíveis dos componentes e as mensagens de erro.
