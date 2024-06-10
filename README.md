# Abordagem para o Problema da Árvore Geradora Mínima com Restrição de Diâmetro via Metaheurística BRKGA

## Descrição

Este projeto apresenta duas abordagens inovadoras para o Problema da Árvore Geradora Mínima com Restrição de Diâmetro (AGMRD). A primeira abordagem considera a criação de um backbone, um caminho central baseado no diâmetro restrito estabelecido. A segunda organiza os nós em níveis de acordo com o diâmetro restrito. Ambas geram soluções iniciais que são melhoradas pelo BRKGA (Biased Random-Key Genetic Algorithm) e refinadas por uma busca local. Os algoritmos propostos produzem soluções de alta qualidade em um tempo computacional viável, demonstrando sua eficácia para resolver o problema AGMRD.

## Resumo

A Árvore Geradora Mínima com Restrição de Diâmetro (AGMRD) é um problema de otimização combinatória importante em diversas áreas que requerem a otimização de redes para minimizar custos e garantir a eficiência operacional. A combinação de heurísticas clássicas e metaheurísticas proporciona ferramentas poderosas para enfrentar os desafios impostos pela natureza NP-difícil desse problema.

Neste artigo apresentamos duas abordagens inovadoras para AGMRD. A primeira considera a criação de um backbone, um caminho central baseado no diâmetro restrito estabelecido. A segunda organiza os nós em níveis de acordo com o diâmetro restrito. Ambas geram soluções iniciais que são melhoradas pelo BRKGA (Biased Random-Key Genetic Algorithm) e, finalmente, por uma busca local. Os algoritmos propostos produzem soluções de alta qualidade em tempo computacional viável, demonstrando sua eficácia para resolver o problema AGMRD.

## Palavras-chave

- AGMRD
- Heurísticas construtivas
- Metaheurística BRKGA

## Metodologia

Para resolver o problema da AGMRD, foram desenvolvidas duas heurísticas construtivas inovadoras:
1. **Heurística do Backbone**: Cria um caminho central (backbone) e conecta os nós restantes a ele.
2. **Heurística de Níveis**: Organiza os nós em níveis de acordo com o diâmetro restrito.

Ambas as heurísticas geram soluções iniciais que são refinadas usando a metaheurística BRKGA e técnicas de busca local (child node swap e 1-opt).

## Experimentos Computacionais

Os experimentos foram realizados com instâncias euclidianas de 50 a 500 vértices, utilizando Python. Os resultados mostraram que as abordagens propostas produzem soluções de alta qualidade com tempos de execução viáveis. 

## Resultados

Os algoritmos foram testados em várias instâncias, apresentando bons resultados em termos de custo e tempo de execução. A heurística de níveis combinada com o BRKGA modificado apresentou os melhores resultados.

## Conclusão

As heurísticas construtivas desenvolvidas para o BRKGA mostraram-se eficazes para resolver o problema da AGMRD. A implementação de uma busca local genérica baseada em propriedades e teoremas dos grafos é sugerida para trabalhos futuros, bem como a utilização de processamento paralelo para aumentar a eficiência.

## Referências

- Abdalla, A., & Deo, N. (2002). Random-tree Diameter and the Diameter-constrained MST. International Journal of Computer Mathematics, 79(6), 651–663.
- Gonçalves, J. F., & Resende, M. G. C. (2011). Biased random-key genetic algorithms for combinatorial optimization. International Journal of Production Economics, 141(1), 50–67.
- Santos, A. C., Lima, D. R., & Aloise, D. J. (2014). Modeling and solving the bi-objective minimum diameter-cost spanning tree problem. Journal of Global Optimization, 60(2), 195–216.

---

Feito com ❤️ por [Seu Nome](https://github.com/seu-usuario)
