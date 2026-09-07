# 📊 Tabela: PCDESTSITTRIBUT

### Estrutura de Colunas e Restrições

         Tabela     Coluna Tipo/Tamanho                                                                                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESTSITTRIBUT  SITTRIBUT  VARCHAR2(3)                                                                                                  Campo que especifica a situação tributária. |Campo do tipo caracter, de tamanho 3.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESTSITTRIBUT  VLISENTAS  VARCHAR2(1) Quando tiver o valor "S", identifica onde deve ser gerado a diferença de redução de  base de  calculo ou outro valor de situação tributária. |Campo do tipo caracter, de tamanho 1.            OPERACIONAL                        NaN
PCDESTSITTRIBUT   VLOUTRAS  VARCHAR2(1) Quando tiver o valor "S", identifica onde deve ser gerado a diferença de redução de  base de  calculo ou outro valor de situação tributária. |Campo do tipo caracter, de tamanho 1.            OPERACIONAL                        NaN
PCDESTSITTRIBUT VLBASEICMS  VARCHAR2(1)                                                                               O valor da base de cálculo do ICMS redizida será destacado na coluna Outras ou Isento do Livro Fiscal            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*