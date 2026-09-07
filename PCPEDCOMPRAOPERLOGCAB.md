# 📊 Tabela: PCPEDCOMPRAOPERLOGCAB

### Estrutura de Colunas e Restrições

               Tabela                Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDCOMPRAOPERLOGCAB                NUMPED  NUMBER(15,0)                               Número do Pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDCOMPRAOPERLOGCAB                 DTPED          DATE                                 Data do Pedido            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB             CODFORNEC   NUMBER(6,0)                           Código do Fornecedor            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB             CODFILIAL   VARCHAR2(2)                               Código da Filial            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB            CODUSUARIO   NUMBER(8,0)                       Matrícula do Funcionário            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB           INTEGRADORA   NUMBER(6,0)                          Código da Integradora            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB              SITUACAO   VARCHAR2(1)                                       Situação            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB           DTGERARQPED          DATE                     Dt. Geração Arquivo Pedido            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB            ARQUIVOPED VARCHAR2(200)                            Nome Arquivo Pedido            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB NUMTRANSVENDAORIGINAL  NUMBER(10,0)          Número da transação de venda original            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB        NUMPEDORIGINAL  NUMBER(10,0)                      Número do Pedido Original            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB     ENVIAPREPEDIDOAPI   VARCHAR2(1)                    Envia Pré-Pedido para a API            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB            MODALIDADE   VARCHAR2(1) Modalidade do Pedido (C - Compra ou V - Venda)            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGCAB         CODSERVICOEDI   NUMBER(6,0)                       Código do Serviço de EDI            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*