# 📊 Tabela: PCINSERVIVEL

### Estrutura de Colunas e Restrições

      Tabela         Coluna Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINSERVIVEL  CODINSERVIVEL  NUMBER(6,0)              Código sequencial identificador de grupo inservível    CHAVE PRIMÁRIA (PK)                        NaN
PCINSERVIVEL      AMPERAGEM  NUMBER(6,0)                             Representa a amperagem do inservível            OPERACIONAL                        NaN
PCINSERVIVEL           PESO NUMBER(12,6)                              Peso em KG da carcaça do inservível            OPERACIONAL                        NaN
PCINSERVIVEL        VLVENDA NUMBER(18,6)                                     Valor na venda do inservível            OPERACIONAL                        NaN
PCINSERVIVEL       VLCOMPRA NUMBER(18,6)                                    Valor na compra do inservível            OPERACIONAL                        NaN
PCINSERVIVEL     DTEXCLUSAO         DATE                                        Data para exclusão lógica            OPERACIONAL                        NaN
PCINSERVIVEL CODPRODCARCACA  NUMBER(6,0) Código do produto vinculado à Carcaça, cadastrado na rotina 203.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*