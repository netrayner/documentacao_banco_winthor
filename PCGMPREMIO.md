# 📊 Tabela: PCGMPREMIO

### Estrutura de Colunas e Restrições

    Tabela       Coluna Tipo/Tamanho                                                                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMPREMIO       CODIGO NUMBER(10,0)                                                                                                                            Código do prêmio    CHAVE PRIMÁRIA (PK)                        NaN
PCGMPREMIO CODPARAMMETA NUMBER(10,0)                                                                                                          Código da parametrização do prêmio CHAVE ESTRANGEIRA (FK)              PCGMPARAMMETA
PCGMPREMIO GRATIFICACAO  VARCHAR2(1)  Tipo de gratificação: ''V'' VALOR,''P'' PONTO,''G'' %FATURAMENTO GERAL,''F'' %FATURAMENTO CRITÉRIO, ''I'' INADIMPLÊNCIA ,''R'' RECEBIMENTO            OPERACIONAL                        NaN
PCGMPREMIO DATAEXCLUSAO         DATE                                                                                                                  Data da exclusão do prêmio            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*