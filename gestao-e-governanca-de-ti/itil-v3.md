---
description: >-
  Neste documento você vai encontrar um resumo dos principais conceitos e
  definições da biblioteca ITIL
---

# ITIL V3

## Introdução

Por muito tempo, a tecnologia da informação foi considerada um mero setor de suporte administrativo às organizações, um centro de custo que a princípio não gerava qualquer retorno para o negócio. A TI das organizações desempenhava funções meramente operacionais, como por exemplo, realizar manutenção da impressora, trocar o cartucho, instalar um novo software, formatar um computador e etc.

Com a evolução das tecnologias o setor de TI se tornou cada vez mais complexo e estratégico para as organizações, passando a ter um papel de destaque na tomada de decisão para atingir seus objetivos estratégicos.

Assim, a TI deixou de ser tratada por técnicos e passou a ser incorporada na estratégia da empresa para alcançar seus objetivos, garantindo que a TI sustente as estratégias e objetivos do negócio. A TI passou a ser a responsável pelo sucesso da organização.

Antes da popularização da tecnologia da informação, não havia necessidade realizar o gerenciamento dos serviços de TI, porém a partir dos anos 80, os serviços de TI passaram a ocupar um espaço mais relevante nas organizações, fazendo-se necessário um controle mais organizado dos serviços.

### O que é ITIL?

Ao pé da letra, **ITIL** é um acrônimo para _**Information Technology Infrastructure Library**_. Como o próprio nome diz, é uma biblioteca de Infraestrutura de Tecnologia da Informação. É composta por uma série de 5 livros, onde cada um representa uma fase do ciclo de vida do serviço:

* Estratégia de Serviço \(Service Strategy\)
* Desenho de Serviço \(Service Design\)
* Transição de Serviço \(Service Transition\)
* Operação de Serviço \(Service Operation\)
* Melhoria Contínua de Serviço \(Continual Service Improvement\)

![Os cinco principais livros da ITIL](../.gitbook/assets/livros-da-itil.jpg)

É um conjunto de livros/publicações que apresenta as melhores práticas para gerenciamento de serviços de TI. É considerado um padrão de mercado e largamente utilizado em todo o mundo. Atualmente, é de propriedade da **AXELOS**.

ITIL **não é uma norma** que tenha que ser seguida a risca, mas sim um guia de práticas que podem ser **adotadas** e **adaptadas** a organização conforme necessidade.

{% hint style="info" %}
\*\*\*\*👁**Para ficar de olho!**

Uma das recomendações do ITIL é que as organizações ajustem seu contexto às boas práticas ITIL, adotando-as, de modo a viabilizar transparentemente a estrutura de gerenciamento de serviços ~~padronizada~~ personalizada.

ITIL não é um padrão que tem que ser seguido; é um guia que deve ser lido e entendido, e usado para criar valor para o provedor do serviço e seus clientes.
{% endhint %}

A **ITIL** está organizada em 26 processos e 4 funções distribuídos em 5 estágios do ciclo de vida.

{% hint style="success" %}
✅ Outras definições de ITIL:

* É uma biblioteca composta por um conjunto de 5 livros
* É um framework público
* É um padrão aberto que se tornou de domínio público
* É um modelo/abordagem para gestão de serviços de TI
* É um modelo de gestão orientada à processos
* Conjunto de boas práticas de infraestrutura, operação e serviços de TI
* Padrão de boas práticas para gerenciamento de serviços de TI
{% endhint %}

{% hint style="danger" %}
❌ A ITIL não é:

* ITIL **não é modelo prescritivo**, ou seja, **não é uma metodologia**
* Também não é uma norma ISO
* Não é uma ferramenta que devemos instalar ou implementar
* Não especifica procedimentos, nem é um passo a passo
* Não é estático, pode ser adaptado para cada organização
* Não é teoria, mas sim baseado em práticas
{% endhint %}

### História da ITIL

A ITIL foi desenvolvida pelo CCTA _**\(Central Computer Telecommunications Agency\)**_ ****no final da década de 80, a partir de uma solicitação do governo britânico, que não estava satisfeito com o nível de qualidade dos serviços a ele prestado.

Em abril de 2001, o CCTA foi incorporado ao OGC _\(Office of Government Commerce\)_, que na época era o órgão responsável evolução da ITIL.

A versão 3 da ITIL foi lançada em maio de 2007 e representou uma grande evolução em relação à versão anterior, por organizar os processos de gerenciamento de serviços em um estrutura de ciclo de vida de serviço.

Em julho de 2011 foi publicada uma atualização da ITIL V3, que ficou conhecida como ITIL 2011.

## Conceitos Básicos

### Serviços

De acordo com a ITIL, um **serviço** é um meio de fornecer **valor** aos clientes, facilitando a obtenção de resultados que eles desejam, sem que eles tenham que arcar com a propriedade de determinados **custos** e **riscos**.

### Gerenciamento de Serviços

O Gerenciamento de Serviços é um conjunto especializado de **capacidades organizacionais** para fornecer valor para o cliente em forma de serviços.

Essas **capacidades organizacionais** especializadas incluem os **processos, métodos, funções, papéis e ativididades** que um provedor de serviços usa para permitir que eles prestem serviços a seus clientes.

