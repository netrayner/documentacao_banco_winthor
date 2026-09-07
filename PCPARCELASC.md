# 📊 Tabela: PCPARCELASC

### Estrutura de Colunas e Restrições

     Tabela        Coluna Tipo/Tamanho                                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARCELASC    CODPARCELA  NUMBER(6,0)                                                                                   Código sequêncial.     CHAVE PRIMÁRIA (PK)                        NaN
PCPARCELASC     DESCRICAO VARCHAR2(60)                                          Descrição sobre o nome da parcela ou condição de pagamento.             OPERACIONAL                        NaN
PCPARCELASC   TIPOPARCELA  VARCHAR2(2)                                                 Prazo determinado) / AV (A vista) / PF (Prazo Fixo).             OPERACIONAL                        NaN
PCPARCELASC QTDMAXPARCELA  NUMBER(3,0) Número de parcelas que virá ser defino pelo cadastro da PCConsum, podendo ser apenas menor que está.             OPERACIONAL                        NaN
PCPARCELASC    DIFPARCELA  VARCHAR2(1)                      Diferença da parcela será considera na: P-Primeira parcela ou U-Ultima parcela.             OPERACIONAL                        NaN
PCPARCELASC       DIABASE  NUMBER(2,0)                                                                   De 1 a 30 dias quando for tipo PF.             OPERACIONAL                        NaN
PCPARCELASC    DTCADASTRO         DATE                                                                  Data atual do cadastro do registro.             OPERACIONAL                        NaN
PCPARCELASC    DTEXCLUSAO         DATE Quando tentar excluir, e já existir dados, gravar a data de exclusão para desabilitar esta condição.             OPERACIONAL                        NaN
PCPARCELASC    CODFUNCCAD NUMBER(10,0)                                                                Funcionário que cadastrou o registro.             OPERACIONAL                        NaN
PCPARCELASC    CODFUNCALT NUMBER(10,0)                                                                  Funcionário que alterou o registro.             OPERACIONAL                        NaN
PCPARCELASC     CODROTINA NUMBER(10,0)                                                                 Rotina que alterou/criou o registro.             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*