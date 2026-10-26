# 📚 Estudo Ativo com NotebookLM — Finanças Pessoais e Investimentos

> Projeto de aprendizagem ativa usando IA **grounded** (fundamentada exclusivamente
> nas fontes selecionadas). O NotebookLM é limitado a um repositório curado de
> materiais, reduzindo alucinações e criando um ambiente de estudo mais confiável.

> ⚠️ **Aviso:** material **educacional**. Não constitui recomendação de investimento.
> Taxas, limites e regras tributárias mudam — sempre confirme nas fontes oficiais.

---

## 🎯 Objetivos de Aprendizagem

Ao final deste estudo, o aluno deve ser capaz de:

| # | Objetivo | Onde é trabalhado |
|---|----------|-------------------|
| 1 | **Compreender** a diferença entre renda fixa e renda variável. | [resumos](miniguia/resumos.md) · [autoavaliação](miniguia/autoavaliacao.md) |
| 2 | **Entender** a dinâmica da taxa Selic e o impacto da inflação no poder de compra. | [resumos](miniguia/resumos.md) · [autoavaliação](miniguia/autoavaliacao.md) |
| 3 | **Aprender** a estruturar uma reserva de emergência antes de investir. | [resumos](miniguia/resumos.md) · [autoavaliação](miniguia/autoavaliacao.md) |
| 4 | **Dominar** o vocabulário básico do mercado financeiro. | [glossário](miniguia/glossario.md) |
| 5 | **Aplicar** prompts estruturados para extrair conhecimento das fontes. | [prompt book](prompts/prompt-book.md) · [matriz de testes](prompts/matriz-testes.md) |

---

## 📂 Estrutura do Projeto

```
EstudoAtivo-NotebookLM/
├── README.md                    ← este arquivo
├── fontes/
│   └── curadoria.md             ← fontes oficiais, links e status de verificação
├── prompts/
│   ├── prompt-book.md           ← prompts reutilizáveis
│   └── matriz-testes.md         ← comparação simples vs. estruturado + rubrica
├── miniguia/
│   ├── resumos.md               ← resumos estruturados (com exemplos numéricos)
│   ├── glossario.md             ← glossário em ordem alfabética
│   ├── autoavaliacao.md         ← questões e exercícios com gabarito
│   └── miniguia-final.md        ← síntese consolidada
├── notas/
│   └── diario-de-bordo.md       ← registro de experimentos
└── assets/                      ← prints e imagens
```

---

## 🗺️ Roteiro Passo a Passo

### Etapa 1 — Criar o caderno no NotebookLM
- Acesse https://notebooklm.google.com
- Crie o caderno **"Estudo Ativo: Finanças Pessoais e Investimentos"**.
- Faça upload das fontes listadas em [`fontes/curadoria.md`](fontes/curadoria.md)
  (PDFs ou links; recomendado: 3 a 5 fontes).

### Etapa 2 — Conferir os objetivos de aprendizagem
- Use a tabela acima como bússola: cada prompt deve servir a um objetivo.

### Etapa 3 — Executar perguntas estratégicas
- Use os modelos de [`prompts/prompt-book.md`](prompts/prompt-book.md).
- Compare variações (simples vs. estruturado) em [`prompts/matriz-testes.md`](prompts/matriz-testes.md).

### Etapa 4 — Registrar e avaliar
- Anote cada experimento em [`notas/diario-de-bordo.md`](notas/diario-de-bordo.md)
  usando a rubrica de 1 a 5 (precisão, profundidade, alinhamento com as fontes).

### Etapa 5 — Validar a IA contra as fontes
- Rode o prompt de **verificação** e **confira ao menos 2 citações por sessão**
  abrindo a fonte original. Corrija os resumos se algo divergir.

### Etapa 6 — Autoavaliar e sintetizar
- Resolva [`miniguia/autoavaliacao.md`](miniguia/autoavaliacao.md) sem consultar o gabarito.
- Consolide tudo em [`miniguia/miniguia-final.md`](miniguia/miniguia-final.md) e
  marque os objetivos que você realmente atingiu.

---

## 🧪 Matriz de Teste de Prompts (resumo)

| Objetivo | Prompt Simples | Prompt Estruturado | Fonte |
|---|---|---|---|
| Reserva de Emergência | "O que é reserva de emergência?" | "Explique em 3 passos, com valor ideal e ativos." | CVM / BCB |
| Juros Compostos | "Como funcionam?" | "Crie analogia + diferencie nominal vs. real." | BCB |
| Comparativo de Ativos | "Tesouro vs. Ações?" | "Tabela: risco, liquidez, previsibilidade." | Tesouro + ANBIMA |

A matriz completa (5 cenários + rubrica) está em [`prompts/matriz-testes.md`](prompts/matriz-testes.md).

---

## 📌 Tecnologias e Conceitos

- **NotebookLM** (IA grounded)
- **Engenharia de Prompt** (simples vs. estruturado)
- **Aprendizagem Ativa** (Feynman, autoavaliação, síntese, revisão espaçada)
- **Curadoria de Fontes Abertas** (CVM, BCB, Tesouro Nacional, ANBIMA)

---

## 📄 Licença

Projeto educacional de uso livre. As fontes citadas pertencem aos seus respectivos órgãos
e devem ser creditadas ao serem reutilizadas.
