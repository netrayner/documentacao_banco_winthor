# 📊 Tabela: PCLOGBORDERO

### Estrutura de Colunas e Restrições

      Tabela            Coluna  Tipo/Tamanho                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGBORDERO                ID  NUMBER(10,0)                                               Chave primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGBORDERO            RECNUM   NUMBER(8,0) Chave estrangeria com a PCLANC, para garantir que o lançamento existe.            OPERACIONAL                        NaN
PCLOGBORDERO        NUMBORDERO   NUMBER(6,0)               Campo para indicar a qual borderô o lançamento pertence.            OPERACIONAL                        NaN
PCLOGBORDERO          OPERACAO  VARCHAR2(15)                             Indica operação realizada sobre o borderô.            OPERACIONAL                        NaN
PCLOGBORDERO      DATAOPERACAO          DATE                       Data em que a operação de borderô foi executada.            OPERACIONAL                        NaN
PCLOGBORDERO DESCRICAOOPERACAO VARCHAR2(120)                      Descrição longa da operação realizada no borderô.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*