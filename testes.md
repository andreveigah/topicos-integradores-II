# Por que devemos fazer testes automatizados nas aplicações que desenvolvemos?

O foco da entrega contínua é entregar novos lançamentos de código o mais rápido possível para os clientes. Não há como automatizar a entrega aos usuários se houver uma etapa manual e demorada no processo de entrega.
Escalabilidade: Assim, a automação de testes permite manipular verificações para atender praticamente qualquer número de alterações e também escalar a execução dos testes em localização.
Confiabilidade: Os testes automatizados são menos suscetíveis a erros humanos, pois são sempre repetidos da mesma maneira. Isso permite uma confiabilidade constante na qualidade do produto, agilizando o processo de desenvolvimento e lançamento de aplicativos. É também uma forma de garantir o nível de segurança da aplicação, pois o rigor do teste não oscila entre um teste e outro.
Ciclos de feedback mais rápidos: Problemas de qualidade, configuração e implantação podem ser detectados antecipadamente e tratados de modo a reduzir totalmente o impacto no usuário final.
Economia de recursos: Ao garantir que o produto seja corretamente testado toda vez, a equipe minimiza os riscos de retrabalho, causado por erros humanos no processo de testagem. Otimizar o tempo de testagem permite direcionar os recursos a outras atividades, como o aprimoramento da aplicação, o prosseguimento do desenvolvimento ou até mesmo o trabalho em outros projetos.
Mais valor agregado à aplicação: Uma aplicação bem acabada, livre de bugs e problemas de usabilidade, estável e de confiança tem um valor agregado muito mais alto do que um produto similar de qualidade inferior. Isso é crucial para o estabelecimento de uma sólida base de usuários para a aplicação, permitindo o sucesso da operação.
Desenvolvimento mais rápido: O tempo economizado com o teste manual pode ser aplicado em outras atividades, como correção de bugs, melhoria de funcionalidade e desenvolvimento de novas versões do software. Após o desenvolvimento e validação dos sistemas de teste do aplicativo, o desenvolvimento torna-se ainda mais ágil e rápido. O tempo economizado pode ser usado para outros projetos não relacionados.

# O que são testes unitários?

Descrição: É a forma de se testar unidades individuais de código fonte. Unidades podem ser métodos, classes, funcionalidades, módulos, etc. Depende muito do que é a menor parte que seu Software pode ser testado.

Objetivo: dos testes unitários é mostrar que cada unidade atende corretamente sua especificação.

Exemplo: testes automáticos criados para darem entradas e conferirem saídas a cada método, permitindo que se saiba que está funcionando de acordo com o esperado.

Benefícios: encontrar problemas o quanto antes, facilitam a mudança da unidade, simplificam a integração e melhoram a documentação.

# O que são testes automatizados?

De maneira simples, os testes automatizados são definidos como programas que realizam testes em softwares que estão em construção de modo padronizado, sem que seja necessária a intervenção humana. Isso porque eles contam com funcionalidades que são capazes de testar automaticamente todos os aspectos de uma plataforma, a fim de garantir um desempenho adequado.

# Escolha uma pirâmide de testes e descreva com suas palavras cada secção da pirâmide.

A função da pirâmide de testes é basicamente definir níveis de testes e te dar um norte quanto à quantidade de testes que você deveria ter em cada um desses níveis.

Os testes de ponta a ponta geralmente acontecem em um ambiente controlado (não é o ambiente de produção) e quem realiza as ações é um robozinho. Vale lembrar que quando dizemos “usuário” não estamos necessariamente falando do cliente que acessará sua página ou aplicativo desktop. Esses testes são complexos de escrever e geralmente levam um tempo considerável para serem executados. Quando um teste ponta a ponta falha, não é trivial inferir onde está o problema na aplicação, pois o teste é bastante abrangente. Por esses motivos, geralmente são testes que abrangem apenas os fluxos principais da aplicação.

Os testes de unidade verificam a operação da menor unidade de código testável em nosso aplicativo. A unidade geralmente é vista como um método público em uma classe, mas também pode ser um conjunto de objetos de métodos de classes. Deixo a discussão de qual deve ser o tamanho de cada unidade para outro artigo, mas independentemente do que você ou sua equipe usar como padrão, a unidade sempre será definida como a menor parte testável do seu sistema.

Testes de integração testam algumas unidades trabalhando juntas. Ao contrário dos testes de ponta a ponta, são testes que testam a funcionalidade, não o sistema como um todo. Os testes de integração são: Mais complicados (para fazer e manter) e demorados do que os testes de unidade. Muito mais simples e rápido do que os testes de ponta a ponta.








