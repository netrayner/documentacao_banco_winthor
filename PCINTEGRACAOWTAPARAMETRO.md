# 📊 Tabela: PCINTEGRACAOWTAPARAMETRO

### Estrutura de Colunas e Restrições

                  Tabela       Coluna   Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOWTAPARAMETRO           ID         NUMBER             Identificador do parâmetro    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOWTAPARAMETRO      SERVICO   VARCHAR2(80) Identificador do serviço da integração            OPERACIONAL                        NaN
PCINTEGRACAOWTAPARAMETRO VERSAOORIGEM   VARCHAR2(20)        Versão que originou o parâmetro            OPERACIONAL                        NaN
PCINTEGRACAOWTAPARAMETRO    PARAMETRO  VARCHAR2(255)                     Chave do parâmetro            OPERACIONAL                        NaN
PCINTEGRACAOWTAPARAMETRO        VALOR VARCHAR2(4000)                     Valor do parâmetro            OPERACIONAL                        NaN
PCINTEGRACAOWTAPARAMETRO CODIGOFILIAL   VARCHAR2(80)                Código filial vinculada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*