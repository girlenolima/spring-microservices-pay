# Microsserviços com Spring.


# O que microsserviços
Microserviços, ou arquitetura de microserviços, é uma abordagem para o desenvolvimento de software onde uma aplicação grande é dividida em serviços menores e independentes que podem ser desenvolvidos, implantados e escalados de forma independente. Cada microserviço geralmente representa uma capacidade de negócio específica e se comunica com outros serviços através de APIs (Interfaces de Programação de Aplicativos) bem definidas.

Aqui estão algumas características e benefícios-chave dos microserviços:

- Modularidade: Os microserviços são projetados para serem componentes pequenos e focados que podem ser desenvolvidos, implantados e escalados de forma independente. Essa modularidade permite uma manutenção e atualizações mais fáceis.

- Escalabilidade: Como cada microserviço pode ser escalado de forma independente, isso permite uma utilização mais eficiente dos recursos. Por exemplo, se um serviço específico estiver experimentando uma alta demanda, é possível escalá-lo sem afetar toda a aplicação.

- Resiliência: Os microserviços promovem o isolamento de falhas. Se um serviço falhar, isso não necessariamente derruba todo o sistema. Outros serviços podem continuar operando, proporcionando um sistema mais resiliente.

- Diversidade Tecnológica: Diferentes serviços dentro de uma arquitetura de microserviços podem ser implementados usando tecnologias diferentes, dependendo dos requisitos do serviço. Isso permite que as equipes escolham a melhor ferramenta para o trabalho, em vez de estarem limitadas a uma única pilha tecnológica.

- Implantação Contínua: Os microserviços são bem adequados para práticas de integração e implantação contínuas (CI/CD). Como cada serviço é independente, as atualizações podem ser implantadas com mais frequência sem afetar todo o sistema.

- Autonomia da Equipe: Os microserviços permitem que as equipes trabalhem independentemente em diferentes serviços. Isso promove ciclos de desenvolvimento mais rápidos e permite que as equipes inovem e iterem mais rapidamente.

-  Design Orientado ao Domínio: Os microserviços geralmente são projetados em torno de domínios de negócios específicos, o que pode ajudar a alinhar a arquitetura mais de perto com os requisitos de negócios.

Newman (2015) define que 
> Microserviços são pequenos serviços autônomos que trabalham juntos, cada qual como uma
entidade separada, que pode ser implementado como um serviço isolado em uma plataforma
como serviço (PAAS).

Martin Fowler define que 
> Uma aplicação única, desenvolvida como um
conjunto de pequenos serviços, cada um executando
o seu próprio processo e se comunicando com
mecanismos leves, geralmente por API's REST
através do protocolo HTTP


> Spring boot actuator

