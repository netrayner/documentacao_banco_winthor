# 📊 Tabela: PCINTEGRACAOFRETEBRAS

### Estrutura de Colunas e Restrições

               Tabela       Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOFRETEBRAS       NUMPED NUMBER(10,0)                              Número do pedido            OPERACIONAL                        NaN
PCINTEGRACAOFRETEBRAS       NUMCAR NUMBER(10,0)                        Número do carregamento            OPERACIONAL                        NaN
PCINTEGRACAOFRETEBRAS  IDFRETEBRAS VARCHAR2(30) Identicador do frete retornado pela Fretebras            OPERACIONAL                        NaN
PCINTEGRACAOFRETEBRAS       FILIAL  VARCHAR2(2)                 Filial do carregamento/pedido            OPERACIONAL                        NaN
PCINTEGRACAOFRETEBRAS     SITUACAO VARCHAR2(30)                    Status do anúncio do frete            OPERACIONAL                        NaN
PCINTEGRACAOFRETEBRAS    DTCRIACAO         DATE          Data de criação  do anúncio do frete            OPERACIONAL                        NaN
PCINTEGRACAOFRETEBRAS DTVENCIMENTO         DATE       Data do vencimento  do anúncio do frete            OPERACIONAL                        NaN
PCINTEGRACAOFRETEBRAS   DTEXCLUSAO         DATE          Data da exclusão do anúncio do frete            OPERACIONAL                        NaN
PCINTEGRACAOFRETEBRAS    IDUSUARIO NUMBER(10,0)                 Identicador do usuário do WTA            OPERACIONAL                        NaN
PCINTEGRACAOFRETEBRAS  IDMOTORISTA NUMBER(10,0)       Identificador do motorista concretizado            OPERACIONAL                        NaN
PCINTEGRACAOFRETEBRAS    IDVEICULO NUMBER(12,0)           Idenficador do veículo concretizado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*