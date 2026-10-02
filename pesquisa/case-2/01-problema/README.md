# Case 2 — Baixa utilidade diária e engajamento recorrente

**Localiza Assinatura | Hackathon Ruptura 2026 | Pesquisa atualizada em 02/10/2026**

> **Diagnóstico provisório:** o aplicativo tem alta adoção mensal e oferece recursos de gestão da assinatura. O ponto a investigar é por que essas capacidades geram uso predominantemente pontual e em quais atividades de dirigir existe uma necessidade relevante que o app não atende, não torna visível ou não permite concluir com vantagem para o cliente.

Este documento aprofunda exclusivamente os dois subproblemas definidos pelo grupo:

1. **Por que 36% dos clientes utilizam o app apenas de 1 a 2 vezes por mês e só 17% são altamente engajados?**
2. **Quais funcionalidades do contexto diário de dirigir — abastecimento, estacionamento, pedágio e rotas — estão ausentes no app atual?**

**Estado da pesquisa:** análise documental, sem entrevistas com assinantes, acesso ao aplicativo autenticado ou dados internos de navegação. Os números e recursos do case foram conferidos. A descrição oficial do app, o site de benefícios e descrições de alternativas de mobilidade foram consultados. As causas específicas e a ausência efetiva de determinadas funções ainda precisam de validação.

## Guia de leitura e método

| Parte | O que entrega |
|---|---|
| 1. Enquadramento | Definição do problema e pergunta central |
| 2. Subproblema 1 | Leitura dos percentuais, causas possíveis, alta frequência e critérios de análise |
| 3. Subproblema 2 | Inventário atual, análise das quatro atividades, alternativas e auditoria de lacunas |
| 4. Relação entre os dois | Por que atividade recorrente ou funcionalidade nova não garante retorno ao app |
| 5. Validação | Entrevistas, dados e critérios para confirmar o problema |
| 6. Síntese | Argumentação que o grupo já pode sustentar |
| 7. Fontes | Referências, páginas e limites da investigação |

A estrutura segue **definir → enquadrar → priorizar/analisar → sintetizar**, usando SCQ, árvore de problemas, decomposição de jornadas e priorização, conforme os PDFs. A etapa do conceito vem depois. [M1, M2]

Distinguimos quatro tipos de informação:

- **Fato documental:** o material ou fornecedor afirma algo; não implica que testamos sua execução.
- **Sinal exploratório:** relato público ou observação que ajuda a levantar hipóteses, sem representar toda a base.
- **Hipótese:** explicação plausível a confirmar ou descartar.
- **Lacuna de evidência:** informação necessária que ainda não foi obtida.

As páginas citadas são as posições físicas no PDF, começando na primeira página do arquivo.

## 1. Enquadramento do problema

### 1.1 Situação

O app Localiza Assinatura reúne contrato, documentos, faturas, manutenção, multas, quilometragem, benefícios e informações do veículo. O case apresenta **80,1% de acesso mensal, 53 mil MAU e NPS do app 84**. [C1, p. 24–36]

O material descreve a jornada atual como: **precisa resolver algo → acessa → resolve pontualmente → fecha → retorna quando surge outra necessidade**. [C1, p. 20–21]

### 1.2 Complicação

O carro participa de atividades frequentes, mas o aplicativo é usado principalmente para tarefas pontuais. O próprio case afirma que benefícios e serviços nem sempre se conectam ao contexto do cliente e que faltam utilidades relevantes em outros momentos de mobilidade. [C1, p. 19–22]

Essa observação justifica investigar uma oportunidade. Ainda não demonstra que o cliente esteja insatisfeito com a frequência atual ou que deseje centralizar todas as atividades de dirigir no mesmo aplicativo.

### 1.3 Pergunta central — SCQ

> **Por que o valor disponível no app gera uso predominantemente pontual, e quais necessidades recorrentes de abastecimento, estacionamento, pedágio e rotas permanecem sem atendimento útil no contexto do assinante?**

Precisamos distinguir três situações: pouca necessidade legítima de interação; uma necessidade que existe, mas já é bem atendida fora do app; e uma necessidade relevante que continua mal atendida.

### 1.4 Definições para não investigar o problema errado

| Termo | Definição para a pesquisa |
|---|---|
| Utilidade diária | Pertinência às atividades da rotina; não obriga abertura diária |
| Recorrência | Reaparecimento da necessidade em uma cadência real, que pode ser diária, semanal, mensal ou por evento |
| Frequência de acesso | Contagem segundo a definição técnica do case, ainda a esclarecer |
| Engajamento útil | Uso que ajuda a compreender, decidir ou concluir uma necessidade com benefício reconhecível |
| Hábito | Tendência a recorrer a uma alternativa em determinado contexto; não pode ser inferido de um único mês |
| Lacuna funcional | Capacidade necessária indisponível no recorte auditado |
| Lacuna de experiência | Capacidade existe, mas não é descoberta, compreendida, elegível ou concluída com utilidade |

**A frequência de dirigir é diferente da frequência de abastecer, pagar estacionamento, passar em pedágio ou consultar uma rota. E todas elas são diferentes da frequência necessária de abrir um app.**

## 2. Subproblema 1 — Por que 36% acessam 1–2 vezes e 17% têm alta frequência?

### 2.1 O que a distribuição realmente mostra

| Acessos no mês | Participação apresentada |
|---|---:|
| 1–2 | 36% |
| 3–5 | 28% |
| 6–10 | 19% |
| 11–20 | 11% |
| 21 ou mais | 6% |

Fonte: [C1, p. 25].

Os 17% correspondem à soma das faixas de 11–20 e 21+, isto é, **11% + 6%**. Os **47% restantes estão entre 3 e 10 acessos**. Portanto, a distribuição não se resume a pouco uso versus alto uso.

Derivações simples da própria tabela: **64% estão em até 5 acessos** e **83% em até 10**. Esses totais descrevem frequência, sem medir satisfação, esforço, utilidade ou oportunidade perdida.

O slide apresenta a distribuição entre os clientes que acessam o app no mês. Precisamos confirmar o denominador e o significado de “acesso engajado” antes de falar em 36% de toda a base. Não aplicamos automaticamente os percentuais à frota ou aos 53 mil MAU.

### 2.2 Limites que mudam a interpretação

