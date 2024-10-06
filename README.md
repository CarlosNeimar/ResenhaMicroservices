# ResenhaMicroservices

https://www.martinfowler.com/articles/microservices.html

O artigo **"Microservices"** de James Lewis e Martin Fowler explora a arquitetura de microserviços como uma alternativa ao modelo monolítico tradicional. A arquitetura de microserviços permite o desenvolvimento de aplicações como um conjunto de pequenos serviços independentes, cada um executando seu próprio processo e comunicando-se por meio de APIs leves, como HTTP. Esses serviços são centrados nas capacidades de negócio e são implantados de maneira independente, o que proporciona maior flexibilidade e escalabilidade.

Os autores apontam as principais características dessa abordagem, incluindo a **componentização via serviços**, o que facilita a substituição e a atualização de partes individuais da aplicação. Ao contrário do monólito, onde mudanças em uma pequena parte requerem o redesenho completo, os microserviços permitem atualizações localizadas, reduzindo o impacto nas demais funcionalidades.

A divisão de serviços é feita com base em **capacidades de negócios**, ou seja, cada serviço cobre uma funcionalidade de negócio específica, o que reflete em uma organização mais eficiente. A filosofia de **produtos, não projetos** incentiva as equipes a manterem e operarem os serviços por todo o seu ciclo de vida, o que aproxima desenvolvedores dos problemas reais dos usuários.

Além disso, os autores destacam a importância de **pontos inteligentes e pipelines simples**. Ao invés de utilizar arquiteturas complexas de integração, como o barramento de serviços corporativos (ESB), a arquitetura de microserviços favorece uma abordagem mais simples e eficaz para a comunicação entre serviços.

Por fim, o artigo discute os desafios e os benefícios dos microserviços, como a **governança descentralizada** e a **automação da infraestrutura**, e menciona que, embora a arquitetura seja promissora, ainda é cedo para afirmar que os microserviços são o futuro, dado o tempo relativamente curto de sua implementação em larga escala.
