---
description: >-
  Neste documento descreveremos os conceitos por trás da ITIL bem como seus
  processos
---

# ITIL V3

## Introdução

ITIL é um framework público que descreve as melhores práticas para gerenciamento de serviços de tecnologia da informação \(TI\). ITIL é um acrônimo de _Information Technology Infrastructure Library_.

Como o próprio nome sugere, a ITIL é uma biblioteca composta por 5 livros, são eles: **Service Strategy**, **Service Design**, **Service Transition**, **Service Operation** e **Continual Service Improvement**.

{% hint style="success" %}
Outras definições de ITIL:

* É uma biblioteca composta de 5 livros
* É um padrão aberto que se tornou de domínio público
* É uma abordagem/modelo para gestão de serviços de TI
* É um modelo de gestão baseado em processos
* Conjunto de boas práticas de infraestrutura, operação e serviços de TI
* Padrão de boas práticas para gerenciamento de serviços de TI
{% endhint %}

{% hint style="danger" %}
ITIL não é:

* Não é uma metodologia, nem norma ISO
* Não é uma ferramenta que devemos instalar ou implementar
* Não especifica procedimentos, nem é um passo a passo
* Não é estático, pode ser adaptado
* Não é teoria, é baseado em práticas
{% endhint %}

### Histórico

## Conceitos Básicos

> Um **serviço** é um meio de entregar valor aos clientes, facilitando os resultados que os clientes querem alcançar, sem ter que assumir custos e riscos específicos.

> O **Gerenciamento de Serviços** é um conjunto de capacidades organizacionais para fornecer valor para o cliente em forma de serviços.

## Ciclo de Vida

A ITIL trabalha com o conceito de ciclo de vida do serviço que se traduz em estágios pelos quais o serviço passará desde a sua concepção até seu encerramento.

![Vis&#xE3;o geral do modelo](../.gitbook/assets/screenshot_2020-02-18-kindle-cloud-reader.png)

## Processos e Funções

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
        <ol>
          <li>Gerenciamento de Estrat&#xE9;gia de Servi&#xE7;os</li>
          <li>Gerenciamento de Portf&#xF3;lio</li>
          <li>Gerenciamento Financeiro</li>
          <li>Gerenciamento de Demanda</li>
          <li>Gerenciamento de Relacionamento com o Neg&#xF3;cio</li>
        </ol>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="itil-v3.md#desenho-de-servico">Desenho de Servi&#xE7;o</a>
      </td>
      <td style="text-align:left">
        <ol>
          <li>Coordena&#xE7;&#xE3;o do Desenho</li>
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
        <ol>
          <li>Planejamento e Suporte &#xE0; Transi&#xE7;&#xE3;o</li>
          <li>Gerenciamento de Mudan&#xE7;as</li>
          <li>Gerenciamento de Configura&#xE7;&#xE3;o e Ativos</li>
          <li>Gerenciamento de Libera&#xE7;&#xE3;o e Implata&#xE7;&#xE3;o</li>
          <li>Avalia&#xE7;&#xE3;o de Mudan&#xE7;as</li>
          <li>Valida&#xE7;&#xE3;o e Testes de Servi&#xE7;os</li>
          <li>Gerenciamento do Conhecimento</li>
        </ol>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="itil-v3.md#operacao-de-servico">Opera&#xE7;&#xE3;o de Servi&#xE7;o</a>
      </td>
      <td style="text-align:left">
        <ol>
          <li>Gerenciamento de Eventos</li>
          <li>Gerenciamento de Incidentes</li>
          <li>Gerenciamento de Problemas</li>
          <li>Cumprimento de Requisi&#xE7;&#xF5;es</li>
          <li>Gerenciamento de Acesso</li>
        </ol>
      </td>
      <td style="text-align:left">
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
        <ol>
          <li>Melhoria em 7 passos</li>
        </ol>
      </td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>

## Estratégia de Serviço

Na estratégia de serviços define-se o plano estratégico para o serviço de TI.

Nesse estágio, busca-se responder as seguintes perguntas:

### Os  4 Ps  da estratégia

* **Perspectiva**:
* **Posição**:
* **Plano**:
* **Padrão**:

### Valor do serviço

**Utilidade** + **Garantia**

### Tipos de provedores de serviço

Os tipos de provedores são classificados em 3 tipos:

1. **Tipo I**: interno e dedicado
2. **Tipo II**: interno e compartilhado
3. **Tipo III:** externo\(terceirizado\)

### Ativos estratégicos

* **Habilidades**: Pessoas, conhecimento
* **Recursos**: Pessoas, informação

### Processos

## Desenho de Serviço

No desenho de serviço são feitas as especificações técnicas dos serviços de TI.

## Transição de Serviço

Em elaboração

## Operação de Serviço

### Processos

### Funções

## Melhoria Contínua de Serviço

Em elaboração

