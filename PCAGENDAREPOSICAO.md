# 📊 Tabela: PCAGENDAREPOSICAO

### Estrutura de Colunas e Restrições

           Tabela     Coluna Tipo/Tamanho                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDAREPOSICAO      CODCD  VARCHAR2(2)                                                                  Filial de Origem (CD)            OPERACIONAL                        NaN
PCAGENDAREPOSICAO    CODLOJA  VARCHAR2(2)                                                               Filial de Destino (Loja)            OPERACIONAL                        NaN
PCAGENDAREPOSICAO TIPOEVENTO  VARCHAR2(2)               Tipo de Evento - [1-Sub-Categoria; 2-Categoria; 3-Seção; 4-Departamento]            OPERACIONAL                        NaN
PCAGENDAREPOSICAO  CODEVENTO  VARCHAR2(6)                           Código do Evento que dependerá o Tipo de Evento selecionado.            OPERACIONAL                        NaN
PCAGENDAREPOSICAO    SEGUNDA  VARCHAR2(1) Informa se haverá reposicao de produto na segunda-feira. (S)im - (N)ao - Default = Não            OPERACIONAL                        NaN
PCAGENDAREPOSICAO      TERCA  VARCHAR2(1)   Informa se haverá reposicao de produto na terça-feira. (S)im - (N)ao - Default = Não            OPERACIONAL                        NaN
PCAGENDAREPOSICAO     QUARTA  VARCHAR2(1)  Informa se haverá reposicao de produto na quarta-feira. (S)im - (N)ao - Default = Não            OPERACIONAL                        NaN
PCAGENDAREPOSICAO     QUINTA  VARCHAR2(1)  Informa se haverá reposicao de produto na quinta-feira. (S)im - (N)ao - Default = Não            OPERACIONAL                        NaN
PCAGENDAREPOSICAO      SEXTA  VARCHAR2(1)   Informa se haverá reposicao de produto na sexta-feira. (S)im - (N)ao - Default = Não            OPERACIONAL                        NaN
PCAGENDAREPOSICAO     SABADO  VARCHAR2(1)        Informa se haverá reposicao de produto no sábado. (S)im - (N)ao - Default = Não            OPERACIONAL                        NaN
PCAGENDAREPOSICAO    DOMINGO  VARCHAR2(1)       Informa se haverá reposicao de produto no domingo. (S)im - (N)ao - Default = Não            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*