# 📊 Tabela: PCFORNECPLANOCOMP

### Estrutura de Colunas e Restrições

           Tabela       Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORNECPLANOCOMP    CODFORNEC  NUMBER(6,0)                                            Código do fornecedor    CHAVE PRIMÁRIA (PK)                   PCFORNEC
PCFORNECPLANOCOMP CODCOMPRADOR  NUMBER(8,0)                                             Código do comprador    CHAVE PRIMÁRIA (PK)                        NaN
PCFORNECPLANOCOMP   CODPARCELA  NUMBER(6,0)                                               Código da parcela    CHAVE PRIMÁRIA (PK)                        NaN
PCFORNECPLANOCOMP     PRAZOMIN  NUMBER(4,0) Prazo mínimo pagamento aceito no pedido de compra por comprador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*