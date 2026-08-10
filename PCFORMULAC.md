# 📊 Tabela: PCFORMULAC

### Estrutura de Colunas e Restrições

    Tabela     Coluna   Tipo/Tamanho                                                                                                                                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORMULAC CODFORMULA   NUMBER(10,0) Campo gerado de forma automática (sequence) para identificar a fórmula criada. Criado através da rotina de gerenciamento de fórmulas 5xx. |Campo do tipo numérico, de tamanho 10, sem casas decimais.    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULAC  DESCRICAO   VARCHAR2(60)                                                                                                                  Campo para armazenar a descrição da fórmula. |Campo do tipo caracter, de tamanho 60.            OPERACIONAL                        NaN
PCFORMULAC     FILTRO           CLOB                                                             Condições que deverão ser verificadas para aplicação da fórmula. Estas condições serão cláusulas WHERE de um SELECT. |Campo do tipo clob.            OPERACIONAL                        NaN
PCFORMULAC    FORMULA VARCHAR2(1000)                                                                                                                                    Fórmula a ser utilizada. |Campo do tipo caracter, de tamanho 1000.            OPERACIONAL                        NaN
PCFORMULAC     PADRAO    VARCHAR2(1)                                                        Indica se esta fórmula é padrão do WinThor, e caso seja, não será permitida nenhuma alteração na mesma. |Campo do tipo caracter, de tamanho 1.            OPERACIONAL                        NaN
PCFORMULAC       HASH   VARCHAR2(32)                          Assinatura digital do registro, para evitar a utilização de fórmulas que não tenham sido criadas através da rotina de gerenciamento. |Campo do tipo caracter, de tamanho 32.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*