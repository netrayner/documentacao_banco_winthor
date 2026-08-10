# 📊 Tabela: PCLOGDADOSFISCAIS

### Estrutura de Colunas e Restrições

           Tabela      Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGDADOSFISCAIS     CODFUNC  NUMBER(8,0)           Código do funcionário no Winthor            OPERACIONAL                        NaN
PCLOGDADOSFISCAIS     TIPOOBJ  VARCHAR2(1)                   Tipo da tabela de origem            OPERACIONAL                        NaN
PCLOGDADOSFISCAIS      CODOBJ  NUMBER(6,0) Código do fornecedor ou cliente ou produto            OPERACIONAL                        NaN
PCLOGDADOSFISCAIS DTALTERACAO         DATE                          Data de alteração            OPERACIONAL                        NaN
PCLOGDADOSFISCAIS      ROTINA VARCHAR2(40)                 Nome da rotina que alterou            OPERACIONAL                        NaN
PCLOGDADOSFISCAIS         OBS VARCHAR2(40)               Observação sobre a alteração            OPERACIONAL                        NaN
PCLOGDADOSFISCAIS       CAMPO VARCHAR2(30)             Nome do campo que foi alterado            OPERACIONAL                        NaN
PCLOGDADOSFISCAIS    VALORANT         CLOB                    Valor anterior do campo            OPERACIONAL                        NaN
PCLOGDADOSFISCAIS    VALORATU         CLOB                       Valor atual do campo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*