# 📊 Tabela: PCSINCRONIZACAOEXTERNA

### Estrutura de Colunas e Restrições

                Tabela            Coluna  Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSINCRONIZACAOEXTERNA           DESTINO VARCHAR2(255)                                  Destino dos dados            OPERACIONAL                        NaN
PCSINCRONIZACAOEXTERNA TIPOSINCRONIZACAO VARCHAR2(255)                              Tipo de sincronização            OPERACIONAL                        NaN
PCSINCRONIZACAOEXTERNA     QTDEREGISTROS   NUMBER(8,0)      Quantidade de registros a serem sincronizados            OPERACIONAL                        NaN
PCSINCRONIZACAOEXTERNA  QTDESINCRONIZADA   NUMBER(8,0)           Quantidade de registros já sincronizados            OPERACIONAL                        NaN
PCSINCRONIZACAOEXTERNA      SINCRONIZADO       CHAR(1)                Se a sincronizacao já foi concluida            OPERACIONAL                        NaN
PCSINCRONIZACAOEXTERNA              CNPJ VARCHAR2(255)             Cnpj da empresa que esta sincronizando            OPERACIONAL                        NaN
PCSINCRONIZACAOEXTERNA          LIBERADO       CHAR(1) Se os dados sincronizados estão liberados para uso            OPERACIONAL                        NaN
PCSINCRONIZACAOEXTERNA  CODSINCRONIZACAO  NUMBER(10,0)              Código identificador da sincronização    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*