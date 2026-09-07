# 📊 Tabela: PCTERMOUSOSERVICO

### Estrutura de Colunas e Restrições

           Tabela        Coluna  Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTERMOUSOSERVICO   CODTERMOUSO  NUMBER(10,0)                 Código de identificação do termo de uso    CHAVE PRIMÁRIA (PK)                        NaN
PCTERMOUSOSERVICO          CNPJ  VARCHAR2(50)                                                    CNPJ            OPERACIONAL                        NaN
PCTERMOUSOSERVICO USUARIOLOGADO  VARCHAR2(50)                Email do usuário que executou a operação            OPERACIONAL                        NaN
PCTERMOUSOSERVICO          DATA          DATE                            Data da execução da operação            OPERACIONAL                        NaN
PCTERMOUSOSERVICO   TIPOSERVICO VARCHAR2(255) Para qual tipo de serviço o termo de uso foi respondido            OPERACIONAL                        NaN
PCTERMOUSOSERVICO       DESTINO VARCHAR2(255)                              Quem vai usar este serviço            OPERACIONAL                        NaN
PCTERMOUSOSERVICO        ACEITO       CHAR(1)                     Se o termo de uso foi aceito ou não            OPERACIONAL                        NaN
PCTERMOUSOSERVICO       ARQUIVO          CLOB                                 Arquivo do termo de uso            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*