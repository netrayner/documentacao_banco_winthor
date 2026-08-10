# 📊 Tabela: PCPESSOA

### Estrutura de Colunas e Restrições

  Tabela          Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPESSOA       CODPESSOA   NUMBER(8,0)       Chave primária da tabela pccpessoa.    CHAVE PRIMÁRIA (PK)                        NaN
PCPESSOA      CODCLIENTE   NUMBER(8,0)      Chave secundária da tabela pcclient. CHAVE ESTRANGEIRA (FK)                   PCCLIENT
PCPESSOA   CODFORNECEDOR   NUMBER(8,0)      Chave secundária da tabela pcfornec. CHAVE ESTRANGEIRA (FK)                   PCFORNEC
PCPESSOA  CODFUNCIONARIO   NUMBER(8,0)        Chave secundária da tabela pcempr. CHAVE ESTRANGEIRA (FK)                     PCEMPR
PCPESSOA        ECLIENTE   VARCHAR2(1)                             Se é cliente.            OPERACIONAL                        NaN
PCPESSOA     EFORNECEDOR   VARCHAR2(1)                          Se é fornecedor.            OPERACIONAL                        NaN
PCPESSOA ETRANSPORTADORA   VARCHAR2(1)                      Se é Transportadora.            OPERACIONAL                        NaN
PCPESSOA    EFUNCIONARIO   VARCHAR2(1)                         Se é Funcionairo.            OPERACIONAL                        NaN
PCPESSOA  CODFUNCADASTRO   NUMBER(6,0)         Código funcionario que cadastrou.            OPERACIONAL                        NaN
PCPESSOA      DTCADASTRO          DATE                         Data de cadastro.            OPERACIONAL                        NaN
PCPESSOA  CODFUNEXCLUSAO   NUMBER(8,0)           Código funcionario que excluiu.            OPERACIONAL                        NaN
PCPESSOA      DTEXCLUSAO          DATE                         Data de exclusão.            OPERACIONAL                        NaN
PCPESSOA       CODROTINA   NUMBER(6,0)                         Código da rotina.            OPERACIONAL                        NaN
PCPESSOA         CNPJCPF  VARCHAR2(18)                              Cnpj ou Cpf.            OPERACIONAL                        NaN
PCPESSOA            NOME  VARCHAR2(40)                              Nome pessoa.            OPERACIONAL                        NaN
PCPESSOA        FANTASIA  VARCHAR2(40)                            Nome Fantasia.            OPERACIONAL                        NaN
PCPESSOA      OBSERVACAO VARCHAR2(200)                               Observação.            OPERACIONAL                        NaN
PCPESSOA        ESERVICO   VARCHAR2(1) Se o fornecedor for prestador de serviço.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*