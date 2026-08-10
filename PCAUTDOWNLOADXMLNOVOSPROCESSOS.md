# 📊 Tabela: PCAUTDOWNLOADXMLNOVOSPROCESSOS

### Estrutura de Colunas e Restrições

                        Tabela              Coluna Tipo/Tamanho                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUTDOWNLOADXMLNOVOSPROCESSOS              CODIGO NUMBER(10,0)                                              Código identificador do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTDOWNLOADXMLNOVOSPROCESSOS CODFORNECAUTORIZADO  NUMBER(6,0)                            Cód. Fornecedor autorizado a fazer download do xml            OPERACIONAL                        NaN
PCAUTDOWNLOADXMLNOVOSPROCESSOS            PROCESSO  VARCHAR2(1) Diferencia o registro por provessos, hoje usado na 535, possuem valores 1 e 2            OPERACIONAL                        NaN
PCAUTDOWNLOADXMLNOVOSPROCESSOS  CODFORNECPRODVENDA  NUMBER(6,0)                                           Cód. Fornecedor do produto na venda            OPERACIONAL                        NaN
PCAUTDOWNLOADXMLNOVOSPROCESSOS           CODFILIAL  VARCHAR2(2)                            Código da filial que esta realizando a autorização            OPERACIONAL                        NaN
PCAUTDOWNLOADXMLNOVOSPROCESSOS             CNPJCPF VARCHAR2(14)                                           CNPJ/CPF do autorizado a baixar XML            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*