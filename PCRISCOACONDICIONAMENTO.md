# 📊 Tabela: PCRISCOACONDICIONAMENTO

### Estrutura de Colunas e Restrições

                 Tabela         Coluna  Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRISCOACONDICIONAMENTO        CODTIPO   VARCHAR2(4)                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCRISCOACONDICIONAMENTO       MENSAGEM VARCHAR2(200)                          NaN            OPERACIONAL                        NaN
PCRISCOACONDICIONAMENTO         CODONU   VARCHAR2(6)         Indica o código ONU.            OPERACIONAL                        NaN
PCRISCOACONDICIONAMENTO     GRUPORISCO   VARCHAR2(6)     Indica o grupo de risco.            OPERACIONAL                        NaN
PCRISCOACONDICIONAMENTO GRUPOEMBALAGEM   VARCHAR2(6) Indica o grupo de embalagem.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*