| Informação que falta | Por que importa |
|---|---|
| Acesso significa sessão, evento, login ou dia ativo? | Onze eventos num mesmo episódio não equivalem a onze dias de uso |
| Qual é o mês/período de referência? | Entrega de veículos, férias ou serviços podem alterar a distribuição |
| Quem entra na base? | Titulares, condutores, contas e contratos não são necessariamente equivalentes |
| Qual tarefa motivou o acesso? | Uma frequência idêntica pode representar comportamentos muito diferentes |
| A tarefa foi concluída? | Retornar pode indicar utilidade ou tentativa repetida |
| O cliente percebeu valor? | Acesso não comprova benefício reconhecido |
| O comportamento persiste em outros meses? | A faixa pode refletir um evento temporário, sem representar um segmento estável |

O texto da página 21 diz “menos de 2x”, enquanto a tabela da página 25 diz “1 a 2”. Adotamos a faixa explícita da tabela. MAU, WAU e adesão mensal precisam de bases e janelas compatíveis; sua razão não deve ser apresentada como retenção.

**Não conseguimos calcular uma média exata de acessos a partir dessas faixas**, especialmente porque 21+ não tem limite superior. Também não sabemos quais usuários transitam entre faixas ao longo do contrato.

### 2.3 A explicação mais diretamente sustentada pelo case: tarefas episódicas

Os recursos apresentados concentram atividades administrativas e eventos relacionados ao contrato. [C1, p. 24–36]

| Capacidade documentada | Disparador típico a investigar | Relação possível com a frequência |
|---|---|---|
| Consultar fatura/pagamento | Vencimento ou dúvida de cobrança | Pode concentrar consultas em torno do ciclo mensal |
| Acessar contrato/CRLV | Conferência, documento ou dúvida | Pode ocorrer somente quando necessário |
| Agendar manutenção | Prazo, necessidade preventiva/corretiva | Depende do serviço; não é necessariamente mensal |
| Administrar multa/condutor | Recebimento de infração | Evento eventual |
| Consultar quilometragem | Interesse em acompanhar uso contratado | Pode ser periódico ou pontual, conforme a pessoa |
| Ver localização/combustível | Necessidade de consultar o veículo | Potencial de frequência distinto; cobertura e utilidade precisam de confirmação |
| Consultar benefícios | Intenção de usar uma vantagem | Depende de conhecimento, elegibilidade e contexto |

Os disparadores são interpretações de possíveis situações de uso, não frequências medidas. Ainda assim, o desenho descrito explica por que um cliente pode abrir o app poucas vezes mesmo dirigindo diariamente.

**Conclusão documental:** o caso é compatível com uso orientado a eventos. **Questão em aberto:** quanto desse uso é suficiente e quanto revela necessidades adicionais mal atendidas?

### 2.4 Dez mecanismos que podem explicar pouca recorrência

#### A. Pouca necessidade de interação, com boa resolução

O cliente pode entrar uma ou duas vezes, resolver e seguir a rotina. Se não há pendência, incerteza ou dificuldade, o pouco uso não configura dor. Precisamos perguntar o que deixou de fazer, se algo ficou sem resolver e se deseja mais interação.

**Fortalece a hipótese:** poucas tarefas, conclusão fácil e satisfação. **Enfraquece:** necessidade recorrente que o cliente relata estar mal atendida.

#### B. A assinatura é contratada para reduzir administração

A promessa comercial de comodidade e menos preocupações torna plausível que alguns clientes queiram pensar menos no carro. [L1] Acompanhar mais painéis ou consultar informações sem consequência prática pode contrariar essa expectativa.

Isso precisa ser recuperado na motivação real da contratação. Não podemos assumir que todos delegam da mesma maneira: alguns valorizam controle, outros preferem ser envolvidos somente quando há decisão necessária.

**Pergunta-chave:** “O que você esperava deixar de administrar ao assinar?”

#### C. O valor disponível concentra-se no contrato, enquanto a rotina acontece fora dele

O case declara pouca utilidade fora das necessidades contratuais e benefícios nem sempre conectados ao contexto. [C1, p. 21] Uma pessoa pode pensar em chegar ao trabalho, abastecer ou estacionar, sem associar essas situações à Localiza.

O mecanismo possível é uma distância entre o objetivo cotidiano e o uso que a pessoa atribui ao app. Precisamos identificar quais episódios ocorrem, como são resolvidos e onde existe dificuldade; não basta perguntar quais funções ela gostaria de ter.

#### D. Recursos existem, mas não são descobertos ou lembrados

A apresentação de benefícios na home não comprova que o cliente saiba o que está disponível nem que se lembre disso no momento de usar. Um recurso pode ser desconhecido, conhecido de forma vaga ou conhecido sem compreensão do benefício.

Investigar conhecimento espontâneo antes de mostrar a lista. Depois, observar se o usuário encontra uma vantagem pertinente e entende como utilizá-la. Uma resposta positiva após explicação do pesquisador não demonstra descoberta espontânea.

#### E. Benefícios não compensam no contexto real

Uma vantagem pode exigir parceiro distante, cadastro adicional, cupom, condição de pagamento ou etapa externa. Pode também não existir para o contrato, região ou situação da pessoa. Esses são mecanismos possíveis, ainda sem auditoria completa das ofertas.

Investigar o ganho líquido percebido: benefício obtido versus deslocamento, tempo, restrição e esforço adicional. A oferta pode existir e continuar pouco útil. Conhecimento sem resgate não deve ser interpretado automaticamente como desinteresse.

#### F. Alternativas já ocupam o momento de decisão

Aplicativos especializados anunciam navegação, pagamento de abastecimento e gestão de tag. [A2–A5] Isso demonstra disponibilidade de alternativas, mas não sua adoção entre assinantes.

O cliente pode já ter cadastro, meio de pagamento, histórico, benefício ou preferência em outra opção. Se ela resolve bem, pode não haver motivo para consultar a Localiza na mesma atividade.

**Pergunta-chave:** “Na última vez em que precisou disso, qual opção usou e por que foi a primeira?”

#### G. Informação pouco confiável ou pouco acionável reduz retorno

Um dado que o cliente não compreende, não consegue verificar ou não sabe como usar pode perder utilidade. A pesquisa anterior encontrou relatos sobre acesso, quilometragem e localização, mas não reproduziu as falhas nem confirmou sua persistência. [R1, H1]

Separar confiabilidade percebida de cobertura real. A pessoa pode deixar de consultar um recurso porque já encontrou inconsistência, porque a informação não está disponível naquele carro ou porque o dado não altera uma decisão.

