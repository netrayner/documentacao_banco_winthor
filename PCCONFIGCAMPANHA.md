# 📊 Tabela: PCCONFIGCAMPANHA

### Estrutura de Colunas e Restrições

          Tabela      Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGCAMPANHA      CODIGO  NUMBER(4,0)                   Código da configuração de campanha.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGCAMPANHA    TIPOMETA  VARCHAR2(2)                                         Tipo de meta.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGCAMPANHA      COLUNA VARCHAR2(32)                                   Coluna do critério.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGCAMPANHA OBRIGATORIO  VARCHAR2(2) Indica se o critério e obrigatório ou não na apuração            OPERACIONAL                        NaN
PCCONFIGCAMPANHA  DTMXSALTER         DATE                                                   NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*