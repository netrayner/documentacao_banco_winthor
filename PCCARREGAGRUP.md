# 📊 Tabela: PCCARREGAGRUP

### Estrutura de Colunas e Restrições

       Tabela           Coluna  Tipo/Tamanho   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCARREGAGRUP           NUMCAR  NUMBER(10,0)  Número carregamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCCARREGAGRUP          CODPROD   NUMBER(6,0)       Código produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCCARREGAGRUP        TIPOAGRUP  VARCHAR2(10)     Tipo agrupamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCCARREGAGRUP         CODAGRUP VARCHAR2(100)   Código agrupamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCCARREGAGRUP               QT  NUMBER(20,6)           Quantidade.            OPERACIONAL                        NaN
PCCARREGAGRUP       QTSEPARADA  NUMBER(20,6)  Quantidade separada.            OPERACIONAL                        NaN
PCCARREGAGRUP      CODFUNCCONF   NUMBER(8,0)    Código conferente.            OPERACIONAL                        NaN
PCCARREGAGRUP CODFUNCSEPARADOR   NUMBER(8,0)     Código separador.            OPERACIONAL                        NaN
PCCARREGAGRUP CODFUNCEMBALADOR   NUMBER(8,0)     Código embalador.            OPERACIONAL                        NaN
PCCARREGAGRUP DTINICIOCHECKOUT          DATE Data início checkout.            OPERACIONAL                        NaN
PCCARREGAGRUP    DTFIMCHECKOUT          DATE    Data fim checkout.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*