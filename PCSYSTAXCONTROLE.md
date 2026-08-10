# 📊 Tabela: PCSYSTAXCONTROLE

### Estrutura de Colunas e Restrições

          Tabela               Coluna Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSYSTAXCONTROLE          CODCONTROLE  NUMBER(7,0)                           CÓDIGO SEQUENCIAL DE CONTROLE    CHAVE PRIMÁRIA (PK)                        NaN
PCSYSTAXCONTROLE           ID_CENARIO  VARCHAR2(7)                                           ID DO CENARIO            OPERACIONAL                        NaN
PCSYSTAXCONTROLE             COD_PROD  NUMBER(7,0)                                       CÓDIGO DO PRODUTO            OPERACIONAL                        NaN
PCSYSTAXCONTROLE       ORIGEM_PRODUTO  VARCHAR2(3)                                       ORIGEM DO PRODUTO            OPERACIONAL                        NaN
PCSYSTAXCONTROLE               STATUS  VARCHAR2(1)            STATUS DO REGISTRO. I-INICIADO; F-FINALIZADO            OPERACIONAL                        NaN
PCSYSTAXCONTROLE PONTEIRO_ATUALIZACAO VARCHAR2(50) Ponteiro de atualização dos produtos tributados Cockpit            OPERACIONAL                        NaN
PCSYSTAXCONTROLE            DT_INSERT         DATE                             DATA DE INSEÇÃO DO REGISTRO            OPERACIONAL                        NaN
PCSYSTAXCONTROLE            DT_UPDATE         DATE                         DATA DE ATUALIZAÇÃO DO REGISTRO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*