# Case 2 — Baixa utilidade recorrente e dependência do atendimento

**Hackathon Ruptura 2026 | Localiza Assinatura | 02/10/2026**

> **Diagnóstico de trabalho:** o aplicativo já tem adoção e boa avaliação. A oportunidade é entender onde o valor da assinatura deixa de se conectar às necessidades de mobilidade do cliente, quanto esforço ele precisa fazer para resolver essas necessidades e como isso afeta a percepção de cuidado e a relação com a marca.

Este documento desenvolve **a etapa do problema**, com foco nas duas frentes atribuídas ao responsável pela pesquisa no grupo. A escolha do conceito, da solução, da tecnologia e do MVP vem depois da validação e da priorização das necessidades.

| Responsabilidade combinada com o grupo | Onde está a análise |
|---|---|
| **Problema 1:** baixa utilidade diária e engajamento recorrente | Seções 2 e 8 |
| Subproblema 1: por que 36% usam 1–2 vezes/mês e só 17% são classificados como altamente engajados? | Seção 2: leitura dos dados, causas possíveis e testes |
| Subproblema 2: quais funcionalidades de abastecimento, estacionamento, pedágio e rotas estão ausentes? | Seção 8: inventário e lacunas a confirmar |
| **Problema 2:** alta dependência de atendimento humano | Seção 9 |
| Subproblema 1: quais gargalos contribuem para os mais de 80 mil contatos mensais? | Seção 9.1: barreiras possíveis e rastreabilidade |
| Subproblema 2: por que o cliente busca humanos em demandas transacionais ou contratuais simples? | Seções 9.2–9.4: esforço, interpretação, risco e preferência |

**Estado da investigação:** pesquisa documental, com conferência dos PDFs, nova consulta à descrição oficial do app e à página do Clube de Benefícios e reaproveitamento crítico da pesquisa registrada no histórico do repositório. Não foram realizadas entrevistas com assinantes, observação do app autenticado ou análise dos sistemas internos. As causas específicas permanecem hipóteses.

## Como ler este documento

As seções seguem as técnicas do PDF de ideação: **definir → enquadrar → priorizar/analisar → sintetizar**. Aplicamos SCQ, pergunta central, árvore de problemas e critérios de priorização. A orientação de aprender com experiências reais dos usuários vem do PDF “Aula o Problema”. [M1, M2]

Ao longo do texto:

- **Evidência documental:** informação apresentada pelo case ou por uma fonte identificada. Não significa auditoria dos dados internos.
- **Sinal exploratório:** relato público ou mecanismo descrito em pesquisa de outro contexto. Ajuda a formular perguntas, sem medir a base Localiza.
- **Hipótese:** explicação plausível que precisa ser confirmada, modificada ou descartada.
- **Lacuna:** informação necessária que ainda não temos.

As referências estão na seção 20. As páginas dos PDFs são contadas desde a primeira página do arquivo, independentemente da numeração impressa no slide.

## 1. O desafio apresentado pela Localiza

O case 2 pergunta como aumentar a relevância do aplicativo na rotina dos clientes e gerar novos motivos de uso recorrente. O objetivo explícito é criar valor adicional na jornada de mobilidade, fortalecer a relação com a marca e produzir impacto para cliente e negócio. [C1, p. 22]

O material descreve uma jornada predominantemente pontual:

**Surge uma necessidade → cliente acessa o app → resolve → fecha → retorna quando surge outra necessidade.** [C1, p. 20–21]

Também afirma que os benefícios e serviços nem sempre estão conectados ao contexto do cliente e que existem oportunidades na percepção de valor da assinatura, no atendimento, na renovação e na indicação. [C1, p. 19–22]

**A questão a investigar é quando essa dinâmica representa uma oportunidade perdida e quando representa um serviço eficiente.** Um cliente que resolve rapidamente e fecha o app pode estar recebendo exatamente o que contratou.

## 2. Problema 1 / Subproblema 1 — Por que 36% acessam 1–2 vezes e 17% acessam 11 ou mais?

### 2.1 O que os números dizem — e o que não dizem

| Informação apresentada | O que podemos afirmar | O que ainda precisamos descobrir |
|---|---|---|
| 80,1% de acesso mensal | Há adoção mensal relevante | Quem compõe o denominador e o que essas pessoas concluem |
| 53 mil MAU e 31 mil WAU | Existe uma base importante de usuários ativos | Período, definição de atividade e distribuição por jornada |
| 36% na faixa de 1–2 acessos mensais | Parte dos usuários acessa pontualmente | Se a frequência atende às necessidades ou revela dificuldade de encontrar valor |
| 17% com 11 ou mais acessos mensais | Há um grupo com alta frequência | Se retorna por utilidade, acompanhamento, múltiplas responsabilidades ou tentativas repetidas |
| NPS do app 84 | O app é bem avaliado na pesquisa apresentada | Amostra, momento de coleta, respondentes e diferenças entre tarefas |
| NPS relacional aproximadamente 45 | A experiência global merece investigação própria | Quais aspectos da assinatura explicam a avaliação |
| Mais de 80 mil contatos mensais | O atendimento recebe volume relevante | Clientes únicos, motivos, resolução, recontatos e tentativa prévia no app |
| 75% dos contatos por chat; 25% por telefone | Conhecemos a distribuição dos contatos nesses canais | Quanto é humano, automatizado, escolha do cliente ou exigência do processo |
| Cerca de 48% de renovação | Renovação é um resultado de negócio relevante | Base elegível, janela, preço, necessidade de continuar e motivos de saída |
| 7% de indicação | Existe espaço para investigar comportamento de indicação | Período, denominador, significado de indicar e conversão |

Fontes: [C1, p. 19, 21 e 25].

### 2.2 Cuidados com a interpretação

Na página 21, o texto diz “menos de 2x”; na tabela da página 25, a faixa é **“1 a 2”**. Adotamos a classificação explícita da tabela, preservando a divergência para confirmação.

A distribuição apresentada é: 1–2 acessos, 36%; 3–5, 28%; 6–10, 19%; 11–20, 11%; 21 ou mais, 6%. O critério de “acesso engajado” precisa ser esclarecido. [C1, p. 25]

Os 17% resultam das duas faixas superiores, 11% + 6%. **Os outros 47% estão entre 3 e 10 acessos.** A base não se divide apenas entre pouco e muito uso. A tabela se refere aos clientes que acessam o app no mês; precisamos confirmar a definição exata do denominador antes de falar em 36% de todos os clientes.

Frota, contratos, clientes e usuários não são necessariamente a mesma unidade. Os números de aproximadamente 70 mil e 53 mil MAU/80,1% não devem ser harmonizados por suposição. Precisamos das bases e dos períodos.

