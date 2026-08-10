# 📊 Tabela: PCLOGROTINASDESATUALIZADAS

### Estrutura de Colunas e Restrições

                    Tabela               Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGROTINASDESATUALIZADAS            CODROTINA VARCHAR2(40)                                Apresenta codigo da rotina            OPERACIONAL                        NaN
PCLOGROTINASDESATUALIZADAS        VERSAOCLIENTE  NUMBER(8,0)                   Apresenta a versão da rotina do cliente            OPERACIONAL                        NaN
PCLOGROTINASDESATUALIZADAS          MENORVERSAO  NUMBER(8,0)           Apresenta a menor versao que deve ser executada            OPERACIONAL                        NaN
PCLOGROTINASDESATUALIZADAS           CODUSUARIO  NUMBER(4,0)                             Apresenta o codigo do usuario            OPERACIONAL                        NaN
PCLOGROTINASDESATUALIZADAS                 DATA         DATE                             Apresnta a data de lancamento            OPERACIONAL                        NaN
PCLOGROTINASDESATUALIZADAS       USUARIOMAQUINA VARCHAR2(30) Apresenta o usuario que esta logado na maquina da máquina            OPERACIONAL                        NaN
PCLOGROTINASDESATUALIZADAS              MAQUINA VARCHAR2(30)                Apresenta a maquina que esta desatualizada            OPERACIONAL                        NaN
PCLOGROTINASDESATUALIZADAS EXECUTANDOLOCALMENTE  VARCHAR2(1)         Apresenta se o usuario esta executando localmente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*