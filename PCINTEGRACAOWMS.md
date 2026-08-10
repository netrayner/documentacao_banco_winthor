# 📊 Tabela: PCINTEGRACAOWMS

### Estrutura de Colunas e Restrições

         Tabela              Coluna Tipo/Tamanho                                                                                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOWMS               NUMOS NUMBER(12,0)                                                                                                                                            Número da O.S.            OPERACIONAL                        NaN
PCINTEGRACAOWMS        COD_ENDERECO  NUMBER(8,0)                                                                                                                                        Codigo do endereço            OPERACIONAL                        NaN
PCINTEGRACAOWMS QUANTIDADE_SEPARADA NUMBER(20,8)                                                                                                                                       Quantidade Separada            OPERACIONAL                        NaN
PCINTEGRACAOWMS          CODFUNC_OS  NUMBER(8,0)                                                                                                                                     Código do Funcionario            OPERACIONAL                        NaN
PCINTEGRACAOWMS     TIPO_INTEGRACAO  NUMBER(1,0)                                                                                                                                        Tipo de Integração            OPERACIONAL                        NaN
PCINTEGRACAOWMS           NUMPALETE  NUMBER(6,0)                                                                                                                                          Número do palete            OPERACIONAL                        NaN
PCINTEGRACAOWMS              SEQUMA  NUMBER(3,0)                                                                                                                                 Sequência de movimentação            OPERACIONAL                        NaN
PCINTEGRACAOWMS           CODIGOUMA NUMBER(14,0)                                                                                                                                             Código da UMA            OPERACIONAL                        NaN
PCINTEGRACAOWMS         NUMTRANSWMS NUMBER(10,0)                                                                                                                                Número de transação no WMS            OPERACIONAL                        NaN
PCINTEGRACAOWMS        NUMAGRUPADOR NUMBER(10,0)                                                                                                                          Número do equipamento agrupador.            OPERACIONAL                        NaN
PCINTEGRACAOWMS     NUMVOLAGRUPADOR  NUMBER(4,0)                                                                                                                            Número do volume no agrupador.            OPERACIONAL                        NaN
PCINTEGRACAOWMS   COD_ENDERECO_ORIG  NUMBER(8,0) Endereço que foi gerado pelo endereçamento do ERP, este campo irá receber a informação de quando for alterado o COD_ENDERECO na execução da OS pelo VOICE            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*