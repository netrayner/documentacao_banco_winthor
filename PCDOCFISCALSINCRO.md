# 📊 Tabela: PCDOCFISCALSINCRO

### Estrutura de Colunas e Restrições

           Tabela      Coluna Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCFISCALSINCRO      CODIGO  NUMBER(7,0)                   Código do Serviço    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCFISCALSINCRO     SERVICO VARCHAR2(30)        Nome do serviço no DocFiscal            OPERACIONAL                        NaN
PCDOCFISCALSINCRO    DATAHORA         DATE          Data e hora do sincronismo            OPERACIONAL                        NaN
PCDOCFISCALSINCRO DATAHORAANT         DATE Data e hora do sincronismo anterior            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*