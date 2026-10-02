# Pesquisa e recomendação — case 2, Ruptura 2026

Data de consulta: **02/10/2026**. Referências identificadas por códigos entre colchetes estão detalhadas em [Evidências e fontes](../04-evidencias-e-fontes/README.md).

## A tese para o grupo

**O app já tem adoção relevante. A oportunidade é fazer o cliente perceber a Localiza como alguém que cuida da sua mobilidade nos momentos certos, incluindo quando não há um problema.**

Não começaria o pitch com “vamos construir um superapp”. Começaria com esta pergunta: **qual trabalho o cliente ainda precisa fazer sozinho, apesar de ter contratado uma assinatura que promete tranquilidade?**

O diagnóstico aponta duas frentes complementares: diminuir esforço e incerteza nas jornadas existentes; criar utilidade recorrente ligada à rotina real. A primeira sustenta confiança. A segunda amplia a relevância. Uma interface acolhedora ajuda, mas não substitui informações corretas, uma oficina disponível ou um atendimento que assume responsabilidade.

Essa é uma recomendação fundamentada em pesquisa documental e exploratória, ainda sujeita a validação com assinantes e dados internos.

## 1. Definir: o que o case efetivamente diz

### 1.1 A premissa “as pessoas não usam o app” precisa ser corrigida

| Informação do material | Interpretação útil | Limite da interpretação |
|---|---|---|
| 80,1% acessam no mês; 53 mil MAU | A adoção mensal já é elevada | Não informa conclusão de tarefas ou valor percebido |
| 31 mil WAU | Há uma base relevante de uso semanal | Não conhecemos semana de referência ou distribuição por cliente |
| 36% dos usuários ativos têm 1–2 acessos mensais | Parte da base usa de forma pontual | Dois acessos podem bastar para resolver tudo de que a pessoa precisa |
| 17% têm 11 ou mais acessos mensais | Há um grupo com alta frequência | Pode ser valor recorrente, gestão de vários veículos ou dificuldade/repetição |
| NPS do app 84 | O app é bem avaliado na pesquisa apresentada | Não equivale à satisfação com a assinatura inteira |
| NPS relacional aproximadamente 45 | Há espaço para melhorar a relação global | Não prova que frequência baixa causou esse resultado |
| Mais de 80 mil contatos/mês; 75% chat, 25% telefone | Existe carga operacional relevante | Não sabemos clientes únicos, motivos, recontatos ou tentativa prévia no app |
| Aproximadamente 48% renovam ao fim do contrato | Renovação é um resultado de negócio importante | Precisamos da base elegível e dos motivos de não renovação |
| Apenas 7% indicam alguém | Há espaço para investigar indicação | Não sabemos período, denominador ou conversão das indicações |

Fonte: [C1], páginas físicas 19, 21 e 25. A página 25 classifica o grupo como **1–2 acessos**, enquanto o texto da página 21 diz “menos de 2x”; nesta análise prevalece a tabela explícita.

O material também traz NPS do produto de 85 na página 5 e NPS relacional de aproximadamente 45 nas páginas do case 2. É preciso pedir a definição, período e população de cada indicador antes de compará-los. NPS é normalmente reportado em pontos de -100 a +100, embora os slides usem o símbolo de porcentagem em alguns locais.

Os aproximadamente 70 mil carros ativos não são necessariamente 70 mil pessoas. O número de 53 mil MAU também não corresponde exatamente a 80,1% de 70 mil. Não force equivalência entre frota, contratos, clientes e usuários: peça os denominadores.

### 1.2 SCQ: situação, complicação e pergunta central

**Situação:** a Localiza Assinatura oferece um carro e diversos serviços incluídos; seu app permite gerenciar contrato, pagamentos, serviços, quilometragem, multas, benefícios e recursos de telemetria.

**Complicação:** o uso se concentra em resolver necessidades pontuais. O case afirma que benefícios nem sempre se conectam ao contexto do cliente, enquanto atendimento, renovação e indicação apresentam oportunidades. Ao mesmo tempo, aumentar acessos sem valor claro não atende ao desafio.

**Core Question:** como aumentar a utilidade percebida do app nos momentos recorrentes da mobilidade, com menos esforço e mais confiança, de modo a fortalecer a relação com a Localiza e produzir impacto mensurável?

Essa formulação permite investigar um superapp, uma experiência contextual, uma mudança operacional ou uma combinação. Ela não escolhe a tecnologia antes de entender o problema.

### 1.3 TOSCA e estado atual/desejado

O PDF cita TOSCA e R1/R2, mas detalha principalmente SCQ e árvores lógicas. A aplicação abaixo é uma estrutura de trabalho, não uma reprodução de uma explicação que não está no material. [M1]

| Elemento | Aplicação |
|---|---|
| Trouble — dificuldade | Valor episódico, possíveis falhas de jornada e benefícios pouco contextualizados |
| Owner — responsável | Time do produto digital junto com operação e experiência da assinatura |
| Success — sucesso | Mais episódios de valor concluídos, menor esforço e melhora da confiança; efeito comercial acompanhado |
| Constraints — restrições | App existente, integrações, contratos, rede de parceiros, qualidade da telemetria e prazo do hackathon |
| Actors — envolvidos | Assinantes, condutores autorizados, atendimento, oficinas, parceiros, produto, dados e operação |

**R1, atual:** o cliente procura a Localiza quando precisa resolver algo. **R2, desejado:** reconhece a Localiza como apoio confiável para a rotina, porque recebe ajuda útil e consegue concluir suas ações com clareza.

## 2. Público-alvo: quem estamos atendendo

### 2.1 Assinatura não é todo o ecossistema Localiza

