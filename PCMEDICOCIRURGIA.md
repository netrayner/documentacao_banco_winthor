# 📊 Tabela: PCMEDICOCIRURGIA

### Estrutura de Colunas e Restrições

          Tabela            Coluna  Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMEDICOCIRURGIA CODMEDICOCIRURGIA   NUMBER(6,0)         Cód. Médico    CHAVE PRIMÁRIA (PK)                        NaN
PCMEDICOCIRURGIA              NOME  VARCHAR2(40)      Nome do Médico            OPERACIONAL                        NaN
PCMEDICOCIRURGIA            NUMCRM  VARCHAR2(14)          Número CRM            OPERACIONAL                        NaN
PCMEDICOCIRURGIA          ENDERECO  VARCHAR2(70)            Endereço            OPERACIONAL                        NaN
PCMEDICOCIRURGIA       COMPLEMENTO  VARCHAR2(20)         Complemento            OPERACIONAL                        NaN
PCMEDICOCIRURGIA               CEP   VARCHAR2(9)                 CEP            OPERACIONAL                        NaN
PCMEDICOCIRURGIA            CIDADE  VARCHAR2(30)              Cidade            OPERACIONAL                        NaN
PCMEDICOCIRURGIA                UF   VARCHAR2(2)                  UF            OPERACIONAL                        NaN
PCMEDICOCIRURGIA          TELEFONE  VARCHAR2(20)            Telefone            OPERACIONAL                        NaN
PCMEDICOCIRURGIA               FAX  VARCHAR2(20)                 Fax            OPERACIONAL                        NaN
PCMEDICOCIRURGIA           DATACAD          DATE       Data Cadastro            OPERACIONAL                        NaN
PCMEDICOCIRURGIA             EMAIL VARCHAR2(100)               Email            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*