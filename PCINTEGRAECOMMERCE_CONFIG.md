# 📊 Tabela: PCINTEGRAECOMMERCE_CONFIG

### Estrutura de Colunas e Restrições

                   Tabela     Coluna  Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRAECOMMERCE_CONFIG     CODIGO  NUMBER(20,0)                 Código da configuração de layout de integração    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRAECOMMERCE_CONFIG  DESCRICAO VARCHAR2(100)                                      Descrição da configuração            OPERACIONAL                        NaN
PCINTEGRAECOMMERCE_CONFIG  CODLAYOUT   NUMBER(6,0) Código do layout referente a tabela PCINTEGRAECOMMERCE_LAYOUTC CHAVE ESTRANGEIRA (FK) PCINTEGRAECOMMERCE_LAYOUTC
PCINTEGRAECOMMERCE_CONFIG DTEXCLUSAO          DATE                      Data da exclusão (inativação) do cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*