O case identifica **pessoas físicas, microempresas e PMEs**. O site distingue assinatura para uso prolongado, aluguel para necessidades temporárias, gestão de frotas e Zarp para motoristas de aplicativo. Não monte a proposta supondo que todos sejam turistas ou motoristas de Uber. [C1, L1]

A promessa comercial recorrente é previsibilidade e comodidade: carro zero, menos burocracia e menos preocupações com documentação, manutenção e revenda. Os depoimentos selecionados pela própria empresa mencionam tempo, família, orçamento e capital disponível. São úteis para entender o posicionamento; não são uma amostra independente de satisfação. [L1]

Uma consequência importante: **o assinante pode ter contratado justamente para pensar menos no carro**. Criar um painel que exija acompanhamento diário pode contrariar essa motivação.

### 2.2 O que sabemos sobre idade e renda

Na página 17, o material apresenta uma pesquisa de julho de 2026 com **671 leads não convertidos e clientes RAC**, enviada por WhatsApp: 60% dos respondentes têm 45 anos ou mais; 50% têm renda familiar acima de R$ 10 mil; 28% assinam carro; 5% já possuem híbrido ou elétrico. [C1]

Isso é uma referência sobre o mercado potencial investigado no case 1. **Não é a distribuição etária ou de renda da base ativa do case 2.** Não permite dizer “60% dos assinantes têm mais de 45 anos”, nem definir a persona média do aplicativo.

Para o case 2, faltam cruzamentos de idade × frequência × motivo de uso × tarefa concluída × contatos × tempo de contrato. Também faltam escolaridade, acessibilidade, aparelho e papel da pessoa na conta.

### 2.3 Segmentação comportamental recomendada

Estas são **hipóteses para recrutamento e escolha de MVP**, não segmentos com tamanho medido:

| Segmento | Trabalho que quer realizar | O que tende a gerar valor | O que precisa ser validado |
|---|---|---|---|
| Pessoa que delega a burocracia | “Quero dirigir sem ter que administrar o carro” | Próxima ação clara, revisão coordenada, status e continuidade | Se prefere proatividade ou somente autonomia sob demanda |
| Pessoa que busca controle financeiro | “Quero saber o que vou pagar e evitar surpresas” | Explicação de cobranças, projeção de uso e regras claras | Se a preocupação principal é franquia, preço ou transparência |
| Família com rotina intensa | “Preciso que o carro funcione para escola, trabalho e viagem” | Preparação de viagem e serviços compatíveis com horários | Quem conduz, decide, paga e recebe os avisos |
| Profissional/autônomo ou pequena empresa | “Não posso perder trabalho com o carro parado” | Previsibilidade de manutenção e gestão de pendências | Se precisa de múltiplos veículos, comprovantes e permissões |
| Cliente com baixa confiança digital | “Quero resolver sem errar nem ficar preso” | Linguagem simples, confirmação e apoio humano disponível | Se a causa é habilidade, experiência anterior ou risco da tarefa |
| Cliente de elétrico/híbrido conectado | “Quero usar a tecnologia sem ter que decifrá-la” | Contexto de bateria/recarga e orientação compatível com o veículo | Cobertura dos dados e frequência da necessidade |

As categorias podem se sobrepor. Elas não são uma árvore MECE; são lentes de pesquisa. Uma pessoa pode valorizar família, controle financeiro e delegação ao mesmo tempo.

**Recorte inicial sugerido:** assinantes PF que já usam o app, usam o carro na rotina e querem reduzir esforço; dentro desse grupo, comparar pessoas de 25–44, 45–59 e 60+ com diferentes níveis de familiaridade digital. É uma escolha de foco para validação, não a afirmação de que esse é o maior segmento.

## 3. Idade: como considerar sem transformar em estereótipo

### 3.1 Evidência brasileira

A TIC Domicílios 2025 permite separar acesso à internet, comunicação e atividades digitais específicas. [B1–B3]

| Faixa da pesquisa | Usuários de internet, indicador ampliado — população da faixa | Mensagens instantâneas — usuários de internet da faixa | Declararam instalar programas/apps — usuários de internet da faixa |
|---|---:|---:|---:|
| 16–24 | 98% | 95% | 48% |
| 25–34 | 98% | 97% | 49% |
| 35–44 | 96% | 95% | 42% |
| 45–59 | 90% | 95% | 29% |
| 60+ | 59% | 83% | 12% |

Os denominadores das colunas são diferentes. A pesquisa abrange domicílios e indivíduos de 10 anos ou mais no Brasil, não clientes da Localiza. “Não declarou realizar uma atividade” não significa “é incapaz de fazê-la”; esses indicadores não são testes de competência. As diferenças são descritivas, não explicações causais para o uso do app.

A interpretação mais útil é: **familiaridade com conversar digitalmente não garante familiaridade com cada operação digital**. E estar conectado não garante achar uma jornada fácil, segura ou vantajosa.

### 3.2 Hipóteses por faixa para investigar

| Recorte de recrutamento | Hipóteses que vale testar | Consequência de projeto se confirmadas |
|---|---|---|
| 18–24 | Comparação com experiências digitais rápidas; possível decisão ou pagamento compartilhados | Fluxos diretos, permissões por papel e explicação de contratos; não assumir que são compradores autônomos |
| 25–34 | Rotina profissional, decisões financeiras e possível família em formação | Economia de tempo e previsibilidade; não reduzir a proposta a cashback |
| 35–44 | Múltiplas responsabilidades e uso do carro por mais de uma pessoa | Coordenação da rotina, calendário e próximo passo acessível |
| 45–59 | Desejo de conveniência, domínio de canais familiares e expectativa de qualidade do serviço | App que poupa trabalho, transparência e continuidade com atendimento |
| 60+ | Grande diversidade de habilidade; possíveis necessidades visuais, motoras ou de memória | Texto ajustável, contraste, alvos adequados, menos passos e confirmação clara |

