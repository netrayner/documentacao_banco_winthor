# 📊 Tabela: PCCSRTWINTHOR

### Estrutura de Colunas e Restrições

       Tabela     Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCSRTWINTHOR         ID  NUMBER(6,0)                       Código sequencial da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCCSRTWINTHOR         UF  VARCHAR2(2) Unidade da federação onde o código foi registrado            OPERACIONAL                        NaN
PCCSRTWINTHOR   AMBIENTE  VARCHAR2(1)       Ambiente de emissão do documento eletrônico            OPERACIONAL                        NaN
PCCSRTWINTHOR       CNPJ VARCHAR2(14)                             CNPJ do Totvs Winthor            OPERACIONAL                        NaN
PCCSRTWINTHOR     IDCSRT  VARCHAR2(2)  Identificador do código CSRT da Totvs junto à UF            OPERACIONAL                        NaN
PCCSRTWINTHOR       CSRT VARCHAR2(64)                   Código CSRT da Totvs junto à UF            OPERACIONAL                        NaN
PCCSRTWINTHOR DATAINICIO         DATE                   Data de início da norma técnica            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*