# 🧪 Matriz de Teste de Prompts

Comparação entre abordagem **simples (A)** e **estruturada (B)**.
Execute os dois prompts no mesmo caderno, avalie com a rubrica abaixo e registre o resultado.

## 📏 Rubrica de avaliação (1 a 5)

| Nota | Precisão | Profundidade | Alinhamento com as fontes |
|------|----------|--------------|---------------------------|
| 1 | Erros graves | Superficial, genérico | Sem citações ou fora das fontes |
| 3 | Correto com imprecisões | Cobre o básico | Cita, mas sem seção ou com trechos não conferidos |
| 5 | Correto e completo | Exemplo, nuance e aplicação | Toda afirmação citada e conferida na fonte |

## 🧪 Cenários de teste

| # | Objetivo de Estudo | Prompt Simples (A) | Prompt Estruturado (B) | Resultado Esperado | Fonte a conferir |
|---|--------------------|--------------------|------------------------|--------------------|------------------|
| 1 | Reserva de Emergência | "O que é reserva de emergência?" | "Com base nas fontes, explique o conceito em 3 passos, citando o valor ideal recomendado e em quais ativos ela deve ser mantida." | Guia prático com ativos específicos (ex.: Tesouro Selic, CDB com liquidez diária) | CVM (Livro TOP) / BCB (Caderno) |
| 2 | Mecanismo de Juros | "Como funcionam os juros compostos?" | "Crie uma analogia didática para iniciante. Em seguida, diferencie rendimento real de nominal citando os textos." | Explicação + analogia + distinção nominal/real | BCB (Caderno) |
| 3 | Comparativo de Ativos | "Qual a diferença entre Tesouro Direto e Ações?" | "Elabore tabela comparativa entre Renda Fixa (Tesouro) e Renda Variável (Ações) considerando risco, liquidez e previsibilidade." | Tabela sintética | Tesouro Nacional + ANBIMA |
| 4 | Impacto da Inflação | "O que é inflação?" | "Explique como a inflação afeta o poder de compra em 5 anos, usando exemplo numérico simples, citando o IPCA." | Exemplo numérico + citação | BCB |
| 5 | Papel da Selic | "O que é Selic?" | "Descreva o mecanismo de transmissão da Selic para os investimentos de renda fixa, citando a fonte." | Cadeia causal explicada | BCB / Tesouro Nacional |

> O campo "Fonte a conferir" indica onde procurar a confirmação. Registre o capítulo/seção
> real em [`../fontes/curadoria.md`](../fontes/curadoria.md) depois de conferir.

## 📝 Registro de Resultados

| Data | Cenário (#) | Versão | Precisão (1-5) | Profundidade (1-5) | Alinhamento (1-5) | Observações |
|------|-------------|--------|----------------|--------------------|--------------------|-------------|
| | | A | | | | |
| | | B | | | | |

## 🔎 Perguntas para analisar após os testes

1. O prompt estruturado melhorou mais a precisão, a profundidade ou o alinhamento?
2. Em algum cenário o prompt simples foi suficiente? Por quê?
3. A IA disse "não consta nas fontes" em algum momento? Isso é um bom sinal de grounding.
4. Qual elemento do prompt B (formato, exigência de citação, escopo) teve mais efeito?