O material apresenta também NPS do produto 85 em outra página. Isso exige verificar a população e a definição de cada pesquisa. NPS costuma ser expresso em pontos, de −100 a +100, embora os slides utilizem o símbolo de porcentagem em alguns locais. [C1, p. 5, 19 e 25]

**Não é possível concluir que baixa frequência causa menor NPS ou não renovação.** O case apresenta essa relação como preocupação de negócio, mas não disponibiliza uma análise causal. Também não sabemos quanto do atendimento é evitável.

### 2.3 Causas possíveis do uso pontual

| Explicação a investigar | Como poderia produzir 1–2 acessos/mês | Evidência necessária |
|---|---|---|
| Frequência natural das tarefas | Fatura é mensal; documentos e serviços são consultados quando necessários | Motivo e conclusão de cada acesso |
| Delegação desejada | Assinante quer pensar menos na administração do carro | Motivação da contratação e satisfação com pouco uso |
| Pouca relevância adicional | Cliente não identifica algo útil fora das tarefas contratuais | Necessidades frequentes que o serviço deixa de atender |
| Benefícios desconhecidos | Não sabe o que existe ou onde encontrar | Conhecimento espontâneo e observação de descoberta |
| Benefícios inadequados | Sabe que existem, mas não compensam no seu contexto | Elegibilidade, região, esforço e ganho percebido |
| Alternativas estabelecidas | Já resolve rotas, estacionamento ou abastecimento em outro serviço | Alternativa real e motivo de escolha |
| Atrito ou confiança reduzida | Evita retornar depois de erro, dificuldade ou informação inconsistente | Histórico de falha e comportamento posterior |
| Valor entregue sem abrir o app | Aviso ou outro canal pode atender à necessidade | Cobertura e uso efetivo desses canais; hipótese ainda sem medição |

O case dá suporte documental às tarefas pontuais e à falta de conexão contextual. As demais linhas são hipóteses, não causas confirmadas nem partes de uma distribuição medida.

### 2.4 O que pode explicar o grupo de 11+ acessos

Pode representar utilidade recorrente, consulta de dados do carro, acompanhamento de um serviço, gestão de responsabilidades ou tentativas repetidas de resolver o mesmo assunto. O rótulo “alto engajamento” do slide é uma faixa de frequência; ainda precisamos verificar a qualidade desse uso.

Comparar, entre faixas, **tarefas distintas concluídas, erros, tempo, contatos, recontatos, tempo de contrato e percepção de valor**. Se o grupo de 11+ acessos concentra erros e recontatos, frequência alta não é necessariamente o comportamento desejado. Se o grupo de 1–2 conclui tudo com satisfação, não há justificativa para exigir mais interação.

**Resposta provisória ao subproblema:** o padrão é compatível com um app voltado a tarefas episódicas. O case aponta falta de relevância contextual, mas não sabemos quanto do uso pontual é saudável, quanto decorre de desconhecimento/inadequação e quanto decorre de barreiras. A investigação deve separar esses mecanismos.

### 2.5 Definição de engajamento que precisamos investigar

Para este diagnóstico, **utilidade diária** significa pertinência às atividades da rotina; não exige uma abertura todos os dias. **Engajamento recorrente útil** significa retornar para necessidades nas quais o cliente consegue obter valor, distinguindo novos episódios de repetição do mesmo bloqueio.

Medir retorno por tipo de necessidade e por cliente elegível, junto da conclusão e do esforço. Precisamos descobrir a cadência natural da atividade antes de adotar frequência diária, semanal ou mensal como expectativa. Se a necessidade só surge mensalmente, compará-la a um hábito diário pode levar à conclusão errada.

## 3. Formulação do problema com SCQ

### Situação

O cliente contrata um serviço de assinatura com carro e serviços associados. O app já reúne recursos para contrato, pagamentos, documentos, manutenção, quilometragem, multas, benefícios e ajuda. O case mostra alta adesão mensal e boa avaliação do canal. [C1]

A promessa comercial enfatiza comodidade, previsibilidade e menos preocupações com a administração do carro. É uma promessa da marca; ainda precisamos descobrir quais dessas motivações pesaram na decisão de cada assinante. [L1]

### Complicação

Segundo o case, a relação digital é principalmente reativa e os benefícios nem sempre acompanham o contexto do cliente. Há oportunidade de fortalecer o valor percebido da assinatura e a relação com a marca. [C1]

**Hipótese a investigar:** em determinados episódios, o cliente precisa descobrir, interpretar ou coordenar sozinho informações e ações para atingir seu objetivo. Em outros, pode não reconhecer uma utilidade relevante fora das tarefas contratuais. Esses mecanismos são diferentes e exigem evidências próprias.

### Pergunta central

> **Em quais situações de mobilidade o assinante deixa de perceber valor ou precisa fazer esforço relevante para obter o que espera da assinatura, e quais causas explicam isso?**

Perguntas de apoio:

- Que resultado a pessoa queria alcançar?
- Como tentou resolver e qual foi a primeira barreira?
- O que levou ao atendimento: escolha, dúvida, falha, urgência ou exigência do processo?
- Quando o valor existe, mas não é reconhecido?
- Quando simplesmente não existe necessidade de interação?

Essa formulação mantém a investigação aberta. Não pressupõe superapp, comunidade, chatbot, IA ou qualquer jornada específica.

## 4. Separando sintoma, dor, causa e consequência

| Camada | Exemplo no case | Como tratar |
|---|---|---|
| Sintoma observável | Poucos acessos; contato com atendimento; benefício sem uso | Medir e contextualizar |
| Dor do cliente | Esforço, dúvida, perda de tempo, imprevisibilidade ou sensação de falta de apoio | Recuperar episódios reais e consequências |
| Possível causa | Informação ausente, regra difícil, falha técnica, indisponibilidade, ausência de relevância | Confirmar com observação, dados e operação |
| Consequência para a empresa | Custo de atendimento, recontato, menor confiança, possível perda de renovação | Verificar vínculo e magnitude, considerando outros fatores |

**“O cliente não abre o app todos os dias” descreve um comportamento, mas não identifica uma dor.** Da mesma forma, “o cliente quer um superapp” seria uma preferência por uma solução; ainda precisaríamos entender a necessidade que a originou.

Uma formulação inicial, ainda hipotética, da dor é:

> “Quero usar o carro para seguir minha vida com tranquilidade, mas em algumas situações preciso gastar tempo descobrindo o que fazer, entendendo as regras e confirmando se tudo foi resolvido.”

Essa frase é uma síntese do time para orientar pesquisa. **Não é uma fala coletada de um cliente.**

## 5. Para quem esse problema pode existir

O material apresenta **pessoas físicas, microempresas e PMEs** como públicos da assinatura. Isso não equivale a todo o público da Localiza: aluguel eventual, gestão de frotas e serviços para motoristas de aplicativo possuem contextos próprios. [C1, p. 5–6; L1]

