# Relatório de Higienização — pbi-rh-Audit_Higie_auditoria

**Data/Hora:** 2026-11-17 09:58:43
**Projeto Original:** pbi-rh-Audit_Higie
**Critério:** StatusFinal = "Não utilizada"

---

## Resumo

| Métrica | Valor |
|---------|-------|
| Tabelas removidas | 0 |
| Objetos removidos (total) | 0 |
| — Colunas | 0 |
| — Colunas Calculadas | 0 |
| — Medidas | 0 |
| Relacionamentos removidos | 0 |
| Objetos protegidos (não removidos) | 31 |

### Estatísticas de Classificação Original

| Status | Quantidade |
|--------|------------|
| Utilizada | 84 |
| Cadeia sem uso real (verificar) | 23 |
| Não utilizada | 66 |

---

## Tabelas Completamente Removidas

_Nenhuma tabela completamente removida._

---

## Objetos Removidos por Tabela

---

## Relacionamentos Removidos

_Nenhum relacionamento removido._

---

## Proteções Aplicadas (Não Removidos Apesar de "Não utilizada")

| Tabela | Tipo | Nome | Motivo |
|--------|------|------|--------|
| DateTableTemplate_6815794a-a7df-41ed-928b-197a947cd374 | Coluna Calculada | Ano | Tabela de data referenciada por variation blocks |
| DateTableTemplate_6815794a-a7df-41ed-928b-197a947cd374 | Coluna Calculada | Dia | Tabela de data referenciada por variation blocks |
| DateTableTemplate_6815794a-a7df-41ed-928b-197a947cd374 | Coluna Calculada | Mês | Tabela de data referenciada por variation blocks |
| DateTableTemplate_6815794a-a7df-41ed-928b-197a947cd374 | Coluna Calculada | Trimestre | Tabela de data referenciada por variation blocks |
| LocalDateTable_882d33ab-1416-450e-a1ea-527ed74fea6b | Coluna Calculada | Ano | Tabela de data referenciada por variation blocks |
| LocalDateTable_882d33ab-1416-450e-a1ea-527ed74fea6b | Coluna Calculada | Dia | Tabela de data referenciada por variation blocks |
| LocalDateTable_882d33ab-1416-450e-a1ea-527ed74fea6b | Coluna Calculada | Mês | Tabela de data referenciada por variation blocks |
| LocalDateTable_882d33ab-1416-450e-a1ea-527ed74fea6b | Coluna Calculada | Trimestre | Tabela de data referenciada por variation blocks |
| LocalDateTable_9fbf330c-a63d-4710-8f16-d4400b2bae5f | Coluna Calculada | Ano | Tabela de data referenciada por variation blocks |
| LocalDateTable_9fbf330c-a63d-4710-8f16-d4400b2bae5f | Coluna Calculada | Dia | Tabela de data referenciada por variation blocks |
| LocalDateTable_9fbf330c-a63d-4710-8f16-d4400b2bae5f | Coluna Calculada | Mês | Tabela de data referenciada por variation blocks |
| LocalDateTable_9fbf330c-a63d-4710-8f16-d4400b2bae5f | Coluna Calculada | Trimestre | Tabela de data referenciada por variation blocks |
| LocalDateTable_cf14291d-6606-44c3-bc1c-c1b772a0bd8f | Coluna Calculada | Ano | Tabela de data referenciada por variation blocks |
| LocalDateTable_cf14291d-6606-44c3-bc1c-c1b772a0bd8f | Coluna Calculada | Dia | Tabela de data referenciada por variation blocks |
| LocalDateTable_cf14291d-6606-44c3-bc1c-c1b772a0bd8f | Coluna Calculada | Mês | Tabela de data referenciada por variation blocks |
| LocalDateTable_cf14291d-6606-44c3-bc1c-c1b772a0bd8f | Coluna Calculada | Trimestre | Tabela de data referenciada por variation blocks |
| stgFuncionarios | Coluna | Beneficios | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Data de Contratacao | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Data de Demissao | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Data de Nascimento | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Endereço | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Ferias Acumuladas | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Flag Avaliação Fora 0 a 10 | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Flag Competência Fora 0 a 10 | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Flag Data Demissão Antes Contratação | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Flag Férias Negativas | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Flag Horas Extras Negativas | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Flag Valor Financeiro Negativo | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Imagem | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Nome Completo | Referenciada na partição M do stgFuncionarios |
| stgFuncionarios | Coluna | Salario Base | Referenciada na partição M do stgFuncionarios |

---

## Instruções Pós-Higienização

1. Abrir `pbi-rh-Audit_Higie_auditoria.pbip` no Power BI Desktop
2. Verificar se todos os visuais carregam corretamente
3. Revisar este relatório para confirmar que as remoções são esperadas
4. Se houver problemas, restaurar do projeto original e ajustar proteções
