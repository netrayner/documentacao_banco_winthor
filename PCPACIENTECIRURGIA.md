# 📊 Tabela: PCPACIENTECIRURGIA

### Estrutura de Colunas e Restrições

            Tabela              Coluna  Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPACIENTECIRURGIA CODPACIENTECIRURGIA   NUMBER(9,0)       Cód. Paciente    CHAVE PRIMÁRIA (PK)                        NaN
PCPACIENTECIRURGIA                NOME  VARCHAR2(40)    Nome do Paciente            OPERACIONAL                        NaN
PCPACIENTECIRURGIA        NUMDOCUMENTO  VARCHAR2(14)    Número Documento            OPERACIONAL                        NaN
PCPACIENTECIRURGIA            ENDERECO  VARCHAR2(70)            Endereço            OPERACIONAL                        NaN
PCPACIENTECIRURGIA         COMPLEMENTO  VARCHAR2(20)         Complemento            OPERACIONAL                        NaN
PCPACIENTECIRURGIA                 CEP   VARCHAR2(9)                 CEP            OPERACIONAL                        NaN
PCPACIENTECIRURGIA              CIDADE  VARCHAR2(30)              Cidade            OPERACIONAL                        NaN
PCPACIENTECIRURGIA                  UF   VARCHAR2(2)                  UF            OPERACIONAL                        NaN
PCPACIENTECIRURGIA            TELEFONE  VARCHAR2(20)            Telefone            OPERACIONAL                        NaN
PCPACIENTECIRURGIA                 FAX  VARCHAR2(20)                 Fax            OPERACIONAL                        NaN
PCPACIENTECIRURGIA             DATACAD          DATE       Data Cadastro            OPERACIONAL                        NaN
PCPACIENTECIRURGIA               EMAIL VARCHAR2(100)               Email            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*