#### H. Falta um motivo reconhecível no momento da necessidade

Uma atividade recorrente pode ocorrer sem que o cliente se lembre do app. A página do modelo comportamental de Fogg organiza comportamento em motivação, facilidade/capacidade e estímulo. [F1] Usamos essa lente para investigar, não como prova de uma causa na Localiza.

Verificar o que dispara o acesso atual: vencimento, aviso, pendência ou iniciativa própria. Comunicação vista e comunicação que ajuda são resultados diferentes. Não supomos que mais notificações produzam mais utilidade.

#### I. Condições de uso e familiaridade mudam o esforço

Disponibilidade de tempo, conectividade, aparelho, habilidade digital e acessibilidade podem tornar uma consulta conveniente ou trabalhosa. A idade é uma variável de contexto, sem equivaler a capacidade. [B1, B3, A1]

Precisamos observar a tarefa e a condição em que ela ocorre. Uma pessoa pode dominar aplicativos de mensagens e não ter prática com uma operação específica; outra pode ter grande autonomia em qualquer idade. Barreiras devem ser descritas pela tarefa, não por um rótulo geracional.

#### J. Papéis, intensidade de uso e fase do contrato são diferentes

Quem assina pode não ser quem dirige, abastece ou organiza os serviços. Uma conta também pode acompanhar mais de um veículo ou uma rotina empresarial. A fase de entrega, manutenção ou mudança de contrato pode gerar consultas temporárias.

Identificar papel, número de veículos, dias em que dirige, quilômetros, cidade, tempo de contrato e eventos recentes. Sem isso, uma média mistura clientes com oportunidades muito diferentes de uso.

### 2.5 Aprofundando os 17%: frequência alta pode ter naturezas opostas

| Padrão possível | O que observar | Interpretação possível |
|---|---|---|
| Consultas recorrentes úteis | Dados consultados, decisão tomada, confiança | O recurso encontra uma necessidade real |
| Uso de vantagens | Benefício elegível e utilização confirmada | O app participa de episódios de economia/conveniência |
| Acompanhamento de evento | Várias consultas sobre um serviço em andamento | Uso concentrado numa fase específica |
| Várias responsabilidades | Múltiplos veículos/papéis e tarefas distintas | Maior frequência decorre do contexto de gestão |
| Tentativas repetidas | Mesmo objetivo, erro/abandono, sem conclusão | A frequência pode refletir esforço excessivo |
| Curiosidade ou novidade | Exploração inicial que diminui depois | Acesso temporário, sem recorrência estabelecida |

Não sabemos qual padrão predomina. Precisamos comparar os grupos pelo que conseguem realizar, e não apenas pela quantidade de eventos.

**Uma pergunta especialmente útil:** “Se a frequência desse cliente cair porque ele passou a resolver com menos passos, consideraríamos isso melhora ou piora?” A resposta obriga o time a definir valor antes de perseguir acessos.

### 2.6 Árvore de investigação da baixa frequência

```text
Por que houve pouca utilização no período?
│
├── 1. Poucas necessidades pertinentes ao app surgiram
│   ├── Tarefas naturalmente episódicas
│   └── Papel/fase/intensidade de uso com pouca demanda
│
└── 2. Necessidades pertinentes surgiram
    ├── 2.1 Não existe capacidade útil para o contexto
    ├── 2.2 Existe, mas o cliente não conhece/encontra/lembra
    ├── 2.3 Conhece, mas prefere uma alternativa com maior vantagem
    ├── 2.4 Pretende usar, mas encontra barreira de acesso/execução
    ├── 2.5 Obtém valor sem precisar abrir o app
    └── 2.6 Outro mecanismo ou evidência insuficiente
```

Aplicação de MECE: primeiro verificar se houve necessidade; se houve, classificar a primeira razão demonstrada para não usar. Registrar outras razões como fatores secundários, sem contar o mesmo episódio várias vezes. Essa árvore é inicial e deve ser revista com casos reais. [M1, p. 20–22]

### 2.7 Idade, cultura e rotina dentro deste subproblema

O case traz 60% de respondentes com 45+ em uma pesquisa de 671 leads/clientes RAC, no contexto do case 1. **Não é o perfil etário da base ativa do app.** [C1, p. 17]

Para estudar recorrência, considerar faixas adultas de 18–24, 25–34, 35–44, 45–59 e 60+, sempre cruzando com habilidade, papel e atividade. O mesmo interesse em economia de tempo pode aparecer em qualquer faixa.

| Dimensão | Como pode mudar a oportunidade de uso | O que perguntar/observar |
|---|---|---|
| Cidade e infraestrutura | Parceiros, estacionamento e pedágio não estão distribuídos igualmente | Quais serviços realmente usa no território |
| Rotina urbana/rodoviária | Exposição a cada atividade é diferente | Episódios de uma semana e de um mês habituais |
| Organização familiar/empresarial | Quem dirige e quem consulta podem ser pessoas distintas | Responsabilidade de cada pessoa |
| Preço e orçamento | Economia nominal pode ou não compensar esforço | Como compara alternativas e custos |
| Familiaridade digital | Mesma tarefa pode exigir esforço diferente | Execução observada, sem usar idade como substituto |
| Preferências e privacidade | Pode evitar compartilhar dados ou novas contas | O que aceita informar e o que considera excessivo |

Essas dimensões geram perguntas; não são explicações causais comprovadas. A investigação deve evitar suposições como “jovem quer gamificação” ou “pessoa mais velha não usa app”.

### 2.8 Como medir recorrência com valor

| Métrica | Definição a estabelecer | Limite |
|---|---|---|
| Conclusão útil por oportunidade | Episódios em que o cliente alcança o resultado entre aqueles em que a necessidade ocorre | Exige identificar necessidade e resultado |
| Retorno para novo episódio | Cliente volta quando surge outra necessidade pertinente | Repetir tentativa no mesmo episódio não equivale a retorno útil |
| Uso confirmado de benefício | Vantagem efetivamente utilizada, não somente clicada | Pode depender de confirmação do parceiro |
| Esforço e compreensão | Tempo/passos e entendimento do resultado | Menos tempo não basta se a decisão fica confusa |
| Cobertura da utilidade | Proporção do público para quem a capacidade é disponível e pertinente | Uma função pode ser excelente para um recorte pequeno |
| Frequência de acesso | Eventos segundo definição técnica | Indicador de contexto, sem valor automático |

