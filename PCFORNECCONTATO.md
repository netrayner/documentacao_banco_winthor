# 📊 Tabela: PCFORNECCONTATO

### Estrutura de Colunas e Restrições

         Tabela           Coluna   Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORNECCONTATO CODFORNECCONTATO    NUMBER(6,0)     Codigo contato.    CHAVE PRIMÁRIA (PK)                        NaN
PCFORNECCONTATO        CODFORNEC    NUMBER(6,0)  Codigo fornecedor. CHAVE ESTRANGEIRA (FK)                   PCFORNEC
PCFORNECCONTATO             NOME   VARCHAR2(40)               Nome.            OPERACIONAL                        NaN
PCFORNECCONTATO         ENDERECO   VARCHAR2(23)           Endereço.            OPERACIONAL                        NaN
PCFORNECCONTATO           BAIRRO   VARCHAR2(13)             Bairro.            OPERACIONAL                        NaN
PCFORNECCONTATO        CODCIDADE    NUMBER(6,0)             Cidade. CHAVE ESTRANGEIRA (FK)                   PCCIDADE
PCFORNECCONTATO              CEP    NUMBER(8,0)                Cep.            OPERACIONAL                        NaN
PCFORNECCONTATO    DTANIVERSARIO           DATE   Data aniversario.            OPERACIONAL                        NaN
PCFORNECCONTATO            EMAIL  VARCHAR2(100)              Email.            OPERACIONAL                        NaN
PCFORNECCONTATO         NEXTELID   VARCHAR2(18)    Telefone nextel.            OPERACIONAL                        NaN
PCFORNECCONTATO              FAX   VARCHAR2(20)                Fax.            OPERACIONAL                        NaN
PCFORNECCONTATO          CELULAR   VARCHAR2(20)            Celular.            OPERACIONAL                        NaN
PCFORNECCONTATO         TELEFONE   VARCHAR2(20)           Telefone.            OPERACIONAL                        NaN
PCFORNECCONTATO      CARGOFUNCAO   VARCHAR2(40)       Cargo função.            OPERACIONAL                        NaN
PCFORNECCONTATO       OBSERVACAO VARCHAR2(2000)         Observação.            OPERACIONAL                        NaN
PCFORNECCONTATO      DTALTERACAO           DATE     Data alteração.            OPERACIONAL                        NaN
PCFORNECCONTATO       DTCADASTRO           DATE      Data cadastro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*