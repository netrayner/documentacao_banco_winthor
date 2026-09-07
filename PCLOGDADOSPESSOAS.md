# 📊 Tabela: PCLOGDADOSPESSOAS

### Estrutura de Colunas e Restrições

           Tabela          Coluna   Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGDADOSPESSOAS   DATA_REGISTRO           DATE                       Data atual da gravação do log            OPERACIONAL                        NaN
PCLOGDADOSPESSOAS DATA_REQUISICAO           DATE               Data da requisição do dados da pessoa            OPERACIONAL                        NaN
PCLOGDADOSPESSOAS       DESCRICAO VARCHAR2(1500)                                    Descrição do log            OPERACIONAL                        NaN
PCLOGDADOSPESSOAS  DADOS_ANTERIOR           CLOB                          Dados anterior a alteração            OPERACIONAL                        NaN
PCLOGDADOSPESSOAS     DADOS_ATUAL           CLOB                              Dados após a alteração            OPERACIONAL                        NaN
PCLOGDADOSPESSOAS CODIGO_CADASTRO   VARCHAR2(50)             Código do cadastro do registro alterado            OPERACIONAL                        NaN
PCLOGDADOSPESSOAS          TABELA   VARCHAR2(60)       Nome da tabela em que o registro foi alterado            OPERACIONAL                        NaN
PCLOGDADOSPESSOAS       MATRICULA    NUMBER(8,0) Código da matrícula do usuário que alterou os dados            OPERACIONAL                        NaN
PCLOGDADOSPESSOAS          ROTINA   VARCHAR2(10)               Código da rotina que alterou os dados            OPERACIONAL                        NaN
PCLOGDADOSPESSOAS            HASH   VARCHAR2(64)                     Hash de integridade dos valores            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*