Essas hipóteses não são resultados de entrevistas. Os dados brasileiros usam 16–24; o recrutamento usa 18–24 para focar participantes adultos.

Uma pessoa de 65 anos pode preferir autoatendimento, e uma de 25 pode pedir ajuda quando há risco financeiro. **Tipo de tarefa, urgência, confiança e experiência anterior provavelmente explicam mais do que idade isolada; isso precisa ser testado.**

A W3C recomenda atender necessidades de usuários mais velhos com padrões de acessibilidade existentes. Aplicar acessibilidade a todos é melhor do que criar um “modo idoso” sem demanda demonstrada. Não se deve inferir deficiência a partir da idade. [A1]

### 3.3 Como analisar idade corretamente

Colete idade em faixas, nível de conforto com tarefas digitais, escolaridade quando pertinente, papel no contrato, aparelho, problemas anteriores e urgência da tarefa. Compare pessoas de idades diferentes com rotinas semelhantes e pessoas da mesma idade com habilidades diferentes.

Com 12–18 entrevistas, vocês podem encontrar mecanismos e melhorar perguntas. Não conseguem estimar a prevalência de preferências por idade. Para isso, usem pesquisa quantitativa e dados internos com amostra e denominadores definidos.

## 4. Questões culturais e contexto brasileiro

### 4.1 Conversar é um hábito digital forte

Em 2025, 92% dos usuários de internet declararam usar mensagens instantâneas; 59% enviaram/receberam e-mails. Na faixa 45–59, as proporções são 95% e 59%; na de 60+, 83% e 40%. [B2]

Isso apoia investigar **interfaces e canais familiares de conversa**. Não demonstra preferência pelo WhatsApp especificamente, por atendimento de empresas ou por humanos: mensagens também podem ser trocadas com automações. O “chat” que representa 75% dos contatos do case também não está identificado como WhatsApp.

Uma ponte entre uma mensagem relevante e a ação no app pode facilitar adoção. Mas se a ponte gera novo login, menus genéricos e repetição de dados, ela apenas acrescenta esforço.

### 4.2 Relação pessoal, responsabilidade e interpretação

É plausível que alguns clientes vejam o atendente como alguém que interpreta o caso e assume responsabilidade: “essa cobrança se aplica a mim?”, “está realmente confirmado?”, “alguém vai me ajudar se der errado?”. Estudos de UX encontram busca por confirmação, informação ausente e percepção de complexidade como motivos para contato. [U1, U2]

Trate essa explicação como hipótese situacional, não como “o brasileiro gosta de falar com gente”. Relatos locais incluem tanto elogios ao atendimento quanto elogios à autonomia digital. [R1, R2]

A tradução para produto é **identificar quem responde pela solicitação, dar prazo verificável e preservar histórico**. Colocar um nome humano num robô sem poder de resolução não entrega essa responsabilidade.

### 4.3 O carro pode significar mais do que transporte

Propriedade, independência, status, segurança e cuidado com a família são dimensões possíveis da relação com o carro. Para alguns, assinatura é liberdade da burocracia; para outros, pode envolver receio de restrições, franquia, avarias e cobrança ao devolver.

Não há nesta pesquisa evidência quantitativa da prevalência dessas motivações entre assinantes. Perguntem quais significados aparecem espontaneamente. O site usa mensagens de tranquilidade, personalização e “carro do seu jeito”, mostrando que a marca trabalha essas dimensões em seu posicionamento. [L1]

### 4.4 Família, empresa e papel de cada pessoa

Quem assina, paga, dirige e cuida da manutenção pode ser diferente. Uma conta individual não necessariamente representa uma rotina individual. Investiguem compartilhamento autorizado de informações, recebimento de alertas, decisões sobre revisão e indicação do condutor.

Evitem assumir que o titular é sempre homem, que mulheres dirigem menos ou que familiares podem acompanhar localização sem autorização. Diferenças observadas devem ser interpretadas pelo papel na rotina e pelas necessidades, não usadas como estereótipos.

### 4.5 Região, infraestrutura e renda

O benefício disponível numa capital pode não existir em outra cidade. Rede de oficinas, distância, estacionamento, cobertura móvel e parceiros afetam a utilidade da mesma tela.

Na TIC 2025, a declaração de uso de mensagens instantâneas é 92% em área urbana e 85% em área rural; a declaração de instalação de programas/apps é 39% e 18%, respectivamente. Isso mostra heterogeneidade nacional, sem permitir transferir esses percentuais aos clientes da Localiza. [B2, B3]

Para alguém com renda alta, recuperar tempo pode valer mais que um desconto pequeno; para alguém com orçamento pressionado, previsibilidade financeira pode ser decisiva. São hipóteses para comparar, não consequências automáticas da renda.

### 4.6 Confiança e privacidade

Contexto útil não precisa significar rastreamento contínuo. Localização, telemetria e compartilhamento com parceiros exigem clareza sobre finalidade, cobertura e controle. O estudo da Salesforce consultado reforça a relação entre personalização, cautela com dados e transparência sobre IA, mas é um relatório comercial e internacional; não estima atitudes dos assinantes brasileiros. [T1]

Para o MVP, informação declarada pelo cliente — “vou viajar”, “prefiro estacionamento”, “me avise mensalmente” — pode produzir relevância sem exigir coleta adicional de todos os trajetos. Permitir corrigir contexto e desligar comunicações fortalece confiança.

## 5. Por que um cliente procura atendimento humano?

**O volume de contatos não permite responder sozinho.** Há ao menos seis mecanismos possíveis:

