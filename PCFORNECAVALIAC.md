# 📊 Tabela: PCFORNECAVALIAC

### Estrutura de Colunas e Restrições

         Tabela       Coluna  Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORNECAVALIAC CODAVALIACAO  NUMBER(10,0)     Indica o código da avaliação.    CHAVE PRIMÁRIA (PK)                        NaN
PCFORNECAVALIAC    CODFORNEC   NUMBER(6,0)   Indica o código do fornencedor.            OPERACIONAL                        NaN
PCFORNECAVALIAC      CODFUNC   NUMBER(6,0)     Indica o código do avaliador.            OPERACIONAL                        NaN
PCFORNECAVALIAC  DTAVALIACAO          DATE       Indica a data da avaliação.            OPERACIONAL                        NaN
PCFORNECAVALIAC     DTCOMPRA          DATE Indica a data da compra avaliada.            OPERACIONAL                        NaN
PCFORNECAVALIAC          OBS VARCHAR2(255) Indica a observação da avaliação.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*