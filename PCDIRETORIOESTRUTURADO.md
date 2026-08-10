# 📊 Tabela: PCDIRETORIOESTRUTURADO

### Estrutura de Colunas e Restrições

                Tabela                     Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDIRETORIOESTRUTURADO          FILIALSELECIONADO  VARCHAR2(1)                       Filial Selecionado            OPERACIONAL                        NaN
PCDIRETORIOESTRUTURADO   ANOMESDIAYYYYSELECIONADO  VARCHAR2(1)                         Data Selecionado            OPERACIONAL                        NaN
PCDIRETORIOESTRUTURADO   ANOMESDIAAAAASELECIONADO  VARCHAR2(1)                         Data Selecionado            OPERACIONAL                        NaN
PCDIRETORIOESTRUTURADO            TIPOSELECIONADO  VARCHAR2(1)                         Tipo Selecionado            OPERACIONAL                        NaN
PCDIRETORIOESTRUTURADO NUMCARREGAMENTOSELECIONADO  VARCHAR2(1)       Número do Carregamento Selecionado            OPERACIONAL                        NaN
PCDIRETORIOESTRUTURADO     FILIALSELECIONADOORDEM  NUMBER(1,0)                 Ordem Filial Selecionado            OPERACIONAL                        NaN
PCDIRETORIOESTRUTURADO         ANOMESDIAYYYYORDEM  NUMBER(1,0)                  Orderm Data Selecionado            OPERACIONAL                        NaN
PCDIRETORIOESTRUTURADO         ANOMESDIAAAAAORDEM  NUMBER(1,0)                  Orderm Data Selecionado            OPERACIONAL                        NaN
PCDIRETORIOESTRUTURADO                  TIPOORDEM  NUMBER(1,0)                   Ordem Tipo Selecionado            OPERACIONAL                        NaN
PCDIRETORIOESTRUTURADO       NUMCARREGAMENTOORDEM  NUMBER(1,0) Ordem Número de Carregamento Selecionado            OPERACIONAL                        NaN
PCDIRETORIOESTRUTURADO  DIRESTRUTURADOSELECIONADO  VARCHAR2(1)        Diretorio estruturado Selecionado            OPERACIONAL                        NaN
PCDIRETORIOESTRUTURADO                     CODIGO NUMBER(10,0)                                   Código    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*