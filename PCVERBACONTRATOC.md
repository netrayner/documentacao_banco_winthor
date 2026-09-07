# 📊 Tabela: PCVERBACONTRATOC

### Estrutura de Colunas e Restrições

          Tabela           Coluna Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVERBACONTRATOC      NUMCONTRATO NUMBER(12,0)                                                                            Número do contrato.    CHAVE PRIMÁRIA (PK)                        NaN
PCVERBACONTRATOC        CODFORNEC  NUMBER(6,0)                                                                          Código do fornecedor.            OPERACIONAL                        NaN
PCVERBACONTRATOC CALCVLSEMIMPOSTO  VARCHAR2(1)                                Para calcular o produto utilizando ou não o valor dos impostos.            OPERACIONAL                        NaN
PCVERBACONTRATOC  GERADESCONTOFIN  VARCHAR2(1) Se o valor da verba gerado será utilizado ou não para desconto de duplicada do contas a pagar.            OPERACIONAL                        NaN
PCVERBACONTRATOC     TIPOCONTRATO  VARCHAR2(1)                                               Tipo de contrato: Por Fornecedor ou Por Produto.            OPERACIONAL                        NaN
PCVERBACONTRATOC       TIPOINDICE  VARCHAR2(1)                                           Tipo do índice: Calculo por Percentual ou por Valor.            OPERACIONAL                        NaN
PCVERBACONTRATOC         VLINDICE NUMBER(18,6)        Valor do índice (podendo ser percentual ou valor, de acordo com a opção marcada acima).            OPERACIONAL                        NaN
PCVERBACONTRATOC       PRAZOPAGTO  NUMBER(3,0)                                                            Prazo de pagamento da verba gerada.            OPERACIONAL                        NaN
PCVERBACONTRATOC        TIPOVERBA  VARCHAR2(1)                                                 Tipo da verba: Mercadoria, Dinheiro ou Outros.            OPERACIONAL                        NaN
PCVERBACONTRATOC     CODTIPOVERBA NUMBER(10,0)                                                                       Código do tipo da verba.            OPERACIONAL                        NaN
PCVERBACONTRATOC         CODCONTA NUMBER(10,0)                                                                     Código da conta gerencial.            OPERACIONAL                        NaN
PCVERBACONTRATOC        DTINICIAL         DATE                                                         Data inicial da virgência do contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOC          DTFINAL         DATE                                                           Data final da virgência do contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOC       DTCONTRATO         DATE                                                   Data do acordo do contrato com o fornecedor.            OPERACIONAL                        NaN
PCVERBACONTRATOC       DTINCLUSAO         DATE                                                       Data de inclusão do contrato no sistema.            OPERACIONAL                        NaN
PCVERBACONTRATOC       DTEXCLUSAO         DATE                                                                     Data exclusão do contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOC      DTALTERACAO         DATE                                                                    Data alteração do contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOC       HISTORICO1 VARCHAR2(40)                                                               Historico para geração da verba.            OPERACIONAL                        NaN
PCVERBACONTRATOC       HISTORICO2 VARCHAR2(40)                                                 Historico para geração de verbas, continuação.            OPERACIONAL                        NaN
PCVERBACONTRATOC       SUPERVISOR VARCHAR2(40)                                                        Supervisor responsável pela fornecedor.            OPERACIONAL                        NaN
PCVERBACONTRATOC    REPRESENTANTE VARCHAR2(40)                                                                Nome do fornecedor/responsável.            OPERACIONAL                        NaN
PCVERBACONTRATOC     REPRESENTCPF VARCHAR2(30)                                                            CPF/CNPJ do fornecedor/responsável.            OPERACIONAL                        NaN
PCVERBACONTRATOC      REPRESENTRG VARCHAR2(30)                                                                  RG do fornecedor/responsável.            OPERACIONAL                        NaN
PCVERBACONTRATOC        CODROTINA  NUMBER(6,0)                                                         Código da rotina que gerou o contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOC    CODUSUARIOINC  NUMBER(6,0)                                                      Código do usuário que incluiu o contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOC    CODUSUARIOEXC  NUMBER(6,0)                                                      Código do usuário que excluiu o contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOC    CODUSUARIOALT  NUMBER(6,0)                                                      Código do usuário que alterou o contrato.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*