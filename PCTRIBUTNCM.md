# 📊 Tabela: PCTRIBUTNCM

### Estrutura de Colunas e Restrições

     Tabela          Coluna  Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBUTNCM             NCM  VARCHAR2(15)                   Nomeclatura comum Mercosul    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBUTNCM       DESCRICAO  VARCHAR2(60)                                    Descrição            OPERACIONAL                        NaN
PCTRIBUTNCM    PERCIPIVENDA NUMBER(22,10) % de IPI (imposto produtos industrializados)            OPERACIONAL                        NaN
PCTRIBUTNCM      PASSELIVRE   VARCHAR2(1)                                  Passe Livre            OPERACIONAL                        NaN
PCTRIBUTNCM  CODPASSEFISCAL  NUMBER(22,8)                          Código passe fiscal            OPERACIONAL                        NaN
PCTRIBUTNCM VLPAUTAIPIVENDA NUMBER(22,18)                  Valor Pauta de IPI na venda            OPERACIONAL                        NaN
PCTRIBUTNCM VLIPIPORKGVENDA NUMBER(22,18)                        Valor de IPI por Kilo            OPERACIONAL                        NaN
PCTRIBUTNCM      CODPRODDNF  NUMBER(22,3)                         Código produto (DNF)            OPERACIONAL                        NaN
PCTRIBUTNCM       CAPVOLDNF  NUMBER(22,5)                      capacidade Volume (DNF)            OPERACIONAL                        NaN
PCTRIBUTNCM    FATORCONVDNF NUMBER(22,18)                     Fator de conversão (DNF)            OPERACIONAL                        NaN
PCTRIBUTNCM           CODST   NUMBER(4,0)               Código da situação tributária.            OPERACIONAL                        NaN
PCTRIBUTNCM          CODICM   NUMBER(8,4)                                    %ICMSCMV.            OPERACIONAL                        NaN
PCTRIBUTNCM       CODICMTAB   NUMBER(8,4)                            %ICMS Antecipado.            OPERACIONAL                        NaN
PCTRIBUTNCM     PERCBASERED   NUMBER(8,4)                           % base de redução.            OPERACIONAL                        NaN
PCTRIBUTNCM    PERDESCCUSTO   NUMBER(8,4)                            % Desconto Custo.            OPERACIONAL                        NaN
PCTRIBUTNCM          IVATAB   NUMBER(8,4)                                       % IVA.            OPERACIONAL                        NaN
PCTRIBUTNCM    ALIQICMS1TAB   NUMBER(8,4)                             % Aliq. Interna.            OPERACIONAL                        NaN
PCTRIBUTNCM    ALIQICMS2TAB   NUMBER(8,4)                             % Aliq. Externa.            OPERACIONAL                        NaN
PCTRIBUTNCM       SITTRIBUT   VARCHAR2(2)                         Situação Tributária.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*