# 📊 Tabela: PCPRODUTOCERTIFIC

### Estrutura de Colunas e Restrições

           Tabela          Coluna  Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTOCERTIFIC CODPRODCERTIFIC  NUMBER(12,0) Indentificador do registro            OPERACIONAL                        NaN
PCPRODUTOCERTIFIC       CODFILIAL   VARCHAR2(2)           Código da filial            OPERACIONAL                        NaN
PCPRODUTOCERTIFIC         CODPROD   NUMBER(6,0)          Código do produto            OPERACIONAL                        NaN
PCPRODUTOCERTIFIC         NUMLOTE  VARCHAR2(15)             Número do lote            OPERACIONAL                        NaN
PCPRODUTOCERTIFIC         ARQUIVO VARCHAR2(400)     Caminho do certificado            OPERACIONAL                        NaN
PCPRODUTOCERTIFIC     DTALTERACAO          DATE          Data de alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*