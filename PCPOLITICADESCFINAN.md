# 📊 Tabela: PCPOLITICADESCFINAN

### Estrutura de Colunas e Restrições

             Tabela             Coluna  Tipo/Tamanho                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPOLITICADESCFINAN    CODPOLITICADESC  NUMBER(10,0)                                     Código da Política de Desconto Financeiro    CHAVE PRIMÁRIA (PK)                        NaN
PCPOLITICADESCFINAN         CODCLIENTE   NUMBER(6,0)                                                           Cliente Relacionado            OPERACIONAL                        NaN
PCPOLITICADESCFINAN         CODPRODUTO   NUMBER(6,0)                                                       Produto Para o desconto            OPERACIONAL                        NaN
PCPOLITICADESCFINAN          CODFILIAL   VARCHAR2(2)                                                              Código da Filial            OPERACIONAL                        NaN
PCPOLITICADESCFINAN          NUMREGIAO   NUMBER(4,0)                                                             Região do cliente            OPERACIONAL                        NaN
PCPOLITICADESCFINAN           DTINICIO          DATE                                        Data de Inicio da Vigencia do desconto            OPERACIONAL                        NaN
PCPOLITICADESCFINAN              DTFIM          DATE                                            Data Final da Vigência do Desconto            OPERACIONAL                        NaN
PCPOLITICADESCFINAN            CODEPTO   NUMBER(6,0)                                                        Código do Departamento            OPERACIONAL                        NaN
PCPOLITICADESCFINAN            PERDESC   NUMBER(8,2)                                                        Percentual do Desconto            OPERACIONAL                        NaN
PCPOLITICADESCFINAN    CODFUNCCADASTRO   NUMBER(8,0)                     Código do Funcionário de cadastrou a política de desconto            OPERACIONAL                        NaN
PCPOLITICADESCFINAN         DTCADASTRO          DATE                                                  Data do Cadastro da Política            OPERACIONAL                        NaN
PCPOLITICADESCFINAN    CODFUNCULTALTER   NUMBER(8,0)                                  Código do Funcionário que alterou a politica            OPERACIONAL                        NaN
PCPOLITICADESCFINAN         DTULTALTER          DATE                                                             Data da Alteração            OPERACIONAL                        NaN
PCPOLITICADESCFINAN          CODFORNEC   NUMBER(6,0)                               Código do Fornecedor para o Desconto Financeiro            OPERACIONAL                        NaN
PCPOLITICADESCFINAN             CODSEC   NUMBER(6,0)                                   Código da seção para a politica de desconto            OPERACIONAL                        NaN
PCPOLITICADESCFINAN      VLMAXDESCONTO  NUMBER(22,6)                  Valor máximo de desconto que poderá ser aplicado na campanha            OPERACIONAL                        NaN
PCPOLITICADESCFINAN        VENDABALCAO   VARCHAR2(1)                     Define se a campanha deverá ser validada na venda Balcão.            OPERACIONAL                        NaN
PCPOLITICADESCFINAN VENDABALCAORESERVA   VARCHAR2(1)             Define se a campanha deverá ser validada na venda Balcão Reserva.            OPERACIONAL                        NaN
PCPOLITICADESCFINAN      VENDATELEMARK   VARCHAR2(1)                    Define se a campanha deverá ser validada no Telemarketing.            OPERACIONAL                        NaN
PCPOLITICADESCFINAN    VENDACALLCENTER   VARCHAR2(1)                      Define se a campanha deverá ser validada no Call Center.            OPERACIONAL                        NaN
PCPOLITICADESCFINAN            VENDAFV   VARCHAR2(1)                  Define se a campanha deverá ser validada no Força de Vendas.            OPERACIONAL                        NaN
PCPOLITICADESCFINAN         OBSERVACAO VARCHAR2(500)                                 Observação da politica de desconto financeira            OPERACIONAL                        NaN
PCPOLITICADESCFINAN    TIPODATADESCFIN   VARCHAR2(1) Indica qual data sera utilizada para gerar o desconto financeiro da campanha.            OPERACIONAL                        NaN
PCPOLITICADESCFINAN           CODPLPAG   NUMBER(4,0)                                                  Código do plano de pagamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*