### Processos

É  o conjunto de atividades coordenadas com o objetivo de produzir uma saída, com a criação de valor para um cliente ou parte interessada. A ITIL preconiza que um processo deve produzir **resultados específicos**, ser **orientado ao cliente**, ser **mensurável** e **responder a eventos específicos**. Os processos compõem o ciclo de vida do serviço.

### Funções

Um conjunto de **pessoas e recursos** empregados para realizar um ou mais processos ou atividades. Vários departamentos podem exercer uma função, assim como uma pessoa ou grupo podem exercer várias funções

### Papéis

O papel é um conjunto de responsabilidades e autoridades concedido a uma pessoa ou grupo de pessoas em determinados processos. A ITIL prevê os seguintes papéis:

* **Dono de serviço:** responsável pela iniciação, transição, manutenção e suporte de um serviço.
* **Dono de processo:** assegura que o processo seja executado conforme acordado e documentado. Patrocina o processo. Normalmente alguém da gerência sênior de TI.
* **Gerente de processo:** é quem gerencia o processo no dia a dia. Em organizações pequenas, também é o dono do processo.
* **Profissional de processo:** nome dado a quem participa da realização de alguma atividade dentro de um processo. Por exemplo, um analista de suporte é um Profissional de Processo no gerenciamento de incidente

## Ciclo de Vida

A ITIL trabalha com o conceito de ciclo de vida do serviço meio pelo qual fornece uma visão dos estágios do serviço. Os estágios pelos quais o serviço passa desde a sua concepção até seu encerramento. Um serviço nasce, se desenvolve, entra em operação e pode ser descontinuado. É necessário gerenciar o serviço durante todo o seu ciclo de vida.

Conforme já vimos anteriormente, o **núcleo** da ITIL v3 é constituído de **5 publicações** principais, sendo cada uma delas relacionada a um estágio do ciclo de vida do serviço. Cada parte do ciclo de vida de serviço exerce influência sobre as demais e conta com entradas, saídas e realimentações entre si.

A **Estratégia do Serviço** é o núcleo que **norteia** os demais estágios, e a **Melhoria Contínua de Serviço** é o estágio que **envolve** todo o ciclo, uma vez que todos os processos podem ser aperfeiçoados. Veja na figura abaixo.

![Ciclo de Vida da ITIL](../.gitbook/assets/screenshot_2020-02-18-kindle-cloud-reader.png)

Vejamos a definição de cada uma das publicações que compõem a ITIL v3:

São características básicas dos 5 estágios do ciclo de vida do serviço:

* **Estratégia de Serviços:** prevê e conceitua um conjunto de serviços que ajuda o negócio alcançar seus objetivos. São tomadas as decisões estratégicas em relação aos serviços que serão desenvolvidos.
* **Desenho de Serviços:** desenha ou projeta os serviços tendo em vista os objetivos de **utilidade** e **garantia**. Basicamente projeta o que a estratégia decidiu e descreve as especificações técnicas para transição de serviço.
* **Transição de Serviço:** move os serviços para o ambiente de produção. Os serviços são desenvolvidos, testados e liberados de forma controlada.
* **Operação de Serviço:** gerencia os serviços em produção para assegurar que sejam alcançados seus objetivos de utilidade e garantia. São os processos do dia a dia que mantém os serviços em funcionamento.
* **Melhoria Contínua de Serviço:** avalia os serviços e identifica formas de melhorar sua utilidade e garantia no suporte aos objetivos de negócio.

## Processos e Funções

Os processos e funções da ITIL encontram-se distribuídos entre os 5 estágios do ciclo de vida, veja o resumo na tabela a seguir:

