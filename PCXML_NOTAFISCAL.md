# 📊 Tabela: PCXML_NOTAFISCAL

### Estrutura de Colunas e Restrições

          Tabela          Coluna  Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCXML_NOTAFISCAL       CODFILIAL   VARCHAR2(2)                           Código da filial            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       CODFORNEC   NUMBER(9,0)                       Código do fornecedor            OPERACIONAL                        NaN
PCXML_NOTAFISCAL          CODCLI   NUMBER(9,0)                          Código do cliente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL    IDE_CHAVENFE  VARCHAR2(44)                  Chave da Nfe conforme xml            OPERACIONAL                        NaN
PCXML_NOTAFISCAL         IDE_CUF   VARCHAR2(2)                            Uf conforme xml            OPERACIONAL                        NaN
PCXML_NOTAFISCAL         IDE_CNF   NUMBER(9,0)         Número da nota fiscal conforme xml            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       IDE_NATOP  VARCHAR2(50)          Natureza da operação conforme xml            OPERACIONAL                        NaN
PCXML_NOTAFISCAL         IDE_MOD   VARCHAR2(2)         Modelo da nota fiscal conforme xml            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       IDE_SERIE   VARCHAR2(3)          Série da nota fiscal conforme xml            OPERACIONAL                        NaN
PCXML_NOTAFISCAL         IDE_NNF   NUMBER(9,0)    Número de controle da nota conforme xml            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       IDE_DHEMI          DATE         Data e hora de missão conforme xml            OPERACIONAL                        NaN
PCXML_NOTAFISCAL    IDE_DHSAIENT          DATE          Data e hora de saida conforme xml            OPERACIONAL                        NaN
PCXML_NOTAFISCAL        IDE_TPNF   VARCHAR2(1)                        Tipo de nota fiscal            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      IDE_IDDEST   VARCHAR2(1) Identificador do destinatário conforme xml            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      IDE_CMUNFG   VARCHAR2(8)                        Código de município            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       IDE_TPIMP   VARCHAR2(1)                            Tipo importacao            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      IDE_TPEMIS   VARCHAR2(1)                               Tipo emissao            OPERACIONAL                        NaN
PCXML_NOTAFISCAL         IDE_CDV   VARCHAR2(1)                  Código digito verificador            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       IDE_TPAMB   VARCHAR2(1)                              Tipo ambiente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      IDE_FINNFE   VARCHAR2(2)                             Finalidade nfe            OPERACIONAL                        NaN
PCXML_NOTAFISCAL    IDE_INDFINAL   VARCHAR2(2)                        Identificador final            OPERACIONAL                        NaN
PCXML_NOTAFISCAL     IDE_INDPRES   VARCHAR2(2)                      Indicador de presença            OPERACIONAL                        NaN
PCXML_NOTAFISCAL     IDE_PROCEMI   VARCHAR2(2)                        Processo de emissao            OPERACIONAL                        NaN
PCXML_NOTAFISCAL     IDE_VERPROC  VARCHAR2(20)                          Versão processada            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       EMIT_CNPJ  VARCHAR2(15)                           Cnpj do emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      EMIT_XNOME VARCHAR2(150)                           Nome do Emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       EMIT_XLGR VARCHAR2(100)                       Endereço do emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL        EMIT_NRO VARCHAR2(120)                   Número endereco emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL    EMIT_XBAIRRO VARCHAR2(120)                            Bairro emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       EMIT_CMUN  VARCHAR2(15)                  Código municipio emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       EMIT_XMUN  VARCHAR2(50)               Descrição município emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL         EMIT_UF   VARCHAR2(2)                             If do emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL        EMIT_CEP  VARCHAR2(15)                            CEP do emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      EMIT_CPAIS   NUMBER(4,0)                       Código pais emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      EMIT_XPAIS  VARCHAR2(25)                    Descrição país emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       EMIT_FONE  VARCHAR2(15)                     Telefone pais emitente            OPERACIONAL                        NaN
PCXML_NOTAFISCAL         EMIT_IE  VARCHAR2(15)                         Inscrição estadual            OPERACIONAL                        NaN
PCXML_NOTAFISCAL        EMIT_CRT  VARCHAR2(15)                   Código regime tributário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       DEST_CNPJ  VARCHAR2(15)                          CNPJ destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      DEST_XNOME VARCHAR2(150)                          Nome destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       DEST_XLGR  VARCHAR2(50)                      Endereço destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL        DEST_NRO   VARCHAR2(8)                        Número destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       DEST_XCPL  VARCHAR2(40)          Complemento endereço destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL    DEST_XBAIRRO  VARCHAR2(30)                        Bairro destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       DEST_CMUN  VARCHAR2(15)              Código município destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       DEST_XMUN  VARCHAR2(25)           Descrição município destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL         DEST_UF   VARCHAR2(2)                            UF destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL        DEST_CEP  VARCHAR2(15)                           CEP destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      DEST_CPAIS  VARCHAR2(15)                   Código país destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      DEST_XPAIS  VARCHAR2(20)                Descrição país destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL       DEST_FONE  VARCHAR2(15)                      Telefone destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL  DEST_INDIEDEST   VARCHAR2(1)  Indicador inscrição estadual destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL         DEST_IE  VARCHAR2(15)            Inscrição estadual destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      DEST_EMAIL  VARCHAR2(50)                         Email destinatário            OPERACIONAL                        NaN
PCXML_NOTAFISCAL    ENTREGA_CNPJ  VARCHAR2(15)                               Cnpj Entrega            OPERACIONAL                        NaN
PCXML_NOTAFISCAL    ENTREGA_XLGR  VARCHAR2(50)                           Endereço entrega            OPERACIONAL                        NaN
PCXML_NOTAFISCAL     ENTREGA_NRO  VARCHAR2(10)                             Número entrega            OPERACIONAL                        NaN
PCXML_NOTAFISCAL    ENTREGA_XCPL  VARCHAR2(40)               Complemento endereço entrega            OPERACIONAL                        NaN
PCXML_NOTAFISCAL ENTREGA_XBAIRRO  VARCHAR2(25)                             Bairro entrega            OPERACIONAL                        NaN
PCXML_NOTAFISCAL    ENTREGA_CMUN  VARCHAR2(15)                   Código município entrega            OPERACIONAL                        NaN
PCXML_NOTAFISCAL    ENTREGA_XMUN  VARCHAR2(40)                Descrição município entrega            OPERACIONAL                        NaN
PCXML_NOTAFISCAL      ENTREGA_UF   VARCHAR2(2)                                 UF entrega            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*