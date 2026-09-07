# 📊 Tabela: PCDESCONTOFIDELIDADE

### Estrutura de Colunas e Restrições

              Tabela            Coluna Tipo/Tamanho                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESCONTOFIDELIDADE     CODFIDELIDADE  NUMBER(6,0)                                           Código sequencial do cadastro.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCONTOFIDELIDADE           CODPROD  NUMBER(6,0)                                                       Código do produto.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE          CODSECAO  NUMBER(6,0)                                                          Código da seção            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE           CODEPTO  NUMBER(6,0)                                                  Código do departamento.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE      CODCATEGORIA  NUMBER(6,0)                                                     Código da categoria.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE   CODSUBCATEGORIA  NUMBER(6,0)                                                  Código da subcategoria.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE         CODFORNEC  NUMBER(6,0)                                                    Código do fornecedor.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE            CODCLI  NUMBER(6,0)                                                       Código do cliente.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE    CODCLICONVENIO  NUMBER(6,0)                                                      Código do convenio.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE           CODUSUR  NUMBER(4,0)                                                      Código do vendedor.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE        VLDESCONTO NUMBER(10,4)                                                       Valor do desconto.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE      PERCDESCONTO NUMBER(10,2)                                                  Percentual de desconto.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE         DTINICIAL         DATE                                  Data inicial da vigência da fidelidade.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE           DTFINAL         DATE                                    Data final da vigência da fidelidade.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE APLICARAUTOMATICO  VARCHAR2(1)                                        Aplicar desconto automaticamente.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE       FISCALCAIXA  VARCHAR2(1)                       Somente o fiscal de caixa pode aplicar o desconto.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE         CODFILIAL  VARCHAR2(2)                                                        Código da filial.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE        DTEXCLUSAO         DATE                                                         Data de exclusão            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE   CODFUNCEXCLUSAO  NUMBER(4,0)                                        Código do funcionário que excluiu            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE            CODSEC  NUMBER(6,0)                                                             Código seção            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE         DTALTERC5 TIMESTAMP(6) Coluna de identifição de alteração para integracao com PDV Supermercados            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE      PERCCASHBACK  NUMBER(5,3)            Percentual de cashback da campanha de desconto de fidelidade.            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE     PRECOCASHBACK NUMBER(18,6)                           Preço do produto em campanha que gera cashback            OPERACIONAL                        NaN
PCDESCONTOFIDELIDADE       CODPARCEIRO  NUMBER(6,0)                                                       Código do parceiro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*