<table>
  <thead>
    <tr>
      <th style="text-align:left">Est&#xE1;gios</th>
      <th style="text-align:left">Processos</th>
      <th style="text-align:left">Fun&#xE7;&#xF5;es</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><a href="itil-v3.md#estrategia-de-servicos">Estrat&#xE9;gia de Servi&#xE7;o</a>
      </td>
      <td style="text-align:left">
        <p></p>
        <ol>
          <li><a href="itil-v3.md#gerenciamento-da-estrategia-de-servico">Gerenciamento da Estrat&#xE9;gia de Servi&#xE7;os</a>
          </li>
          <li><a href="itil-v3.md#gerenciamento-de-portfolio">Gerenciamento de Portf&#xF3;lio</a>
          </li>
          <li><a href="itil-v3.md#gerenciamento-financeiro">Gerenciamento Financeiro</a>
          </li>
          <li><a href="itil-v3.md#gerenciamento-de-demanda">Gerenciamento de Demanda</a>
          </li>
          <li><a href="itil-v3.md#gerenciamento-de-relacionamento-com-o-negocio">Gerenciamento de Relacionamento com o Neg&#xF3;cio</a>
          </li>
        </ol>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="itil-v3.md#desenho-de-servico">Desenho de Servi&#xE7;o</a>
      </td>
      <td style="text-align:left">
        <p></p>
        <ol>
          <li><a href="itil-v3.md#coordenacao-do-desenho">Coordena&#xE7;&#xE3;o do Desenho</a>
          </li>
          <li>Gerenciamento de Cat&#xE1;logo de Servi&#xE7;o</li>
          <li>Gerenciamento de N&#xED;vel de Servi&#xE7;o</li>
          <li>Gerenciamento de Capacidade</li>
          <li>Gerenciamento de Disponibilidade</li>
          <li>Gerenciamento de Continuidade</li>
          <li>Gerenciamento de Seguran&#xE7;a da Informa&#xE7;&#xE3;o</li>
          <li>Gerenciamento de Fornecedores</li>
        </ol>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="itil-v3.md#transicao-de-servico">Transi&#xE7;&#xE3;o de Servi&#xE7;o</a>
      </td>
      <td style="text-align:left">
        <p></p>
        <ol>
          <li>Planejamento e Suporte &#xE0; Transi&#xE7;&#xE3;o</li>
          <li>Gerenciamento de Mudan&#xE7;as</li>
          <li>Gerenciamento de Configura&#xE7;&#xE3;o e Ativos de Servi&#xE7;o</li>
          <li>Gerenciamento de Libera&#xE7;&#xE3;o e Implanta&#xE7;&#xE3;o</li>
          <li>Avalia&#xE7;&#xE3;o de Mudan&#xE7;as</li>
          <li>Valida&#xE7;&#xE3;o e Testes de Servi&#xE7;o</li>
          <li>Gerenciamento do Conhecimento</li>
        </ol>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="itil-v3.md#operacao-de-servico">Opera&#xE7;&#xE3;o de Servi&#xE7;o</a>
      </td>
      <td style="text-align:left">
        <p></p>
        <ol>
          <li>Gerenciamento de Eventos</li>
          <li>Gerenciamento de Incidentes</li>
          <li>Gerenciamento de Problemas</li>
          <li>Cumprimento de Requisi&#xE7;&#xF5;es</li>
          <li>Gerenciamento de Acesso</li>
        </ol>
      </td>
      <td style="text-align:left">
        <p></p>
        <ol>
          <li>Central de Servi&#xE7;os</li>
          <li>Gerenciamento T&#xE9;cnico</li>
          <li>Gerenciamento de Aplica&#xE7;&#xF5;es</li>
          <li>Gerenciamento de Opera&#xE7;&#xF5;es de TI</li>
        </ol>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="itil-v3.md#melhoria-continua-de-servico">Melhoria Cont&#xED;nua de Servi&#xE7;o</a>
      </td>
      <td style="text-align:left">
        <p></p>
        <ol>
          <li>Melhoria em 7 passos</li>
        </ol>
      </td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>

## Estratégia de Serviços

O estágio da estratégia de serviços orienta as políticas e os processos de gerenciamento de serviços a serem implementados como ativos estratégicos no ciclo de vida do serviço.

> Orienta sobre como as políticas e processos de gerenciamento de serviço podem ser desenhadas, desenvolvidas e implementada como ativos estratégicos ao longo do ciclo de vida de serviço. Entre os tópicos abordados nesta publicação, estão os ativos de serviço, o catálogo de serviços, gerenciamento financeiro, gerenciamento do portfólio de serviços, desenvolvimento organizacional, riscos estratégicos etc.
>
> A Estratégia de Serviço busca **garantir que as organizações estejam em posição de lidar com custos e riscos associados a seus Portfólios de Serviços** e que estejam preparadas para a efetividade operacional e, indo além, para um desempenho diferenciado. As decisões tomadas na Estratégia de Serviço têm consequências de longo alcance, inclusive aquelas de efeito tardio.

Na estratégia de serviços se produz e mantém planos estratégicos.

Nesse estágio, busca-se responder algumas perguntas:

* Quais serviços oferecer e para quem?
* Como se diferenciar dos competidores?
* Como criar valor para os interessados no serviço?
* Como alocar recursos de forma eficiente?

### Os  4 Ps  da estratégia