| Mecanismo | O que o cliente procura | Sinal já encontrado | Como investigar |
|---|---|---|---|
| Bloqueio técnico | Conseguir entrar ou concluir a tarefa | Relatos de login, seleção de cidade e agendamento | Eventos de erro, versão/aparelho e tentativa anterior |
| Informação incompleta | Entender o que falta ou o que vai acontecer | Relato sobre informações anteriores à entrega | Perguntas recebidas e lacunas da jornada |
| Risco e confirmação | Segurança antes de aceitar cobrança ou condição | Literatura de UX; relatos de cobrança são sinais exploratórios | Observar tarefa e perguntar o que precisava confirmar |
| Exceção operacional | Resolver algo fora do fluxo padrão | Relatos de atrasos, carro substituto e assistência | Motivos de contato e poderes do atendente |
| Esforço e canal familiar | Explicar uma vez e ser entendido | Relatos de repetição de dados; uso nacional de mensagens | Comparar tempo/etapas e perda de contexto |
| Relação e acolhimento | Sentir que alguém acompanha e se responsabiliza | Relato “o atendimento humano faz falta” e elogios ao atendimento | Perguntar o que o humano fez que a tela não entregou |

Fontes: [R1, R2, U1–U5]. Mecanismos podem coexistir no mesmo episódio; não some suas frequências sem uma regra de classificação.

Na Google Play, um cliente relata que não consegue selecionar a cidade para agendar e acaba falando com o atendente. Isso liga diretamente uma dificuldade digital a uma demanda humana, mas ainda é um relato, não diagnóstico reproduzido ou taxa de incidência. Outro reclama que as respostas às críticas mandam usar e-mail. [R2]

No recorte de 50 avaliações recentes da App Store, há reclamações de acesso e contrato ativo, recuperação de senha, informações, agendamento e telemetria. Também há elogios à facilidade e eficiência. As notas foram 31 de cinco estrelas, 3 de quatro, 1 de três, 3 de duas e 12 de uma. Não use essa distribuição como pesquisa representativa: são avaliações espontâneas, de versões e épocas diferentes, misturando app e serviço. [R1]

Uma pesquisa do NN/g com 45 jornadas de complexidade intermediária encontrou contato em 64% delas e destacou falta de informação, problemas de serviço, barreiras no fluxo e percepção de complexidade. É evidência do mecanismo, de 2016 e de outros setores/mercados; não significa que 64% dos assinantes Localiza tenham a mesma experiência. [U1]

**Recomendação:** digitalizar tarefas claras e repetitivas; manter uma transição fácil para humanos nas exceções, urgências e escolhas do cliente. A transferência deve levar o contexto e continuar a mesma solicitação. Reduzir contatos porque o cliente desistiu seria um resultado negativo.

## 6. Falta de conexão com a marca: o que pode estar acontecendo

### 6.1 A marca aparece nos momentos de obrigação

Fatura, multa, revisão, avaria e limite de quilômetros são eventos administrativos ou potencialmente desagradáveis. Se esses forem os principais encontros com a marca, a associação pode ficar concentrada em obrigações. Esse é um mecanismo plausível a partir da jornada apresentada, não uma emoção já medida entre clientes. [C1]

Em contraste, o prazer de dirigir costuma acontecer fora do app. A Localiza pode estar entregando valor sem que o cliente o atribua à marca, como quando há disponibilidade do carro e ausência de burocracia. Tornar o cuidado visível exige mostrar ajuda concreta, não aumentar exposição ao logotipo.

### 6.2 Existe valor, mas ele pode ser pouco saliente

Manutenção, documentação e suporte incluídos podem parecer distantes em meses tranquilos. Benefícios genéricos podem não ser encontrados ou não servir para a cidade/rotina da pessoa.

É possível comunicar valor entregue: serviço concluído, benefício realmente usado, prazo cumprido, próxima ação organizada. Não invente “você economizou R$ X” comparando preços hipotéticos de seguro ou manutenção; declare a metodologia e distinga economia comprovada de estimativa.

### 6.3 O cliente avalia a jornada inteira

A tela pode funcionar e a oficina atrasar. O atendente pode ser gentil e não ter uma solução. A cobrança pode estar detalhada e ainda ser percebida como injusta. O NPS alto do app não garante uma experiência global equivalente. [U3, U5, U6]

Isso justifica um **service blueprint**: mapear cliente, app, atendimento, oficina e processos de suporte para o mesmo episódio. Conexão com a marca depende de consistência entre promessa e entrega.

### 6.4 Renovação e indicação têm outros determinantes

Preço da renovação, nova necessidade de mobilidade, concorrentes, condições contratuais e disponibilidade do próximo carro podem explicar não renovação. Indicação depende de confiança, oportunidade social, conhecimento das regras e disposição para recomendar algo de compromisso financeiro relevante.

O programa de indicação e o clube já existem. Não os apresentem como novidade. Primeiro descubram onde a jornada atual perde clareza ou relevância. [C1, L2]

**Uma proposta melhor de app pode contribuir para vínculo e renovação; a pesquisa atual não demonstra esse efeito causal.**

## 7. Enquadrar: árvore de problemas e hipóteses

### 7.1 Árvore de problemas — “por quê?”

Pergunta: **por que o app não ocupa mais momentos úteis da mobilidade?**

