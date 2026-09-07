# 📊 Tabela: PCLOGFLUXOCONF

### Estrutura de Colunas e Restrições

        Tabela      Coluna Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGFLUXOCONF      NUMCAR NUMBER(10,0)                Numero do carregamento do conferido.            OPERACIONAL                        NaN
PCLOGFLUXOCONF      NUMPED NUMBER(10,0)                         Numero do pedido conferido.            OPERACIONAL                        NaN
PCLOGFLUXOCONF     CODPROD  NUMBER(6,0)                        Código do produto conferido.            OPERACIONAL                        NaN
PCLOGFLUXOCONF CODFUNCCONF  NUMBER(8,0)                     Codigo do conferente do pedido.            OPERACIONAL                        NaN
PCLOGFLUXOCONF  CODFUNCSEP  NUMBER(8,0)                      Codigo do separador do pedido.            OPERACIONAL                        NaN
PCLOGFLUXOCONF QTCONFERIDA NUMBER(20,6)                    Quantidade conferida do produto.            OPERACIONAL                        NaN
PCLOGFLUXOCONF    DATACONF         DATE                Data/hora de conferencia do produto.            OPERACIONAL                        NaN
PCLOGFLUXOCONF     NUMLOTE VARCHAR2(15) Lote atribuido na conferência dos itens do produto.            OPERACIONAL                        NaN
PCLOGFLUXOCONF    NUMCAIXA VARCHAR2(10)                                    Numero da caixa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*