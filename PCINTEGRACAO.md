# 📊 Tabela: PCINTEGRACAO

### Estrutura de Colunas e Restrições

      Tabela         Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAO         CODIGO  NUMBER(4,0)                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAO      DESCRICAO VARCHAR2(80)                                                       NaN            OPERACIONAL                        NaN
PCINTEGRACAO    NOMEARQUIVO VARCHAR2(80)                                                       NaN            OPERACIONAL                        NaN
PCINTEGRACAO USADESCNOMEARQ  VARCHAR2(1)                      Indica descrição do nome do arquivo.            OPERACIONAL                        NaN
PCINTEGRACAO        CONCATE VARCHAR2(20) Indica a máscara que será concatenada ao nome do arquivo.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*