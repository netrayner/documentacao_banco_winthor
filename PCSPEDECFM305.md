# 📊 Tabela: PCSPEDECFM305

### Estrutura de Colunas e Restrições

       Tabela       Coluna Tipo/Tamanho                                                                                                                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFM305           ID  NUMBER(8,0)                                                                                                                                                   Identificador único do registro (PK)    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFM305 IDLANCAMENTO       NUMBER                                                                                                                                                       ID da tabela PCSPEDECFLANCAMENTO CHAVE ESTRANGEIRA (FK)        PCSPEDECFLANCAMENTO
PCSPEDECFM305       IDM010  NUMBER(8,0)                                                                                                       ID da tabela PCSPEDECFM010. Conta selecionada pelo usuário na tela de lançamento CHAVE ESTRANGEIRA (FK)              PCSPEDECFM010
PCSPEDECFM305        VALOR NUMBER(22,4)                                                                                                                          Valor total dos lançamentos adicionados ou excluídos da conta            OPERACIONAL                        NaN
PCSPEDECFM305    INDICADOR      CHAR(1) Indicador do Valor Total dos Lançamentos: D = Prejuízos ou valores que reduzam o lucro real em períodos subsequentes ou C = Valores que aumentam o lucro real em períodos subsequentes            OPERACIONAL                        NaN
PCSPEDECFM305        LALUR      CHAR(1)                                                                                                                                                                  S = LALUR ou N = LACS            OPERACIONAL                        NaN
PCSPEDECFM305    DTCRIACAO         DATE                                                                                                                                          Data de criação do registro no banco de dados            OPERACIONAL                        NaN
PCSPEDECFM305  TIPOPERIODO      CHAR(1)                                                                                                                                                                        Tipo de período            OPERACIONAL                        NaN
PCSPEDECFM305  PERIODOLANC  NUMBER(2,0)                                                                                                                                                                      Mês de lançamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*