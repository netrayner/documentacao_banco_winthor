# 📊 Tabela: PCRELATOSERASA

### Estrutura de Colunas e Restrições

        Tabela    Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRELATOSERASA      CNPJ  VARCHAR2(14)            Indica o número do CNPJ do cliente.            OPERACIONAL                        NaN
PCRELATOSERASA   IDLINHA   VARCHAR2(6) Indica a identificação do tipop de informação.            OPERACIONAL                        NaN
PCRELATOSERASA     LINHA VARCHAR2(300)              Dados da movimentação do cliente.            OPERACIONAL                        NaN
PCRELATOSERASA DATAATUAL          DATE                           Indica a data atual.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*