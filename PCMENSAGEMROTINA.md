# 📊 Tabela: PCMENSAGEMROTINA

### Estrutura de Colunas e Restrições

          Tabela            Coluna   Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMENSAGEMROTINA            CODIGO    NUMBER(6,0)    Indica o código mensagem.    CHAVE PRIMÁRIA (PK)                        NaN
PCMENSAGEMROTINA            TITULO   VARCHAR2(60)    Indica o titulo mensagem.            OPERACIONAL                        NaN
PCMENSAGEMROTINA    DESCRICAOCURTA  VARCHAR2(100) Indica a descrição mensagem.            OPERACIONAL                        NaN
PCMENSAGEMROTINA DESCRICAOCOMPLETA  VARCHAR2(200)  Indica o conteúdo mensagem.            OPERACIONAL                        NaN
PCMENSAGEMROTINA         CODROTINA    NUMBER(6,0)      Indica o código rotina.    CHAVE PRIMÁRIA (PK)                        NaN
PCMENSAGEMROTINA       ORIENTACOES VARCHAR2(4000)                          NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*