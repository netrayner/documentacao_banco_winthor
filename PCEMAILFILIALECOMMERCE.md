# 📊 Tabela: PCEMAILFILIALECOMMERCE

### Estrutura de Colunas e Restrições

                Tabela      Coluna  Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMAILFILIALECOMMERCE          ID  NUMBER(10,0)         Identificador do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCEMAILFILIALECOMMERCE        HOST  VARCHAR2(50)              Informação do host            OPERACIONAL                        NaN
PCEMAILFILIALECOMMERCE       PORTA  NUMBER(10,0)             Informação da porta            OPERACIONAL                        NaN
PCEMAILFILIALECOMMERCE     USUARIO VARCHAR2(150)           Infomação do usuário            OPERACIONAL                        NaN
PCEMAILFILIALECOMMERCE       SENHA  VARCHAR2(50)             Informação da senha            OPERACIONAL                        NaN
PCEMAILFILIALECOMMERCE        NOME  VARCHAR2(50)              Informação de nome            OPERACIONAL                        NaN
PCEMAILFILIALECOMMERCE EMAILSCOPIA          CLOB        Emails que serão copiados            OPERACIONAL                        NaN
PCEMAILFILIALECOMMERCE    FILIALID  NUMBER(10,0) Identificador da filial ecommerce CHAVE ESTRANGEIRA (FK)          PCFILIALECOMMERCE
PCEMAILFILIALECOMMERCE         TLS   NUMBER(1,0)             Identifica se usa TLS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*