Antes de segmentar por interesse, precisamos conhecer o papel de cada pessoa:

| Papel | Necessidade que pode ter | Pergunta de pesquisa |
|---|---|---|
| Titular do contrato | Entender condições e assumir decisões | É também quem usa o app e dirige? |
| Responsável pelo pagamento | Compreender custos e evitar surpresas | Recebe as informações necessárias? |
| Condutor autorizado | Usar o veículo e lidar com ocorrências | Tem acesso e autonomia compatíveis com seu papel? |
| Pessoa que organiza serviços | Coordenar horários e disponibilidade | Precisa consultar outras pessoas ou canais? |
| Responsável por pequena empresa | Preservar continuidade de trabalho e controlar despesas | A dificuldade é individual ou envolve vários usuários/veículos? |

Os papéis podem coincidir ou estar distribuídos. Não devemos pressupor que uma conta representa uma rotina individual.

### Segmentos comportamentais para investigação

São hipóteses de recrutamento, sem tamanho estimado:

| Comportamento/necessidade | O que queremos entender |
|---|---|
| Deseja delegar a administração do carro | Quanto quer acompanhar e quanto espera que o serviço resolva sem intervenção |
| Busca controle financeiro | Quais cobranças, regras ou estimativas geram insegurança |
| Coordena uma rotina familiar | Como trabalho, escola e outros compromissos afetam os serviços |
| Depende do carro para trabalhar | Qual o impacto de indisponibilidade e espera |
| Encontra dificuldade em tarefas digitais | Qual tarefa, condição de uso ou experiência anterior explica a barreira |
| Prefere autonomia digital | O que já funciona bem e quando precisa de ajuda |

Uma mesma pessoa pode estar em vários grupos. Essas categorias não são personas validadas nem uma divisão estatística da base.

## 6. Idade, habilidade digital e acessibilidade

### O que sabemos sobre a base

O PDF informa que 60% de **671 respondentes de uma pesquisa com leads não convertidos RAC e clientes RAC** tinham 45 anos ou mais; 50% tinham renda familiar acima de R$ 10 mil. O levantamento aparece no contexto do case 1. [C1, p. 17]

**Esses números não caracterizam os assinantes ativos do case 2.** A distribuição etária e de renda desse público continua sendo uma lacuna.

### O que o contexto brasileiro ajuda a investigar

A TIC Domicílios 2025 registra diferenças de acesso à internet e atividades digitais por idade. Entre usuários de internet, o uso de mensagens instantâneas aparece em 95% da faixa de 45–59 e 83% da faixa de 60+. A declaração de instalação de programas/apps aparece em 29% e 12%, respectivamente. [B1–B3]

Os dados indicam que conversar digitalmente e realizar outras tarefas digitais são atividades distintas. Não instalar um app no período investigado não demonstra incapacidade. Esses percentuais nacionais não podem ser transferidos para clientes da Localiza.

| Faixa para recrutamento de adultos | Questões a investigar, sem pressupor o resultado |
|---|---|
| 18–24 | Quem decide/paga; experiência com contratos; comparação com outros serviços digitais |
| 25–34 | Pressão de tempo, previsibilidade financeira e divisão de responsabilidades |
| 35–44 | Coordenação entre compromissos, pessoas e disponibilidade do veículo |
| 45–59 | Familiaridade com canais, confiança nas informações e expectativa de conveniência |
| 60+ | Diversidade de experiência digital, condições de leitura/interação e necessidade de apoio |

Todos esses temas também podem aparecer nas outras faixas. Os recortes servem para diversificar a investigação, não para atribuir um comportamento a uma geração.

É importante comparar pessoas da mesma idade com habilidades diferentes e pessoas de idades diferentes com tarefas semelhantes. Urgência, risco financeiro, experiência anterior, condições de uso e clareza da tarefa precisam ser registrados.

Necessidades de leitura, visão, interação motora ou compreensão devem ser investigadas sem inferir deficiência a partir da idade. As orientações da W3C relacionam necessidades de usuários mais velhos a padrões gerais de acessibilidade. [A1]

## 7. Cultura, rotina e condições de uso

### Conversa como hábito digital

Na TIC Domicílios 2025, 92% dos usuários de internet declararam usar mensagens instantâneas. Isso justifica investigar familiaridade com comunicação por mensagens. **Não demonstra preferência por humanos, WhatsApp ou atendimento empresarial.** [B2]

O chat do case também não é identificado como WhatsApp. Um contato pode envolver automação, atendimento humano ou ambos.

### Confiança e responsabilidade

É plausível que parte dos clientes procure uma pessoa para interpretar uma regra, confirmar uma informação ou saber quem assume responsabilidade se algo der errado. Estudos de experiência de outros setores descrevem mecanismos desse tipo. Sua frequência na Localiza ainda é desconhecida. [U1–U3]

Precisamos perguntar o que o atendente efetivamente entregou: informação, execução, exceção, confirmação ou acolhimento. A expressão “o brasileiro gosta de falar com gente” não explica a causa e esconde diferenças entre tarefas.

### Significado do carro e da assinatura

O carro pode representar autonomia, trabalho, cuidado familiar, conforto ou status. A assinatura pode significar previsibilidade e liberação de burocracia, mas também gerar dúvida sobre limites de uso, avarias e devolução.

São dimensões a investigar, não motivações comprovadas da base. O posicionamento comercial da marca ajuda a reconhecer sua promessa, mas não substitui a escuta de clientes. [L1]

### Região, renda e infraestrutura

Cidade, distância dos prestadores, disponibilidade de parceiros, conectividade e tempo disponível podem transformar uma mesma tarefa em experiências muito diferentes.

Um benefício sem parceiro acessível pode ser irrelevante. Um desconto pequeno pode não compensar o deslocamento ou o esforço de resgate. Pessoas com restrição de orçamento podem priorizar previsibilidade; outras podem priorizar tempo. Essas relações precisam ser verificadas, sem determinismo por renda.

### Privacidade e divisão de responsabilidades

Há diferença entre querer ajuda e aceitar compartilhar contexto, localização ou informações com familiares e parceiros. Precisamos investigar quais dados o cliente considera necessários e em quais situações sente perda de controle.

Gênero, idade, escrita de uma avaliação ou composição familiar não autorizam inferências sobre quem dirige, decide, paga ou tem dificuldade digital.

## 8. Problema 1 / Subproblema 2 — O que falta em abastecimento, estacionamento, pedágio e rotas?

### 8.1 Critério: recurso existente, benefício e ação concluída são coisas diferentes

“Há uma categoria de benefício” não significa “o cliente consegue concluir toda a atividade pelo aplicativo”. Da mesma forma, “a descrição pública não menciona” não significa “a função não existe”.

Nesta etapa usamos duas classificações:

