# 📊 Tabela: PCLOGFATECF

### Estrutura de Colunas e Restrições

     Tabela               Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGFATECF               CODIGO  NUMBER(8,0)                           Chave primária.            OPERACIONAL                        NaN
PCLOGFATECF                 DATA         DATE                              Data do log.            OPERACIONAL                        NaN
PCLOGFATECF            NUMPEDECF NUMBER(10,0)                         Número do pedido.            OPERACIONAL                        NaN
PCLOGFATECF              NUMORCA NUMBER(10,0)                      Número do orçamento.            OPERACIONAL                        NaN
PCLOGFATECF             NUMCAIXA  NUMBER(4,0)                          Número do caixa.            OPERACIONAL                        NaN
PCLOGFATECF              NUMVALE NUMBER(10,0)                           Número do vale.            OPERACIONAL                        NaN
PCLOGFATECF        NUMSERIEEQUIP VARCHAR2(30)                    Serial do equipamento.            OPERACIONAL                        NaN
PCLOGFATECF            CODFUNCCX  NUMBER(8,0)                       Código do vendedor.            OPERACIONAL                        NaN
PCLOGFATECF               VERSAO VARCHAR2(40)                    Versão do faturamento.            OPERACIONAL                        NaN
PCLOGFATECF            CODROTINA  NUMBER(5,0)              Código da rotina que vendeu.            OPERACIONAL                        NaN
PCLOGFATECF               TABELA VARCHAR2(30)                       Tabela em inclusão.            OPERACIONAL                        NaN
PCLOGFATECF FINALIZADOCOMSUCESSO  VARCHAR2(1) Status do item importado pelo faturamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*