# 📊 Tabela: PCFAIXASATRASO

### Estrutura de Colunas e Restrições

        Tabela           Coluna  Tipo/Tamanho                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFAIXASATRASO           CODIGO   NUMBER(8,0)                                                        Código da faixa de atraso    CHAVE PRIMÁRIA (PK)                        NaN
PCFAIXASATRASO    QTDMINIMADIAS   NUMBER(3,0)                                                                Quantidade mínima            OPERACIONAL                        NaN
PCFAIXASATRASO    QTDMAXIMADIAS   NUMBER(3,0)                                                                Quantidade máxima            OPERACIONAL                        NaN
PCFAIXASATRASO CAMINHORELATORIO VARCHAR2(100)                                                  Caminho do arquivo de relatório            OPERACIONAL                        NaN
PCFAIXASATRASO      TIPOGERACAO   VARCHAR2(2)                                                       Tipo de geração do arquivo            OPERACIONAL                        NaN
PCFAIXASATRASO  MODELORELATORIO   NUMBER(3,0)                                                    Modelo do relatório utilizado            OPERACIONAL                        NaN
PCFAIXASATRASO     ENVIARBOLETO   VARCHAR2(1)                                                 Envia boleto bancário via e-mail            OPERACIONAL                        NaN
PCFAIXASATRASO     TIPOOPERACAO   VARCHAR2(1) Tipo de operação: Por faixa de atraso ou Por faixa de atraso/aviso de vencimento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*