Uma passagem de pedágio automática ou uma informação entregue por aviso pode criar valor sem sessão adicional. Isso precisa ser medido separadamente. A meta de recorrência deve acompanhar a cadência da necessidade, evitando transformar uma atividade mensal em obrigação diária.

### 2.9 Resposta provisória ao primeiro subproblema

**O suporte mais forte está no caráter episódico das funções atuais e na desconexão contextual descrita pelo próprio case.** Outras explicações plausíveis são desconhecimento, inadequação de benefícios, preferência por alternativas, barreiras e diferenças de papel/rotina.

Ainda não sabemos quanto cada causa explica os 36%. Também não sabemos se os 17% representam uso valioso, acompanhamento ou esforço repetido. A investigação precisa comparar resultados por episódio e acompanhar a mesma base em mais de um período.

## 3. Subproblema 2 — Quais funcionalidades de dirigir estão ausentes?

### 3.1 O que podemos afirmar sobre o app atual

O case descreve gestão de quilometragem, alertas de aproximação do limite, localização do carro, alertas de movimentação/carro ligado, nível de combustível e bateria. Também apresenta um clube de benefícios. [C1, p. 24, 28 e 32–33]

A descrição oficial do app consultada em 02/10/2026 anuncia **descontos em hotéis, pedágios e estacionamentos**. A versão retornada pelo catálogo Apple é 5.2.0. [L3]

Portanto, não podemos dizer que o app não possui qualquer recurso relacionado a abastecimento, estacionamento, pedágio ou rotas. Precisamos separar informação, vantagem comercial e capacidade de executar uma atividade.

### 3.2 Escala de comprovação

| Situação | Significado |
|---|---|
| Documentado pelo fornecedor/case | A capacidade é anunciada; não foi executada nesta pesquisa |
| Não confirmado nas fontes | Não encontramos evidência suficiente; ausência permanece em aberto |
| Disponível e concluído | Uma auditoria futura comprova o resultado num perfil/versão/região |
| Disponível com limitação | Existe, mas cobertura, elegibilidade ou execução restringem o uso |
| Ausente no recorte auditado | A função não está disponível na conta e condições testadas, com confirmação adequada |

**Ausência de menção na descrição não é prova de ausência no produto.** Também não basta um botão visível: ele pode encaminhar para outro serviço ou depender de condições que impeçam a conclusão.

### 3.3 Matriz consolidada das capacidades

| Atividade | Capacidade | Estado documental | Fonte/base |
|---|---|---|---|
| Abastecimento | Visualizar nível de combustível | Documentado | Case, p. 33 |
| Abastecimento | Localizar/comparar postos e preços | Não confirmado | Não comprovado no material examinado |
| Abastecimento | Aplicar benefício específico vigente de combustível | Não confirmado | Catálogo completo de parceiros não recuperado |
| Abastecimento | Pagar e acompanhar abastecimentos | Não confirmado | Jornada transacional não comprovada |
| Estacionamento | Acessar descontos | Documentado na descrição oficial | Catálogo Apple da Localiza |
| Estacionamento | Encontrar opções por destino e cobertura | Não confirmado | Desconto não comprova busca contextual |
| Estacionamento | Consultar vagas/preços ou reservar | Não confirmado | Disponibilidade e transação não comprovadas |
| Estacionamento | Pagar, estender período e acompanhar utilização | Não confirmado | Operação completa não comprovada |
| Pedágio | Acessar descontos | Documentado na descrição oficial | Catálogo Apple da Localiza |
| Pedágio | Ativar/administrar tag e vínculo com veículo | Não confirmado | Parceria e gestão operacional não auditadas |
| Pedágio | Consultar passagens, extrato e cobranças | Não confirmado | Jornada específica não comprovada |
| Pedágio | Estimar custos por trajeto | Não confirmado | Planejamento não comprovado |
| Rotas | Consultar localização do carro | Documentado | Case, p. 33 |
| Rotas | Acompanhar km e limite contratado | Documentado | Case, p. 32 |
| Rotas | Planejar/navegar com trânsito e previsão de chegada | Não confirmado | Localização não comprova navegação |
| Rotas | Relacionar trajeto a custos/uso contratado/benefícios | Não confirmado | Coordenação contextual não comprovada |

Essa matriz registra **lacunas de comprovação**, que serão classificadas como lacunas funcionais somente após auditoria. Não é um levantamento autenticado de todas as funções da versão atual.

### 3.4 Abastecimento — da informação do tanque ao abastecimento realizado

**Trabalho do cliente:** decidir quando, onde e como abastecer com conveniência, custo compreensível e opção adequada.

| Etapa da atividade | Informação/resultado que pode importar | O que sabemos na Localiza |
|---|---|---|
| Perceber necessidade | Combustível disponível e contexto de uso | Nível de combustível documentado; cobertura por veículo a verificar |
| Escolher posto | Distância, horário, preço, combustível e confiança | Busca/comparação não confirmadas |
| Avaliar vantagem | Oferta aplicável e custo líquido | Benefício específico vigente não confirmado |
| Executar | Abastecer e pagar com pouca fricção | Pagamento via app não confirmado |
| Confirmar/acompanhar | Comprovante e histórico úteis | Histórico de abastecimento não confirmado |

**Lacuna possível:** o app informa o estado do carro, mas pode não participar da decisão ou conclusão do abastecimento. O estado final ainda precisa ser auditado.

Pontos que aprofundam o problema:

- O cliente consulta o nível pelo app ou olha o painel? O dado digital resolve uma situação específica?
- O combustível apresentado está atualizado e disponível naquele modelo? Um recurso anunciado pode ter cobertura variável.
- Onde o cliente já abastece e por quê: caminho, preço, confiança, benefício ou conveniência?
- Encontrar um posto mais barato gera economia depois do deslocamento e do tempo adicional?
- Uma vantagem da Localiza acumula com benefícios já usados ou exige trocar uma opção melhor?
- O responsável pelo pagamento é quem dirige e tem acesso ao benefício?

**Cadência:** abastecimento depende de consumo, deslocamento e veículo. Dirigir diariamente não significa abastecer diariamente. Não existe no material uma frequência média de abastecimento dos assinantes.

**Alternativa documentada:** Shell Box anuncia busca de postos participantes, pagamento pelo app e benefícios/pontos. Waze anuncia postos na rota e preços, com variação de disponibilidade. [A2, A4] Isso mostra que a necessidade possui alternativas; precisamos descobrir se o cliente as usa e qual dificuldade permanece.