```text
Relevância recorrente insuficiente
├── A. Necessidade/oportunidade
│   ├── As necessidades atuais são naturalmente pouco frequentes?
│   ├── Quais problemas recorrentes ainda ficam fora da assinatura?
│   └── Há necessidade relevante, mas atendida melhor por outro serviço?
├── B. Descoberta e adequação
│   ├── O cliente sabe que existe uma solução?
│   ├── Ela está disponível para seu carro, cidade e contrato?
│   └── Aparece na hora em que é útil?
├── C. Realização do valor
│   ├── A tarefa pode ser concluída sem erro ou retrabalho?
│   ├── O dado é claro, atual e confiável?
│   └── A operação/parceiro entrega o prometido?
└── D. Continuidade e atribuição
    ├── O cliente sabe o resultado e a próxima ação?
    ├── O histórico acompanha a troca de canais?
    └── O valor entregue é reconhecido como parte da assinatura?
```

A organização procura aproximar MECE por etapa: oportunidade, descoberta, execução, pós-execução. Causas se relacionam, então cada observação deve receber uma **causa primária pelo primeiro ponto de falha**, com fatores secundários separados. Não afirmar MECE perfeito quando o comportamento real contém interdependências.

Baixa abertura sem necessidade pode ser saudável. Diferencie isso de uma necessidade perdida, uma tentativa frustrada e um valor entregue sem reconhecimento.

### 7.2 Árvore de hipóteses — “como?”

| Hipótese | Evidência existente | Teste necessário | O que a enfraqueceria |
|---|---|---|---|
| H1: relevância contextual amplia valor recorrente | Case declara desalinhamento entre benefícios e contexto; UX de contexto [C1, U4] | Tarefa real com benefício/ação relevante | Pessoas não encontram um ganho útil ou o parceiro não entrega |
| H2: clareza e continuidade diminuem contatos evitáveis | Relatos e estudos de jornadas [R1, R2, U1, U3] | Tarefa observada + tentativa anterior + recontato | Contatos decorrem principalmente de exceções ou falta de capacidade operacional |
| H3: projeção interpretável ajuda mais que um número de km | Gestão e alertas já existem [C1] | Comparar informação atual com explicação e ação | Dado não confiável ou cliente não vê preocupação recorrente |
| H4: valor comprovado e acompanhamento melhoram percepção | Posicionamento e literatura de jornada [L1, U5, U6] | Teste de compreensão e piloto | Pessoas percebem como propaganda ou compensação de serviço ruim |
| H5: a resposta muda por tarefa, habilidade e idade | Dados nacionais e acessibilidade [B1–B3, A1] | Recrutamento cruzado | Diferenças de canal desaparecem ao corrigir a tarefa |
| H6: amplo catálogo de serviços cria razão para superapp | Benchmark Sem Parar [K1] | Testar duas jornadas integradas de alto valor | Benefícios são esporádicos ou repetem apps que já funcionam melhor |

Todas permanecem abertas. H1 e H2 merecem prioridade pela conexão com o case e por poderem ser testadas rapidamente. H3 depende da confiabilidade dos dados. H6 não é refutada por princípio, mas exige demonstrar sinergia entre serviços.

## 8. O superapp é uma boa ideia?

### 8.1 O que precisaria significar

Um superapp pode integrar parceiros, pagamentos, identidade e jornadas. Pode ser útil quando reduz trocas, repetições e esforço em atividades frequentes. **Um menu com links e muitos benefícios não demonstra essa integração.**

O Sem Parar oferece pagamentos de pedágio, estacionamento, abastecimento e outros serviços por tag, além de funções no SuperApp. O ponto relevante do benchmark é a conexão com transações da rotina e uma infraestrutura de execução. Seu site comercial não comprova que o mesmo modelo melhora renovação numa assinatura de veículos. [K1]

### 8.2 Por que uma versão genérica é fraca para este case

O app da Localiza já contém muitos dos serviços que vocês poderiam listar. Mapas, combustível, estacionamento e recompensas também competem com produtos especializados e hábitos existentes. Ampliar o catálogo pode elevar esforço de descoberta, integrações e atendimento sem fortalecer a relação.

O diferencial precisa estar no que a Localiza sabe e consegue fazer legitimamente: veículo, contrato, serviços incluídos, rede, contexto autorizado e continuidade da operação. Ainda assim, cobertura e acesso aos dados precisam ser confirmados.

### 8.3 Critérios para decidir a favor

Só avançaria com o superapp se o grupo demonstrasse uma jornada em que:

1. O cliente tem uma necessidade recorrente e relevante.
2. Hoje precisa coordenar serviços separados ou repetir informação.
3. A integração poupa esforço ou dinheiro comprovável.
4. A Localiza tem capacidade/parcerias para concluir a ação.
5. O ganho supera usar os apps especializados que o cliente já conhece.

Exemplo que merece teste: preparação de uma viagem conectando situação do carro, uso contratado, benefício disponível e ação para manutenção quando necessária. O valor seria coordenar a viagem, não “ter um mapa”.

**Minha recomendação:** apresentar a solução como uma evolução contextual do app existente. Se houver sinergias comprovadas, o superapp pode surgir como consequência da estratégia.

### 8.4 Benchmarks: o que aprender e o que não presumir

| Referência | O que a fonte descreve | Aprendizado para a Localiza | Limite |
|---|---|---|---|
| Sem Parar | Tag, extrato, locais de uso, pagamentos e benefícios | Recorrência pode vir de transações concretas com pouco esforço | IPVA/licenciamento já incluídos na assinatura têm outro papel; não copiar todo o catálogo |
| My BMW | Estado do veículo, planejamento de viagens, recarga e contato com serviço | Organizar informações ao redor do carro e de objetivos reais | Recursos variam por país, equipamento e contrato ConnectedDrive |
| Volvo Cars | Climatização, carga, serviço, manuais e apoio de especialistas | Conveniência digital pode coexistir com suporte humano | Recursos variam por modelo/mercado; não comprova integração disponível à Localiza |
| App Localiza Assinatura atual | Gestão do contrato, km, localização, serviços e benefícios | Muitos ativos para uma experiência contextual já são previstos | Existência da função não garante disponibilidade, precisão ou conclusão em cada veículo |

