# 📊 Tabela: PCALCADASAPROVPAGC

### Estrutura de Colunas e Restrições

            Tabela           Coluna Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCALCADASAPROVPAGC        CODALCADA NUMBER(10,0)                                       Código da alçada cadastrada    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADASAPROVPAGC         DTINICIO         DATE                           Data de início do de vigencia da alçada            OPERACIONAL                        NaN
PCALCADASAPROVPAGC            DTFIM         DATE                              Data de fim do de vigencia da alçada            OPERACIONAL                        NaN
PCALCADASAPROVPAGC       CODFUNCCAD NUMBER(10,0)                      Código do funcionario que cadastrou a alçada            OPERACIONAL                        NaN
PCALCADASAPROVPAGC            DTCAD         DATE                                        Data de cadastro da alçada            OPERACIONAL                        NaN
PCALCADASAPROVPAGC GERADOCOMDIAUTIL  VARCHAR2(1) Determina se a alçada foi gerada em período utilizando dias uteis            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*