# 📊 Tabela: PCBIONEXOESTADO

### Estrutura de Colunas e Restrições

         Tabela        Coluna Tipo/Tamanho                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBIONEXOESTADO            UF  VARCHAR2(2) ID utilizado para realizar a chamada e identificador na conexão com o VoipMundo    CHAVE PRIMÁRIA (PK)                        NaN
PCBIONEXOESTADO     CODFILIAL  VARCHAR2(2)                                                                Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCBIONEXOESTADO      CODPRACA  NUMBER(6,0)                                                       Codigo da praça principal            OPERACIONAL                        NaN
PCBIONEXOESTADO    DTINCLUSAO         DATE                                                    Data de inclusão do registro            OPERACIONAL                        NaN
PCBIONEXOESTADO CODUSUARIOINC  NUMBER(8,0)                                        Código do usuário que incluiu o registro            OPERACIONAL                        NaN
PCBIONEXOESTADO   DTALTERACAO         DATE                                            Data da última alteração do registro            OPERACIONAL                        NaN
PCBIONEXOESTADO CODUSUARIOALT  NUMBER(8,0)                             Código do usuário que alterou por último o registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*