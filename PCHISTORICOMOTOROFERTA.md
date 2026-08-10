# 📊 Tabela: PCHISTORICOMOTOROFERTA

### Estrutura de Colunas e Restrições

                Tabela           Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTORICOMOTOROFERTA        NUMPEDECF NUMBER(10,0)            Numero do Pedido gerado pelo caixa    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOMOTOROFERTA         NUMCAIXA  NUMBER(4,0)                               Numero do caixa    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOMOTOROFERTA             DATA  NUMBER(8,0)     Data do pedido enviado ao motor de oferta            OPERACIONAL                        NaN
PCHISTORICOMOTOROFERTA DADOSMOTOROFERTA         CLOB Armazena o Json de retorno do motor de oferta            OPERACIONAL                        NaN
PCHISTORICOMOTOROFERTA        EXPORTADO  VARCHAR2(1)                       Enviado para o servidor            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*