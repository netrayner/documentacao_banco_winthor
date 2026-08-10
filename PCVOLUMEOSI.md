# 📊 Tabela: PCVOLUMEOSI

### Estrutura de Colunas e Restrições

     Tabela      Coluna Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVOLUMEOSI       NUMOS NUMBER(16,0)                                    Número da ordem de serviço            OPERACIONAL                        NaN
PCVOLUMEOSI      NUMVOL  NUMBER(6,0)                    Número do volume de localização do produto            OPERACIONAL                        NaN
PCVOLUMEOSI     CODFUNC  NUMBER(8,0) Matricula do funcionário que realizou a separaração do volume            OPERACIONAL                        NaN
PCVOLUMEOSI     CODPROD NUMBER(16,0)                            Código de identificação do produto            OPERACIONAL                        NaN
PCVOLUMEOSI  QTSEPARADA NUMBER(16,0)                   Quantidade do produto separada para produto            OPERACIONAL                        NaN
PCVOLUMEOSI     NUMLOTE NUMBER(20,0)                         Número do lote informado pelo produto            OPERACIONAL                        NaN
PCVOLUMEOSI CODAUXILIAR VARCHAR2(20)                                    Código de barra do produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*