Fontes: [K1–K3, C1, L3]. As descrições de BMW e Volvo foram consultadas nas fichas oficiais dos aplicativos, publicadas pelos fabricantes na loja brasileira. Não foram executadas essas funções ou verificadas suas APIs. Os benchmarks mostram possibilidades e padrões; não demonstram efeitos sobre retenção.

## 9. Priorizar: comparar caminhos antes de construir

Avaliação qualitativa do autor, baseada na aderência ao case e nas dependências visíveis. Não são notas de clientes nem resultados financeiros medidos.

| Caminho | Potencial para cliente/negócio | Esforço e dependências | Risco principal | Decisão sugerida |
|---|---|---|---|---|
| Corrigir bloqueios e simplificar autoatendimento | Alto onde há falhas; melhora confiança | Precisa diagnóstico e integração operacional | Resolver só atendimento e não ampliar relevância | Base necessária, priorizada pelos motivos reais |
| Experiência contextual dentro do app | Alto se ligada a rotina relevante | Regras, contrato, catálogo e eventos confiáveis | Notificação sem ação ou recomendação errada | Melhor conceito para validar primeiro |
| Preparação de viagem | Valor tangível num momento concreto | Dados do carro e cobertura de parceiros | Sazonalidade; não atende toda rotina | Boa jornada demonstrável para o hackathon |
| Economia contextual de mobilidade | Recorrência possível | Parceiros, elegibilidade e confirmação de uso | Clube genérico ou subsídio inviável | Complemento se já houver parceiro executável |
| Chatbot/IA genérica | Pode facilitar descoberta | Base confiável e ação integrada | Resposta simpática sem resolução | Camada opcional, não proposta central |
| Superapp amplo | Potencial depende da sinergia | Muitas integrações e coordenação de parceiros | Complexidade e diferenciação fraca | Adiar expansão até provar uma jornada |
| Gamificação de abertura diária | Aumenta uma métrica de acesso | Implementação relativamente simples | Hábito sem benefício e desgaste | Não priorizar |
| Comunidade/social | Pode apoiar nichos | Moderação e massa crítica | Participação baixa e escopo distante | Investigar só com demanda demonstrada |

O PDF recomenda Pareto. A aplicação correta é **descobrir quais poucas causas concentram maior impacto**, usando motivos e custo dos contatos. Não presumir que 20% de causas já explicam 80% do problema sem dados. [M1]

## 10. Problema → conceito → solução

### 10.1 Problema

**Hipótese de problema centrada no cliente:** “Apesar de contratar conveniência, ainda preciso descobrir sozinho o que fazer, interpretar regras e acompanhar pendências; os benefícios e informações nem sempre ajudam na minha rotina.”

Essa frase precisa ser confirmada com clientes. O case sustenta desalinhamento de contexto; os relatos sustentam exemplos de esforço e quebra de jornada. Não sabemos a prevalência.

### 10.2 Conceito

**Cuidado de mobilidade no momento certo:** usar o que a assinatura já sabe e entrega para antecipar uma necessidade, explicar o que importa e facilitar uma ação, com continuidade para humanos quando necessário.

Promessa para o cliente: **“Menos coisas para lembrar. Mais clareza para seguir sua rotina.”**

O vínculo desejado é sentir amparo, autonomia e respeito pelo tempo. Ele será sustentado por entregas, não apenas pela aparência ou personalidade de um assistente.

### 10.3 Solução proposta: “Localiza Presente” — nome de trabalho

Uma camada contextual na home e nas jornadas existentes, com três capacidades:

| Capacidade | Experiência concreta | Diferença em relação ao que já existe |
|---|---|---|
| Próximo passo útil | Explicar uma necessidade e oferecer ação elegível | Organiza o contexto em torno do objetivo; gestão de km e alertas já existem |
| Benefício relevante e realizável | Mostrar uma opção adequada à rotina e confirmar uso | Clube já existe; novidade proposta é pertinência, execução e resultado |
| Continuidade de cuidado | Status, próxima atualização e transferência com histórico | Atendimento e ajuda já existem; oportunidade é evitar perda de contexto |

Pode funcionar com regras e conteúdo estruturado. IA só acrescenta valor se melhorar compreensão, com dados confiáveis e capacidade de concluir a tarefa. Não é necessário um agente generativo para demonstrar o conceito.

As telas do case já mostram status de manutenção/ocorrência e uma opção “Fale com a Liza”. O diferencial a testar é coordenar o objetivo do cliente entre dados, ação e canais, com menos esforço. Sua existência atual precisa ser considerada na comparação; não se pode vender um novo chatbot ou uma linha de status como novidade sem investigar o que já funciona.

### 10.4 Uma jornada concreta para o pitch

**Exemplo ilustrativo, não cliente real:** um assinante que usa o carro para trabalho e família pretende viajar no próximo fim de semana.

| Etapa | Experiência proposta | Condição para entregar |
|---|---|---|
| Contexto | Cliente escolhe “vou viajar” e informa distância estimada | Entrada voluntária; não inferir todos os planos pela localização |
| Compreensão | App reúne situação de manutenção e uso contratado numa linguagem clara | Dados atualizados e regras específicas do contrato |
| Decisão | Mostra próximo passo, inclusive “não há ação de manutenção pendente nos dados disponíveis” | Não declarar segurança mecânica total com base em dados incompletos |
| Ação | Cliente consulta uma opção de serviço ou benefício elegível | Disponibilidade verificada; sem prometer agenda sem confirmação |
| Continuidade | Recebe confirmação e acompanha a solicitação | Status compartilhado entre app e operação |
| Exceção | Se precisar de ajuda, atendente recebe contexto e histórico autorizado | Integração do atendimento e identificação da solicitação |
| Resultado | App registra o serviço/benefício efetivamente concluído | Evidência de execução, não somente clique |

