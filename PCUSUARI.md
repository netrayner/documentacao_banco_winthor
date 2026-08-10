# 📊 Tabela: PCUSUARI

### Estrutura de Colunas e Restrições

  Tabela                     Coluna  Tipo/Tamanho                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCUSUARI                    CODUSUR   NUMBER(4,0)                                                                                              NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCUSUARI                       NOME  VARCHAR2(40)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                      SENHA  VARCHAR2(10)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                   TIPOVEND   VARCHAR2(2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                    PERCENT   NUMBER(4,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                   PERCENT2   NUMBER(6,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                   ENDERECO  VARCHAR2(40)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                     CIDADE  VARCHAR2(15)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                     ESTADO   VARCHAR2(2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                        CEP   VARCHAR2(9)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  TELEFONE1  VARCHAR2(13)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  TELEFONE2  VARCHAR2(13)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                        CPF  VARCHAR2(20)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                         CI  VARCHAR2(20)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                        FAX  VARCHAR2(13)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                        BIP  VARCHAR2(20)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                      MENS1  VARCHAR2(60)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                      MENS2  VARCHAR2(60)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                      MENS3  VARCHAR2(60)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                      MENS4  VARCHAR2(60)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                   BLOQUEIO   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                   DTINICIO          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  DTTERMINO          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                     MOTIVO  VARCHAR2(40)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                     DTNASC          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                      FIRMA  VARCHAR2(40)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                        CGC  VARCHAR2(20)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                     BAIRRO  VARCHAR2(25)                                                                    Bairro do cadastro de usuário            OPERACIONAL                        NaN
PCUSUARI              CODSUPERVISOR   NUMBER(4,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                    CONJUGE  VARCHAR2(40)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI               DTNASCONJUGE          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  TIPOFIRMA   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                     NUMDEP   NUMBER(2,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                 DTULTVENDA          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI               DTENTREGADOC          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI             CODCOMOCLIENTE   NUMBER(6,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  CCORRENTE   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                      EMAIL VARCHAR2(100)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI              DTINFORMATIZA          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI              NUMSERIEEQUIP  NUMBER(10,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                 PROXNUMPED  NUMBER(14,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  ULTNUMPED  NUMBER(10,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                   NUMBANCO   NUMBER(3,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                 NUMAGENCIA   NUMBER(4,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI               NUMDVAGENCIA   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI               NUMCCORRENTE  NUMBER(12,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI             NUMDVCCORRENTE   VARCHAR2(2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI             DTULTALTERACAO          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                 DTEXCLUSAO          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                 VENDEDORQK   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  CODEQUIPE   NUMBER(4,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                    PERMETA  NUMBER(10,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  CODFILIAL   VARCHAR2(2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                       OBS1  VARCHAR2(80)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                       OBS2  VARCHAR2(80)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI            PROXNUMPEDFORCA  NUMBER(10,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  BLOQCOMIS   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                    OBSBLOQ  VARCHAR2(30)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                 VLCORRENTE  NUMBER(10,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  VLLIMCRED  NUMBER(10,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                NUMCONSELHO  VARCHAR2(20)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                       INSS  NUMBER(12,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                VLVENDAPREV  NUMBER(12,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                 CODDISTRIB   VARCHAR2(4)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI            DTLIMENTREGADOC          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI               MASKPREPOSTO   VARCHAR2(9)                                                                    Descricao coluna MASKPREPOSTO            OPERACIONAL                        NaN
PCUSUARI               EXPORTADADOS   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI             NUMSERIEEQUIP2  VARCHAR2(15)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI           DTULTPAGCONSELHO          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI              INSCMUNICIPAL  VARCHAR2(15)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                     PRACA1  VARCHAR2(80)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                     PRACA2  VARCHAR2(80)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  ENDERECO2  VARCHAR2(40)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                 PERDESCMAX   NUMBER(5,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                     EMAIL2 VARCHAR2(100)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI              BLOQVENDATLMK   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                AREAATUACAO   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI              VLVENDAMINPED  NUMBER(12,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI              PERCMETADEPTO  NUMBER(10,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI               TIPOCOMISSAO   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI              USADEBCREDRCA   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI         PERCACRESCIMOVENDA   NUMBER(5,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI               NUMBANCOPOUP   NUMBER(3,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI           NUMCCORRENTEPOUP  NUMBER(12,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI             NUMAGENCIAPOUP   NUMBER(4,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI         NUMDVCCORRENTEPOUP   VARCHAR2(2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI           NUMDVAGENCIAPOUP   VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI         HORAINICONEXAOPALM   NUMBER(2,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI       MINUTOINICONEXAOPALM   NUMBER(2,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI         HORAFIMCONEXAOPALM   NUMBER(2,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI       MINUTOFIMCONEXAOPALM   NUMBER(2,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI             PROXCODCLIPALM   NUMBER(6,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI             QTITENSPEDPREV  NUMBER(14,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  QTPEDPREV  NUMBER(14,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                TELPROVEDOR  VARCHAR2(15)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                   SENHAPOP  VARCHAR2(10)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                    USURPOP  VARCHAR2(40)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                   SERVSMTP  VARCHAR2(30)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                    SERVPOP  VARCHAR2(30)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                 USURDIALUP  VARCHAR2(40)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                SENHADIALUP  VARCHAR2(12)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                PERCACRESFV   NUMBER(8,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI            ROTAMASTERFOODS  VARCHAR2(20)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  NUMPEDECF  NUMBER(10,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  USURLOGIN  VARCHAR2(40)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                 SENHALOGIN  VARCHAR2(10)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  USURDIRFV  VARCHAR2(50)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI             DIRRECEPCAOFTP  VARCHAR2(50)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                DIRENVIOFTP  VARCHAR2(50)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                    SERVFTP  VARCHAR2(50)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                    USURFTP  VARCHAR2(40)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                   SENHAFTP  VARCHAR2(10)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI               PERMETAMETRO  NUMBER(10,2)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI              PROXNUMPEDWEB  NUMBER(10,0)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                CODOPERACAO   VARCHAR2(3)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                 TIPOPESSOA   VARCHAR2(1)                                         Indica o tipo do RCA: Pessoa Física ou Pessoa Jurídica.             OPERACIONAL                        NaN
PCUSUARI      PERMITEADIANTCOMISSAO   VARCHAR2(1)                Indica se o RCA poderá receber adiantamento de comissão, através da rotina 1266.             OPERACIONAL                        NaN
PCUSUARI       INDICECPFECHCOMISSAO   VARCHAR2(1)                          Indica o valor do índice para este RCA no lançamento de Contas a Pagar             OPERACIONAL                        NaN
PCUSUARI                PERMAXVENDA  NUMBER(18,6)                                                                                               .             OPERACIONAL                        NaN
PCUSUARI       INDICERATEIOCOMISSAO   NUMBER(5,2)                                                                   Indice de rateio de comissão.             OPERACIONAL                        NaN
PCUSUARI            USARRCAOPERADOR   VARCHAR2(1)                                                                  Usar RCA do operador da venda.             OPERACIONAL                        NaN
PCUSUARI                 PERCOMMETA   NUMBER(8,4)                                                       Indica o percentual de comissão por meta.             OPERACIONAL                        NaN
PCUSUARI                  NUMCLIPOS  NUMBER(20,8)                                                     Indice a meta de clientes para positivação.             OPERACIONAL                        NaN
PCUSUARI                 VLMAXTROCA   NUMBER(6,2)                                                                Indica o valor máximo para troca.            OPERACIONAL                        NaN
PCUSUARI               COMISSAOFIXA  NUMBER(10,2)                                                      Indica o valor da comissão fixa para o RCA.            OPERACIONAL                        NaN
PCUSUARI                 CODMONITOR   NUMBER(8,0)                                                             Indica o código do monitor de venda.            OPERACIONAL                        NaN
PCUSUARI          CODPRACAPRINCIPAL   NUMBER(4,0)                                                              Indica o código da praça principal.            OPERACIONAL                        NaN
PCUSUARI          USACOBRANCACARTAO   VARCHAR2(1)                                                                             Usa cobrança cartão.            OPERACIONAL                        NaN
PCUSUARI                EXPORTARECF   VARCHAR2(1)                                                                       Exportar RCA Auto Serviço.            OPERACIONAL                        NaN
PCUSUARI           NUMCCORRENTEALFA  VARCHAR2(12)                                                             Numero conta corrente alfa numérico.            OPERACIONAL                        NaN
PCUSUARI VALIDARACRESCDESCPRECOFIXO   VARCHAR2(1)                                                           Validar acréscimo desconto preço fixo.            OPERACIONAL                        NaN
PCUSUARI                     CPFAUX  VARCHAR2(20)                                              Campo auxiliar para armazenar o cpf sem formatação.            OPERACIONAL                        NaN
PCUSUARI              NUMNOTABLOCO1  VARCHAR2(10)                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  CODCIDADE   NUMBER(6,0)                                                                                 Código da cidade            OPERACIONAL                        NaN
PCUSUARI                  CODBAIRRO   NUMBER(6,0)                                                                                 código do bairro            OPERACIONAL                        NaN
PCUSUARI               CODCONTACSRF  NUMBER(10,0)                                                                              Código da conta SRF            OPERACIONAL                        NaN
PCUSUARI                   PERCINSS   NUMBER(5,2)                                                                              Percentual de Inss.            OPERACIONAL                        NaN
PCUSUARI                   PERCCSRF   NUMBER(5,2)                                                                              Percentual de CRSF.            OPERACIONAL                        NaN
PCUSUARI           PERCPISNFSERVICO   NUMBER(6,2)                                                                               Percentual de PIS.            OPERACIONAL                        NaN
PCUSUARI        PERCCOFINSNFSERVICO   NUMBER(6,2)                                                                            Percentual de COFINS.            OPERACIONAL                        NaN
PCUSUARI                    PERCISS   NUMBER(4,2)                                                                               Percentual de ISS.            OPERACIONAL                        NaN
PCUSUARI                   PERCIRRF   NUMBER(4,2)                                                                              Percentual de IRRF.            OPERACIONAL                        NaN
PCUSUARI               CODCONTAIRRF  NUMBER(10,0)                                                                            Código da conta IRRF.            OPERACIONAL                        NaN
PCUSUARI                CODCONTAISS  NUMBER(10,0)                                                                             Código da conta ISS.            OPERACIONAL                        NaN
PCUSUARI               CODCONTAINSS  NUMBER(10,0)                                                                            Código da conta INSS.            OPERACIONAL                        NaN
PCUSUARI                CODCONTAPIS  NUMBER(10,0)                                                                             Código da conta PIS.            OPERACIONAL                        NaN
PCUSUARI             CODCONTACOFINS  NUMBER(10,0)                                                                          Código da conta COFINS.            OPERACIONAL                        NaN
PCUSUARI    EXPORTARPARAFORCAVENDAS   VARCHAR2(1)                                                                    Exportar para força de vendas            OPERACIONAL                        NaN
PCUSUARI        DIRETORIOASSINATURA VARCHAR2(200)                                                      Diretório da Assinatura digitalizada do RCA            OPERACIONAL                        NaN
PCUSUARI                 MODELOPALM  VARCHAR2(30)                                                        Armazena o Modelo do Palm em poder do RCA            OPERACIONAL                        NaN
PCUSUARI            OBSFORCAVENDAS1  VARCHAR2(80)                                                    Observações referente ao Palm em poder do RCA            OPERACIONAL                        NaN
PCUSUARI            OBSFORCAVENDAS2  VARCHAR2(80)                                                    Observações referente ao Palm em poder do RCA            OPERACIONAL                        NaN
PCUSUARI            OBSFORCAVENDAS3  VARCHAR2(80)                                                    Observações referente ao Palm em poder do RCA            OPERACIONAL                        NaN
PCUSUARI            OBSFORCAVENDAS4  VARCHAR2(80)                                                    Observações referente ao Palm em poder do RCA            OPERACIONAL                        NaN
PCUSUARI          CODIGOCENTROCUSTO  VARCHAR2(40)                                                                        Código do centro de custo            OPERACIONAL                        NaN
PCUSUARI     VISUALIZARPRODDEPTOSEC   VARCHAR2(1)                                                        Visualizar produtos do departamento/secão            OPERACIONAL                        NaN
PCUSUARI                  CODCONTAB  VARCHAR2(12)                                                                                   Conta Contábil            OPERACIONAL                        NaN
PCUSUARI            SIMPLESNACIONAL   VARCHAR2(1)                                                 Optante pelo regime de impostos simples nacional            OPERACIONAL                        NaN
PCUSUARI    COMISSAOSERVICOPRESTADO  NUMBER(12,2)                                                                   Comissão RCA serviço prestado.            OPERACIONAL                        NaN
PCUSUARI              FATORCOMISLIQ  NUMBER(18,6)                              Fator para acréscimo do valor da comissão por liquidez da rot.1266.            OPERACIONAL                        NaN
PCUSUARI             NUMDEPENDENTES   NUMBER(3,0)                                                                           Número de dependentes.            OPERACIONAL                        NaN
PCUSUARI    EXPORTARCOMISSAOFOLHARM   VARCHAR2(1)                                                              Exporta comissão do RCA para folha.            OPERACIONAL                        NaN
PCUSUARI                    CODROTA   NUMBER(4,0)                                                                           Código da rota do RCA.            OPERACIONAL                        NaN
PCUSUARI                   LATITUDE  VARCHAR2(20)                                                                                     Latitude RCA            OPERACIONAL                        NaN
PCUSUARI                  LONGITUDE  VARCHAR2(20)                                                                                    Longitude RCA            OPERACIONAL                        NaN
PCUSUARI             NUMSELOINICIAL  VARCHAR2(20)                                                                              Nro do selo inicial            OPERACIONAL                        NaN
PCUSUARI               NUMSELOFINAL  VARCHAR2(20)                                                                                Nro do selo final            OPERACIONAL                        NaN
PCUSUARI             NUMFORMINICIAL  NUMBER(10,0)                                                                  Nro do formulário da nf inicial            OPERACIONAL                        NaN
PCUSUARI               NUMFORMFINAL  NUMBER(10,0)                                                                    Nro do formulário da nf final            OPERACIONAL                        NaN
PCUSUARI           UTILIZASELOSEFAZ   VARCHAR2(1)                                                             Utiliza controle de formulário sefaz            OPERACIONAL                        NaN
PCUSUARI                    SERIENF   VARCHAR2(3)                                                                             Série da Nota Fiscal            OPERACIONAL                        NaN
PCUSUARI   USACONTROLEFORMSELOSEFAZ   VARCHAR2(1)                                                                          Utiliza o selo da sefaz            OPERACIONAL                        NaN
PCUSUARI                PROXNUMFORM  NUMBER(10,0)                                                                     Próximo número do formulário            OPERACIONAL                        NaN
PCUSUARI                PROXNUMSELO  NUMBER(10,0)                                                                           Próximo número do selo            OPERACIONAL                        NaN
PCUSUARI                CODCONTASRF  NUMBER(10,0)                                                                             Código da conta SRF.            OPERACIONAL                        NaN
PCUSUARI                    NUMAIDF  VARCHAR2(30)                                                                                      Número AIDF            OPERACIONAL                        NaN
PCUSUARI               CPFTITULARCC  VARCHAR2(20)                                                            CPF/CNPJ do titular da conta corrente            OPERACIONAL                        NaN
PCUSUARI               CPFTITULARCP  VARCHAR2(20)                                                            CPF/CNPJ do titular da conta poupança            OPERACIONAL                        NaN
PCUSUARI      CONTRIBINDIVIDUALINSS   VARCHAR2(1)                                     Flag para dizer se o RCA eh contruibuinte individual do INSS            OPERACIONAL                        NaN
PCUSUARI                        NIT  VARCHAR2(20)                                                               Número de Inscrição do Trabalhador            OPERACIONAL                        NaN
PCUSUARI               PARTCLUBEITT   VARCHAR2(1)                    Campo que informa se o RCA participa ou não do Clube ITT Colgate (Integração)            OPERACIONAL                        NaN
PCUSUARI           DTFIMVIGCLUBEITT          DATE              Campo que informa a data final da vigência do RCA no Clube ITT Colgate (Integração)            OPERACIONAL                        NaN
PCUSUARI                   CHAPA_RM  VARCHAR2(16)                                                                     Chapa de identificação da RM            OPERACIONAL                        NaN
PCUSUARI                CALCULARDSR   VARCHAR2(1)                               Calcular Descanso Semanal Remunerado nas rotinas 1248, 1249 e 1266            OPERACIONAL                        NaN
PCUSUARI         TIPOCONTAPAGAMENTO   NUMBER(1,0)   Identifica qual conta será utilziada para pgamento "1 - Conta Corrente" e "2 - Conta Poupança"            OPERACIONAL                        NaN
PCUSUARI PERMITEPRODSEMDISTRIBUICAO   VARCHAR2(1) Definine se será permitida a venda de produtos que não possuam distribuição vinculada para o RCA            OPERACIONAL                        NaN
PCUSUARI                 DTMXSALTER          DATE                                                                                              NaN            OPERACIONAL                        NaN
PCUSUARI                  CODUSURPG   VARCHAR2(6)                                                                                       Código P&G            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*