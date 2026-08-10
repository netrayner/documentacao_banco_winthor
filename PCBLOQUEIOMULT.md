# 📊 Tabela: PCBLOQUEIOMULT

### Estrutura de Colunas e Restrições

        Tabela         Coluna Tipo/Tamanho                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBLOQUEIOMULT CODMOTBLOQUEIO NUMBER(10,0)                                                        Código do registro.            OPERACIONAL                        NaN
PCBLOQUEIOMULT           TIPO  NUMBER(2,0) 1 Filial, 2 Praça, 3 Cliente, 4 Cobrança, 5 Plano de Pagamento, 6 Produto.            OPERACIONAL                        NaN
PCBLOQUEIOMULT        CODIGOA VARCHAR2(10)                        Valor do registro referente ao seu respectivo tipo.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*