- **Documentado:** o case ou a descrição oficial apresenta a capacidade. Ainda não foi testada no app autenticado.
- **Não comprovado nos materiais:** não encontramos confirmação da capacidade nas fontes examinadas. Precisa de auditoria do produto para ser classificada como ausente.

### 8.2 Inventário das quatro atividades

| Atividade | O que já está documentado | O que não ficou comprovado | Necessidade a investigar |
|---|---|---|---|
| **Abastecimento** | Visualização do nível de combustível no case, p. 33 | Busca/comparação de postos e preços; benefício específico vigente de combustível; pagamento e histórico de abastecimento | Onde abastece, como escolhe, quais dificuldades e se quer ajuda da Localiza |
| **Estacionamento** | Descontos em estacionamentos anunciados na descrição oficial do app | Busca de vagas, reserva, pagamento integrado, extensão de tempo ou disponibilidade em tempo real | Frequência, cobertura, esforço para estacionar e utilidade dos descontos existentes |
| **Pedágio** | Descontos em pedágios anunciados na descrição oficial do app | Gestão de tag, extrato específico, contestação e estimativa de custo de pedágio por trajeto | O que já usa, quem administra a cobrança e onde encontra dúvidas |
| **Rotas** | Localização do carro e gestão de quilometragem apresentadas no case | Navegação passo a passo, trânsito, planejamento de rota e integração explícita com custo/franquia/serviços | Se há uma dificuldade não resolvida pelos aplicativos de navegação atuais |

Fontes: [C1, p. 24, 28 e 32–33; L2, L3]. A localização do veículo não comprova navegação. O nível de combustível não comprova uma jornada de abastecimento. Um desconto não comprova pagamento integrado ou operação de uma tag.

Na nova consulta à página do Clube de Benefícios, as categorias são visíveis, mas os cartões de parceiros vieram como conteúdo dinâmico não resolvido no HTML recebido. **Não foi possível verificar nomes, cobertura ou regulamentos individuais de todos os parceiros.** Por isso, não classificamos benefício de combustível como existente ou ausente com base nessa página. [L2]

**Resposta provisória ao subproblema:** existem recursos e benefícios relacionados à rotina de dirigir. As lacunas mais específicas estão na comprovação de jornadas completas e na sua utilidade para o contexto do cliente. A lista de funcionalidades efetivamente ausentes depende de acesso ao app e confirmação com produto.

### 8.3 Como confirmar ausência e relevância

Para cada uma das quatro atividades, registrar versão do app, sistema operacional, perfil/contrato, veículo, cidade, recurso encontrado, caminho, elegibilidade, eventual parceiro externo e resultado alcançado. Conferir também funções liberadas apenas para parte da base.

Classificar o resultado da auditoria como: **disponível e concluída; disponível com limitação; benefício/encaminhamento externo; ausente no recorte testado; ou não verificável**. Isso evita generalizar um teste de uma conta para todos os clientes.

A existência de um recurso não encerra a investigação: precisamos saber se é descoberto, compreendido, elegível e útil. A ausência também não justifica automaticamente construí-lo: uma alternativa já pode resolver a necessidade melhor e sem esforço relevante.

### 8.4 Trabalhos do cliente, antes de funcionalidades

O objetivo do cliente geralmente está ligado à vida que o carro viabiliza. A tabela registra trabalhos a investigar, sem escolher funcionalidades:

| Situação | Resultado desejado | Dificuldade possível | Evidência necessária |
|---|---|---|---|
| Trabalho e compromissos | Chegar e manter a rotina sem interrupção | Serviço incompatível com horários; espera; indisponibilidade | Episódio recente e impacto real |
| Escola e rotina familiar | Coordenar deslocamentos e responsabilidades | Informação ou decisão concentrada na pessoa errada | Identificar papéis e sequência |
| Abastecimento/estacionamento | Usar uma opção conveniente e com custo compreensível | Vantagem desconhecida, distante ou trabalhosa | Elegibilidade, tentativa e resultado |
| Manutenção | Cumprir o necessário com previsibilidade | Dúvida, agendamento difícil ou falta de confirmação | Fluxo observado e dados operacionais |
| Viagem e passeio | Organizar o plano com clareza sobre o veículo e condições | Informação dispersa ou regra pouco compreendida | Relato de preparação e alternativa usada |
| Evento ou atividade esportiva | Entender condições de uso relevantes | Dúvida sobre equipamento e regras | Caso concreto e orientação oficial disponível |
| Cobrança ou incidente | Entender a situação e obter uma resolução | Incerteza financeira, urgência ou exceção | Motivo de contato e conclusão |

**Não sabemos quais dessas situações concentram a maior dor.** Viajar, por exemplo, permanece apenas uma possibilidade a investigar. A decisão do recorte precisa vir da frequência, intensidade e capacidade de atuação sobre o problema.

## 9. Problema 2 — Alta dependência de atendimento humano

### 9.1 Subproblema 1: quais gargalos podem contribuir para os 80 mil+ contatos?

O case afirma sobrecarga com demandas que poderiam ser digitais, mas não fornece os motivos dos contatos ou a parcela evitável. [C1, p. 21] A pergunta precisa ser respondida com a sequência **necessidade → tentativa → barreira → contato → resultado**.

| Gargalo possível | Base disponível | Dado que confirma ou descarta |
|---|---|---|
| Login/recuperação de acesso | Relatos públicos na pesquisa anterior [R1, R2] | Erro, versão, aparelho e contato posterior pelo mesmo motivo |
| Contrato não reconhecido/sincronização | Relato público [R1] | Conta/contrato elegível, atualização e ocorrência registrada |
| Descoberta da função | Hipótese: o recurso existe, mas o cliente não o encontra | Tarefa observada e motivo do contato |
| Regra ou cobrança não compreendida | Jornada financeira e contrato existem; barreira é hipótese [C1, U1] | Dúvida recebida, informação vista e explicação que resolveu |
| Agendamento/seleção de local | Relatos públicos [R2] | Funil, erro, cidade, oficinas e disponibilidade real |
| Falta de status ou confirmação | O case já mostra acompanhamento; insuficiência é hipótese [C1, p. 31 e 36] | Atualização disponível versus perguntas e recontatos |
| Repetição entre canais | Relatos exploratórios de repetição [R1] | Quantas vezes o mesmo dado foi solicitado no episódio |
| Exceção ou dependência de operação | Hipótese apoiada por relatos de assistência [R1] | Poder de decisão, responsável, prazo e ação necessária |
| Atendimento para acompanhar promessa não cumprida | Hipótese, não frequência medida | Solicitação original, prazo e motivo do novo contato |

Relatos antigos não confirmam falha atual; recursos já documentados não podem ser descritos como inexistentes. Uma tela disponível também não garante conclusão: precisamos acompanhar o resultado operacional.

