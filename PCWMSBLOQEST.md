# 📊 Tabela: PCWMSBLOQEST

### Estrutura de Colunas e Restrições

      Tabela      Coluna Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWMSBLOQEST CODENDERECO NUMBER(10,0)                                          Código do endereço bloqueado            OPERACIONAL                        NaN
PCWMSBLOQEST     CODPROD NUMBER(10,0)                                         código do produto no endereço            OPERACIONAL                        NaN
PCWMSBLOQEST        TIPO  VARCHAR2(2) Tipo do bloqueio, 'BC' , bloqueio comercial e BL , bloqueio logistico            OPERACIONAL                        NaN
PCWMSBLOQEST          QT NUMBER(20,6)                                                  Quantidade bloqueada            OPERACIONAL                        NaN
PCWMSBLOQEST       DTVAL         DATE                     Data de validade do produto bloqueado no endereço            OPERACIONAL                        NaN
PCWMSBLOQEST    NUMBONUS  NUMBER(6,0)                                                      Numero do bônus.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*