**Evidência necessária para declarar uma lacuna relevante:** episódio recente, tentativa/alternativa, resultado insatisfatório ou esforço importante e capacidade ausente/limitada na conta auditada. Sem isso, temos uma função candidata, não uma dor validada.

### 3.5 Estacionamento — do destino à utilização encerrada

**Trabalho do cliente:** estacionar numa opção adequada ao destino, horário e orçamento, entendendo condições e resultado.

| Etapa da atividade | Informação/resultado que pode importar | O que sabemos na Localiza |
|---|---|---|
| Identificar opções | Localização, acesso e distância ao destino | Busca contextual não confirmada |
| Comparar | Horário, preço, regra e adequação | Comparação não confirmada |
| Garantir acesso, se aplicável | Disponibilidade ou reserva | Reserva/vaga em tempo real não confirmadas |
| Utilizar | Entrada, período, pagamento ou benefício | Descontos anunciados; execução não auditada |
| Encerrar | Saída, cobrança e comprovante | Acompanhamento transacional não confirmado |

**O recurso já anunciado é o desconto.** Precisamos descobrir a natureza desse benefício: estabelecimento, condição, forma de resgate, localização, vigência e eventual parceiro. Não sabemos se engloba estacionamento privado, rotativo público ou ambos.

Pontos que aprofundam o problema:

- Estaciona em garagem própria, vaga do trabalho, via pública ou estacionamento pago? Essas situações geram necessidades diferentes.
- A maior dificuldade é encontrar uma opção, pagar, entender o tempo permitido ou usar o desconto?
- O parceiro fica perto do destino ou exige desvio que elimina a vantagem?
- O benefício é fácil de aplicar no momento certo? A pessoa só descobre depois de pagar?
- Existe um serviço já contratado que elimina a necessidade de abrir qualquer app na entrada/saída?
- O preço anunciado é o preço que efetivamente paga naquela condição?

**Cadência:** pode ser alta para alguns trajetos urbanos e baixa para quem utiliza garagem fixa ou estacionamento incluído. Frequência deve ser medida por rotina, sem assumir que toda a base estaciona em locais pagos.

**Alternativas documentadas:** Waze anuncia busca de estacionamentos perto do destino; Sem Parar anuncia locais de uso em estacionamentos e extrato da tag. [A2, A3] Isso não comprova vagas reais, reserva ou cobertura para um cliente específico.

**Lacuna possível:** a pessoa conhece uma vantagem, mas não consegue relacioná-la ao destino ou concluí-la com conveniência. A ausência de uma função de busca pode importar; a baixa cobertura do benefício também pode ser a causa. São problemas distintos.

### 3.6 Pedágio — da passagem ao entendimento da cobrança

**Trabalho do cliente:** passar pelo pedágio com conveniência e compreender custos, condições e cobrança.

| Etapa da atividade | Informação/resultado que pode importar | O que sabemos na Localiza |
|---|---|---|
| Planejar | Praças/tarifas e custo do trajeto | Estimativa de pedágio não confirmada |
| Preparar meio de passagem | Tag/vínculo/elegibilidade | Desconto anunciado; natureza e operação não auditadas |
| Passar | Cobrança/pagamento aplicável | Execução integrada não confirmada |
| Conferir | Passagem, valor e responsável | Extrato específico não confirmado |
| Ajustar vínculo | Troca de veículo, retirada ou encerramento | Jornada de tag não confirmada |

Não sabemos se o desconto anunciado se refere a tarifa, contratação de parceiro, mensalidade de serviço ou outra condição. **Não devemos transformar a frase comercial em promessa de desconto sobre toda passagem.**

Pontos que aprofundam o problema:

- Usa estrada com pedágio na rotina ou somente em viagens?
- Já tem tag? Quem contratou, paga e administra o vínculo com o veículo?
- Qual parte dá trabalho: preparação, pagamento, conferência ou entendimento da condição?
- A passagem automática já resolve o problema sem abrir app?
- Existem cobranças em sistemas de pedágio eletrônico que exigem uma consulta específica? Como a pessoa acompanha hoje?
- Quando troca ou devolve o veículo, quais responsabilidades precisa administrar? As regras reais dependem do contrato e do fornecedor.

**Cadência:** pode ser cotidiana para um trajeto rodoviário e eventual para outro cliente. Mesmo pedágio diário pode produzir poucas aberturas se a tag funcionar automaticamente.

**Alternativas documentadas:** Sem Parar anuncia extrato da tag e cobrança de pedágio eletrônico; Waze anuncia evitar rotas pedagiadas e consultar tarifas com antecedência, com restrições de disponibilidade. [A2, A3]

**Lacuna possível:** não conseguir compreender ou administrar uma condição pertinente ao veículo/assinatura. Simplesmente adicionar uma consulta já resolvida pelo fornecedor da tag pode ter pouco valor. Precisamos avaliar a dificuldade restante.

### 3.7 Rotas — da intenção de chegar ao destino à decisão de trajeto

**Trabalho do cliente:** chegar ao destino com previsibilidade, escolhendo uma opção adequada ao tempo, custo e condições.

| Etapa da atividade | Informação/resultado que pode importar | O que sabemos na Localiza |
|---|---|---|
| Definir destino/horário | Objetivo do deslocamento | Planejamento de destino não confirmado |
| Comparar caminhos | Tempo, distância, trânsito e pedágio | Navegação/comparação não confirmadas |
| Considerar condições do carro | Uso contratado e informação disponível | Km e localização documentados; relação com um trajeto não confirmada |
| Seguir percurso | Orientação e atualização do caminho | Navegação passo a passo não confirmada |
| Avaliar resultado | Tempo/custo/uso relevante | Jornada contextual completa não confirmada |

**Localização do carro não equivale a navegação. Gestão de km não equivale a previsão de impacto de uma rota no contrato.** O case documenta as primeiras capacidades, sem comprovar as segundas.

Pontos que aprofundam o problema:

- O cliente já conhece o caminho e quer apenas trânsito, ou precisa de orientação completa?
- Qual aplicativo consulta antes de sair? Qual se tornou a alternativa habitual?
- A dificuldade está no caminho ou numa condição de mobilidade que o navegador não conhece?
- Tempo de chegada, distância ou custo pesam mais naquela situação?
- Existe dúvida sobre como um deslocamento se relaciona ao uso contratado? Com que frequência?
- A informação precisa aparecer no celular ou na interface que a pessoa já usa no carro?

