# 📊 Tabela: PCCONDICAOVENDA

### Estrutura de Colunas e Restrições

         Tabela            Coluna Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONDICAOVENDA  CODCONDICAOVENDA  NUMBER(6,0)                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONDICAOVENDA         DESCRICAO VARCHAR2(80)                                                      NaN            OPERACIONAL                        NaN
PCCONDICAOVENDA    DTVALIDINICIAL         DATE Data inicial do periódo de vigência da condição de venda            OPERACIONAL                        NaN
PCCONDICAOVENDA      DTVALIDFINAL         DATE   Data final do periódo de vigência da condição de venda            OPERACIONAL                        NaN
PCCONDICAOVENDA     TIPODESCBONIF  VARCHAR2(1)                        Tipo de desconto para Bonificação            OPERACIONAL                        NaN
PCCONDICAOVENDA   TIPOVALORMINIMO  VARCHAR2(1)                      Tipo de valor mínino para o período            OPERACIONAL                        NaN
PCCONDICAOVENDA    VALORMINIMOPED NUMBER(15,2)                                   Valor mínimo do pedido            OPERACIONAL                        NaN
PCCONDICAOVENDA  CONDICAOINTEGRAD  VARCHAR2(1)                                  Condição da integradora            OPERACIONAL                        NaN
PCCONDICAOVENDA TIPOPRAZOINTEGRAD  VARCHAR2(1)                             Tipo de prazo da integradora            OPERACIONAL                        NaN
PCCONDICAOVENDA     PRAZOINTEGRAD  NUMBER(3,0)                                     Prazo da integradora            OPERACIONAL                        NaN
PCCONDICAOVENDA  CODPRAZOINTEGRAD VARCHAR2(20)                                             Código Prazo            OPERACIONAL                        NaN
PCCONDICAOVENDA         TIPOPLPAG  NUMBER(1,0)                               Tipo de Plano de Pagamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*