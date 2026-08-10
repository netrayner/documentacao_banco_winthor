# 📊 Tabela: PCINTEGRACAOFLUXOONLINE

### Estrutura de Colunas e Restrições

                 Tabela                   Coluna Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOFLUXOONLINE                       ID NUMBER(10,0)                                             Id do registro.    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOFLUXOONLINE            ORDEMEXECUCAO  NUMBER(5,0)                           Ordem de execução do fluxo online            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOONLINE            IDROTASERVICO NUMBER(10,0)                                                 Id da rota.            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOONLINE IDINTEGRACAOCLASSEMETODO NUMBER(10,0)                                              Id do recurso.            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOONLINE                  IDFLUXO  NUMBER(5,0)                                                Id do fluxo.            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOONLINE             IDDEPENDENTE NUMBER(10,0)                                      Id da rota dependente.            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOONLINE           STATUSEXECUCAO  NUMBER(1,0)                         Status da execução do fluxo online.            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOONLINE          IDEMPRESAFILIAL NUMBER(10,0) Id da empresa filial a qual o recurso deverá ser executado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*