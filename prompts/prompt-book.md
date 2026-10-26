# 🧠 Prompt Book — Prompts Reutilizáveis

> Cole estes modelos diretamente no NotebookLM. Sempre substitua os `[COLCHETES]`.

## ✅ Regras gerais (valem para todos os prompts)

1. **Delimite o escopo:** "com base exclusivamente nas fontes carregadas".
2. **Exija citação:** nome da fonte + capítulo/seção/página.
3. **Defina o formato:** tabela, passos numerados, bullets, limite de tamanho.
4. **Peça admissão de lacunas:** "se a fonte não trouxer, diga que não consta".
5. **Itere:** se a resposta vier genérica, refine o prompt em vez de aceitar.
6. **Confira:** abra a fonte e valide pelo menos 2 citações por sessão.

---

## 1. PROMPT DE SÍNTESE
```
Com base exclusivamente nas fontes fornecidas, resuma os 5 pontos
mais importantes sobre [TÓPICO] em bullet points simples e objetivos.
Cada ponto deve citar a fonte (nome + seção). Se algum ponto não
estiver nas fontes, não o inclua.
```
**Objetivo atendido:** 1, 2, 3

---

## 2. PROMPT DE AUTOAVALIAÇÃO (SIMULADO)
```
Atue como um examinador de [ÁREA]. Com base nos textos do caderno,
crie 3 perguntas de múltipla escolha com 4 alternativas cada sobre
[TÓPICO]. Faça uma pergunta por vez e não mostre o gabarito até que
eu responda. Depois de cada resposta, diga se acertei, explique a
alternativa correta e cada alternativa errada, citando a fonte.
```
**Objetivo atendido:** 1, 2, 3

---

## 3. PROMPT DE SIMPLIFICAÇÃO (TÉCNICA FEYNMAN)
```
Explique o conceito de [CONCEITO COMPLEXO] como se estivesse ensinando
para uma pessoa sem conhecimento prévio em exatas, usando uma metáfora
do dia a dia. Limite-se ao que está descrito nas fontes e indique
onde a metáfora deixa de representar bem o conceito.
```
**Objetivo atendido:** 2, 4

---

## 4. PROMPT DE COMPARAÇÃO (TABELA)
```
Elabore uma tabela comparativa entre [ITEM A] e [ITEM B] considerando:
risco, liquidez, previsibilidade de retorno e tributação.
Baseie-se apenas nas fontes carregadas e cite a fonte em cada linha.
Onde as fontes não trouxerem a informação, escreva "não consta nas fontes".
```
**Objetivo atendido:** 1

---

## 5. PROMPT DE APLICAÇÃO PRÁTICA
```
Com base nas fontes, crie um plano de ação em 5 passos para uma pessoa
que quer [OBJETIVO, ex: montar reserva de emergência]. Cada passo deve
incluir: ação concreta, valor sugerido (se houver) e fonte citada.
Não invente valores que não estejam nas fontes.
```
**Objetivo atendido:** 3

---

## 6. PROMPT DE VERIFICAÇÃO (ANTI-ALUCINAÇÃO)
```
Releia a sua última resposta. Liste as afirmações que você NÃO conseguiu
comprovar diretamente nas fontes carregadas sobre [TÓPICO], indicando o
trecho que sustenta cada uma das demais. Se não houver afirmações sem
respaldo, diga explicitamente "tudo comprovado nas fontes".
```
**Objetivo atendido:** 5

---

## 7. PROMPT DE GLOSSÁRIO AUTOMÁTICO
```
Extraia das fontes os 10 termos técnicos mais recorrentes sobre [TÓPICO]
e monte um glossário em ordem alfabética, com definição de 1 linha cada
e a fonte de onde veio cada definição.
```
**Objetivo atendido:** 4

---

## 8. PROMPT DE FLASHCARDS
```
Crie 10 flashcards sobre [TÓPICO] com base nas fontes, no formato:
Frente: pergunta curta | Verso: resposta em até 2 linhas + fonte.
Misture definições, diferenças entre conceitos e pequenos cálculos.
```
**Objetivo atendido:** 4 (revisão espaçada: revise em 1, 3 e 7 dias)

---

## 9. PROMPT "ENSINE DE VOLTA" (CORREÇÃO DA MINHA EXPLICAÇÃO)
```
Vou explicar [CONCEITO] com minhas palavras. Compare com as fontes e
responda: (1) o que está correto, (2) o que está incorreto ou impreciso,
(3) o que faltou. Cite a fonte em cada ponto.

Minha explicação: [COLE SUA EXPLICAÇÃO]
```
**Objetivo atendido:** 1, 2, 3

---

## 10. PROMPT DE DIVERGÊNCIAS ENTRE FONTES
```
Existe alguma divergência, diferença de ênfase ou informação possivelmente
desatualizada entre as fontes sobre [TÓPICO]? Liste cada ponto com as
duas fontes lado a lado. Se não houver, diga "sem divergências encontradas".
```
**Objetivo atendido:** 5

---

## 11. PROMPT DE PLANO DE ESTUDO
```
Monte um plano de estudo de [N] dias para dominar [TÓPICO] usando apenas
as fontes carregadas. Para cada dia: o que ler (capítulo/seção), uma
atividade prática e uma pergunta de autoavaliação.
```
**Objetivo atendido:** 5
