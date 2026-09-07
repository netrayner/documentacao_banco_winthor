# 📊 Tabela: PCBAIRRO

### Estrutura de Colunas e Restrições

  Tabela             Coluna  Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBAIRRO          CODBAIRRO   NUMBER(6,0)                  Código do bairro a ser cadastrado.            OPERACIONAL                        NaN
PCBAIRRO          DESCRICAO VARCHAR2(150)                                Descrição do bairro.            OPERACIONAL                        NaN
PCBAIRRO                 UF   VARCHAR2(2)                           Identifica a UF do bairro            OPERACIONAL                        NaN
PCBAIRRO          CODCIDADE   NUMBER(6,0)                       Identifica a Cidade Do bairro            OPERACIONAL                        NaN
PCBAIRRO        VLTXENTREGA  NUMBER(18,6) Identifica o valor da Taxa de Entrega para o bairro            OPERACIONAL                        NaN
PCBAIRRO FATORMULTIPLICADOR  NUMBER(18,6)      Identifica o fator multiplicador para o bairro            OPERACIONAL                        NaN
PCBAIRRO         DTMXSALTER          DATE                                                 NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*