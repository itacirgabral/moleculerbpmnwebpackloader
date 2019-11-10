# [https://camunda.com/learn/whitepapers/microservices-and-bpm/](https://camunda.com/learn/whitepapers/microservices-and-bpm/)

No final ele acaba usando outra stack, springboot e camunda.

Bpmn possui recursos de organização que vai além do escopo dos recursos nativos que os frameworks nodejs fornecem. Ele escolhe modelar muita coisa começando com um icone de messagem, isto descobre a aproximação com actor-model. O bpmn possui mecanismos para expressar timeout, trycatch e transação, além de capacidades de agenda com cron.

Erlang é uma linguagem que implementar actor-model, OTP seria a biblioteca padrão de processos para gerenciar esses atormodelos, parte do escopo se sobrepõem ao bpmn, outra parte significante que diverge do bpmn está preocupado com supervisão dos atormodelos, com hotreload, roteamento balanceado, com toda essa parte da infraestrutura relacionado com o sistema ser distribuídos e paralelo.

Talvez existam ícones apropriados no bpmn que possam expressas esses conceitos de delevops do OTP pra gente também deixar a parametrização disso ser feito pelo bpmn