# 📊 Tabela: PCBRINDEFV

### Estrutura de Colunas e Restrições

    Tabela            Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBRINDEFV         NUMPEDRCA NUMBER(10,0)                      Número do pedido    CHAVE PRIMÁRIA (PK)                   PCPEDCFV
PCBRINDEFV           CODUSUR  NUMBER(4,0)                     Código do usuário    CHAVE PRIMÁRIA (PK)                   PCPEDCFV
PCBRINDEFV            CGCCLI VARCHAR2(18)                CPF ou CNPJ do cliente    CHAVE PRIMÁRIA (PK)                   PCPEDCFV
PCBRINDEFV DTABERTURAPEDPALM         DATE Data da abertura do pedido no palmtop    CHAVE PRIMÁRIA (PK)                   PCPEDCFV
PCBRINDEFV           CODPROD  NUMBER(6,0)                     Código do produto            OPERACIONAL                        NaN
PCBRINDEFV       CODPROMOCAO  NUMBER(6,0)          Código da promoção do brinde            OPERACIONAL                        NaN
PCBRINDEFV                QT NUMBER(20,6)                   Quantidade de itens            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*