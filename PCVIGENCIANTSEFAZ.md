# 📊 Tabela: PCVIGENCIANTSEFAZ

### Estrutura de Colunas e Restrições

           Tabela              Coluna  Tipo/Tamanho                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVIGENCIANTSEFAZ         CODVIGENCIA  NUMBER(10,0)                                                       PK da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCVIGENCIANTSEFAZ    IDENTIFICADOR_NT VARCHAR2(100)          Identificador da Nota Técnica, usado para busca na tabela            OPERACIONAL                        NaN
PCVIGENCIANTSEFAZ       TIPODOCUMENTO  VARCHAR2(20)     Identificador do tipo do documento da NT (NFE/ CTE/ MDFE/ CCE)            OPERACIONAL                        NaN
PCVIGENCIANTSEFAZ DATAINICIALVIGENCIA          DATE                                     Data inicial da vigência da NT            OPERACIONAL                        NaN
PCVIGENCIANTSEFAZ   DATAFINALVIGENCIA          DATE                                       Data final da vigência da NT            OPERACIONAL                        NaN
PCVIGENCIANTSEFAZ           DESCRICAO VARCHAR2(500)       Campo de descrição livre, para detalhar melhor a NotaTécnica            OPERACIONAL                        NaN
PCVIGENCIANTSEFAZ                  UF   VARCHAR2(2)                                          Unidade Federada da União            OPERACIONAL                        NaN
PCVIGENCIANTSEFAZ            AMBIENTE   VARCHAR2(1) Ambiente de emissão da NFe (A: Ambos, P: Produção, H: Homologação)            OPERACIONAL                        NaN
PCVIGENCIANTSEFAZ     DATAATUALIZACAO          DATE                                    Data de atualização do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*