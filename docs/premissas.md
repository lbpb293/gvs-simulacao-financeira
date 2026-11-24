# Premissas da simulação financeira

Todas as premissas editáveis estão na aba **Premissas** da planilha. Valores monetários em R$.

## Gerais
- Horizonte: Ano 0 (desenvolvimento) + 3 anos de operação
- Taxa de desconto (TMA): 15% a.a.
- Reajuste anual de preço (crescimento): 5%
- Inflação anual dos custos: 5%
- Tributos sobre a receita (Simples Nacional): 6%

## Produto e preço
- Implantação: R$ 15.000 por cliente (única)
- Mensalidade: R$ 2.290 por cliente
- Custo de implantação por novo cliente: R$ 3.500
- Custo de suporte por cliente: R$ 150/mês

## Cenários de vendas da empresa (novos clientes Ano 1/2/3; churn)
| Cenário | Novos clientes | Churn |
|---|---|---|
| Pessimista | 3 / 4 / 4 | 10% |
| Esperado | 8 / 12 / 16 | 5% |
| Otimista | 14 / 22 / 30 | 3% |

## Cliente padrão (GVS Terceirizações)
- 12 clientes fixos e 8 variáveis por mês (relatório de Engenharia de Software II)
- Volume intermediado: R$ 1.344.000/ano; margem de intermediação de 18%
- Ganhos: horas administrativas, retenção (corte do intermediário), inadimplência e crescimento
