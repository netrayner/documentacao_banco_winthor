# 📊 Tabela: PCDFESPROCESSADOS

### Estrutura de Colunas e Restrições

           Tabela         Coluna  Tipo/Tamanho                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDFESPROCESSADOS           DATA          DATE                                                                         Data do processamento            OPERACIONAL                        NaN
PCDFESPROCESSADOS CHAVEDOCUMENTO  VARCHAR2(44)                                                                            Chave do documento            OPERACIONAL                        NaN
PCDFESPROCESSADOS        TIPODOC   VARCHAR2(7)                                               Tipo do documento, pode ser NFE, CTE, MDFE, CCE            OPERACIONAL                        NaN
PCDFESPROCESSADOS         STATUS VARCHAR2(100) Status do documento (CANCELADO, APROVADO, EM_PROCESSAMENTO, REPROVADO_LOCAL, REPROVADO_SEFAZ)            OPERACIONAL                        NaN
PCDFESPROCESSADOS    TIPOEMISSAO   VARCHAR2(1)                                                                     Tipo emissão do documento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*