# 📊 Tabela: PCORDEMIMPRESSAONF

### Estrutura de Colunas e Restrições

            Tabela    Coluna Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORDEMIMPRESSAONF    CODDOC  NUMBER(8,0) Código do documento informado na PCFILIAL.CODDOCNF.    CHAVE PRIMÁRIA (PK)                        NaN
PCORDEMIMPRESSAONF     SECAO  VARCHAR2(2)                                     Indica a seção.    CHAVE PRIMÁRIA (PK)                        NaN
PCORDEMIMPRESSAONF DESCRICAO VARCHAR2(60)                                 Indica a descrição.            OPERACIONAL                        NaN
PCORDEMIMPRESSAONF     ORDEM  NUMBER(3,0)               Ordem em que será impresso no DANF-e.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*