![4 P&apos;s da estrat&#xE9;gia](../.gitbook/assets/4ps-estrategia.jpg)

* **Perspectiva**: é o direcionamento, visão estratégica da organização sobre o mercado, missão, valores e convicções.
* **Posição**: a imagem que a organização pretende passar para os clientes, ou seja, como o mercado enxerga a organização.
* **Plano**: traduz a estratégia para ações.
* **Padrão**: descreve as características essenciais dos serviços.

### Valor do serviço

Para a ITIL, o valor do serviço é medido pela combinação de **utilidade** + **garantia** do serviço.

É o grau em que as expectativas do cliente são atingidas, e pode ser definido em função de duas variáveis:

* **Utilidade:** adequado ao **propósito**. É a capacidade de atender às necessidades dos clientes e de minimizar as suas restrições.
* **Garantia:** adequado ao **uso**. Está relacionada ao atendimento dos requisitos de disponibilidade, capacidade, continuidade e segurança estabelecido pelos clientes.

![Valor do servi&#xE7;o](../.gitbook/assets/utilidadexgarantia.png)

### Tipos de provedores de serviço

Os tipos de provedores são classificados em 3 tipos:

1. **Tipo I**: interno e dedicado
2. **Tipo II**: interno e compartilhado
3. **Tipo III:** externo\(terceirizado\)

### Ativos estratégicos

O provedor de serviços cria valor para os seus serviços por meio dos **ativos de serviço**. Eles podem ser:

| **Habilidades** | **Recursos** |
| :--- | :--- |
| **Pessoas\(intelectual\)** | **Pessoas** |
| Conhecimento | Informações |
| Processos | Aplicações |
| Organização | Infraestrutura |
| Gerenciamento | Capital Financeiro |

**Recursos** e **habilidades** são considerados ativos de serviço de uma organização e são a base para a criação de valor para o serviço.

* **Habilidades**: aptidão da organização para executar atividades. São ativos intangíveis.
* **Recursos**: Infraestrutura, pessoas, dinheiro ou qualquer outra coisa que possa ajudar na entrega de serviços de TI.

{% hint style="success" %}
\*\*\*\*🧠 **Mnemônico!**

**Pessoas** detém o conhecimento...
{% endhint %}

### Estilos Organizacionais

* **Rede:**
* **Diretivo:**
* **Delegação:**
* **Coordenação:**
* **Colaboração:**

### Processos

Os processos integrantes da estratégia de serviço são:

#### Gerenciamento da Estratégia de Serviço

Neste processo, a ITIL cita a utilização da técnica **SWOT** para a realização da avaliação estratégica.

Para a prova, basta saber que SWOT é simplesmente a soma de siglas dos termos em Inglês: “Strengths” \(forças\), “Weakness” \(fraquezas\), “Opportunities” \(oportunidades\) e “Threats” \(ameaças\). Traduzindo a sigla temos: FOFA \(forças, oportunidades, fraquezas e ameaças\).

A matriz SWOT trata do levantamento e registro das forças, fraquezas, ameaças e oportunidades de uma organização ou área. Desta maneira, devem ser analisados os ambientes interno e externo à organização.

A **Análise SWOT** - é uma ferramenta de planejamento estratégico usada para avaliar forças \(_**S**trengths_\), fraquezas \(_**W**eakness_\) , ameaças \(_**T**hreats_\) e oportunidades \(_**O**portunities_\) envolvidas em um projeto, negócio, ou qualquer outra situação que exija uma decisão. As forças e fraquezas estão focadas nos aspectos internos da organização e as ameaças e oportunidades estão focadas nos aspectos externos. O mapeamento das forças e fraquezas internas da organização, e das ameças e oportunidades externas fornecem uma rápida visão da situação estratégica da organização.

#### Gerenciamento de Portfólio

O processo de gerenciamento de portfólio de serviço é responsável por gerenciar o portfólio de serviços durante todo o ciclo de vida de um serviço, focando no valor que os serviços entregam ao negócio.

O portfólio de serviço é conjunto completo de serviços que é gerenciado por um provedor de serviço. O portfólio de serviço é usado para gerenciar o ciclo de vida inteiro de todos os serviços de TI, incluindo três categorias: funil de serviço \(proposto ou em desenvolvimento\); catálogo de serviço \(em produção ou disponível para implantação\) e serviços obsoletos.

O portfólio de serviço está dividido em três partes:

1. **Funil de serviços**, ou _**pipeline de serviços**_, que mostra o que está em fila para ser desenvolvido \(serviços propostos ou em desenvolvimento\);
2. **Catálogo de Serviços**, que mostra os serviços que estão em operação ou disponível para implantação;
3. **Serviços Obsoletos**, que mostra os serviços que devem ser aposentados e os que estão fora de operação.

#### Gerenciamento de Demanda

#### Gerenciamento Financeiro

#### Gerenciamento de Relacionamento com o Negócio

{% hint style="info" %}
**Importante!**

**Termo de abertura**: um documento que contém detalhes de um novo serviço, uma mudança significativa ou outro projeto significante. Os termos de abertura são normalmente autorizados pelo gerenciamento de portfólio de serviço ou por um escritório de gerenciamento de projeto. O termo de abertura também é usado para descrever a ação de autorização do trabalho necessário para concluir a mudança de serviço ou de projeto. 
{% endhint %}

## Desenho de Serviço

> Fornece orientação para o desenho e desenvolvimento dos serviços e dos processos de gerenciamento de serviços, detalhando aspectos do gerenciamento do catálogo de serviços, do nível de serviço, da capacidade, da disponibilidade, da continuidade, da segurança da informação e dos fornecedores, além de mudanças e melhorias necessárias para manter ou agregar valor aos clientes ao longo do ciclo de vida de serviço.

Este estágio do ciclo de vida tem como foco o desenho e a criação de serviços de TI, cujo propósito será realizar a estratégia concebida no estágio de estratégia de serviço. Através do uso das práticas, processos e políticas de TI vigente, os serviços devem ser construídos de forma a assegurar a qualidade da entrega, a satisfação dos clientes, a eficiência dos custos e a facilidade de colocá-los em produção.

No desenho de serviço são feitas as especificações técnicas dos serviços de TI.

### Os 5 aspectos do desenho de serviço

* Soluções de serviço para serviços novos ou alterados
* Sistemas de informações de gerenciamento e ferramentas
* Arquitetura tecnológicas e de gerenciamento
* Processos
* Métodos de medição e métricas

### 4 Ps do desenho

Assim como na estratégia de serviços aqui no desenho de serviço também temos a definição dos 4 Ps, mas aqui eles estão mais focados no contexto técnico. Os 4P’s são os pilares necessários para que os objetivos do gerenciamento de serviços de TI possam ser alcançados.

* **Pessoas:** habilidade e competências necessárias para prover os serviços.
* **Produtos:** tecnologias necessárias para entregar os serviços.
* **Processos:** papéis e atividades envolvidos para prover os serviços.
* **Parceiros:** fornecedores que auxiliam o provimento dos serviços.

### Service Design Package\(SDP\)

É o documento que especifica todos os aspectos técnicos do serviço de TI.

### Acordo de Nível Operacional

O **Acordo de Nível Operacional** é um acordo entre o Provedor de Serviço de TI e outra parte da mesma organização. Esse acordo define mercadorias ou serviços a serem fornecidas e as responsabilidades de ambas as partes.

### Processos

#### Coordenação do Desenho

#### Gerenciamento de Catálogo de Serviço

#### Gerenciamento de Nível de Serviço

O **Gerenciamento de Nível de Serviço** visa manter e melhorar a qualidade dos serviços de TI através de um ciclo contínuo de atividades envolvendo planejamento, coordenação, elaboração, estabelecimento de acordo de metas de desempenho e responsabilidades mútuas, monitoramento e divulgação de níveis de serviço \(em relação aos clientes\), de níveis operacionais \(em relação a fornecedores internos\) e de contratos de apoio com fornecedores de serviços.

> SLA\(Service level agreement\) ou ANS\(Acordo de nível de serviço\) é um acordo **entre o provedor de serviços de TI e um cliente**. O acordo de nível de serviço descreve o serviço de TI, documenta metas de nível de serviço e especifica as responsabilidades do provedor de serviço de TI e do cliente. Um único acordo pode cobrir múltiplos serviços de TI ou múltiplos clientes.
>
> ANO\(Acordo de nível operacional\) é um acordo entre um **provedor de serviços de TI e outra parta da mesma organização**. Ele dá apoio à entrega, pelo provedor de serviço de TI, de serviços de TI a clientes e define os produtos ou serviços a serem fornecidos e as responsabilidades de ambas as partes.

{% hint style="info" %}
\*\*\*\*💡**Dica:** veja que a maior diferença entre os dois é o cliente em si. Enquanto no ANS o cliente é externo ao provedor de serviço, no ANO esse cliente é da mesma organização.
{% endhint %}

#### Gerenciamento de Capacidade

{% hint style="info" %}
**Gerenciamento de Capacidade de Negócio** - garantir que os requisitos de negócio futuros definidos para os serviços de TI sejam considerados e compreendidos para serem usados em um plano de capacidade. O gerenciamento de capacidade do negócio traduz as necessidades e planos de negócio em serviço e infraestrutura de TI, garantindo que requisitos do negócio futuros sejam quantificados, desenhados, planejados e implementados de forma oportuna.

**Gerenciamento de Capacidade de Serviço** - o foco desse subprocesso é o gerenciamento, controle e prognóstico sobre o desempenho e capacidade de uso e carga de trabalho dos serviços operacionais de TI ativos, de ponta a ponta. Isso garante que o desempenho de todos os serviços, detalhados por meio de metas estabelecidas em acordos de nível de serviço e requisitos de nível de serviço, seja monitorado e medido e que os dados coletados sejam registrados, analisados e reportados, com vistas ao atendimento desses acordos.

**Gerenciamento de Capacidade de Componente \(recurso\)** - o foco desse subprocesso é o gerenciamento, controle e prognóstico sobre o desempenho, utilização e capacidade de componentes \(recursos\) individuais de Tecnologia da Informação.
{% endhint %}

#### Gerenciamento de Disponibilidade

O processo de gerenciamento da disponibilidade visa assegurar que os serviços de TI sejam projetados para atender e preservar os níveis de disponibilidade e confiabilidade requeridos pelo negócio.

> Este processo é responsável por garantir que os serviços de TI atendam às necessidades atuais e futuras de disponibilidade do negócio de uma maneira mais efetiva em custo e mais oportuna. O gerenciamento de disponibilidade define, analisa, planeja, mede e melhora todos os aspectos da disponibilidade de serviços de TI e garante que todos os processos, infraestruturas, ferramentas, papéis, etc. de TI sejam adequados para as metas de nível de serviço acordadas para disponibilidade.

Este processo atua em 2 níveis de tratamento:

**Atividades reativas**: **monitoramento**, medição, análise e gerenciamento de eventos, incidentes e problemas envolvendo indisponibilidade de serviço.

**Atividades proativas**: **planejamento** proativo, **projeto**, recomendação e melhoria de disponibilidade.

{% hint style="info" %}
\*\*\*\*✏**Nota:** Definições importantes

* **Disponibilidade:** refere-se a habilidade de um serviço, componente ou item de configuração **desempenhar suas funções acordadas quando necessário**.
* **Confiabilidade:** tempo que um serviço ou componente pode funcionar **sem interrupção** em conformidade com o acordo.
* **Sustentabilidade:** rapidez que um serviço, componente ou item de configuração consegue ser **restaurado** para seu estado normal após uma falha.
* **Serviceability:** é a habilidade de um fornecedor em atender os termos de seu contrato. É a medida de quão efetivamente os fornecedores terceirizados entregam seus serviços conforme acordado contratualmente.  
{% endhint %}

![](../.gitbook/assets/tempo-medio-entre-incidentes.jpg)

#### Gerenciamento de Continuidade

> **Este processo é responsável pelo gerenciamento de risco que podem impactar seriamente o negócio**. O gerenciamento de continuidade de negócio protege as conveniências das principais partes interessadas, reputação, marca e atividades de criação de valor. O processo envolve a redução de riscos a um nível aceitável e planejamento para a recuperação de processos de negócio caso ocorra uma interrupção ao negócio. O gerenciamento de continuidade de negócio define objetivos, escopo e requisitos para o gerenciamento de continuidade de serviço de TI.

#### Gerenciamento da Segurança da Informação

O gerenciamento de segurança da informação, que faz parte do estágio de Desenho de Serviço, define os seguintes objetivos:

* Garantir que o acesso à informação seja fornecido de maneira correta \(**confidencialidade** dos dados\);
* Garantir que a informação seja entregue completa, precisa e protegida contra a modificação \(**integridade** dos dados\);
* Disponibilizar a informação e deixá-la disponível para uso quando requerida, preparando os sistemas de TI para que possam resistir aos ataques e prevenindo contra falhas de segurança \(**disponibilidade** dos dados\);
* Garantir a confiabilidade das transações \(troca de informações\) que existem na organização e entre parceiros \(**autenticidade**\).

Segundo a ITIL, o processo Gerenciamento de Segurança da Informação visa garantir que uma Política de Segurança será construída, mantida e implementada, cobrindo tanto o uso quanto o uso indevido de todos os sistemas e serviços de TI.

#### Gerenciamento de Fornecedores

## Transição de Serviço

O estágio de transição do serviço tem como principal objetivo colocar no ambiente de produção, em plena operação, um serviço que acabou de sair do estágio de desenho do serviço.

> Orienta sobre como efetivar a transição de serviços novos e modificados para operações implementadas, detalhando os processos de planejamento e suporte à transição, gerenciamento de mudanças, gerenciamento da configuração e dos ativos de serviço, gerenciamento da liberação e da distribuição, teste e validação de serviço, avaliação e gerenciamento do conhecimento.

A fase de transição de serviço da ITIL define 7 processos, sendo que um deles é específico para o Planejamento e suporte da transição de serviço, o que invalida a questão, já que o gerenciamento de mudanças é outro processo da fase de transição. Vejamos todos os processos dessa fase:

* Planejamento e suporte de transição;
* Gerenciamento de mudanças;
* Gerenciamento de ativos de serviço e de configuração;
* Gerenciamento de liberação e implantação;
* Validação e teste de serviço;
* Avaliação de mudança;
* Gestão do conhecimento.

Resumidamente os processos de Transição do Serviço da ITIL v3, apresentados por FERNANDES e ABREU \(2012\) v3 são:

**Planejamento e Suporte à Transição:** tem o objetivo de planejar e coordenar os recursos necessários para colocar um serviço novo ou modificado no ambiente de produção, dentro do custo, do prazo e da qualidade estimados.

**Gerenciamento de Mudanças:** visa assegurar o tratamento sistemático e padronizado de todas as mudanças ocorridas no ambiente operacional, para minimizar os impactos provocados por eventuais incidentes e ou problemas, decorrentes destas mudanças.

**Gerenciamento de Ativos de Serviço e da Configuração:** abrange identificação, registro, controle e verificação de ativos de serviço e itens de configuração \(componentes de TI, tais como hardware, software e documentação relacionada\), incluindo suas versões, componentes e interfaces, dentro de um repositório centralizado.

**Gerenciamento da Liberação e da Distribuição:** é o gerenciamento das atividades que envolvem mudanças autorizadas em um serviço de TI \(incluindo atividades de planejamento, desenho, construção, configuração e teste de itens de software e hardware\), visando criar um conjunto de componentes finais para ser implantado em um ambiente de produção.

**Validação e Teste do Serviço:** processo que busca a garantia da qualidade de uma liberação visando a entrega de um serviço validado e testado, pronto para o uso dentro dos propósitos para os quais foi desenhado e construído.

**Avaliação de Mudanças:** visa criar meios padronizados e consistentes para avaliar o desempenho de uma mudança em uma infraestrutura de TI e serviços já existente, a partir de metas pré-estabelecidas inclusive com o gerenciamento dos desvios encontrados.

**Gerenciamento do Conhecimento:** busca garantir a entrega da informação nas condições adequadas para a tomada de decisão, por meio do uso de um Sistema de Gerenciamento do Conhecimento sobre Serviços e de uma base de conhecimento ampla, contendo informações tais como experiência da equipe, requisitos, habilidades e expectativas dos fornecedores e parceiros, histórico de configurações, etc.

### Processos

#### Gerenciamento de Mudanças

> Segundo a ITIL v3., nenhuma mudança deve ser aprovada sem ter explicitamente definida a questão do que fazer se ela não for bem sucedida. Idealmente, deve haver um plano de volta à situação inicial, geralmente por meio da restauração dos conjuntos de linhas de base dos Itens de Configuração.
>
> Portanto, o **Plano de Remediação** consiste em um procedimento ou roteiro usado no caso da mudança não ser bem sucedida.
>
> Dito isto, cabe ressaltar que **nenhuma mudança deve ser autorizada sem que esteja definido o plano exato do que fazer se esta mudança falhar**. É neste contexto que entra o Plano de Remediação, que irá restaurar o serviço a seu estado original, muitas vezes através de procedimentos de restauração de uma Baseline.

{% hint style="warning" %}
\*\*\*\*⭐**Caiu na prova!**

A ITIL faz distinção entre três tipos diferentes de mudança:

* **Mudança padrão:** alterações pré-autorizadas e de baixo risco que seguem um procedimento conhecido.
* **Mudança de emergência:** alterações que devem ser implementadas imediatamente, por exemplo, para resolver um incidente grave.
* **Mudança normais:** todas as outras alterações que não são alterações padrão ou mudanças de emergência.

As Mudança Normais são frequentemente categorizadas como _Major, Significant or Minor_, dependendo do nível de risco envolvido. As organizações devem definir, em suas políticas de mudança, esses tipos de mudanças e as autoridades que devem ser envolvidas em cada uma destas . As mudanças podem exigir, por exemplo, reuniões regulares com o _**CAB \(Change Advisory Board\)**_ com o objetivo de que estas tenham o adequado tratamento.
{% endhint %}

**Mudanças Técnicas**: Mudanças que possam impactar componentes de TI, porém não alteram os serviços. Geralmente, são mudanças necessárias para compoentes de TI.  
  
**Mudanças Operacionais**: Mudanças que possam impactar serviços operacionais da empresa. São relacionadas à serviços e devem ser originadas nos ciclos Desenho de Serviço e/ou Melhoria Continuada de Serviços.  
  
**Mudanças Táticas**: Mudanças que possam impactar os serviços que atentedem atividades comerciais da organização. Estão originadas no ciclo de Estratégia de Serviços.  
  
**Mudanças Estratégicas**: Mudanças que possam impactar serviços estratégicos da organização. Geralmente são serviços que, em caso de falha, causam perdas financeiras, implicações legais ou danos à imagem da empresa.

#### Gerenciamento de Configuração e Ativo de Serviço

Esse processo é responsável, dentre outros, por:

* identificar, **controlar,** registrar, auditar e verificar **ativos de serviço e itens de configuração**, incluindo versões, linhas de base, componentes constituintes, atributos e **relacionamentos.**
* gerenciar e proteger a integridade dos ativos de serviço e itens de configuração ao longo de todo ciclo de vida do serviço, garantindo que somente componentes autorizados sejam usados e que apenas mudanças autorizadas sejam realizadas.
* estabelecer e manter um acurado e completo **Sistema de Gerenciamento de Configuração**.

#### Avaliação das Mudanças

É **responsável pela avaliação formal de um serviço de TI** novo ou alterado para garantir que os riscos tenham sido gerenciados e para **ajudar a determinar se a mudança deve ser autorizada**.

Além disso trata da avaliação da relevância do desenho do serviço, da abordagem de transição e da adequação do serviço novo ou alterado aos ambientes operacionais e de negócios.

## Operação de Serviço

A **Operação de Serviços** é o único estágio que, além de possuir processos, **possui funções**. Elas são quatro, a saber: **Central de Serviço**, Gerenciamento Técnico, Gerenciamento de Aplicações e Gerenciamento das Operações de TI.  
  
A **Central de Serviços** é uma unidade funcional composta por uma equipe e recursos, **cujo objetivo é ser um ponto focal de contato dos usuários quando ocorre uma interrupção do serviço**, para receber requisições de serviço ou mesmo lidar com algumas categorias de Requisição de Mudança. Sim, é o famoso service desk.

> Descreve a fase do ciclo de vida do gerenciamento de serviços que é responsável pelas atividades do dia a dia, orientando sobre como garantir a entrega e o suporte a serviços de forma eficiente e eficaz e detalhando os processos de gerenciamento de eventos, incidentes, problemas, acesso e de execução de requisições.

Este é o estágio que se preocupa em entregar aos clientes e usuários os níveis de serviço acordados e gerenciar as aplicações, tecnologia e infraestrutura que suportam a entrega do serviço. É nele que os serviços efetivamente entregam **valor** ao cliente.

> O estágio Operação do Serviço gerencia os serviços em produção para assegurar que sejam alcançados os seus objetivos de utilidade e garantia. Nele estão os processos do dia a dia, que mantêm os serviços funcionando.
>
> Dito isso, os seguintes processos fazem parte da Operação de Serviço:
>
> * **Gerenciamento de eventos**
> * **Gerenciamento de incidentes**
> * **Execução de requisição**
> * **Gerenciamento de acesso**
> * **Gerenciamento de problema**
>
> E as seguintes funções são desempenhadas no contexto da Operação de Serviço:
>
> * **Central de serviços**
> * **Gerenciamento técnico**
> * **Gerenciamento de operações de TI**
> * **Gerenciamento de aplicações**

{% hint style="info" %}
\*\*\*\*✏**TOME NOTA!**

É o estágio responsável pelas atividades do dia a dia, orientando sobre como garantir a entrega e o suporte a serviços de forma eficiente e eficaz, detalhando os processos de gerenciamento de **eventos**, **incidentes**, **problemas**, **acesso** e **execução de requisições**.
{% endhint %}

### Processos

#### Gerenciamento de Eventos

#### Gerenciamento de Incidentes

O Gerenciamento de Incientes visa garantir que a operação normal de um serviço seja restaurada tão rapidamente quando possível.

O objetivo do **Gerenciamento de Incidentes** é restaurar o serviço o mais rápido possível. Se o incidente não puder ser resolvido rapidamente, ele pode ser escalado funcionalmente ou hierarquicamente.

> Conforme a ITIL V3, os passos relacionados a execução do processo de gerenciamento de incidentes são os seguintes:
>
> 1. **Identificação de incidentes**: reconhecimento do incidente;
> 2. **Registro de incidentes \(recording\)**: incidentes são registrados em uma ferramenta específica;
> 3. **Categorização e priorização do incidente \(classification\)**: incidentes são classificados, bem como é realizada a avaliação da urgência que um determinado incidente deve ser resolvido;
> 4. **Diagnóstico de incidentes**: Se deve em um primeiro momento fazer uso da base de conhecimento \(formada por outros problemas, incidentes e erros conhecidos\) pelos atendentes do primeiro nível de suporte **\(matching\)**. Em seguida deve ser realizado o entendimento do incidente que foi identificado e registrado **\(diagnosis\)**;
> 5. **Escalada de incidentes**: caso o atendente do primeiro nível não consiga solucionar o incidente, este é escalonado para níveis de suporte superiores;
> 6. **Resolução de incidentes**: ocorre a solução do incidente registrado;
> 7. **Fechamento de incidentes**: encerramento do incidente registrado.

#### Gerenciamento de Problemas

O Gerenciamento de Problemas visa minimizar o impacto de incidentes e problemas, podendo ser reativo ou proativo, ou seja, pode se antecipar ao problema ou pode servir para minimizar seus efeitos.

{% hint style="info" %}
\*\*\*\*✏**Nota:** Definições importantes

**Solução de contorno:** Redução ou eliminação do impacto de um incidente ou problema para o qual uma resolução completa ainda não está disponível, por exemplo, reiniciando um item de configuração em falha. Soluções de contorno para problemas são documentadas nos registros de erro conhecido. As soluções de contorno para incidentes que não possuem um registro de problema associado são documentadas no registro de incidente

**Evento:** Uma mudança de estado que possui significado para o gerenciamento de um item de configuração ou serviço de TI. Evento também é o termo usado para quando um alerta ou notificação é criado por qualquer serviço de TI, item de configuração ou ferramenta de monitoração. Eventos geralmente requerem uma ação da equipe de operações de TI e às vezes podem levar à geração e registro de incidentes.

**Incidente:** Uma interrupção não planejada de um serviço de TI ou uma redução da qualidade de um serviço de TI. A falha de um item de configuração que ainda não afetou o serviço também é um incidente, por exemplo, a falha em um disco de um conjunto espelhado.

**Alerta:** Uma notificação de que certo limite foi atingido, algo mudou ou uma falha ocorreu. Alertas são muitas vezes criados e gerenciados por ferramentas de gerenciamento de sistema e são gerenciados pelo processo de gerenciamento de evento.

**Evento:** Qualquer ocorrência que tenha significado para o serviço ou para o gerenciamento de um item de configuração.

**Incidente:** Uma interrupção não planejada de um serviço de TI ou uma redução da qualidade de um serviço de TI. A falha de um item de configuração que ainda não afetou o serviço também é um incidente, por exemplo, a falha em um disco de um conjunto espelhado.

**Problema:** a causa raiz de um ou mais incidentes. A causa geralmente não é conhecida no momento em que o registro de problema é criado e o processo do gerenciamento de problema é responsável pela investigação a ser conduzida.
{% endhint %}

#### Cumprimento de Requisição

É o processo de tratamento de solicitações de baixo risco que ocorrem com frequência e de atendimento de baixo custo. Pode envolver a solicitação de informações ou serviços simples, como instalação de software ou autorizações de acesso.

#### Gerenciamento de Acesso

### Funções

#### Central de Serviços

#### Gerenciamento Técnico

#### Gerenciamento de Aplicações

#### Gerenciamento de Operações de Serviço

## Melhoria Contínua de Serviço

Melhoria Contínua do Serviço: orienta, através de princípios, práticas e métodos de gerenciamento da qualidade, sobre como fazer sistematicamente melhorias incrementais e de larga escala na qualidade do serviço, **com base principalmente no modelo PDCA** preconizado pela ISO/IEC 20000.

**PDCA** \(do inglês: **PLAN** - **DO** - **CHECK** - **ACT** ou Adjust\) é um método iterativo de gestão de quatro passos, utilizado para o controle e melhoria contínua de processos e produtos.

## Provas recentes

* TJ/PA
* SEFAZ/DF
* SEFAZ/AL
* SEFAZ/RS
* COGE/CE
* SEFAZ/BA
* SEMEF/MA
* TRF 4
* TJ/MA
* TCE/RO
* TJ/AM
* TRF 3
* DPE/AM

