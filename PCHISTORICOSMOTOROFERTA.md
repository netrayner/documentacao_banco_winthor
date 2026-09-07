# 📊 Tabela: PCHISTORICOSMOTOROFERTA

### Estrutura de Colunas e Restrições

                 Tabela           Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTORICOSMOTOROFERTA        NUMPEDECF NUMBER(10,0)               Código do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOSMOTOROFERTA         NUMCAIXA  NUMBER(4,0)                Número do caixa    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOSMOTOROFERTA             DATA         DATE                 Data histórico            OPERACIONAL                        NaN
PCHISTORICOSMOTOROFERTA DADOSMOTOROFERTA         CLOB       Dados do motor de oferta            OPERACIONAL                        NaN
PCHISTORICOSMOTOROFERTA        EXPORTADO  VARCHAR2(1) Define se foi exportado ou não            OPERACIONAL                        NaN
PCHISTORICOSMOTOROFERTA    NUMTRANSVENDA NUMBER(10,0)                            NaN            OPERACIONAL                        NaN
PCHISTORICOSMOTOROFERTA       DADOSENVIO         CLOB                            NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*