**Cadência:** conhecer o caminho não elimina interesse em trânsito, mas também não prova necessidade de consulta. Precisamos observar a rotina real, evitando assumir navegação diária de toda a base.

**Alternativas documentadas:** Waze e Google Maps anunciam navegação, trânsito e recálculo de trajetos. Waze anuncia planejamento por horário, tarifas de pedágio, postos e estacionamentos. A disponibilidade varia por região/recurso. [A2, A5]

**Lacuna possível:** informação relevante da assinatura permanece separada de uma decisão de deslocamento. Isso é diferente de ausência de um navegador próprio. Precisamos demonstrar qual dúvida ou esforço a separação produz antes de definir o conceito.

### 3.8 O que as alternativas mostram — e o que não mostram

| Alternativa | Capacidades anunciadas relevantes | Pergunta para o assinante |
|---|---|---|
| Shell Box | Postos participantes, pagamento e benefícios | O que ainda dá trabalho mesmo usando essa opção? |
| Sem Parar | Tag, extrato, locais de uso e pedágio eletrônico | Qual parte da relação com seu carro/contrato continua separada? |
| Waze | Rotas, trânsito, pedágios, postos e estacionamento | Que necessidade sua não é atendida por essa jornada? |
| Google Maps | Navegação, trânsito, lugares e mapas off-line | Há algum esforço que o serviço atual deixa para você? |

Fontes: descrições dos respectivos fornecedores nas lojas, consultadas nesta etapa. [A2–A5] Não testamos as funções nem comprovamos disponibilidade no território, adesão ou preferência dos clientes Localiza.

O benchmark ajuda a avaliar **redundância e dificuldade restante**. Não prova que a Localiza deva reproduzir essas capacidades. Promoções das alternativas, números de usuários e alegações comerciais de economia não são usados como previsão de resultado.

### 3.9 Limite específico do catálogo de benefícios

A página oficial do Clube mostra categorias e afirma acesso via app. Os cartões de parceiros são carregados dinamicamente. Nesta pesquisa, o HTML recebido não continha o catálogo resolvido; a fonte pública de dados indicada pela própria página respondeu **HTTP 406**. [L2]

Assim, não foi possível verificar todos os parceiros, benefícios vigentes, regiões ou regulamentos. A descrição oficial do app confirma que descontos de estacionamento/pedágio são anunciados, mas não confirma as condições de cada oferta.

Esse limite é relevante: não podemos declarar ausência de benefício de combustível nem prometer uma parceria específica com base numa coleta incompleta.

### 3.10 Como auditar ausência no produto atual

Auditar uma atividade por vez, começando pelo resultado que o cliente deseja. Registrar:

| Campo | Por que precisa constar |
|---|---|
| Data, versão e sistema operacional | A disponibilidade pode mudar entre versões/plataformas |
| Tipo de usuário e papel | Titular e condutor podem ter acessos diferentes |
| Contrato e veículo pertinentes | Recursos podem depender de elegibilidade e conectividade |
| Cidade/território | Cobertura de parceiros e informação local pode variar |
| Caminho de descoberta | Existir não significa ser fácil de encontrar |
| Informação, regra e atualização | A decisão depende de clareza e confiabilidade |
| Etapas externas | Encaminhar para parceiro não equivale a conclusão dentro do app |
| Resultado alcançado | Desconto aplicado, serviço utilizado ou informação compreendida |
| Motivo da limitação | Ausência, cobertura, acesso, compreensão ou execução |

Testar busca por termos, navegação pelos menus, catálogo/regulamentos e eventual encaminhamento. Conferir com produto se o resultado é restrição do perfil ou ausência efetiva. Não generalizar o comportamento de uma conta para toda a base.

**Resultado esperado da auditoria:** uma lista de capacidades comprovadas e limitações por recorte, acompanhada de evidência. A lista final de funções ausentes ainda não pode ser fechada nesta pesquisa documental.

### 3.11 Resposta provisória ao segundo subproblema

**Já documentado:** nível de combustível, localização do veículo, gestão de km e descontos anunciados de estacionamento/pedágio.

**Não comprovado:** busca/comparação e pagamento de abastecimento; busca/reserva/pagamento de estacionamento; gestão de tag/extrato de pedágio; navegação e planejamento de rotas; coordenação dessas atividades com contexto, contrato e benefícios.

A conclusão correta é que **há capacidades e jornadas a verificar**, não que todas essas funções estejam definitivamente ausentes. A importância de cada possível lacuna depende da dificuldade real, da elegibilidade e da alternativa já utilizada.

## 4. Como os dois subproblemas se relacionam

### 4.1 Atividade frequente não garante interação frequente

| Situação ilustrativa | Por que pode gerar poucos acessos |
|---|---|
| Dirige diariamente num caminho conhecido | Pode não precisar consultar uma rota em todos os deslocamentos |
| Abastece quando necessário e já tem posto de preferência | A decisão pode estar resolvida sem nova pesquisa |
| Estaciona na vaga fixa do trabalho | Busca/reserva de vaga pode não ser pertinente |
| Passa em pedágio com cobrança automática | O serviço funciona sem abrir o app a cada passagem |

São exemplos analíticos, não personas ou achados de entrevistas. Eles mostram por que o potencial de uso precisa ser estimado por episódio elegível e tarefa.

### 4.2 Quatro tipos de lacuna com efeitos diferentes

| Tipo de lacuna | Diagnóstico | Relação possível com recorrência |
|---|---|---|
| Funcional | Não existe capacidade para uma necessidade mal atendida | Cliente precisa resolver fora, se houver alternativa |
| Descoberta | A capacidade existe, mas não é conhecida/lembrada | Uso potencial não se materializa |
| Adequação | Existe, mas contexto/condição/cobertura não atende | Conhecimento não se transforma em utilização |
| Execução | O cliente tenta, mas não chega ao resultado | Pode gerar abandono ou acessos repetidos |

Esses mecanismos não autorizam a mesma conclusão. Uma lacuna de descoberta não comprova necessidade de nova função. Uma alternativa externa satisfatória também não comprova uma lacuna relevante para o cliente.

### 4.3 Formulação aprofundada do problema

> **A rotina de dirigir cria oportunidades potenciais de utilidade, mas o app é associado principalmente à gestão pontual da assinatura. Precisamos descobrir em quais episódios existe uma necessidade importante, se a capacidade está disponível e por que ela não se transforma em resultado reconhecido pelo cliente.**

