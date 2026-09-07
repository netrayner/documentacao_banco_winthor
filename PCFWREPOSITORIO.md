# 📊 Tabela: PCFWREPOSITORIO

### Estrutura de Colunas e Restrições

         Tabela        Coluna  Tipo/Tamanho   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFWREPOSITORIO       SERVICO VARCHAR2(200)             Descrição    CHAVE PRIMÁRIA (PK)                        NaN
PCFWREPOSITORIO        VERSAO  VARCHAR2(10)                Versão    CHAVE PRIMÁRIA (PK)                        NaN
PCFWREPOSITORIO         PATCH   NUMBER(4,0)                 Patch            OPERACIONAL                        NaN
PCFWREPOSITORIO CRIPTOGRAFADO   VARCHAR2(1)         Criptografado            OPERACIONAL                        NaN
PCFWREPOSITORIO        SCRIPT          CLOB                Script            OPERACIONAL                        NaN
PCFWREPOSITORIO    DTINCLUSAO          DATE      Data de inclusão            OPERACIONAL                        NaN
PCFWREPOSITORIO   DTALTERACAO          DATE     Data de alteração            OPERACIONAL                        NaN
PCFWREPOSITORIO    ASSINATURA  VARCHAR2(32) Assinautra do serviço            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*