A projeção de quilometragem deve ser uma estimativa, com origem e data do dado. Não calcule cobrança automática simplesmente subtraindo um limite mensal: compensação, período de apuração e cobrança dependem do contrato. A pessoa pode corrigir a distância planejada. O app não deve sugerir uso durante a condução.

### 10.5 O que construir no hackathon

**Uma jornada principal, com quatro ou cinco telas:** contexto → resumo útil → ação → confirmação/status → exceção com continuidade. Simular integrações de forma identificada e explicar quais seriam necessárias em produção.

O protótipo deve mostrar um diferencial visível: a mesma pessoa não precisa procurar regras em vários menus ou explicar de novo o que já tentou. O benefício deve corresponder a uma necessidade real e a um parceiro disponível, ou ser claramente demonstrativo.

A validação pode escolher outra jornada se revisão, fatura ou benefício de rotina aparecerem como necessidades mais fortes. “Viagem” é uma boa hipótese para demonstrar coordenação, mas sua sazonalidade pode limitar recorrência.

### 10.6 O que fica para uma segunda etapa

Integração transacional ampla com parceiros, previsão por telemetria, controle de múltiplos veículos, permissões familiares detalhadas e personalização por modelos avançados. Antes disso, confirme cobertura dos dados, elegibilidade dos serviços e operação capaz de responder.

Na tela apresentada, “bateria” aparece com tensão de 12,1 V. Não há demonstração de estado de carga da bateria de tração de um elétrico. Uma proposta de autonomia/recarga precisaria confirmar esse dado específico; não deve inferi-lo a partir do rótulo genérico de bateria.

Não introduzir outro app, feed genérico, moeda virtual, recompensa por simplesmente abrir ou rastreamento adicional indiscriminado. Esses caminhos precisariam de problemas próprios e justificativa.

## 11. Hábito com valor e conexão com a marca

O modelo de Fogg descreve a convergência de **motivação, capacidade/facilidade e um estímulo no mesmo momento**. É um modelo conceitual, não prova de que notificações aumentarão renovação. [F1]

Aplicação ao case:

| Elemento | Pergunta de projeto | Exemplo |
|---|---|---|
| Motivação | O que a pessoa ganha agora? | Evitar retrabalho, planejar uma viagem, usar um benefício relevante |
| Facilidade | Ela consegue resolver sem pesquisar tudo de novo? | Dados reunidos, linguagem clara e uma ação coerente |
| Estímulo | Qual momento justifica interrompê-la? | Planejamento declarado ou pendência realmente importante |

Recorrência pode ser semanal, mensal ou por evento. A rotina do carro é diária; a necessidade de interagir com a Localiza pode não ser. Uma notificação útil que resolve algo sem abrir o app pode fortalecer a relação mesmo sem elevar acessos.

Mantenha controle de frequência e canal. Quando o cliente diz que um aviso não é útil, isso é aprendizado. Não use ansiedade, excesso de alertas ou pontuação para forçar abertura.

## 12. Viabilidade e impacto de negócio

### 12.1 Dados e integrações mínimos

Contrato e elegibilidade; estado de manutenção; quilometragem com data de atualização; catálogo por cidade; status de solicitações; identificação e permissões; preferências de comunicação. Não existe confirmação nesta pesquisa de que as APIs estejam disponíveis ou os dados tenham cobertura completa.

Uma primeira versão pode usar regras explícitas, contexto declarado e um catálogo pequeno, dentro da infraestrutura existente. A dificuldade central provavelmente está na coordenação dos sistemas e da operação, mais do que em produzir texto com IA.

### 12.2 Métricas: o que seria sucesso

**Métrica principal sugerida:** proporção dos clientes elegíveis que tiveram um episódio de valor útil concluído no período — uma ação ou informação reconhecida como útil, com definição explícita por jornada. Não contar automaticamente uma visualização ou abertura.

| Dimensão | Métrica | Cuidado |
|---|---|---|
| Utilidade | Conclusão da jornada e benefício efetivamente resgatado | Separar intenção, clique e execução |
| Esforço | CES pós-jornada, tempo e repetição de dados | Medir também falhas e abandono |
| Confiança | Clareza do próximo passo e confiança no resultado | Não substituir por satisfação com o visual |
| Recorrência | Retorno a episódios úteis em 30 dias | Não premiar contatos repetidos pelo mesmo problema |
| Atendimento | Contatos evitáveis por motivo e recontato | Não reduzir acesso ao humano para melhorar a taxa |
| Relação | Percepção de cuidado e NPS relacional | Mesma população e metodologia ao comparar |
| Negócio | Renovação da base elegível e indicação convertida | Controle de preço, tempo de contrato e mudança de necessidade |
| Proteções | Erros, reclamações, alertas ignorados e desistência | Não aceitar ganho de acesso com pior experiência |

O CES mede esforço em uma interação e complementa a visão da relação inteira. A Qualtrics descreve diferenças entre CES, CSAT e NPS; seus números comerciais não foram usados para estimar o resultado da Localiza. [Q1]

### 12.3 Um cenário financeiro transparente

O case informa mais de 80 mil contatos mensais. Usando **80 mil apenas como referência arredondada**, um cenário com 10% de redução líquida corresponderia a 8 mil contatos evitados/mês. Isso não é uma previsão nem significa que 10% sejam digitalizáveis.

```text
Economia bruta mensal = contatos efetivamente evitados × custo incremental por contato
Resultado líquido = economia bruta + contribuição comercial incremental
                    − integrações − operação adicional − incentivos − manutenção
```