**Não conhecemos a contribuição de cada gargalo para o volume total.** Os 80 mil+ são contatos, não clientes únicos nem 80 mil falhas digitais. A divisão de 75% chat/25% telefone também não mede preferência.

### 9.2 Subproblema 2: por que buscar humano em uma demanda aparentemente simples?

“Simples” pode ser uma classificação da empresa. Para quem teme pagar um valor indevido, interromper o trabalho ou aceitar uma condição, a mesma tarefa pode ser importante e incerta.

Separar **consultar informação**, **interpretar sua aplicação**, **executar uma ação** e **resolver uma exceção**. O app pode permitir baixar o contrato, enquanto a pessoa ainda precisa entender uma cláusula; pode mostrar uma fatura, enquanto a pessoa deseja contestá-la. Consulta não equivale a interpretação ou resolução.

Há pelo menos seis explicações possíveis. Elas podem coexistir:

| Mecanismo | O que a pessoa precisa | Sinal ou referência | Como distinguir |
|---|---|---|---|
| Bloqueio técnico | Entrar ou concluir uma tarefa | Relatos públicos de acesso e agendamento [R1, R2] | Confirmar versão, erro e tentativa anterior |
| Informação insuficiente | Entender o que falta ou vai acontecer | Relato de informação antes da entrega; pesquisa de UX [R1, U1] | Comparar pergunta com informação disponível |
| Risco e confirmação | Saber se uma regra ou cobrança se aplica | Mecanismo de UX em outros contextos [U1] | Perguntar qual incerteza impedia a decisão |
| Exceção operacional | Obter ação fora do fluxo padrão | Relatos exploratórios sobre assistência [R1] | Verificar autoridade e disponibilidade necessárias |
| Menor esforço/canal familiar | Explicar a situação com menos trabalho | Relatos de repetição; hábito nacional de mensagens [R1, B2] | Comparar a sequência real dos canais |
| Relação e acolhimento | Sentir acompanhamento e responsabilidade | Relato de falta de humano e elogio a consultor [R1] | Identificar o que a pessoa entregou além da informação |

### 9.3 Três situações que precisam ser separadas

**Escolha:** a tarefa era possível digitalmente, mas o cliente quis conversar. Ainda precisamos conhecer o motivo.

**Contato induzido:** o cliente tentou o digital e encontrou uma barreira. Aqui, chamar o comportamento de “preferência pelo humano” esconderia o problema.

**Contato necessário:** a tarefa exigia avaliação, autorização, negociação ou ação operacional. A presença de um humano pode ser parte adequada do serviço.

Um mesmo cliente pode preferir autonomia para consultar um documento e atendimento para contestar uma cobrança. A unidade de análise deve ser o episódio, não um rótulo permanente de “cliente digital” ou “cliente humano”.

### 9.4 Como verificar se existe preferência pelo humano

Na entrevista, perguntar o que a pessoa tentou, quais opções conhecia e o que o atendente fez. Sempre que viável, observar uma tarefa em que o autoatendimento esteja disponível e funcione para aquele perfil.

Se a pessoa escolhe conversar porque quer interpretação ou confirmação, há uma preferência contextual a compreender. Se não consegue entrar, encontrar ou concluir, o contato é consequência de uma barreira. Se só um atendente pode executar a ação, a dependência está no processo.

**Resposta provisória ao subproblema:** não há evidência de preferência humana generalizada. Esforço, risco percebido, interpretação, familiaridade e exceções são mecanismos plausíveis. Precisamos distinguir escolha de contato induzido ou obrigatório e identificar o ganho entregue pelo humano em cada episódio.

## 10. O que as avaliações públicas acrescentam

A pesquisa anterior registrou 50 avaliações recentes da App Store brasileira, entre 11/05/2025 e 18/09/2026, além de três avaliações exibidas pela Google Play. O recorte contém elogios e críticas. [R1, R2, H1]

| Sinal encontrado | O que permite investigar |
|---|---|
| Elogios à facilidade e à autonomia | Em quais tarefas o canal já entrega valor |
| Pedido de informação completa antes da entrega | Expectativas e lacunas no acompanhamento |
| Relatos de acesso, reconhecimento do contrato e seleção de cidade | Barreiras técnicas ou de integração |
| Relatos de repetição de dados e procura reiterada de atendimento | Esforço e continuidade |
| Elogio à orientação de consultor | Interpretação e valor do apoio humano |
| Relato de sentir falta de humano | O que a pessoa esperava e não encontrou |

São relatos selecionados por mecanismos das lojas, não uma amostra representativa. Não temos idade ou renda dos autores; não reproduzimos falhas; alguns relatos dizem respeito a versões anteriores. Portanto, não estimamos prevalência nem afirmamos que os problemas persistem na versão atual.

**As avaliações servem para montar perguntas e selecionar tarefas de investigação.** A existência de experiências positivas é relevante: a pesquisa deve explicar tanto o que falha quanto o que funciona.

## 11. Onde pode estar a falta de conexão entre cliente e marca

“Falta de conexão” precisa virar algo observável. Propomos investigar quatro dimensões:

| Dimensão | Pergunta que revela o problema | Sinal possível |
|---|---|---|
| Reconhecimento | O serviço considera minha situação quando isso importa? | Cliente relata oferta ou informação incompatível com sua necessidade |
| Confiança | Posso acreditar na informação e no que foi combinado? | Busca repetida por confirmação, inconsistência ou promessa não cumprida |
| Continuidade | Meu assunto segue sendo acompanhado entre etapas e canais? | Repetição de dados, perda de histórico, responsabilidade indefinida |
| Valor percebido | Consigo identificar o que a assinatura faz por mim? | Dificuldade de explicar utilidade ou benefício efetivamente recebido |

Essas dimensões podem afetar a relação, mas ainda não medimos sua presença na base. Uma pessoa também pode estar satisfeita sem buscar proximidade emocional com a marca.

O contraste entre avaliação do app e avaliação relacional sugere investigar experiências além da interface: preço, entrega do carro, manutenção, disponibilidade, assistência, devolução e expectativas. Não demonstra que a causa esteja no aplicativo.

Para aprender sobre vínculo, perguntar por episódios: “Quando você sentiu que a Localiza ajudou?” e “Quando sentiu que precisava resolver tudo sozinho?”. “Você se conecta com a marca?” tende a produzir uma resposta abstrata.

## 12. Enquadramento: árvore de problemas

**Questão investigada:** por que, em determinado episódio de mobilidade, o cliente não obtém ou não percebe valor na relação com a assinatura?