Essa formulação conecta frequência e funcionalidades sem assumir que centralização, mais conteúdo ou abertura diária sejam a resposta.

## 5. Plano de validação exclusivo destes dois subproblemas

### 5.1 Dados a solicitar à Localiza

| Dado | Pergunta respondida |
|---|---|
| Definição de acesso e base da distribuição | O que 36% e 17% representam exatamente? |
| Distribuição mensal da mesma base por 3–6 meses | As faixas são estáveis ou refletem fases/eventos? |
| Entradas, jornadas, conclusão, erros e duração | O cliente retorna por utilidade ou esforço? |
| Descoberta e uso confirmado de benefícios | Falta conhecimento, adequação ou execução? |
| Elegibilidade por veículo/contrato/região | A capacidade anunciada atende quem? |
| Papel do usuário, tempo de contrato e intensidade de uso | Oportunidades são comparáveis entre grupos? |
| Catálogo atual de funções/parceiros e regras | Quais ausências e limitações são efetivas? |
| Preferência/alternativa e esforço por atividade | O que já está resolvido fora do app? |

Priorizar dados agregados. Relacionar eventos do mesmo episódio somente com acesso autorizado e identificadores necessários. Não coletar trajetos contínuos apenas para investigar se uma atividade é relevante; relatos e dados adequados ao objetivo podem bastar.

### 5.2 Recrutamento para pesquisa qualitativa

Uma primeira rodada de aproximadamente **12–18 assinantes**, se houver disponibilidade, pode revelar mecanismos. É uma proposta de investigação, não uma amostra capaz de estimar a prevalência das causas.

Incluir clientes das faixas 1–2, 3–10 e 11+, com diferentes papéis, cidades, idades e habilidades. Selecionar também rotinas expostas e pouco expostas a estacionamento pago/pedágio. Registrar uso de alternativas e fase do contrato.

Faixa de acesso só é critério confiável se confirmada nos dados. Autodeclaração aproximada deve ser identificada como tal. Pessoas sem assinatura podem ajudar a entender o enunciado, mas não substituem os clientes na validação desses percentuais.

### 5.3 Perguntas sobre frequência e valor

1. Conte seus últimos usos do app: qual era o objetivo de cada um?
2. O que conseguiu concluir? Precisou voltar para o mesmo assunto?
3. Quando não usa, existe algo que gostaria de resolver e não consegue?
4. Quais recursos conhece sem que eu mostre uma lista?
5. Na última vez que usou um benefício, como descobriu, aplicou e confirmou?
6. O que esperava deixar de administrar quando assinou?
7. Que atividades relacionadas ao carro já resolve bem de outra forma?
8. Qual foi a última situação em que o app poupou trabalho? E em que acrescentou trabalho?
9. Seu padrão de uso mudou em algum período? O que aconteceu naquele momento?

Evitar “por que você não se engaja?”: a pergunta pressupõe que o comportamento está errado. Buscar sequência, resultado e consequência.

### 5.4 Perguntas específicas das quatro atividades

| Atividade | Perguntas de aprofundamento |
|---|---|
| Abastecimento | Onde foi o último abastecimento? Como escolheu? Qual benefício utilizou? Qual etapa tomou esforço? Consultou o nível pelo app? |
| Estacionamento | Onde estacionou no último destino pago? Como encontrou e pagou? Conhecia uma vantagem Localiza aplicável? Por que usou ou deixou de usar? |
| Pedágio | Quando foi a última passagem? Como pagou e conferiu? Quem administra a tag? Qual condição gerou dúvida ou trabalho? |
| Rotas | No último deslocamento que exigiu consulta, o que precisava saber? Qual alternativa abriu? O que continuou faltando? |

Perguntar por episódios recentes antes de sugerir capacidades. A resposta “seria legal ter” não demonstra problema, frequência ou disposição de uso.

### 5.5 Observação e registro

Para um episódio, registrar: objetivo, situação, alternativa, recurso encontrado, primeira barreira, fatores secundários, tempo/esforço, resultado, valor percebido e evidência.

Observar tarefas como localizar um benefício aplicável, compreender suas regras e verificar a forma de utilização; ou encontrar uma informação do veículo e explicar qual decisão ela permite. Quando houver etapa externa, acompanhar sua conclusão possível sem tratar um clique como resultado final.

Não confundir falha do recurso com indisponibilidade do parceiro ou ausência de elegibilidade. Registrar também casos de sucesso, para entender por que a mesma capacidade funciona em determinado contexto.

### 5.6 Critérios para confirmar uma dor prioritária

| Critério | Evidência desejada |
|---|---|
| Necessidade real | Episódio concreto, sem depender da sugestão do pesquisador |
| Recorrência | Repetição na cadência da rotina, não apenas curiosidade inicial |
| Impacto | Esforço, custo, incerteza ou perda de conveniência demonstrados |
| Alternativa insuficiente | Dificuldade permanece depois da forma atual de resolver |
| Lacuna identificada | Ausência/descoberta/adequação/execução comprovada no recorte |
| Alcance | Público elegível descrito; prevalência medida ou reconhecida como lacuna |
| Capacidade de atuação | Dependências de produto, dados e parceiros compreendidas |

Priorizar a coleta que mais reduz incerteza: definição das métricas; motivos e resultados por faixa; inventário autenticado; elegibilidade e utilidade das quatro atividades. O princípio de Pareto orienta foco, sem afirmar uma distribuição 80/20 que não foi medida. [M1, p. 26–28]

Se o cliente está satisfeito com pouco uso, registrar sucesso. Se a alternativa externa atende bem, reconhecer esse limite. Se uma vantagem existe, mas não serve ao território, classificar adequação/cobertura. Se 11+ significa repetir tentativas, rever o rótulo de engajamento útil.

## 6. Síntese para compartilhar com o grupo

### Subproblema 1 — resposta fundamentada

> “Os 36% com 1–2 acessos são compatíveis com a natureza episódica das funções de gestão da assinatura. O case aponta pouca relevância contextual fora dessas tarefas, mas ainda precisamos distinguir uso eficiente, desconhecimento, inadequação, alternativas e barreiras. Os 17% com alta frequência também precisam ser avaliados por conclusão e valor, porque retorno pode representar utilidade ou repetição.”

### Subproblema 2 — resposta fundamentada

