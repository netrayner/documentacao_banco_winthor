# 📊 Tabela: PCUNMEDIDAINVENT

### Estrutura de Colunas e Restrições

          Tabela    Coluna Tipo/Tamanho                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCUNMEDIDAINVENT  CODPARAM NUMBER(10,0)                                            Código da parametrização    CHAVE PRIMÁRIA (PK)          PCPARAMETROINVENT
PCUNMEDIDAINVENT  UNMEDIDA      CHAR(1)                         Unidade de medida da contagem do inventário    CHAVE PRIMÁRIA (PK)                        NaN
PCUNMEDIDAINVENT TIPOENDER      CHAR(2)                                    Tipo de endereço da configuração    CHAVE PRIMÁRIA (PK)                        NaN
PCUNMEDIDAINVENT UTILIZADO      CHAR(1) Informa se a unidade de medida está sendo utilizada na configuração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*