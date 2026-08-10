# 📊 Tabela: PCTIPORENDIMENTOSPEDIRPF

### Estrutura de Colunas e Restrições

                  Tabela            Coluna   Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTIPORENDIMENTOSPEDIRPF CODTIPORENDIMENTO   NUMBER(10,0)        Código natureza do rendimento    CHAVE PRIMÁRIA (PK)                        NaN
PCTIPORENDIMENTOSPEDIRPF         DESCRICAO VARCHAR2(1000)  Descrição da natureza de rendimento            OPERACIONAL                        NaN
PCTIPORENDIMENTOSPEDIRPF               FCI    VARCHAR2(1)       Fundo ou Clube de Investimento            OPERACIONAL                        NaN
PCTIPORENDIMENTOSPEDIRPF    DECIMOTERCEIRO    VARCHAR2(1)                          13° salário            OPERACIONAL                        NaN
PCTIPORENDIMENTOSPEDIRPF               RRA    VARCHAR2(1) Rendimentos Recebidos Acumuladamente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*