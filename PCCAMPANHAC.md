# 📊 Tabela: PCCAMPANHAC

### Estrutura de Colunas e Restrições

     Tabela        Coluna Tipo/Tamanho                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCAMPANHAC        CODIGO NUMBER(10,0)                                                      Indica o código da campanha de venda.    CHAVE PRIMÁRIA (PK)                        NaN
PCCAMPANHAC     DESCRICAO VARCHAR2(40)                                                   Indica a descrição da campanha de venda.            OPERACIONAL                        NaN
PCCAMPANHAC     CODFILIAL  VARCHAR2(2)                            Indica o código da filial ao qual a campanha de venda pertence.            OPERACIONAL                        NaN
PCCAMPANHAC      DTINICIO         DATE                                           Indica a vigência inicial da campanha de vendas.            OPERACIONAL                        NaN
PCCAMPANHAC         DTFIM         DATE                                             Indica a vigência final da campanha de vendas.            OPERACIONAL                        NaN
PCCAMPANHAC     CODFORNEC  NUMBER(6,0)                                       Indica o código do fornecedor da campanha de vendas.            OPERACIONAL                        NaN
PCCAMPANHAC  TIPOCAMPANHA  VARCHAR2(2)                          Indica o tipo da campanha de vendas: [P]Produto ou [F]Fornecedor.            OPERACIONAL                        NaN
PCCAMPANHAC TIPOPREMIACAO  VARCHAR2(2)                    Indica o tipo da premiação: [UN]Única, [PR]Proporcional e [UM]Múltiplo.            OPERACIONAL                        NaN
PCCAMPANHAC     PREMVALOR NUMBER(18,6)                                         Indica o valor da premiação da campanha de vendas.            OPERACIONAL                        NaN
PCCAMPANHAC      PREMPERC NUMBER(10,4)                    Indica o percentual de premiação a ser aplicado sobre o total da venda.            OPERACIONAL                        NaN
PCCAMPANHAC    CODFUNCCAD  NUMBER(8,0)        Indiaca o código do funcionário que realizou o cadastramento da campanha de vendas.            OPERACIONAL                        NaN
PCCAMPANHAC    DTCADASTRO         DATE                                          Indiaca a data de cadastro da campanha de vendas.            OPERACIONAL                        NaN
PCCAMPANHAC  CODFUNCFECHA  NUMBER(8,0) Indica o código do funcionário que realizou a apuração e fechamento da campanha de vendas.            OPERACIONAL                        NaN
PCCAMPANHAC       DTFECHA         DATE                              Indica a data de apuração e fechamento da campanha de vendas.            OPERACIONAL                        NaN
PCCAMPANHAC      SITUACAO  VARCHAR2(1)           Indica a situação da campanha. Os valores possíveis serão [A]Ativa e [I]Inativa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*