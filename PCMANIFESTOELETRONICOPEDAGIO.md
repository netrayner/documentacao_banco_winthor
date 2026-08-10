# 📊 Tabela: PCMANIFESTOELETRONICOPEDAGIO

### Estrutura de Colunas e Restrições

                      Tabela             Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMANIFESTOELETRONICOPEDAGIO  CNPJFORNECPEDAGIO VARCHAR2(18)                                 CNPJ Forn. Pedágio            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPEDAGIO CNPJRESPPAGPEDAGIO VARCHAR2(18)                CNPJ/CFP Resp. pagamento do pedágio            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPEDAGIO          NUMCOMPRA VARCHAR2(20)                                   Número de Compra            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPEDAGIO          VLPEDAGIO NUMBER(15,2)                                   Valor do Pedágio            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPEDAGIO       NUMTRANSACAO NUMBER(10,0)                                  Transação do MDFe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPEDAGIO    TIPOVALEPEDAGIO  VARCHAR2(2) Tipo do Vale Pedágio (01=TAG, 02=Cupom, 03=Cartão)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*