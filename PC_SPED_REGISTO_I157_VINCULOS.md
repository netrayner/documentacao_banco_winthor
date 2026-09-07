# 📊 Tabela: PC_SPED_REGISTO_I157_VINCULOS

### Estrutura de Colunas e Restrições

                       Tabela                    Coluna Tipo/Tamanho                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PC_SPED_REGISTO_I157_VINCULOS                    CODIGO NUMBER(10,0)                                                      Chave Primária artificial    CHAVE PRIMÁRIA (PK)                        NaN
PC_SPED_REGISTO_I157_VINCULOS             CODPLANOCONTA  NUMBER(5,0) Chave Estrangeira Composta, é referente ao plano de contas em exercício atual. CHAVE ESTRANGEIRA (FK)                 PCMODELOPC
PC_SPED_REGISTO_I157_VINCULOS            CODREDUZIDO_PC VARCHAR2(12) Chave Estrangeira Composta, é referente ao plano de contas em exercício atual. CHAVE ESTRANGEIRA (FK)                 PCMODELOPC
PC_SPED_REGISTO_I157_VINCULOS             ANO_VINCULADO  NUMBER(4,0)                        Ano anterior ao ano plano de contas do exercício atual.            OPERACIONAL                        NaN
PC_SPED_REGISTO_I157_VINCULOS   CODPLANOCONTA_VINCULADO  NUMBER(5,0)                            Referente ao plano de contas do exercício anterior.            OPERACIONAL                        NaN
PC_SPED_REGISTO_I157_VINCULOS  CODREDUZIDO_PC_VINCULADO VARCHAR2(12)                            Referente ao plano de contas do exercício anterior.            OPERACIONAL                        NaN
PC_SPED_REGISTO_I157_VINCULOS CODGRUPOFILIAL_VINCULADOR  NUMBER(5,0)                    Referente ao grupo de filiais dono desta linha no registro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*