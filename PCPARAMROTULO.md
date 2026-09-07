# 📊 Tabela: PCPARAMROTULO

### Estrutura de Colunas e Restrições

       Tabela       Coluna Tipo/Tamanho                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMROTULO           ID VARCHAR2(40)                                               Identificador do rótulo.    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMROTULO   NOMEEDITOR VARCHAR2(30)     Como o rótulo será apresentado: RADIOBUTTON, COMBOBOX ou CHECKBOX.            OPERACIONAL                        NaN
PCPARAMROTULO VALORDEFAULT VARCHAR2(15) Valor padrão se o usuário não selecionar nenhum dos valores do rótulo.            OPERACIONAL                        NaN
PCPARAMROTULO VALORCHECKED VARCHAR2(15)   Se o NOMEEDITOR for "CHECKBOX", qual valor do rótulo será o Checked.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*