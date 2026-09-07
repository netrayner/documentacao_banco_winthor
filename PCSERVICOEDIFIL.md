# 📊 Tabela: PCSERVICOEDIFIL

### Estrutura de Colunas e Restrições

         Tabela        Coluna  Tipo/Tamanho       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOEDIFIL CODSERVICOEDI   NUMBER(6,0)  Código do Serviço de EDI    CHAVE PRIMÁRIA (PK)                        NaN
PCSERVICOEDIFIL     CODFILIAL   VARCHAR2(2)          Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCSERVICOEDIFIL CXPOSTALREMET  VARCHAR2(35) Caixa Postal do Remetente            OPERACIONAL                        NaN
PCSERVICOEDIFIL  CODFILIALVAN  VARCHAR2(20)   Código da Filial na VAN            OPERACIONAL                        NaN
PCSERVICOEDIFIL     DIRETORIO VARCHAR2(200)                 Diretório            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*