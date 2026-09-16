# Rádio e Modulação

A comunicação via rádio é um dos pilares operacionais do serviço policial. Sua correta utilização garante agilidade, precisão e segurança nas ações coordenadas entre as viaturas, centrais e demais unidades da força.

O uso do rádio não é opcional: todo policial deve estar familiarizado com os procedimentos e códigos adequados.

## Regras Gerais

* Todo policial de serviço deve manter o rádio ativo e monitorado durante todo o tempo de atuação.
* O rádio é exclusivo para comunicações operacionais — proibido para conversas pessoais ou piadas.
* Antes de transmitir, verifique se o canal está livre, evitando interferências.
* Utilize sempre linguagem adequada. Palavrões ou termos ofensivos são proibidos.
* Seja breve e objetivo: evite transmissões longas, vagas, repetitivas ou desnecessárias.
* O rádio não deve ser usado para questionar ou discutir ordens de superiores.
* Conversas paralelas na frequência comprometem o fluxo de informações.
* Ao ouvir **“Prioridade, Código 5”**, cesse imediatamente qualquer comunicação até que a situação crítica seja resolvida.
* Sempre confirme o recebimento das mensagens com **“QSL”**.
* A responsabilidade pela comunicação cabe ao **P2 da viatura primária** ou ao piloto do GAEP, SAER, DOA ou GRAER.
* Quando todas as viaturas em uma ocorrência estiverem visualizadas, limite as transmissões ao essencial.
* Em operações com múltiplas QRUs ativas, redobre a atenção para não interromper outras transmissões e identifique sua equipe de forma rápida e clara.

## Estrutura da modulação

Toda modulação começa com **“QAP Central”**, seguida da identificação da **QSV** e da comunicação do **Código 0** ou da ocorrência, usando corretamente os [Códigos Q](codigos-q.md).

```
QAP Central, QSV [nº/modelo], [mensagem objetiva], [código da ocorrência]
```

## Modelos de modulação

{% tabs %}
{% tab title="Entrada em serviço" %}
> QAP Central, QSV (01), iniciando Código 0. Disponível para QRU.

Obrigatória no primeiro Código 0 após acordar na cidade.
{% endtab %}

{% tab title="Apoio para abordagem" %}
> QAP Central, QSV (01), iniciando abordagem de Código (X) em um (veículo ou indivíduo), no QTH (X). Solicito QRR no meu QTH.
{% endtab %}

{% tab title="Acompanhamento" %}
> QAP Central, QSV (01) iniciando acompanhamento a um (veículo), cor (X), na QRU (X). Disponível para mais 2 QSVs e apoio aéreo.
{% endtab %}

{% tab title="Código 5" %}
> QAP Central, QRA [seu QRA], liberando Código 5 no acompanhamento do [modelo do veículo], o mesmo efetuou disparos contra a guarnição, solicito QRR no [QTH].

**Exemplo:** “QAP Central, QRA Juca, liberando Código 5 no acompanhamento do Silvia preto, o mesmo efetuou disparos contra a guarnição, solicito QRR no QTH do Hospital.”
{% endtab %}

{% tab title="Encerramento" %}
> QAP Central, Código 4 na QRU do veículo (X), cor (X), QRU de (X).
{% endtab %}
{% endtabs %}

## Chat Policial — PR

O rádio deve ser usado apenas para comunicações que exigem retorno imediato. O **chat policial (PR)** é o canal para situações sem caráter emergencial:

| Situação | Mensagem |
| --- | --- |
| Solicitação de viatura | “QAP Central, alguma viatura com vaga disponível para P2 ou P3?” |
| Início de patrulha | “QAP Central, iniciando Cód. 0. Qualquer QRR ou QRU só lançar na rede.” |
| Mensagem a outro policial | “QAP Comando, poderia comparecer à DP3 se possível?” |

## Boas práticas

* Evite repetições desnecessárias.
* Dê preferência à comunicação objetiva em situações de risco.
* Em situações críticas, mantenha o foco no rádio e reduza comunicações paralelas.
