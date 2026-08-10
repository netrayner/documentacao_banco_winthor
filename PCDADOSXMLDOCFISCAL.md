# 📊 Tabela: PCDADOSXMLDOCFISCAL

### Estrutura de Colunas e Restrições

             Tabela     Coluna  Tipo/Tamanho                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDADOSXMLDOCFISCAL   CHAVENFE  VARCHAR2(45)                                                       Chave de acesso da nota fiscal.            OPERACIONAL                        NaN
PCDADOSXMLDOCFISCAL     TAGXML VARCHAR2(200)                                                                Caminho da tag do xml.            OPERACIONAL                        NaN
PCDADOSXMLDOCFISCAL      VALOR VARCHAR2(800)                                                                  Valor da tag do xml.            OPERACIONAL                        NaN
PCDADOSXMLDOCFISCAL  ESTRUTURA VARCHAR2(200)                      Coluna de agrupamento por tag pai (emitente, destinatario, etc).            OPERACIONAL                        NaN
PCDADOSXMLDOCFISCAL CAMPOIDENT  VARCHAR2(40) Campo de identificação do conjunto agrupado (numero da nota, código do produto, etc).            OPERACIONAL                        NaN
PCDADOSXMLDOCFISCAL VALORIDENT VARCHAR2(200)                                                      Valor do campo de identificação.            OPERACIONAL                        NaN
PCDADOSXMLDOCFISCAL DTCADASTRO          DATE                                                                     Data de cadastro.            OPERACIONAL                        NaN
PCDADOSXMLDOCFISCAL     NUMSEQ  NUMBER(20,0)                                                         Sequência do produto na nota.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*