O percentual evitável, custo por canal, custo do produto e efeito comercial precisam ser fornecidos/medidos. Capacidade liberada de atendentes não vira automaticamente redução de gasto. Cashback financiado pode mudar a conclusão financeira.

Para renovação, +1 ponto percentual significa 10 renovações adicionais em cada 1.000 contratos elegíveis naquele período, não 1% de toda a frota todo mês. Atribuir o ganho ao app exige comparação adequada.

## 13. Validação e decisões que podem mudar a ideia

O roteiro completo está em [Plano de validação](../03-plano-de-validacao/README.md).

Antes de fechar a solução, valide três coisas: **qual necessidade merece foco; por que hoje não é satisfeita; e se a proposta é melhor do que a forma atual de resolver**.

Se o problema dominante for login/agendamento, mostre correção e continuidade como base, mas acrescente uma hipótese de utilidade além do suporte para responder ao case. Se contatos forem majoritariamente operacionais, uma nova interface não bastará. Se clientes estiverem felizes com pouco uso, mude o objetivo para valor e cuidado percebido. Se a jornada de viagem não for importante, escolha uma rotina comprovada nas entrevistas.

Um piloto com grupo de comparação ajuda a medir conclusão, esforço e contato. Renovação exige janela e amostra maiores. Evite comparar usuários já mais engajados com menos engajados como se o app tivesse causado a diferença.

## 14. Sintetizar: argumento e roteiro para a banca

### Mensagem principal em quinze segundos

> “O app já é usado por cerca de 80% dos clientes no mês. Propomos evoluí-lo para antecipar necessidades, facilitar ações e mostrar o cuidado da Localiza nos momentos relevantes da mobilidade. Vamos provar valor numa jornada concreta antes de ampliar o catálogo.”

### SCR: situação, complicação e resolução

**Situação:** o app tem boa adoção e avaliação e já oferece várias funções de gestão. **Complicação:** parte do uso é pontual; contexto, continuidade e percepção de valor ainda apresentam oportunidades, enquanto há uma carga relevante de contatos. **Resolução:** testar uma experiência contextual no app existente, com ação realizável e continuidade humana, medindo utilidade, esforço e impacto.

### Pirâmide de argumentos

1. **O alvo é relevância, não instalação.** Sustentação: dados de adoção e frequência; funcionalidades existentes.
2. **Valor e confiança dependem da jornada.** Sustentação: relatos positivos e negativos, estudos de UX, diferenças entre familiaridade e habilidades digitais.
3. **Uma jornada focada permite provar o conceito.** Sustentação: protótipo comparável, dependências identificadas, métricas e critérios para descartar a hipótese.

### Storyline dot-dash para cinco minutos

| Tempo aproximado | Mensagem do slide | Evidência ou demonstração |
|---|---|---|
| 0:00–0:40 | O app já tem adoção; falta provar relevância em mais momentos | 80,1%, NPS e distribuição de acessos |
| 0:40–1:25 | O cliente pode buscar humano por esforço, risco ou exceção | Relatos locais e mecanismo, com limitações |
| 1:25–2:00 | Nosso público quer conveniência em uma situação específica | Recorte escolhido e aprendizado das entrevistas, quando houver |
| 2:00–3:20 | Mostramos cuidado como uma ação útil na rotina | Jornada demonstrada, confirmação e exceção |
| 3:20–4:20 | A proposta aproveita ativos existentes e tem implantação por etapas | Dependências, serviço por trás da tela e piloto |
| 4:20–5:00 | Mediremos valor concluído e contribuição ao negócio | Métricas, cenário financeiro explícito e próxima decisão |

Não use entrevistas que ainda não aconteceram como evidência. Troque “validado” por “hipótese” nos slides onde só houver pesquisa secundária.

## 15. Como o vídeo indicado orienta esta recomendação

Foi consultada a transcrição automática em português de **“O que é inovação: conceitos básicos”, Professor Mario Sergio Salerno**. Ela contém erros de reconhecimento; os pontos abaixo são paráfrases do conteúdo e os tempos são aproximados. [V1]

- **2:11–3:34:** distingue invenção de inovação e relaciona inovação à realização no mercado. Aplicação: um protótipo bonito ainda precisa demonstrar utilidade, adoção e viabilidade.
- **4:11–4:37 e 6:29–7:23:** destaca que inovação não se limita a alta tecnologia e pode ser organizada. Aplicação: coordenação e clareza podem ser mais relevantes que acrescentar um modelo de IA.
- **7:28–8:43:** discute competitividade, oportunidade, redução de custo e aumento de receita. Aplicação: conectar benefício para o cliente com atendimento, retenção e economia comprovável.
- **8:44–10:36:** aborda processos sistemáticos e tipos diferentes de inovação. Aplicação: transformar hipóteses em experimentos e aprender antes de expandir.

O vídeo dá fundamento para pensar em inovação de serviço e processo. Ele não valida o conceito “Localiza Presente” ou a preferência dos assinantes.

## 16. O que a pesquisa permite afirmar hoje

Há base documental para corrigir a premissa de baixa adoção, identificar funcionalidades existentes e formular hipóteses sobre relevância, esforço e vínculo. Há dados brasileiros que justificam considerar idade, habilidades e canais familiares sem estereótipos. Há relatos públicos que mostram tanto valor digital quanto falhas e necessidades humanas.

Ainda não sabemos qual causa domina a base, qual segmento concentra oportunidade, quais integrações são disponíveis ou quanto a proposta pode mudar renovação. O melhor próximo passo é validar uma jornada concreta com usuários e operação. A confiança na ideia deve vir dessa comparação, não do tamanho do catálogo de funcionalidades.
