# 📊 Tabela: PCPRECOCESTAC

### Estrutura de Colunas e Restrições

       Tabela               Coluna  Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRECOCESTAC        CODPRECOCESTA  NUMBER(22,0)                  Indica o código do preço da cesta.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRECOCESTAC          CODPRODACAB   NUMBER(6,0)                 Indica o código do produto acabado.            OPERACIONAL                        NaN
PCPRECOCESTAC            CODFILIAL   VARCHAR2(2)                    Indica o código da filial venda.            OPERACIONAL                        NaN
PCPRECOCESTAC            NUMREGIAO   NUMBER(4,0)                          Indica o número da região.            OPERACIONAL                        NaN
PCPRECOCESTAC             CODPLPAG   NUMBER(4,0)              Indica o código do plano de pagamento.            OPERACIONAL                        NaN
PCPRECOCESTAC             DTINICIO          DATE                Indica a data de início de vigência.            OPERACIONAL                        NaN
PCPRECOCESTAC                DTFIM          DATE                     Inica a data final de vigência.            OPERACIONAL                        NaN
PCPRECOCESTAC           DTEXCLUSAO          DATE            Indica o data de exclusão do preço fixo.            OPERACIONAL                        NaN
PCPRECOCESTAC      CODFUNCEXCLUSAO   NUMBER(8,0)      Indica o funcionário que excluiu o preço fixo.            OPERACIONAL                        NaN
PCPRECOCESTAC               CODCLI   NUMBER(6,0)                   Indica o código do cliente venda.            OPERACIONAL                        NaN
PCPRECOCESTAC UTILIZAPRECOFIXOREDE   VARCHAR2(1)  Indica se utiliza preço fixo na rede de clientes?.            OPERACIONAL                        NaN
PCPRECOCESTAC      CODFUNCCADASTRO   NUMBER(8,0)         Indica o funcionário que realizou cadastro.            OPERACIONAL                        NaN
PCPRECOCESTAC           DTCADASTRO          DATE                          Indica a data de cadastro.            OPERACIONAL                        NaN
PCPRECOCESTAC      CODFUNCULTALTER   NUMBER(8,0) Indica o funcionário que realizou última alteração.            OPERACIONAL                        NaN
PCPRECOCESTAC           DTULTALTER          DATE                  Indica a data da última alteração.            OPERACIONAL                        NaN
PCPRECOCESTAC             NUMVERBA   NUMBER(8,0)                  Nr. da verba atribuída a campanha.            OPERACIONAL                        NaN
PCPRECOCESTAC       PERCCUSTFORNEC  NUMBER(12,4)                Percentual custeado pelo fornecedor.            OPERACIONAL                        NaN
PCPRECOCESTAC       DTOFERTAINICIO          DATE                              Data inicial da oferta            OPERACIONAL                        NaN
PCPRECOCESTAC        DTOFERTAFINAL          DATE                                Data final da oferta            OPERACIONAL                        NaN
PCPRECOCESTAC           OBSERVACAO VARCHAR2(100)          Observações da política de preço de cesta.            OPERACIONAL                        NaN
PCPRECOCESTAC            DTALTERC5  TIMESTAMP(6)                       Data de alteração do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*