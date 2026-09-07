# 📊 Tabela: PCVOLUMEASSOCIADOPALETE

### Estrutura de Colunas e Restrições

                 Tabela          Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVOLUMEASSOCIADOPALETE          NUMVOL VARCHAR2(40)                           Número do volume    CHAVE PRIMÁRIA (PK)                        NaN
PCVOLUMEASSOCIADOPALETE       CODPALETE VARCHAR2(80)                           Código do palete    CHAVE PRIMÁRIA (PK)                        NaN
PCVOLUMEASSOCIADOPALETE          NUMSEQ NUMBER(10,0)                        Número da sequência            OPERACIONAL                        NaN
PCVOLUMEASSOCIADOPALETE            DATA         DATE                           Data da inclusão            OPERACIONAL                        NaN
PCVOLUMEASSOCIADOPALETE         CODFUNC  NUMBER(6,0)          Código do funcionário que incluiu            OPERACIONAL                        NaN
PCVOLUMEASSOCIADOPALETE          CODBOX  NUMBER(6,0)                              Código do Box            OPERACIONAL                        NaN
PCVOLUMEASSOCIADOPALETE         CODROTA  NUMBER(6,0)                             Código da Rota            OPERACIONAL                        NaN
PCVOLUMEASSOCIADOPALETE DTASSOCIACAOBOX         DATE                  Data de associação do box            OPERACIONAL                        NaN
PCVOLUMEASSOCIADOPALETE  CODFUNCASSCBOX  NUMBER(6,0) Código do funcionário que associou ao box.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*