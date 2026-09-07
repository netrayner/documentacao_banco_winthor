# 📊 Tabela: PCDICIONARIOITEM

### Estrutura de Colunas e Restrições

          Tabela              Coluna  Tipo/Tamanho                                                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDICIONARIOITEM          NOMEOBJETO VARCHAR2(100)                                                                                                    Nome da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOITEM           NOMECAMPO VARCHAR2(100)                                                                                                     Nome do campo    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOITEM               AJUDA VARCHAR2(255)                                                                    Ajuda para o campo, montagem do hint das telas            OPERACIONAL                        NaN
PCDICIONARIOITEM              TITULO VARCHAR2(150)                                                                        Legenda do campo, curta descrição do mesmo            OPERACIONAL                        NaN
PCDICIONARIOITEM           CODROTULO  VARCHAR2(40)                                               Nome do rótulo default, valor padrão para este campo. Campo Default            OPERACIONAL                        NaN
PCDICIONARIOITEM             MASCARA  VARCHAR2(30)                                                            Máscara, utilizado para formatar campos. Campo Default            OPERACIONAL                        NaN
PCDICIONARIOITEM          NOMEEDITOR  VARCHAR2(30)                                                            Editor do cxVerticalGrid usado neste campo no cadastro            OPERACIONAL                        NaN
PCDICIONARIOITEM           AUTOGERAR VARCHAR2(150) S => Campo auto-gerado sempre, N => Campo nao auto-gerado, Tabela.Campo="valor" => Se true, o campo e auto-gerado            OPERACIONAL                        NaN
PCDICIONARIOITEM   CRIADOPELOCLIENTE       CHAR(1)                                                              Indica se o campo foi criado pelo cliente ou pela PC            OPERACIONAL                        NaN
PCDICIONARIOITEM  FORMULAAUTOGERACAO VARCHAR2(200)                 Indica a formula para auto-gerar o valor deste registro. Usado em conjunto com o campo AutoGerar.            OPERACIONAL                        NaN
PCDICIONARIOITEM      USUARIOCRIADOR  VARCHAR2(50)                                                                       Usuário que criou o campo no banco de dados            OPERACIONAL                        NaN
PCDICIONARIOITEM            CHARCASE       CHAR(1)                             Formato das letras: U - Caixa alta/ Maiúsculo, N - Livre, L - Caixa baixa / minúsculo            OPERACIONAL                        NaN
PCDICIONARIOITEM PSQRETIRACARACTERES       CHAR(1)                             Retirar caracteres especiais de campos e filtro durante a pesquisa. Ex.: CGC, CPF, IE            OPERACIONAL                        NaN
PCDICIONARIOITEM         MULTIEDICAO   VARCHAR2(1)                 Se o campo aceita ser processado na multi edição, através das teclas F11 e F10 do grid horizontal            OPERACIONAL                        NaN
PCDICIONARIOITEM          DTCADASTRO          DATE                                                                                       Data de criação do registro            OPERACIONAL                        NaN
PCDICIONARIOITEM        CRIPTOGRAFAR   VARCHAR2(1)                                                                                 Criptografar informação no banco.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*