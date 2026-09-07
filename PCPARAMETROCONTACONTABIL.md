# 📊 Tabela: PCPARAMETROCONTACONTABIL

### Estrutura de Colunas e Restrições

                  Tabela             Coluna Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMETROCONTACONTABIL    CODIGOPARAMETRO NUMBER(10,0)                           Indica o código do parâmetro.    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMETROCONTACONTABIL DESCRICAOPARAMETRO VARCHAR2(40)                        Indica a descrição do parâmetro.            OPERACIONAL                        NaN
PCPARAMETROCONTACONTABIL             STATUS  VARCHAR2(1) Indica a situação do parâmetro - [A]tiva ou [D]esativa.            OPERACIONAL                        NaN
PCPARAMETROCONTACONTABIL              SIGLA  VARCHAR2(5)                             Sigla do parâmetro contabil            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*