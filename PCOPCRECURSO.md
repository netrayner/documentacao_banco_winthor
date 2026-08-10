# 📊 Tabela: PCOPCRECURSO

### Estrutura de Colunas e Restrições

      Tabela         Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOPCRECURSO          NUMOP  NUMBER(8,0)           Número da Ordem de Produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCOPCRECURSO      IDRECURSO NUMBER(10,0)  Código do Recurso utilizado na etapa.    CHAVE PRIMÁRIA (PK)                        NaN
PCOPCRECURSO       CODETAPA  NUMBER(6,0) Código da etapa utilizada na produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCOPCRECURSO      CODFILIAL  VARCHAR2(2)          Código da filial da produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCOPCRECURSO     QTPREVISTA NUMBER(18,6)       Quantidade de Recursos Prevista.            OPERACIONAL                        NaN
PCOPCRECURSO    QTREALIZADA NUMBER(18,6)     Quantidade de Recursos Realizados.            OPERACIONAL                        NaN
PCOPCRECURSO  CUSTOPREVISTO NUMBER(18,6)          Custo dos recursos Previstos.            OPERACIONAL                        NaN
PCOPCRECURSO CUSTOREALIZADO NUMBER(18,6)         Custo dos recursos Realizados.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*