```text
Primeiro, verificar se havia uma necessidade e uma oportunidade real de ajuda.
│
├── A. Não havia necessidade/oportunidade relevante
│   └── Pouca interação pode ser um resultado saudável, sem dor a resolver.
│
└── B. Havia uma necessidade ou oportunidade relevante
    ├── B1. Adequação: a oferta disponível não atende ao contexto
    ├── B2. Descoberta/acesso: existe ajuda, mas não é encontrada ou acessada
    ├── B3. Compreensão: informação ou regra não permite decidir com confiança
    ├── B4. Execução: a pessoa entende o que fazer, mas não conclui a ação
    ├── B5. Continuidade: iniciou a ação, mas não sabe ou não obtém seu desfecho
    ├── B6. Reconhecimento: o resultado ocorreu, mas seu valor não é percebido
    └── B7. Outro mecanismo ou evidência insuficiente
```

### Como aplicar MECE sem esconder sobreposições

O PDF orienta categorias mutuamente excludentes e coletivamente exaustivas. [M1, p. 22] Nesta classificação, registramos **um episódio uma vez**, pela primeira barreira demonstrada na sequência; causas posteriores ficam como fatores secundários.

Exemplo ilustrativo: a pessoa não consegue entrar no app, procura atendimento e repete dados. A primeira barreira é acesso; repetição e perda de continuidade são consequências/fatores secundários. Não contamos três pessoas ou três episódios.

A árvore é uma estrutura inicial. Preferência, urgência e privacidade atravessam etapas e devem ser registradas separadamente. Casos ambíguos precisam de revisão; a categoria “outro/evidência insuficiente” evita forçar relatos nas hipóteses do time. A exaustividade deve ser testada com casos reais.

## 13. Hipóteses causais e explicações alternativas

| Hipótese | Evidência que a fortaleceria | Evidência que a enfraqueceria |
|---|---|---|
| H1. Parte da baixa frequência decorre de pouca relevância contextual | Necessidade frequente e oferta atual desconhecida/inadequada | Cliente não precisa de apoio e está satisfeito com uso pontual |
| H2. Parte do atendimento é gerada por barreiras digitais | Tentativa anterior e bloqueio observável no mesmo episódio | Tarefa digital concluída; contato atende outra necessidade |
| H3. Informação ou confirmação insuficiente leva ao humano | Cliente identifica a lacuna e atendente a resolve | Informação era clara; contato exige uma ação diferente |
| H4. Falta de continuidade aumenta esforço e recontato | Mesma solicitação reaparece por ausência de atualização ou histórico | Novo contato trata de um assunto independente |
| H5. Benefícios têm baixa utilidade no contexto do cliente | Elegibilidade/disponibilidade inadequada ou esforço superior ao ganho | Uso simples e ganho percebido; baixa demanda legítima |
| H6. Esforço e promessas não cumpridas enfraquecem confiança | Episódios concretos ligados à avaliação da relação | Avaliação é explicada principalmente por preço ou mudança de necessidade |
| H7. Idade se relaciona com algumas barreiras, mediada por outros fatores | Diferenças persistem ao considerar tarefa e familiaridade | Diferenças são explicadas por habilidade, aparelho ou contexto |

Essa tabela organiza **hipóteses de causa**, não hipóteses de solução. Relações com renovação ou indicação exigem análise adicional; entrevistas isoladas não demonstram efeito causal.

Explicações concorrentes que precisam permanecer abertas: preço de renovação, alteração de renda, mudança de necessidade, troca de veículo, experiência operacional, condição contratual, ausência de interesse em benefícios ou preferência legítima por pouca interação.

## 14. Impacto do problema para cliente e empresa

| Frente | Impacto possível para o cliente | Consequência possível para a Localiza |
|---|---|---|
| Tempo e esforço | Buscar informações, repetir dados, esperar | Atendimento e recontato adicionais |
| Previsibilidade | Dificuldade de organizar horários ou compreender custos | Reclamação e perda de confiança |
| Disponibilidade do carro | Compromissos ou trabalho afetados | Pressão sobre operação e assistência |
| Benefícios | Valor anunciado não se transforma em ganho utilizável | Investimento com baixa percepção de valor |
| Relação | Sensação de falta de apoio ou responsabilidade | Possível efeito em avaliação, renovação e indicação |

As consequências são hipóteses até serem verificadas por episódio e dados internos. Não há estimativa validada de perda financeira ou ganho potencial neste documento.

Para dimensionar, medir: clientes afetados, episódios por período, duração, severidade, resultado e custo associado. Separar custo variável de capacidade já instalada. Menos contatos não representa economia automaticamente e pode indicar desistência se a resolução também cair.

## 15. Priorizar a investigação antes de priorizar a solução

O PDF recomenda concentrar recursos nas questões de maior impacto. Pareto é uma orientação de foco; **não temos evidência de que 20% das causas expliquem 80% dos problemas da Localiza**. [M1, p. 26–28]

| Prioridade de pesquisa | Por que investigar primeiro | Material necessário |
|---|---|---|
| 1. Motivos de contato e tentativa prévia | Distingue preferência, barreira e necessidade operacional | Taxonomia, episódios e resolução |
| 2. Tarefas concluídas, erros e recontatos | Separa uso eficiente de esforço repetido | Eventos por jornada e solicitação |
| 3. Valor percebido e benefícios | Avalia a oportunidade central apresentada no case | Experiências recentes, elegibilidade e uso confirmado |
| 4. Motivos de renovação/saída | Define o limite de influência do digital | Base elegível e fatores comerciais/operacionais |
| Transversal. Idade, habilidade, papel e região | Explica para quem e em quais condições a dificuldade aparece | Recrutamento diverso e cruzamentos |

Essa ordem expressa valor de informação para a pesquisa. Não afirma que a primeira frente seja a dor mais prevalente.

Depois da coleta, priorizar problemas por **alcance, frequência, intensidade, esforço atual, relação com o desafio e capacidade de atuação da Localiza**. Registrar a qualidade da evidência ao lado da avaliação. Evitar notas numéricas inventadas para aparentar precisão.

## 16. Plano de coleta para validar o problema

### 16.1 Entrevistas com assinantes

Uma rodada exploratória de aproximadamente **12–18 assinantes**, se houver acesso e tempo, pode ajudar a descobrir mecanismos. Não estima prevalência por idade ou retorno financeiro.

Diversificar: pouco e muito uso do app, com e sem contato recente, diferentes idades, habilidades digitais, cidades e tempos de contrato. Registrar PF/empresa e papel na conta. Quando possível, incluir quem está próximo da renovação e quem saiu recentemente, tratando esses grupos separadamente.

Não recrutar somente colegas entusiasmados com tecnologia. Se participarem, registrar sua relação com a assinatura; opiniões de não clientes não validam a dor de assinantes.

### 16.2 Perguntas sobre episódios reais

