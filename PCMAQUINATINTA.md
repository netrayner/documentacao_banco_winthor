# 📊 Tabela: PCMAQUINATINTA

### Estrutura de Colunas e Restrições

        Tabela                 Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMAQUINATINTA             CODMAQUINA  NUMBER(4,0)                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMAQUINATINTA       DESCMAQUINATINTA VARCHAR2(40)                                          NaN            OPERACIONAL                        NaN
PCMAQUINATINTA            TIPOMAQUINA  VARCHAR2(1)                                          NaN            OPERACIONAL                        NaN
PCMAQUINATINTA                CODEPTO  NUMBER(6,0) CADASTRO DO DEPARTAMENTO DA MAQUINA DE TINTA            OPERACIONAL                        NaN
PCMAQUINATINTA                 CODSEC  NUMBER(6,0)        CADASTRO DA SEÇÃO DA MAQUINA DE TINTA            OPERACIONAL                        NaN
PCMAQUINATINTA              CODFORNEC  NUMBER(6,0)   CADASTRO DO FORNECEDOR DA MAQUINA DE TINTA            OPERACIONAL                        NaN
PCMAQUINATINTA           CODCATEGORIA  NUMBER(6,0)    CADASTRO DA CATEGORIA DA MAQUINA DE TINTA            OPERACIONAL                        NaN
PCMAQUINATINTA DESCONSIDERARPIGMENTOS  VARCHAR2(1)            DESCONSIDERAR PREÇO DOS PIGMENTOS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*