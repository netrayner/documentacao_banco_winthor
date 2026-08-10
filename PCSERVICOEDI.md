# 📊 Tabela: PCSERVICOEDI

### Estrutura de Colunas e Restrições

      Tabela           Coluna Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOEDI    CODSERVICOEDI  NUMBER(6,0)    Código do Serviço de EDI    CHAVE PRIMÁRIA (PK)                        NaN
PCSERVICOEDI   NOMESERVICOEDI VARCHAR2(20)             Nome do Serviço            OPERACIONAL                        NaN
PCSERVICOEDI      TIPOSERVICO  NUMBER(3,0)             Tipo de Serviço            OPERACIONAL                        NaN
PCSERVICOEDI            GRUPO  VARCHAR2(1)                       Grupo            OPERACIONAL                        NaN
PCSERVICOEDI        ULTSEQARQ  NUMBER(6,0) Última Sequência do Arquivo            OPERACIONAL                        NaN
PCSERVICOEDI     AGRUPAFILIAL  VARCHAR2(1)       Agrupar Filial (S/N).            OPERACIONAL                        NaN
PCSERVICOEDI CODFILIALPRINCIP  VARCHAR2(2) Código da Filial Principal.            OPERACIONAL                        NaN
PCSERVICOEDI      INTEGRADORA  NUMBER(6,0)       Código da Integradora            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*