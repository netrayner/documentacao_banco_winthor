# 📊 Tabela: PCBRINDEEXRESTRICOES

### Estrutura de Colunas e Restrições

              Tabela     Coluna Tipo/Tamanho                                                                                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBRINDEEXRESTRICOES    CODBREX  NUMBER(6,0)                                                                                                                                            Código da campanha.            OPERACIONAL                        NaN
PCBRINDEEXRESTRICOES  VALIDACAO  VARCHAR2(2)                                                                                                 Tipo de validação para a restrição, "P"roibido ou "E"xclusivo.            OPERACIONAL                        NaN
PCBRINDEEXRESTRICOES       TIPO  VARCHAR2(2) Tipo do objeto a ser validado para a restrição, "R"egião, "P"raça, Redes de Clientes "RC", "C"lientes, Cliente Principal "CP", "CL"asse de Venda dos clientes.            OPERACIONAL                        NaN
PCBRINDEEXRESTRICOES     CODIGO  NUMBER(6,0)                                                                                                              Código do objeto a ser validado, quando numérico.            OPERACIONAL                        NaN
PCBRINDEEXRESTRICOES    CODIGOA  VARCHAR2(6)                                                                                                          Código do objeto a ser validado, quando Alfanumérico.            OPERACIONAL                        NaN
PCBRINDEEXRESTRICOES GRUPOREGRA  NUMBER(6,0)                                                                                                                                               Código da regra.            OPERACIONAL                        NaN
PCBRINDEEXRESTRICOES DTMXSALTER         DATE                                                                                                                                                            NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*