1. Por que você decidiu assinar e o que esperava deixar de administrar?
2. Conte a última situação em que precisou resolver algo relacionado ao carro ou contrato.
3. Qual era seu objetivo? O que tentou primeiro e depois?
4. Onde encontrou dificuldade? O que aconteceu como consequência?
5. Procurou atendimento? O que precisava que a pessoa fizesse?
6. Tentou o app antes? O contato foi escolha ou resultado de uma barreira?
7. Como soube que estava resolvido? Precisou confirmar novamente?
8. Conte uma situação em que conseguiu resolver sozinho com facilidade.
9. Em um mês tranquilo, quando percebe o valor da assinatura?
10. Já tentou usar um benefício? Qual foi a sequência e o resultado?
11. O que pesaria para renovar ou sair? Que experiência sustenta sua resposta?
12. Que tarefa no celular costuma fazer sozinho e em qual pede ajuda?

Evitar perguntas que induzem: “Você prefere humano, certo?”, “Um superapp ajudaria?” ou “Você usaria uma IA?”. Nesta etapa, precisamos entender necessidade, comportamento e alternativa atual.

### 16.3 Observar tarefas e consultar operação

Quando houver autorização e condições adequadas, observar uma tarefa real ou reconstruí-la com o cliente. Registrar a sequência, informação consultada, erro, canal e resultado. A observação deve preservar dados pessoais e não exigir contratação ou cobrança desnecessária.

Conferir os episódios com atendimento e operação: o que o processo permite, qual informação existe, quem executa a ação e o que depende de parceiro. O atendente pode identificar barreiras, mas sua interpretação não substitui a experiência do cliente.

### 16.4 Dados internos a solicitar

| Conjunto | Dados agregados ou acesso autorizado | Pergunta respondida |
|---|---|---|
| Definições | Bases, períodos, atividade, metodologia de NPS | Estamos comparando a mesma população? |
| Uso por tarefa | Início, conclusão, erro, abandono, tempo | Qual jornada concentra esforço? |
| Atendimento | Motivo, canal, cliente único, tentativa prévia, resolução e recontato | Por que o contato acontece e se resolve? |
| Operação | Disponibilidade, prazo, confirmação e cancelamento | A causa depende da interface ou da entrega? |
| Benefícios | Elegibilidade, visualização, tentativa e resgate confirmado | Falta adequação, descoberta ou execução? |
| Perfil/contexto | Idade em faixas, papel, região, PF/empresa, tempo de contrato | Quem é afetado e em quais condições? |
| Negócio | Elegibilidade de renovação, motivo de saída e indicação | Que fatores pesam no resultado? |

Dados individuais identificáveis não são necessários para muitos desses diagnósticos. Para relacionar eventos de uma mesma solicitação, usar apenas o acesso autorizado e os identificadores necessários.

## 17. Como analisar sem confundir correlação e causa

Usar uma ficha por episódio com: objetivo, disparador, sequência, primeira barreira, fatores secundários, consequência, alternativa, resultado, evidência e grau de confiança.

Comparações úteis:

- Frequência de app × conclusão de tarefas: pouco uso pode coexistir com alta eficiência.
- Contato × tentativa prévia × motivo: procurar atendimento não comprova rejeição ao app.
- Recontato × mesma solicitação: contatos diferentes não são automaticamente repetição.
- Idade × habilidade × tarefa: idade isolada não explica a barreira.
- Benefício × elegibilidade × região: não resgatar algo indisponível não é desinteresse.
- Renovação × preço × necessidade × histórico operacional: o digital é apenas um dos fatores possíveis.

As entrevistas explicam mecanismos e ajudam a construir categorias. Dados quantitativos estimam alcance quando têm amostra, cobertura e denominadores adequados. Se houver apenas usuários que escolheram usar um recurso, não atribuir sua maior renovação ao recurso sem considerar seleção e outros fatores.

### Métricas do diagnóstico

Medir conclusão por episódio, esforço percebido, tempo, erros, resolução no primeiro contato, recontato e compreensão do desfecho. Para benefícios, medir uso confirmado e ganho percebido. Para relacionamento, manter avaliação global separada da avaliação da interação.

MAU e frequência ajudam a contextualizar, mas não substituem resultado. NPS global não identifica sozinho a causa de um episódio. Não estabelecer metas de melhoria antes de conhecer a linha de base.

## 18. Critérios para fechar a etapa do problema

Antes de avançar ao conceito, o time precisa conseguir preencher:

| Pergunta | Evidência mínima desejada |
|---|---|
| Quem é afetado? | Papel, segmento e condições de uso descritos |
| Em qual situação? | Disparador e objetivo reconhecíveis |
| Qual é a dificuldade? | Episódios concretos e uma barreira identificável |
| Por que importa? | Consequência e esforço atual demonstrados |
| Como resolve hoje? | Alternativa e suas limitações |
| Qual é a causa provável? | Coerência entre relato, observação e processo |
| Qual é o alcance? | Dados disponíveis ou lacuna explicitada |
| A Localiza consegue atuar? | Responsáveis e limites operacionais conhecidos |
| O que pode contrariar o diagnóstico? | Evidência de sucesso e explicações concorrentes |

Um padrão em entrevistas pode justificar aprofundamento, mas não prova que a maioria da base sofre a mesma dor. Se o hackathon limitar a coleta, o pitch deve distinguir achados, hipóteses e validações planejadas.

**Modelo para a formulação final:**

> “[Público/papel], quando [situação], precisa [resultado], mas enfrenta [barreira demonstrada], o que gera [consequência]. Hoje resolve por [alternativa], com [limitação].”

Preencher esse modelo com evidência é o resultado esperado desta etapa. Se a maior dificuldade estiver no preço ou na operação, o diagnóstico deve refletir isso. Se a frequência baixa for saudável, ela não deve continuar sendo tratada como dor.

## 19. Síntese para discussão do time

**Mensagem principal:** precisamos investigar a distância entre a promessa de conveniência da assinatura e o valor que o cliente consegue obter e reconhecer em seus episódios de mobilidade.

### Respostas que podemos levar ao grupo hoje

| Subproblema | Conclusão sustentada nesta etapa |
|---|---|
| 36% com 1–2 acessos e 17% com 11+ | O uso é distribuído e compatível com tarefas pontuais; frequência sozinha não distingue utilidade, eficiência ou atrito |
| Funcionalidades diárias ausentes | Combustível/localização e descontos de estacionamento/pedágio estão documentados; outras capacidades e jornadas completas ainda precisam ser auditadas |
| Gargalos que geram atendimento | Há sinais de acesso, integração, agendamento e repetição, mas não temos prevalência atual nem atribuição do volume de contatos |
| Preferência por humanos em tarefas simples | Não demonstrada para a base; precisamos separar interpretação/risco, escolha, falha e exigência operacional |

### Duas formulações provisórias do problema

**Utilidade recorrente:** “O assinante pode ter necessidades de mobilidade além da gestão contratual que não são atendidas ou percebidas como úteis no contexto atual. Ainda precisamos identificar essas necessidades e separá-las do uso pontual saudável.”

