# 📊 Tabela: PCMOVLOJA

### Estrutura de Colunas e Restrições

   Tabela              Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVLOJA          CODMOVLOJA  NUMBER(6,0)                                               Código sequencial    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVLOJA           CODFILIAL  VARCHAR2(2)                                                Código da filial            OPERACIONAL                        NaN
PCMOVLOJA                TIPO  VARCHAR2(1)                     Tipo do movimento: Requisição ou Inventário            OPERACIONAL                        NaN
PCMOVLOJA          DTCADASTRO         DATE                                                Data de cadastro            OPERACIONAL                        NaN
PCMOVLOJA             DTBAIXA         DATE                                   Data de baixa da movimentação            OPERACIONAL                        NaN
PCMOVLOJA           CODFUNCAD  NUMBER(8,0)                               Código do funcionário do cadastro            OPERACIONAL                        NaN
PCMOVLOJA     CODFUNEXPEDICAO  NUMBER(8,0)                Código do funcionário de reposição da mercadoria            OPERACIONAL                        NaN
PCMOVLOJA         CODFUNBAIXA  NUMBER(8,0)                                  Código do funcionário da baixa            OPERACIONAL                        NaN
PCMOVLOJA           CODROTINA  NUMBER(6,0)                                    Código da rotina de cadastro            OPERACIONAL                        NaN
PCMOVLOJA      CODMOVLOJAORIG  NUMBER(6,0)                                  Código da movimentação da loja            OPERACIONAL                        NaN
PCMOVLOJA          TIPOCANCEL  VARCHAR2(1)                                            Tipo de cancelamento            OPERACIONAL                        NaN
PCMOVLOJA  LOCALABASTECIMENTO  VARCHAR2(1) Local de Abastecimento (gondola ou area de retirada do produto)            OPERACIONAL                        NaN
PCMOVLOJA CODLOCALARMAZENAGEM NUMBER(10,0)                                  Código do local de armazenagem            OPERACIONAL                        NaN
PCMOVLOJA              CODIMP NUMBER(10,0)                                            Codigo da impressora            OPERACIONAL                        NaN
PCMOVLOJA          CODFUNCIMP NUMBER(10,0)                              Codigo do Funcionario que imprimiu            OPERACIONAL                        NaN
PCMOVLOJA       DTPRIMEIRAIMP         DATE                                      Data da primeira impressão            OPERACIONAL                        NaN
PCMOVLOJA         DTULTIMAIMP         DATE                                        Data da ultima impressão            OPERACIONAL                        NaN
PCMOVLOJA          NUMVIASIMP NUMBER(10,0)                                        Numero de vias impressas            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*