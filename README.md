# The Natty Chef: Receitas e Imagens Tão Reais Que Vão Te Enganar ;)

## 📒 Descrição
Este projeto consiste na criação de um e-book de receitas fitness e saudáveis, utilizando exclusivamente IAs Generativas para a produção de todo o conteúdo: desde o texto das receitas até as imagens de alta qualidade dos pratos. O desafio central foi aplicar técnicas de **Prompt Engineering** e **Fine-tuning** para garantir que o resultado final fosse o mais "natty" (natural e autêntico) possível, evitando o visual genérico e artificial frequentemente associado a conteúdos gerados por IA.

## 🤖 Tecnologias Utilizadas
*   **Modelo de Linguagem (LLM):** `gpt-4.1-mini` (para geração e refinamento das receitas e textos de introdução).
*   **Modelo Text-to-Image:** `Midjourney` (para a criação das imagens dos pratos).
*   **Ferramenta de Edição de Imagem:** `Adobe Firefly` (para pequenos ajustes e retoques finais nas imagens, como correção de iluminação e remoção de artefatos).
*   **Ferramenta de Diagramação:** `Canva` (para a montagem final do e-book em formato PDF).

## 🧐 Processo de Criação
1.  **Geração de Receitas (LLM):** Utilizei o `gpt-4.1-mini` com prompts detalhados, solicitando receitas com ingredientes comuns, passos realistas e linguagem de um chef de cozinha. O prompt incluía restrições como "evitar ingredientes exóticos" e "manter o tom conversacional".
2.  **Prompt Engineering para Imagens (Midjourney):** Para cada receita, criei prompts visuais complexos para o Midjourney, focando em:
    *   **Estilo:** Fotografia de comida rústica, luz natural, foco seletivo (bokeh).
    *   **Composição:** Pratos em tábuas de madeira, com ingredientes frescos espalhados ao redor (mise en place).
    *   **Autenticidade:** Evitar o brilho excessivo e a perfeição irrealista que denunciam a IA.
3.  **Refinamento de Imagens (Adobe Firefly):** As imagens geradas foram importadas para o Firefly para pequenos ajustes. Usei a função de "Inpainting" para corrigir detalhes estranhos (como texturas de comida não naturais) e a função de "Generative Fill" para preencher fundos e dar mais profundidade à cena.
4.  **Revisão e Diagramação:** O texto final foi revisado para garantir a coesão e a fluidez. O e-book foi diagramado no Canva, utilizando um template limpo e profissional, para dar o toque final de um produto "natty".

## 🚀 Resultados
O resultado foi um e-book de 10 páginas com 5 receitas, onde o texto e as imagens são indistinguíveis de um conteúdo criado por um fotógrafo e um chef humano. A aplicação de **Prompt Engineering** focado em "imperfeições realistas" foi crucial para o sucesso do projeto. O e-book final está disponível na pasta `/ebook` deste repositório.

## 💭 Reflexão (Opcional)
O maior desafio foi justamente o de **evitar a perfeição**. As IAs Generativas tendem a criar imagens e textos excessivamente polidos. Para criar algo que pareça "natty", é preciso guiar a IA para introduzir elementos de realismo, como uma pitada de farinha na tábua ou um pequeno erro de foco. Isso demonstra que a habilidade do engenheiro de prompt é o fator decisivo para a qualidade e autenticidade do conteúdo gerado. O futuro da IA Generativa está na curadoria humana.