**Dependência de atendimento:** “Em parte das demandas, o cliente pode não conseguir descobrir, compreender, executar ou confirmar uma ação com autonomia. Ainda precisamos localizar as barreiras e distinguir casos evitáveis das situações em que o atendimento agrega valor ou é necessário.”

Três argumentos sustentam a investigação:

1. **Adoção já existe.** O case apresenta 80,1% de acesso mensal e NPS do app 84; o problema precisa ser mais específico do que conquistar downloads ou acessos.
2. **Há oportunidade declarada de relevância e relacionamento.** O próprio case aponta benefícios pouco conectados ao contexto e uso pontual, mas ainda precisamos localizar as necessidades e suas consequências.
3. **Atendimento e negócio exigem decomposição.** Volume de contatos, renovação e indicação são importantes, porém não isolam causa, preferência ou influência do aplicativo.

**Formulação provisória para o grupo:**

> “O app Localiza Assinatura já é utilizado e bem avaliado. Queremos entender em quais situações o cliente ainda faz esforço relevante para aproveitar a assinatura ou não percebe um valor pertinente à sua mobilidade. Antes de escolher uma solução, vamos identificar quem é afetado, a causa, o impacto e como essa necessidade é atendida hoje.”

**Situação atual da investigação:** o desafio e os sinais documentais estão definidos; a dor prioritária, sua prevalência e suas causas específicas ainda precisam de validação. Essa é a base para a próxima etapa: conceito.

## 20. Fontes, rastreabilidade e limites

### Materiais do repositório — conferidos nesta etapa

- **[C1]** [Cases Meoo Ruptura — apresentação](<../../../Cases Meoo Ruptura ApresentaÃ§Ã£o CD.pdf>): p. 5–6, público/produto; p. 17, pesquisa de leads/clientes RAC; p. 19–22, case 2; p. 24–36, app e recursos. As páginas 19, 21 e 25 foram também inspecionadas visualmente.
- **[M1]** [Ideação e Validação de problemas — Ruptura](<../../../Ideacao e Validacao de problemas - Ruptura(1).pdf>): p. 11–12, etapas; p. 16–17, definição/SCQ; p. 20–22, árvores e MECE; p. 26–28, priorização/análise; p. 33–36, síntese e comunicação. Este documento usa a síntese para comunicar o diagnóstico, mantendo a resolução para a etapa posterior.
- **[M2]** [Aula o Problema](<../../../Aula o Problema.key.pdf>): p. 4, público/origem/impacto/recursos; p. 6, experiências dos usuários; p. 7, coleta, estruturação, hierarquização e validação.

### Fontes externas — consultadas novamente nesta etapa

- **[L2]** [Clube de Benefícios — página oficial](https://assinatura.localiza.com/clube-de-beneficios), consulta em 02/10/2026: categorias e acesso via app documentados; cartões dinâmicos de parceiros não foram resolvidos no conteúdo recebido. Cobertura/regulamentos individuais não auditados.
- **[L3]** [Descrição oficial do app — catálogo Apple Brasil](https://itunes.apple.com/lookup?id=1528537131&country=br), consulta em 02/10/2026: versão 5.2.0, publicada em 25/09/2026. A descrição anuncia descontos em hotéis, pedágios e estacionamentos, além das funções de contrato/serviços. É declaração do fornecedor; a jornada não foi testada.

### Fontes externas — aproveitadas da pesquisa anterior

As fontes abaixo foram registradas na pesquisa de 02/10/2026. Seu conteúdo não foi recolhido novamente nesta etapa; os limites e o recorte original estão preservados no histórico. São apoio ao diagnóstico, com diferenças de população, método e época.

- **[L1]** [Site oficial Localiza Assinatura](https://assinatura.localiza.com/): posicionamento, públicos e serviços divulgados. Conteúdo comercial; condições dependem do contrato.
- **[B1]** [Cetic.br — TIC Domicílios 2025, C2A](https://cetic.br/pt/tics/domicilios/2025/individuos/C2A/): uso de internet; base populacional por faixa, diferente da base Localiza.
- **[B2]** [Cetic.br — TIC Domicílios 2025, C5](https://cetic.br/pt/tics/domicilios/2025/individuos/C5/): comunicação; percentuais citados têm como base usuários de internet de cada recorte.
- **[B3]** [Cetic.br — TIC Domicílios 2025, I1A](https://cetic.br/pt/tics/domicilios/2025/individuos/I1A/): atividades/habilidades declaradas; não é teste de incapacidade. [Metodologia da pesquisa](https://cetic.br/pt/pesquisa/domicilios/).
- **[R1]** [App Store brasileira — Localiza Assinatura](https://apps.apple.com/br/app/localiza-assinatura-meoo/id1528537131) e [feed de avaliações recentes](https://itunes.apple.com/br/rss/customerreviews/id=1528537131/sortBy=mostRecent/json): recorte anterior de 50 relatos, sem representatividade ou reprodução das falhas.
- **[R2]** [Google Play — Localiza Assinatura](https://play.google.com/store/apps/details?id=com.localiza.meoo.app&hl=pt_BR&gl=BR): três relatos exibidos no conteúdo recebido na pesquisa anterior; seleção feita pela loja.
- **[U1]** [NN/g — Minimize the Need for Customer Service to Improve the Omnichannel UX](https://www.nngroup.com/articles/customer-service-omnichannel-ux/), 2016: mecanismos de contato em 45 jornadas de outros contextos; não estima comportamento Localiza.
- **[U2]** [NN/g — The User Experience of Chatbots](https://www.nngroup.com/articles/chatbots/), 2018: estudo com oito participantes nos EUA; anterior aos modelos generativos atuais.
- **[U3]** [NN/g — Consistency in the Omnichannel Experience](https://www.nngroup.com/articles/omnichannel-consistency/), 2016: consistência de informação entre canais e confiança.
- **[A1]** [W3C/WAI — Older Users and Web Accessibility](https://www.w3.org/WAI/older-users/): acessibilidade e possíveis necessidades, sem caracterizar indivíduos por idade.
- **[H1]** Histórico da pesquisa: [evidências e limites no commit 04abccd](https://github.com/Eduardo-Klausing/breaking-time-ruptura-2026/blob/04abccdeaedf6fa733b6c34e67df71a9018c13b1/pesquisa/case-2/04-evidencias-e-fontes/README.md) e [registro de coleta](https://github.com/Eduardo-Klausing/breaking-time-ruptura-2026/blob/04abccdeaedf6fa733b6c34e67df71a9018c13b1/pesquisa/case-2/04-evidencias-e-fontes/REGISTRO-DE-COLETA.json).

Não usamos relatos como proporção da base, demografia de leads como perfil dos assinantes, chat como sinônimo de humano ou frequência como sinônimo de valor. Não há neste documento validação de demanda, demonstração causal de retenção nem estimativa de retorno financeiro.
