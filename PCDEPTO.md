# 📊 Tabela: PCDEPTO

### Estrutura de Colunas e Restrições

 Tabela              Coluna  Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEPTO             CODEPTO   NUMBER(6,0)                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPTO           DESCRICAO  VARCHAR2(25)                                                NaN            OPERACIONAL                        NaN
PCDEPTO   PERCPARTVENDAPREV   NUMBER(8,4)                                                NaN            OPERACIONAL                        NaN
PCDEPTO      PERCMARGEMPREV   NUMBER(8,4)                                                NaN            OPERACIONAL                        NaN
PCDEPTO            TIPOMERC   VARCHAR2(2)                                                NaN            OPERACIONAL                        NaN
PCDEPTO         EMITEQTUNIT   VARCHAR2(1)                                                NaN            OPERACIONAL                        NaN
PCDEPTO    ATUALIZAINVGERAL   VARCHAR2(1)                                                NaN            OPERACIONAL                        NaN
PCDEPTO      MARGEMPREVISTA   NUMBER(6,2)       % de margem prevista padrão de lucratividade            OPERACIONAL                        NaN
PCDEPTO          REFERENCIA  VARCHAR2(20)                                         Referência            OPERACIONAL                        NaN
PCDEPTO     PERDESCMAXIDEAL  NUMBER(10,2)                            % Desconto máximo ideal            OPERACIONAL                        NaN
PCDEPTO  PERDESCMAXPOSSIVEL  NUMBER(10,2)                         % Desconto máximo possível            OPERACIONAL                        NaN
PCDEPTO    PERDESCMAXAVISTA  NUMBER(10,2)                    % Desconto máximo venda a vista            OPERACIONAL                        NaN
PCDEPTO    PERCCOMGARANTIDA  NUMBER(10,2)                        % Comissão mínima garantida            OPERACIONAL                        NaN
PCDEPTO IDINTEGRACAOCIASHOP VARCHAR2(250)   Referência do departamento no E-commerce CiaShop            OPERACIONAL                        NaN
PCDEPTO      ENVIAECOMMERCE   VARCHAR2(1) Identifica se o produto será enviado ao e-commerce            OPERACIONAL                        NaN
PCDEPTO          DTULTALTER          DATE                           Data da ultima alteração            OPERACIONAL                        NaN
PCDEPTO      CODCAMPLOMADEE VARCHAR2(200)                                 Código da Campanha            OPERACIONAL                        NaN
PCDEPTO          CODADWORDS VARCHAR2(200)                              Código de Remarketing            OPERACIONAL                        NaN
PCDEPTO               ATIVO   VARCHAR2(1)                                              Ativo            OPERACIONAL                        NaN
PCDEPTO  DESCRICAOECOMMERCE VARCHAR2(200)                            Descrição do e-commerce            OPERACIONAL                        NaN
PCDEPTO              TITULO VARCHAR2(200)                                             Titulo            OPERACIONAL                        NaN
PCDEPTO       CODDEPTOPRINC   NUMBER(6,0)                   Código do departamento principal            OPERACIONAL                        NaN
PCDEPTO          DTCADASTRO          DATE                                   Data de cadastro            OPERACIONAL                        NaN
PCDEPTO          DTMXSALTER          DATE                                                NaN            OPERACIONAL                        NaN
PCDEPTO              STATUS   VARCHAR2(1)                                                NaN            OPERACIONAL                        NaN
PCDEPTO           DTALTERC5  TIMESTAMP(6)                                     DATA ALTERACAO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*