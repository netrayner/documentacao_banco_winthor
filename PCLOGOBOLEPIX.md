# 📊 Tabela: PCLOGOBOLEPIX

### Estrutura de Colunas e Restrições

       Tabela     Coluna  Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGOBOLEPIX      BANCO   NUMBER(4,0)                               Código do banco            OPERACIONAL                        NaN
PCLOGOBOLEPIX     FILIAL   VARCHAR2(2)                             Código da Filial             OPERACIONAL                        NaN
PCLOGOBOLEPIX    ENDLOGO VARCHAR2(300)                             Diretório da logo            OPERACIONAL                        NaN
PCLOGOBOLEPIX LOGOBASE64          CLOB Imagem em base64 da logo da filial da empresa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*