# 📊 Tabela: PCMOVINSERVIVEL

### Estrutura de Colunas e Restrições

         Tabela                 Coluna Tipo/Tamanho                                                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVINSERVIVEL       CODMOVINSERVIVEL  NUMBER(6,0)                                                               Código sequencial para identificação de movimento de inservível    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVINSERVIVEL CODMOVINSERVIVELORIGEM  NUMBER(6,0)                                    Código do movimento de origem identifica as movimentações referentes a um débito existente            OPERACIONAL                        NaN
PCMOVINSERVIVEL                 CODCLI  NUMBER(6,0)                                                                                            Código de identificação de cliente            OPERACIONAL                        NaN
PCMOVINSERVIVEL              CODFILIAL  VARCHAR2(2)                                                                                             Código de identificação de filial            OPERACIONAL                        NaN
PCMOVINSERVIVEL                CODPROD  NUMBER(6,0)                                                                                            Código de identificação do produto            OPERACIONAL                        NaN
PCMOVINSERVIVEL                 NUMPED NUMBER(10,0)                                                                                             Código de identificação do pedido            OPERACIONAL                        NaN
PCMOVINSERVIVEL             DTINCLUSAO         DATE                                                                                                  Data de inclusão do registro            OPERACIONAL                        NaN
PCMOVINSERVIVEL             DTVALIDADE         DATE                                                                           Data de validade somente quando for registro débito            OPERACIONAL                        NaN
PCMOVINSERVIVEL                SALDOKG NUMBER(12,6)                                                            Saldo de Carcaça em (KG): Caso tenha desconto em carcaça no pedido            OPERACIONAL                        NaN
PCMOVINSERVIVEL                SALDOVL NUMBER(18,6)                                                        Saldo de Carcaça em Valor R$: Caso tenha desconto em carcaça no pedido            OPERACIONAL                        NaN
PCMOVINSERVIVEL             DTEXCLUSAO         DATE                                                                                                       Data da exclusão lógica            OPERACIONAL                        NaN
PCMOVINSERVIVEL                 STATUS  VARCHAR2(2)                                                                                                        Status da movimentação            OPERACIONAL                        NaN
PCMOVINSERVIVEL          TIPOMOVIMENTO  VARCHAR2(3) Tipo de movimentação realizada, DDC = Débito desconto carcaça, CDC = Credito desconto carcaça, CCR = Credito contas a receber            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*