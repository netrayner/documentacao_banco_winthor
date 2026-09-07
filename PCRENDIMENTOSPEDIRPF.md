# 📊 Tabela: PCRENDIMENTOSPEDIRPF

### Estrutura de Colunas e Restrições

              Tabela             Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRENDIMENTOSPEDIRPF         CODSERVICO  NUMBER(10,0)                      Código do serviço    CHAVE PRIMÁRIA (PK)                        NaN
PCRENDIMENTOSPEDIRPF  CODTIPORENDIMENTO  NUMBER(10,0)          Código natureza do rendimento CHAVE ESTRANGEIRA (FK)   PCTIPORENDIMENTOSPEDIRPF
PCRENDIMENTOSPEDIRPF       VALORBRUTONF  NUMBER(14,2)             Valor total da nota fiscal            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPF VALORBASERENTENCAO  NUMBER(14,2)              Valor base de retenção IR            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPF       PERCRETENCAO  NUMBER(14,2)        Percentual alíquota retenção IR            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPF      VALORRETENCAO  NUMBER(14,2)                      Valor retenção IR            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPF                FCI   VARCHAR2(1)         Fundo ou Clube de Investimento            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPF     DECIMOTERCEIRO   VARCHAR2(1)                            13° salário            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPF                RRA   VARCHAR2(1)   Rendimentos Recebidos Acumuladamente            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPF        OBSERVACOES VARCHAR2(200)                   Campo de observações            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPF            ALUGUEL   VARCHAR2(1) Define se o lançamento é para aluguel.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*