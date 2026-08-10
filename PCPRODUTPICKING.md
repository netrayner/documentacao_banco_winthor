# 📊 Tabela: PCPRODUTPICKING

### Estrutura de Colunas e Restrições

         Tabela         Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTPICKING        CODPROD  NUMBER(6,0)                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTPICKING      CODFILIAL  VARCHAR2(2)                     Indica o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTPICKING    CODENDERECO NUMBER(10,0)                                            NaN            OPERACIONAL                        NaN
PCPRODUTPICKING           TIPO  VARCHAR2(1)                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTPICKING     CAPACIDADE  NUMBER(8,2)                                            NaN            OPERACIONAL                        NaN
PCPRODUTPICKING PONTOREPOSICAO  NUMBER(8,2)                                            NaN            OPERACIONAL                        NaN
PCPRODUTPICKING  TIPOESTRUTURA  NUMBER(3,0)                                            NaN            OPERACIONAL                        NaN
PCPRODUTPICKING   TIPOENDERECO  NUMBER(2,0)                                            NaN            OPERACIONAL                        NaN
PCPRODUTPICKING CODENDERECOPTL VARCHAR2(15) Código do endereço de estoque Picking To Light            OPERACIONAL                        NaN
PCPRODUTPICKING     DTMXSALTER         DATE                                            NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*