> “O app já apresenta nível de combustível, localização, gestão de km e descontos anunciados de estacionamento/pedágio. Não conseguimos comprovar jornadas completas de abastecimento, estacionamento, gestão de tag ou navegação. Para declarar ausência, precisamos auditar o app por perfil, versão, veículo e região; para justificar relevância, precisamos identificar a dificuldade que permanece na rotina do cliente.”

### Formulação provisória da dor

> “Quando preciso tomar uma decisão cotidiana de mobilidade, posso não reconhecer o app da assinatura como uma opção útil ou não encontrar uma capacidade aplicável que facilite chegar ao resultado.”

Essa frase sintetiza uma hipótese do time; não é uma fala coletada de cliente.

O próximo marco da pesquisa é identificar **qual público, em qual atividade, enfrenta qual barreira, com qual consequência e usando qual alternativa hoje**. Esse recorte sustentará a etapa do conceito.

## 7. Fontes e limites

### Materiais do repositório

- **[C1]** [Cases Meoo Ruptura — apresentação](<../../../Cases Meoo Ruptura ApresentaÃ§Ã£o CD.pdf>): p. 5–6, público; p. 17, pesquisa de leads/clientes RAC; p. 19–22, desafio; p. 24–36, app; p. 25, indicadores; p. 28, benefícios; p. 32–33, km/telemetria. Números e descrição atribuídos ao material, sem auditoria interna. Páginas de indicadores já foram também inspecionadas visualmente na investigação.
- **[M1]** [Ideação e Validação de problemas — Ruptura](<../../../Ideacao e Validacao de problemas - Ruptura(1).pdf>): p. 11–12, etapas; p. 16–17, SCQ; p. 20–22, árvores/MECE; p. 26–28, priorização; p. 33–36, síntese.
- **[M2]** [Aula o Problema](<../../../Aula o Problema.key.pdf>): p. 4, público/origem/impacto; p. 6, experiências dos usuários; p. 7, coleta, análise e validação.

### Fontes consultadas novamente ou adicionadas nesta atualização

- **[L2]** [Clube de Benefícios Localiza Assinatura](https://assinatura.localiza.com/clube-de-beneficios): página consultada em 02/10/2026. Categorias e acesso via app documentados; catálogo dinâmico não resolvido no HTML. A [fonte pública referenciada pela página](https://caohee.com.br/meoo/wp-json/acf/v3/pages/16) respondeu HTTP 406. Não comprovamos parceiros/regulamentos individuais.
- **[L3]** [Descrição oficial Localiza Assinatura — catálogo Apple Brasil](https://itunes.apple.com/lookup?id=1528537131&country=br) e [ficha do app](https://apps.apple.com/br/app/localiza-assinatura-meoo/id1528537131): consulta em 02/10/2026; versão 5.2.0. A descrição anuncia descontos em pedágios/estacionamentos e funções administrativas. Declaração do fornecedor, sem teste autenticado.
- **[A2]** [Waze — ficha brasileira](https://apps.apple.com/br/app/id323229106): descrição do fornecedor obtida no catálogo Apple em 02/10/2026. Rotas, trânsito, pedágios, postos, estacionamento e CarPlay anunciados; condições variam por recurso/território. Não comprova adesão dos assinantes Localiza.
- **[A3]** [Sem Parar — ficha brasileira](https://apps.apple.com/br/app/id1440651231): descrição do fornecedor consultada em 02/10/2026; tag, extrato e locais de uso anunciados. Não auditamos cobertura, condições ou execução.
- **[A4]** [Shell Box — ficha brasileira](https://apps.apple.com/br/app/id1037433060): descrição da Raízen obtida no catálogo Apple em 02/10/2026; postos participantes, pagamento e benefícios anunciados. Não auditamos condições nem usamos promoções para estimar resultado.
- **[A5]** [Google Maps — ficha brasileira](https://apps.apple.com/br/app/id585027354): descrição da Google consultada em 02/10/2026; navegação, trânsito e mapas off-line anunciados. Disponibilidade varia por cidade/país/recurso.

### Fontes reaproveitadas da pesquisa anterior

Estas referências foram registradas na investigação de 02/10/2026 e não foram recolhidas novamente nesta atualização:

- **[L1]** [Site oficial Localiza Assinatura](https://assinatura.localiza.com/): promessa comercial de comodidade e serviços; não caracteriza independentemente a motivação dos clientes.
- **[B1]** [Cetic.br — TIC Domicílios 2025, C2A](https://cetic.br/pt/tics/domicilios/2025/individuos/C2A/): acesso à internet por população/faixa. Dados nacionais, não da Localiza.
- **[B3]** [Cetic.br — TIC Domicílios 2025, I1A](https://cetic.br/pt/tics/domicilios/2025/individuos/I1A/): atividades/habilidades declaradas entre usuários de internet. Não é teste de capacidade individual.
- **[A1]** [W3C/WAI — Older Users and Web Accessibility](https://www.w3.org/WAI/older-users/): acessibilidade e diversidade de necessidades, sem presumir deficiência por idade.
- **[F1]** [Fogg Behavior Model](https://www.behaviormodel.org/): lente conceitual de motivação, capacidade/facilidade e estímulo; não valida comportamento ou recorrência na base Localiza.
- **[R1]** [App Store brasileira — avaliações Localiza Assinatura](https://itunes.apple.com/br/rss/customerreviews/id=1528537131/sortBy=mostRecent/json): recorte anterior de 50 relatos entre 11/05/2025 e 18/09/2026. Sinais exploratórios; não representativos, sem idade/renda ou reprodução de falhas.
- **[H1]** [Evidências e limites da pesquisa anterior](https://github.com/Eduardo-Klausing/breaking-time-ruptura-2026/blob/04abccdeaedf6fa733b6c34e67df71a9018c13b1/pesquisa/case-2/04-evidencias-e-fontes/README.md) e [registro de coleta](https://github.com/Eduardo-Klausing/breaking-time-ruptura-2026/blob/04abccdeaedf6fa733b6c34e67df71a9018c13b1/pesquisa/case-2/04-evidencias-e-fontes/REGISTRO-DE-COLETA.json): rastreabilidade do recorte reaproveitado.

**Limites finais:** este documento não determina a contribuição de cada causa para os percentuais, não identifica demografia da base ativa, não comprova todas as ausências do produto e não valida demanda por uma nova função. Entrega um diagnóstico documental aprofundado e uma investigação verificável para fechar essas lacunas.
