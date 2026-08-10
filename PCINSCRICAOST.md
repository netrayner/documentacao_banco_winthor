# 📊 Tabela: PCINSCRICAOST

### Estrutura de Colunas e Restrições

       Tabela           Coluna Tipo/Tamanho                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINSCRICAOST               UF  VARCHAR2(2)                          UF a qual pertence a IE da Filial. Rotina 533. IE Subst. Tribut.     CHAVE PRIMÁRIA (PK)                        NaN
PCINSCRICAOST        CODFILIAL  VARCHAR2(2)                      Filial a qual pertence a IE da Filial. Rotina 533. IE Subst. Tribut.     CHAVE PRIMÁRIA (PK)                        NaN
PCINSCRICAOST    IESUBSTTRIBUT VARCHAR2(20)                          IE como Substituto na UF e Filial. Rotina 533. IE Subst. Tribut.             OPERACIONAL                        NaN
PCINSCRICAOST VINCULOPORENDENT  VARCHAR2(1) Determinar se o vínculo da IE de Substituto deve ser feito por endereço de entrega ou não.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*