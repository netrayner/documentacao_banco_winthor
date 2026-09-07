# Dicionário de Dados TOTVS WinThor (Oracle DB)

![Oracle](https://img.shields.io/badge/Database-Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![TOTVS WinThor](https://img.shields.io/badge/ERP-TOTVS%20WinThor-00529B?style=for-the-badge)
![Markdown](https://img.shields.io/badge/Format-Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![LLM Ready](https://img.shields.io/badge/AI-LLM%20Ready-green?style=for-the-badge&logo=openai&logoColor=white)

Repositório de documentação técnica do modelo relacional e dicionário de dados do ERP **TOTVS WinThor** (Oracle Database). Estruturado segundo a convenção moderna `llms.txt`, permitindo indexação semântica, engenharia de prompts avançada e consumo por assistentes baseados em Inteligência Artificial.

---

## 🎯 Propósito do Repositório

O ERP TOTVS WinThor é amplamente utilizado no setor atacado-distribuidor e varejo. Seu banco de dados Oracle possui centenas de tabelas interconectadas com prefixo `PC` (ex: `PCPEDC`, `PCEST`, `PCPRODUT`).

Este repositório fornece:
- **Catálogo de Tabelas**: Estrutura detalhada de colunas, tipos de dados (`NUMBER`, `VARCHAR2`, `DATE`), chaves primárias (PKs) e chaves estrangeiras (FKs).
- **Índice Semântico (`llms.txt`)**: Mapeamento funcional para orientar agentes de IA sobre onde buscar dados de vendas, compras, estoque, precificação e financeiro.
- **Dicionário Consolidado (`llms-full.txt`)**: Contexto único em texto corrido com mais de 74.000 linhas para ingestão direta em modelos com janelas longas (Gemini 1.5/2.0, Claude 3.5, GPT-4o).

---

## 🤖 Como Usar como Contexto em IAs

Você pode utilizar este repositório como base de conhecimento para gerar consultas SQL eficientes, entender relacionamentos complexos ou criar rotinas de ETL/BI.

### 1. No Cursor / Continue / Copilot (IDE)
- Adicione este repositório no seu projeto do Cursor.
- Utilize a tag `@llms.txt` ou `@PCPEDC.md` no chat do Cursor para fornecer o contexto exato do ERP ao programar.

### 2. No ChatGPT / Claude / Gemini (Interface Web)
- Copie o conteúdo de `llms.txt` para contextualizar a IA sobre as regras do WinThor.
- Ou anexe o arquivo `llms-full.txt` (10.9 MB) diretamente no chat para permitir análises complexas sobre o schema do ERP.

### Exemplos de Prompts Úteis:
```text
Atue como um Engenheiro de Dados especialista em TOTVS WinThor (Oracle).
Consulte o arquivo llms.txt e monte uma query SQL que retorne o total vendido (Faturamento)
por Filial e por Supervisor no mês atual, juntando PCPEDC, PCPEDI, PCUSUR e PCSUPERV.
Trate as datas usando TRUNC(PCPEDC.DATA).
```

---

## 📚 Sumário de Módulos do ERP WinThor

| Módulo | Tabelas Principais | Descrição Operacional |
| :--- | :--- | :--- |
| **Vendas & Faturamento** | [`PCPEDC`](PCPEDC.md), [`PCPEDI`](PCPEDI.md), [`PCNFSAID`](PCNFSAID.md), [`PCMOV`](PCMOV.md), [`PCCARREG`](PCCARREG.md), [`PCCLIENT`](PCCLIENT.md), [`PCCOB`](PCCOB.md) | Pedidos de venda, emissão de NFe de saída, movimentação de estoque de vendas, montagem de carga e clientes. |
| **Compras & Entradas** | [`PCPEDCOMP`](PCPEDCOMP.md), [`PCITEMCOMP`](PCITEMCOMP.md), [`PCNFENT`](PCNFENT.md), [`PCNFENTI`](PCNFENTI.md), [`PCFORNEC`](PCFORNEC.md), [`PCBONUSC`](PCBONUSC.md) | Ordens de compra, notas fiscais de entrada de fornecedores, bonificações e divergências de recebimento. |
| **Estoque & WMS** | [`PCEST`](PCEST.md), [`PCHISTEST`](PCHISTEST.md), [`PCESTEND`](PCESTEND.md), [`PCENDERECO`](PCENDERECO.md), [`PCMOVEND`](PCMOVEND.md), [`PCABSTECEWMS`](PCABSTECEWMS.md) | Saldo de estoque físico/gerencial por filial, histórico diário, saldo por endereço WMS e reabastecimento. |
| **Precificação & Produtos** | [`PCPRODUT`](PCPRODUT.md), [`PCTABPR`](PCTABPR.md), [`PCPRODFILIAL`](PCPRODFILIAL.md), [`PCFILIAL`](PCFILIAL.md), [`PCEMBALAGEM`](PCEMBALAGEM.md), [`PCCATEGORIA`](PCCATEGORIA.md) | Cadastro mestre de itens, tabelas de preço por região/ST, parâmetros por filial e estrutura mercadológica. |
| **Financeiro & Fiscal** | [`PCPREST`](PCPREST.md), [`PCLANC`](PCLANC.md), [`PCBANCO`](PCBANCO.md), [`PCCONTA`](PCCONTA.md), [`PCCONTABIL`](PCCONTABIL.md), [`PCTRIBUT`](PCTRIBUT.md) | Títulos a receber de clientes, contas a pagar a fornecedores, tesouraria, DRE gerencial e figuras tributárias. |

---

## 🌐 Publicação via GitHub Pages

Para disponibilizar as URLs da documentação de forma limpa via HTTP/HTTPS (permitindo que IAs web e crawlers acessem os arquivos diretamente):

1. Vá até as **Settings** do seu repositório no GitHub.
2. Na barra lateral esquerda, selecione **Pages**.
3. Em **Build and deployment** -> **Source**, selecione `Deploy from a branch`.
4. Em **Branch**, escolha `main` (ou `master`) e a pasta `/ (root)`.
5. Clique em **Save**.
6. O GitHub irá gerar uma URL (ex: `https://seu-usuario.github.io/documentacao_banco_winthor/llms.txt`).

---

## 📝 Licença e Avisos

Documentação técnica desenvolvida para suporte a engenharia de dados, desenvolvimento de sistemas e integração de IA com o ERP TOTVS WinThor. TOTVS e WinThor são marcas registradas da TOTVS S.A.
