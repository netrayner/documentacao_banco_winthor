# 📊 Tabela: PCLOGCONTROLELIVROFISCAL

### Estrutura de Colunas e Restrições

                  Tabela         Coluna  Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCONTROLELIVROFISCAL         CODLOG   NUMBER(6,0)                                   Código do Log.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGCONTROLELIVROFISCAL           DATA          DATE                          Data de geração do log.            OPERACIONAL                        NaN
PCLOGCONTROLELIVROFISCAL      CODFILIAL   VARCHAR2(2)                                Código da filial.            OPERACIONAL                        NaN
PCLOGCONTROLELIVROFISCAL            MES   NUMBER(2,0)                             Mês de encerramento.            OPERACIONAL                        NaN
PCLOGCONTROLELIVROFISCAL            ANO   NUMBER(4,0)                             Ano de encerramento.            OPERACIONAL                        NaN
PCLOGCONTROLELIVROFISCAL        CODFUNC   NUMBER(8,0)                 Cód.Funcionario que gerou o Log.            OPERACIONAL                        NaN
PCLOGCONTROLELIVROFISCAL       TERMINAL VARCHAR2(200)                            Terminal de execução.            OPERACIONAL                        NaN
PCLOGCONTROLELIVROFISCAL STATUSCONTROLE   VARCHAR2(1) Status do Controle (E ¿ Encerrado/A ¿ Abertura).            OPERACIONAL                        NaN
PCLOGCONTROLELIVROFISCAL           DIAS  VARCHAR2(15)                          Gravar dias encerrados.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*