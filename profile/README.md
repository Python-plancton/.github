<div align="center">
  <img width="200" height="200" alt="Image" src="https://github.com/user-attachments/assets/b8226009-826f-47ec-ae74-8b81d71c981b" />
</div>

## 🐍 Trilha Python para Dados


Python do zero ao tratamento de dados.
---
## 📚 Livros de referência

Esta trilha foi construída com base em livros amplamente utilizados no ensino de Python, algoritmos e análise de dados. Eles servem como referência para a organização dos conteúdos, exemplos e exercícios presentes neste repositório.

<table align="center">
<tr>

<td align="center" width="33%">
<img src="https://github.com/user-attachments/assets/9bbe1ca1-808e-4acf-84ca-48e9610df89f" width="170"><br><br>

<strong>Introdução à Programação com Python (4ª edição)</strong><br>
Nilo Ney Coutinho Menezes
</td>

<td align="center" width="33%">
<img src="https://github.com/user-attachments/assets/7e9e9f47-9fe8-4701-a90f-f0bad6ffb774" width="170"><br><br>

<strong>Estruturas de Dados e Algoritmos com Python</strong><br>
Basant Agarwal
</td>

<td align="center" width="33%">
<img src="https://github.com/user-attachments/assets/cca2cbc4-9fe6-452f-8129-3ee2b67d3258" width="170"><br><br>

<strong>Python para Análise de Dados (3ª edição)</strong><br>
Wes McKinney
</td>


</tr>
</table>

<p align="center">
<sub>
As referências são utilizadas para apoiar a elaboração do material didático. Os direitos autorais das obras pertencem aos respectivos autores e editoras.
</sub>
</p>

---

## O que é esta trilha?

A trilha de python é para quem nunca programou e quer aprender Python com foco em dados, **análise, limpeza e transformação com pandas**.

Cada módulo tem teoria, exemplos práticos e exercícios no estilo LeetCode para treinar escrita de código de verdade.


---

## Para quem é?

- Analistas e engenheiras de dados que ainda não programam
- Profissionais que vieram do Excel/BI e querem migrar para código
- Qualquer pessoa que quer aprender Python com foco em dados desde o zero

---

## O que você vai aprender

| Módulo | Conteúdo |
|---|---|
| 01 - Primeiros passos | Python, VS Code, variáveis, tipos, print |
| 02 - Lógica e estruturas | Condicionais, listas, dicionários, loops, funções |
| 03 - Arquivos e dados | CSV, JSON, try/except, Jupyter Notebook |
| 04 - Pandas na prática | DataFrame, carregar CSV, explorar, filtrar, tratar nulos |
| 05 - Limpeza de dados | Tipos, duplicatas, colunas novas, apply |
| 06 - Análise exploratória | groupby, estatísticas, ordenar, exportar |
| 07 - Visualização | Matplotlib, gráficos, cores, títulos |
| Projeto final | Dataset *a definir* para explorar, limpar, analisar, visualizar |

---

## Estrutura dos arquivos

```
python-para-dados/
├── modulo-01-primeiros-passos/
├── modulo-02-logica-e-estruturas/
│   ├── 01_condicionais.py
│   ├── 02_listas.py
│   ├── 03_dicionarios.py
│   ├── 04_loops.py
│   ├── 05_funcoes.py
│   └── gabarito.py
├── modulo-03-arquivos-e-dados/
├── modulo-04-pandas/
├── modulo-05-limpeza/
├── modulo-06-eda/
├── modulo-07-visualizacao/
├── projeto-final/
└── README.md
```

---

## Como usar os exercícios

Cada arquivo `.py` tem exercícios organizados em três níveis:

**Nível 1 - Básico**
Conceitos fundamentais. Resolve antes de avançar.

**Nível 2 - Intermediário**
Combinação de conceitos. Exige raciocínio lógico.

**Nível 3 - Desafio**
Funções com assinatura definida, entrada e saída esperada.
Treina escrita de código.

> 💡 Tente resolver cada exercício antes de consultar o `gabarito.py`.

---

## Como começar

### 1. Instale o Python

Baixe em: [python.org/downloads](https://python.org/downloads)

Verifique a instalação:
```bash
python --version
```

### 2. Instale o VS Code

Baixe em: [code.visualstudio.com](https://code.visualstudio.com)

Instale a extensão **Python** dentro do VS Code.

### 3. Faça o fork e clone

```bash
# Fork pelo GitHub, depois:
git clone https://github.com/SEU_USUARIO/python-para-dados.git
cd python-para-dados
```

### 4. Crie o ambiente virtual

```bash
python -m venv venv
source venv/bin/activate    # Mac/Linux
venv\Scripts\activate       # Windows
```

### 5. Comece pelo Módulo 01

Abra `modulo-01-primeiros-passos/` e siga a ordem dos arquivos.

---

## Sobre os exercícios de desafio

Os exercícios de Nível 3 seguem o formato do LeetCode:

```python
def nome_da_funcao(parametro: tipo) -> tipo_retorno:
    # SUA SOLUÇÃO AQUI
    pass

# Casos de teste já fornecidos
print(nome_da_funcao(entrada))  # saída esperada
```

Você escreve a solução dentro da função e roda o arquivo para ver se os resultados batem.

---

## Conexão com o projeto prático

Os exercícios do **Módulo 02** já usam dados do contexto da VoughtGuard:

- Exercício de condicionais → classificar risco de transação
- Exercício de listas → analisar transações em lote
- Exercício de dicionários → perfil de fraude por país
- Exercício de loops → validar status de transações
- Exercício de funções → pipeline de limpeza de dados

No **Projeto Final**, você vai aplicar tudo isso no dataset real com 10.000 transações.

---

## Contribuindo

Esta trilha é open source. PRs são bem-vindos.

Antes de contribuir, leia o [CONTRIBUTING.md](../CONTRIBUTING.md).

Tipos de contribuição aceitos:
- Novos exercícios com contexto de dados
- Correções no gabarito
- Melhorias na documentação
- Tradução de enunciados

---

## Não sabe por onde começar?

→ 🌟 [Comece pela trilha-01-fundamentos](https://github.com/Starlight-git-project/trilha-01-fundamentos)

---

<div align="center">

⭐⭐⭐⭐ [Starlight Git Project](https://github.com/Starlight-git-project) · open source · feito para profissionais de dados

💜 Se esta trilha te ajudou, deixa uma estrela no repositório.

</div>
