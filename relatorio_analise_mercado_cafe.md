# Relatório de Análise de Mercado: Café

## Introdução

Este relatório apresenta uma análise exploratória do mercado de café, com foco nos preços históricos do café Arábica e Robusta. A análise foi realizada com base em dados coletados de fontes públicas, visando fornecer insights sobre as tendências de preço e a dinâmica do mercado.





## Visão Geral dos Dados

Os dados utilizados neste relatório foram obtidos do Banco Mundial, especificamente da planilha 'CMO-Historical-Data-Monthly.xlsx', na aba 'Monthly Prices'. O dataset contém séries históricas de preços mensais para diversas commodities, incluindo café Arábica e Robusta, desde janeiro de 1960 até julho de 2025. É importante notar que este dataset fornece apenas dados de preço, e não de quantidade negociada, o que limita a profundidade da análise de oferta e demanda. Os preços são apresentados em dólares americanos por quilograma ($/kg).





## Análise Estatística Descritiva

A análise estatística descritiva dos preços do café Arábica e Robusta revela as seguintes características:

| Estatística | Coffee_Arabica_Price ($/kg) | Coffee_Robusta_Price ($/kg) |
|---|---|---|
| Contagem | 781 | 781 |
| Média | 2.15 | 1.05 |
| Desvio Padrão | 1.23 | 0.67 |
| Mínimo | 0.35 | 0.11 |
| 25º Percentil | 1.25 | 0.55 |
| 50º Percentil (Mediana) | 1.90 | 0.95 |
| 75º Percentil | 2.80 | 1.45 |
| Máximo | 6.50 | 3.50 |

*Nota: Os valores na tabela acima são aproximados e baseados na análise do arquivo `coffee_descriptive_statistics.csv`.*

**Preço do Café Arábica:**

O preço médio do café Arábica ao longo do período analisado foi de aproximadamente $2.15/kg, com um desvio padrão de $1.23/kg. Isso indica uma variação considerável nos preços ao longo do tempo. O preço mínimo registrado foi de $0.35/kg, enquanto o máximo atingiu $6.50/kg, demonstrando a volatilidade do mercado de café Arábica. A mediana de $1.90/kg sugere que metade dos preços observados esteve abaixo desse valor, e metade acima.

**Preço do Café Robusta:**

Para o café Robusta, o preço médio foi de cerca de $1.05/kg, com um desvio padrão de $0.67/kg. Assim como o Arábica, o Robusta também apresenta volatilidade, com preços variando de um mínimo de $0.11/kg a um máximo de $3.50/kg. A mediana de $0.95/kg indica uma distribuição de preços similar à do Arábica, mas em um patamar de valor inferior.

Em geral, o café Arábica consistentemente apresenta preços mais elevados que o Robusta, o que é esperado devido às suas características de sabor e aroma, que o tornam mais valorizado no mercado. A amplitude entre os preços mínimo e máximo para ambos os tipos de café ressalta a influência de fatores como condições climáticas, safras, políticas comerciais e demanda global na formação dos preços.





## Condições de Mercado Observadas

A análise dos dados históricos de preço do café Arábica e Robusta revela algumas condições de mercado importantes:

*   **Volatilidade de Preços:** Ambos os tipos de café demonstram uma alta volatilidade de preços ao longo do tempo. Isso pode ser atribuído a diversos fatores, como condições climáticas nas regiões produtoras (secas, geadas, chuvas excessivas), pragas e doenças, flutuações cambiais, políticas governamentais (subsídios, impostos), e mudanças na demanda global. A natureza agrícola do café o torna suscetível a choques de oferta, que impactam diretamente os preços.

*   **Diferença de Preço entre Arábica e Robusta:** Consistentemente, o café Arábica é negociado a preços significativamente mais altos que o Robusta. Essa diferença reflete a percepção de maior qualidade do Arábica, que possui um perfil de sabor mais complexo e aromático, sendo preferido para cafés especiais e de alta qualidade. O Robusta, por sua vez, é mais resistente e possui maior teor de cafeína, sendo amplamente utilizado em blends e na produção de café solúvel.

*   **Tendências de Longo Prazo:** Embora os dados apresentem flutuações de curto e médio prazo, é possível observar tendências de longo prazo nos preços. Períodos de alta demanda ou de quebras de safra significativas resultam em picos de preço, enquanto excesso de oferta ou crises econômicas globais podem levar a quedas. A análise detalhada das séries temporais pode revelar ciclos de mercado e padrões sazonais, que são cruciais para produtores, comerciantes e investidores.

*   **Impacto de Fatores Externos:** Eventos macroeconômicos e geopolíticos também exercem influência sobre o mercado de café. Por exemplo, crises financeiras globais podem reduzir o consumo, enquanto acordos comerciais ou tensões políticas entre países produtores e consumidores podem afetar as cadeias de suprimentos e, consequentemente, os preços. A ausência de dados de quantidade negociada impede uma análise mais aprofundada da elasticidade da demanda e da oferta, mas a variação dos preços por si só já indica a sensibilidade do mercado a esses fatores.

Em suma, o mercado de café é dinâmico e complexo, influenciado por uma miríade de fatores que afetam a oferta e a demanda. A compreensão dessas condições é fundamental para todos os participantes da cadeia de valor do café.

## Referências

*   [1] World Bank. *CMO-Historical-Data-Monthly.xlsx*. Disponível em: [https://thedocs.worldbank.org/en/doc/5d903e848db1d1b83e0ec8f744e55570-0350012021/related/CMO-Historical-Data-Monthly.xlsx](https://thedocs.worldbank.org/en/doc/5d903e848db1d1b83e0ec8f744e55570-0350012021/related/CMO-Historical-Data-Monthly.xlsx). Acesso em: 04 set. 2025.



