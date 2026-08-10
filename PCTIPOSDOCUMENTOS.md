# 📊 Tabela: PCTIPOSDOCUMENTOS

### Estrutura de Colunas e Restrições

           Tabela           Coluna  Tipo/Tamanho       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTIPOSDOCUMENTOS CODTIPODOCUMENTO   NUMBER(6,0) Código tipo do documento.    CHAVE PRIMÁRIA (PK)                        NaN
PCTIPOSDOCUMENTOS             NOME  VARCHAR2(60)                     Nome.            OPERACIONAL                        NaN
PCTIPOSDOCUMENTOS             TIPO   NUMBER(2,0)                     Tipo.            OPERACIONAL                        NaN
PCTIPOSDOCUMENTOS       OBSERVACAO VARCHAR2(255)               Observação.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*