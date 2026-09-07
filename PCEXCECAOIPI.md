# 📊 Tabela: PCEXCECAOIPI

### Estrutura de Colunas e Restrições

      Tabela              Coluna Tipo/Tamanho                                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXCECAOIPI          CODEXCECAO  NUMBER(8,0)                                                                                   Gravar o código da exceção inclusa    CHAVE PRIMÁRIA (PK)                        NaN
PCEXCECAOIPI               TIPO1  VARCHAR2(2)                         Cliente Suframa: O usuário escolherá se o cliente será cliente Suframa ou não: "Sim" / "Não"            OPERACIONAL                        NaN
PCEXCECAOIPI              VALOR1 VARCHAR2(10) Produto importado: O usuário escolherá se o produto tratado na exceção ser importando ou não. Dominio: "Sim" / "Não"            OPERACIONAL                        NaN
PCEXCECAOIPI        CODFIGURAIPI  NUMBER(8,0)                                                                                Código da figura que está relacionada            OPERACIONAL                        NaN
PCEXCECAOIPI CODFIGURAIPIEXCECAO  NUMBER(8,0)                                                                              Código da figura que será redirecionado            OPERACIONAL                        NaN
PCEXCECAOIPI               TIPO2  VARCHAR2(2)                         Cliente Suframa: O usuário escolherá se o cliente será cliente Suframa ou não: "Sim" / "Não"            OPERACIONAL                        NaN
PCEXCECAOIPI              VALOR2 VARCHAR2(10) Produto importado: O usuário escolherá se o produto tratado na exceção ser importando ou não. Dominio: "Sim" / "Não"            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*