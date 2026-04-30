# Papel 
*(Básico)*

***Qual é a função, a posição, da Inteligência Artificial (IA) na atividade que está sendo requisitada.***

<img src="../imagens/cards/005.png" align="left" width="375" height="375">

Historicamente, a primeira coisa que a maioria dos guias de engenharia de prompts sugere é atribuir um papel à IA. A premissa é simples: ao definir uma persona, fornece-se à IA um contexto comportamental. 

Faça um teste. 

Peça à sua IA de eleição:
```
Pode me explicar o que é um Ovo pochê?
```
Depois, em um novo chat de preferência, tente uma pequena modificação indicando para a IA qual é o seu papel ao atender essa refinição, algo como o seguinte:
```
Como um chefe de cozinha pode me explicar o que é um Ovo pochê?
```
ou
```
Como um professor de culinária pode me explicar o que é um Ovo pochê?
```
Sentiu a diferença? O tom de voz muda, o vocabulário adapta-se e a resposta deixa de ser genérica para se focar numa audiência e num estilo específicos. Tratar a IA com um papel definido melhora a sinergia e direciona a resposta. No entanto, a ciência recente mostra-nos que o uso de "Papeis" tem limites claros e nem sempre é a solução mágica para obter melhores resultados.

Sim, provavelmente a resposta será um pouco diferente para Papeis diferentes, pois a busca e filtro de informações tende a ser diferente também.

Embora o uso de papéis seja um dos itens "básicos" para um bom prompt, um estudo conduzido por investigadores da Universidade de Michigan (EUA) e publicado em 2024 trouxe uma nova e fundamental perspetiva sobre esta prática.

Os investigadores testaram o impacto de adicionar "Papeis" aos prompts em 9 modelos de IA diferentes, avaliando 2.410 perguntas factuais (tarefas objetivas e diretas, como "qual é a capital de X?" ou "quem descobriu Y?"). Cada prompt foi testado com e sem "Papel" (ex.: "Aja como um historiador especialista...") e comparado com um cenário de controlo.

**O achado principal:** Adicionar "Papeis" não aumentou a precisão nas respostas objetivas de forma consistente. Em muitos casos, o desempenho foi aleatório ou até ligeiramente pior do que o de um prompt direto e simples.

Com base nesta descoberta, é fundamental separar o uso intencional de IA em duas categorias:

**1. Tarefas Objetivas e Factuais (Não use "Papeis")**
Para perguntas diretas do tipo "qual é...?", "quando aconteceu...?" ou cálculos e extrações de dados exatos, prompts diretos e bem estruturados (sem papel) saíram-se tão bem ou melhor. O estudo argumenta que o modelo já possui o conhecimento factual na sua base de dados; o "Papel" não adiciona nenhuma "verdade" nova, apenas enviesa o estilo ou adiciona um nível de confiança artificial à resposta que pode, inclusive, gerar alucinações.

**2. Tarefas Criativas e Interpretativas (Use Papel)**
Ainda não vi de que os "Papeis" não ajudem em tarefas criativas. Pelo contrário, para redação com um tom específico, criação de roteiros, simulação de cliente (role-play), ou adequação a um público-alvo, definir um Papel é extremamente poderoso. Nestes contextos, o "Papel" ajuda a padronizar o estilo, o tom e a voz, agindo muito mais como um mecanismo de controlo estilístico do que de precisão factual.

Aqui eu deixo um alerta, a IA nunca, repito "nunca", deve ser usada para susbstituir um humano, um erro comum que tenho visto é o uso de "Clientes Artificiais", Agentes ou Assistentes de IA treinados com dados demograficos e psicograficos de clientes reais, para levantamento de requisitos, por exemplo, a IA nunca vai conseguir simular a "expectativa" de um cliente real, pois essa envolve sentimentos e emoções que ela não consegue replicar.

##Se não melhora a precisão, por que os papéis ainda são tão usadas?

 - **Educação e Experiência do Utilizador (UX):** Muitos guias e plataformas recomendam a atribuição de um papel para dar mais contexto e clareza sobre o objetivo final ao utilizador humano. Ajuda-nos a organizar o raciocínio antes de pedir algo à máquina.
 - **Controlo de Tom e Coerência:** Em tarefas que envolvem simulação profissional (ex.: "atuando como um copywriter sénior", ou "como um editor experiente de um jornal nacional"), o "Papel" enriquece o contexto e restringe o vocabulário ao jargão da área, o que é altamente útil para a personalização de agentes.

O "Papel" não faz diferença (e pode até atrapalhar) em perguntas diretas de conhecimento factual. No entanto, é uma ferramenta poderosa para enriquecer contextos, personalizar respostas de agentes e direcionar produções criativas. Lembre-se sempre de que o humano é você, **a responsabilidade de verificar os factos (com ou sem "Papel") é exclusivamente sua**.

Reintero que este componente, com diferentes nomes, está presente na maioria das "receitas" de proMpt que eu estudei, a Persona o PACEF, o Role no PREP e Papel mesmo no PACIF.

Usar a definição de um Papel para a IA em seus proMpts deve torná-los ainda mais específicos de uma forma muito natural e simples, além de faz com que você trate a IA de forma similar a que trataria um parceiro humano melhorando a sinergia.

## Relações
<table>
<tr>
  <th>Componente</th>	<th>Método</th>	<th>Descrição</th>
</tr>
<tr>
  <td>Papel</td><td>PACIF</td><td>	Qual é o papel da IA na requisição que está sendo feita?</td>
</tr>
  <tr>
  <td>Persona</td><td>PACEF</td><td>	Qual é o papel da IA na requisição que está sendo feita?</td>
</tr>
<tr>
  <td>Role</td><td>PREP</td><td>	Qual é o papel da IA na requisição que está sendo feita?</td>
</tr>
<tr>
  <td>Role</td><td>RTF</td><td>Qual é o papel da IA na "Tarefa" que está sendo feita?</td>
</tr>
 <tr>
  <td>Role</td><td>RISEN</td><td>Qual a base de atuação e limites de conhecimento dessa IA?</td>
</tr> 
</table>

## Referências
Agilers. Almoce e Aprenda: IA na Gestão e Liderança. Disponível em: https://miro.com/app/board/uXjVK8HHzF0=/?moveToWidget=3458764593995821713&cot=14. Acesso em: 15 ago. 2024.

ALMEIDA, Davi Fontebasso Marques de. Papel | prompto. Disponível em: https://davifma.github.io/prompto/partes-de-prompt/papel.html. Acesso em: 30 abr. 2026.

BRADSHAW, Paul. 7 técnicas de design de prompts para IA generativa que todo jornalista deveria conhecer. Online Journalism Blog, 2025. Traduzido do inglês original.

DUARTE, Roberto Dias. Estudo 2024: Personas em Prompts Não Melhoram Resultados Objetivos - RDD10+. 14 jul. 2025. Disponível em: https://www.robertodiasduarte.com.br/estudo-2024-personas-em-prompts-nao-melhoram-resultados-objetivos/. Acesso em: 30 abr. 2026.

ZHENG, Mingqian et al. When "A Helpful Assistant" Is Not Really Helpful: Personas in System Prompts Do Not Improve Performances of Large Language Models. arXiv preprint arXiv:2311.10054v3, 2024. Disponível em: https://arxiv.org/abs/2311.10054. Acesso em: 30 abr. 2026.



<hr><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://davifma.github.io/proMpto/">prompto.github.io</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="http://linkedin.com/in/davifma">Davi Fontebasso Marques de Almeida</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""> <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>
