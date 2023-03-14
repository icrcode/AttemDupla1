# AttemDupla1
Atividade de estudo focada em chatGPT. - Ícaro Botelho e Gustavo Martins

### 1. O que é programação orientada a objetos?

  A programação orientada a objetos é um paradigma de programação que se baseia na ideia de organizar o código em torno de objetos, que representam entidades do mundo real ou conceitual. Cada objeto possui um conjunto de atributos e métodos que definem seu comportamento e interações com outros objetos. A POO permite reutilização de código, encapsulamento de dados e abstração de complexidade, tornando o desenvolvimento de software mais modular, flexível e fácil de manter. Exemplos de linguagens que suportam POO são Java, C++, Python e Ruby.

### 2. Quais são os pilares da programação orientada a objetos?

  A programação orientada a objetos (POO) é baseada em quatro pilares: encapsulamento, herança, polimorfismo e abstração. O encapsulamento é a técnica de esconder a complexidade interna de um objeto e expor apenas as interfaces necessárias para interagir com ele. 
  A herança permite que um objeto herde propriedades e comportamentos de uma classe pai, o que ajuda a reutilizar código e criar hierarquias de classes. O polimorfismo permite que objetos de diferentes classes possam responder de maneira diferente a uma mesma mensagem, tornando o código mais flexível e adaptável. Por fim, a abstração é o processo de identificar as características essenciais de um objeto e criar uma representação simplificada delas na forma de uma classe. Juntos, esses pilares permitem que a POO seja uma abordagem eficiente e organizada para desenvolver programas complexos e escaláveis.

### 3. O que é uma classe em Java?

  Em Java, uma classe é uma estrutura fundamental da programação orientada a objetos que define o comportamento e as propriedades de um objeto. Uma classe contém campos (variáveis) e métodos (funções) que descrevem as características e comportamentos de um objeto, respectivamente. Quando um objeto é criado a partir de uma classe, ele herda todas as suas propriedades e comportamentos, permitindo que seja manipulado e interaja com outros objetos no programa. As classes em Java são definidas usando a palavra-chave "class" seguida pelo nome da classe, que deve começar com uma letra maiúscula e seguir uma convenção de nomenclatura específica. Classes são usadas para criar tipos de dados personalizados em Java, tornando a linguagem flexível e poderosa para desenvolver aplicativos.

### 4. Como criar um objeto a partir de uma classe em Java?

  Para criar um objeto a partir de uma classe em Java, é necessário seguir os seguintes passos:
1. Definir a classe: antes de criar um objeto, é necessário definir a classe que irá representá-lo. Para isso, deve-se usar a palavra-chave "class" seguida pelo nome da classe e pelo corpo da classe, que contém os campos e métodos.
2. Instanciar a classe: para criar um objeto a partir de uma classe, é necessário instanciar a classe usando a palavra-chave "new" seguida pelo nome da classe e pelos parênteses vazios. Por exemplo: "MinhaClasse objeto = new MinhaClasse();".
3. Acessar os campos e métodos do objeto: uma vez criado o objeto, é possível acessar seus campos e métodos usando o nome do objeto seguido pelo operador ponto (.). Por exemplo: "objeto.meuMetodo()**;**".
  Os objetos criados a partir de uma classe em Java têm seus próprios valores de campo e comportamentos, independentes de outros objetos da mesma classe. É possível criar quantos objetos forem necessários a partir da mesma classe, cada um com seus próprios valores de campo e comportamentos.

### 5. O que faz a palavra new no Java

  A palavra-chave "new" é usada em Java para criar uma nova instância de uma classe, ou seja, para criar um novo objeto.  Quando usada com o operador de criação de objetos, a palavra "new" aloca espaço na memória para o novo objeto e chama o construtor da classe para inicializá-lo com os valores padrão ou personalizados. O construtor é um método especial da classe que é executado automaticamente sempre que um objeto é criado a partir daquela classe. O operador "new" é essencial para a programação orientada a objetos em Java, pois permite que os objetos sejam criados dinamicamente em tempo de execução, tornando a linguagem flexível e poderosa para desenvolver aplicativos.

### 6. Quais as semelhanças entre Java e C?

  Java e C são linguagens de programação populares que compartilham algumas semelhanças. Ambas as linguagens foram criadas para fins gerais e são amplamente usadas em desenvolvimento de software, especialmente em aplicativos empresariais e de sistemas operacionais. Ambas as linguagens usam uma sintaxe similar e incluem recursos como variáveis, estruturas de controle de fluxo, funções e tipos de dados básicos. Além disso, ambas suportam programação orientada a objetos, embora a implementação seja diferente em cada uma. No entanto, também existem diferenças significativas entre as duas linguagens, como a forma como lidam com memória, gerenciamento de exceções e a inclusão de recursos específicos da plataforma em Java.

### 7. Quais as diferenças entre Java e C?

  Java e C são linguagens de programação populares, mas diferem em várias características importantes. Java é uma linguagem orientada a objetos, enquanto C é uma linguagem procedural. Java tem uma máquina virtual que gerencia a execução de programas, enquanto C é compilado diretamente em código de máquina. Java é mais seguro, pois não permite acesso direto à memória e tem coleta automática de lixo, enquanto em C, é possível ter acesso direto à memória e a alocação e desalocação de memória é feita manualmente. Java também tem uma biblioteca padrão mais ampla do que C, o que torna o desenvolvimento de aplicativos mais fácil e rápido.

### 8. O que é a classe InputReader e qual é a sua função no programa?

  A classe InputReader é uma classe definida pelo usuário que é usada para ler valores de entrada do usuário a partir da linha de comando. Sua função no programa é solicitar uma entrada de valor double ao usuário com uma mensagem de prompt e retornar esse valor para o método chamador (no caso, o método main). O método readDouble na classe InputReader é responsável por imprimir uma mensagem de prompt, ler o valor double da entrada do usuário usando o objeto Scanner e retornar esse valor. A classe InputReader encapsula a lógica de entrada de dados do usuário em um único local, tornando-a mais fácil de modificar ou reutilizar em outros lugares do programa.

### 9. Qual é a finalidade do método readDouble na classe InputReader?

  O método readDouble na classe InputReader é utilizado para ler um número de ponto flutuante (double) a partir da entrada do usuário e retorná-lo como um resultado. Ele também exibe uma mensagem de prompt para o usuário informando qual valor deve ser digitado.

### 10. O que é a interface PaymentType e como ela é utilizada no programa?

  No código fornecido, a interface PaymentType é utilizada para permitir que o objeto PaymentTypeSelector retorne um objeto do tipo PaymentType com base na entrada do usuário. O método selectPaymentType() da classe PaymentTypeSelector lê a entrada do usuário e retorna uma instância de uma das classes que implementam a interface PaymentType, dependendo da entrada do usuário. Essa instância de PaymentType é então atribuída à variável paymentType na função principal do código.
  A função principal, em seguida, chama o método getName() e isValid() da instância de PaymentType para exibir o nome da opção selecionada pelo usuário e determinar se a opção é válida ou não.

### 11. Como a classe PaymentTypeSelector é responsável por selecionar o tipo de pagamento a ser utilizado?

A classe PaymentTypeSelector é responsável por selecionar o tipo de pagamento a ser utilizado através do método selectPaymentType().
  Esse método é responsável por imprimir no console as opções de pagamento disponíveis e, em seguida, ler a entrada do usuário para determinar qual opção foi selecionada. Com base na entrada do usuário, o método cria uma instância da classe apropriada que implementa a interface PaymentType e retorna essa instância.A classe PaymentTypeSelector usa uma estrutura de switch/case para determinar qual tipo de pagamento foi selecionado com base na entrada do usuário. Se a entrada do usuário não corresponder a nenhuma das opções disponíveis, o método retorna uma instância da classe InvalidPayment que implementa a interface PaymentType e indica que a opção selecionada não é válida.
  A classe PaymentTypeSelector é usada na função principal do código para obter o tipo de pagamento selecionado pelo usuário e armazená-lo na variável paymentType. A partir daí, a função principal usa a instância de PaymentType para exibir o nome da opção selecionada e determinar se a opção é válida ou não.

### 12. Qual é a relação entre a classe PaymentTypeSelector e as classes PixPayment, CreditPayment e BoletoPayment?

  A classe PaymentTypeSelector é responsável por permitir que o usuário selecione uma forma de pagamento entre as opções disponíveis (Pix, Crédito ou Boleto) e criar uma instância correspondente da interface PaymentType. As classes PixPayment, CreditPayment e BoletoPayment implementam a interface PaymentType e fornecem uma implementação personalizada dos métodos getName() e isValid() para representar cada forma de pagamento. Por exemplo, se o usuário selecionar a opção "1" para Pix na classe PaymentTypeSelector, a instância retornada será da classe PixPayment, que implementa a interface PaymentType e fornece uma implementação personalizada para os métodos getName() e isValid().

### 13. O que é polimorfismo e como ele é utilizado no programa?

  Polimorfismo é um conceito da programação orientada a objetos que permite que um objeto possa ser tratado de diferentes formas, ou seja, uma referência de um tipo pode ser utilizada para referenciar objetos de diferentes tipos que são subtipos desse tipo. No programa apresentado, o polimorfismo é utilizado na classe PaymentTypeSelector, que retorna um objeto do tipo PaymentType, mas esse objeto pode ser uma instância de qualquer uma das classes PixPayment, CreditPayment, BoletoPayment ou InvalidPayment. 
  O polimorfismo é útil porque permite escrever um código mais genérico e reaproveitável, tornando-o mais flexível a mudanças futuras.Por exemplo, ao chamar o método selectPaymentType() da classe PaymentTypeSelector, um objeto do tipo PaymentType é retornado, mas esse objeto pode ser uma instância de qualquer uma das classes que implementam a interface PaymentType, como PixPayment, CreditPayment ou BoletoPayment. Isso permite tratar o objeto de diferentes formas, como chamar os métodos getName() e isValid() que são implementados em comum pelas diferentes classes que implementam PaymentType.

### 14. Qual é a finalidade do método getName na interface PaymentType e nas classes que a implementam?

  O método getName() é definido na interface PaymentType e é implementado pelas classes PixPayment, CreditPayment, BoletoPayment e InvalidPayment.
  O método getName() é usado para retornar o nome do tipo de pagamento como uma String. Cada classe de tipo de pagamento implementa esse método para retornar seu respectivo nome, como "Pix", "Crédito", "Boleto" ou uma string vazia para InvalidPayment.
No método main(), o método getName() é chamado no objeto de tipo de pagamento selecionado para obter seu nome, que é então impresso juntamente com uma mensagem informando que a opção foi selecionada.

### 15. O que é a classe Scanner e como ela é utilizada no programa?

  A classe Scanner é uma classe de Java utilizada para ler entradas de dados do usuário, seja por meio do teclado, de um arquivo ou de qualquer outra fonte de entrada. No programa apresentado, a classe Scanner é usada para ler as opções de pagamento selecionadas pelo usuário através do teclado, tanto na classe InputReader, onde o método readDouble() utiliza o scanner para ler o valor informado, quanto na classe PaymentTypeSelector, onde o método selectPaymentType() lê a opção selecionada pelo usuário. O scanner é inicializado com o System.in, que representa a entrada padrão do sistema, ou seja, o teclado no caso de uma aplicação de console.

### 16. O que é uma exceção e como ela é tratada no método selectPaymentType da classe PaymentTypeSelector?

  Uma exceção é um evento que ocorre durante a execução de um programa e que interrompe o fluxo normal do programa. No Java, as exceções são objetos que representam esses eventos e que podem ser lançados por métodos quando ocorre algum problema durante a execução.
  No método selectPaymentType da classe PaymentTypeSelector, a exceção que pode ser lançada é a InputMismatchException, que ocorre quando o valor digitado pelo usuário não é um número inteiro válido. Essa exceção é lançada pelo método scanner.nextInt() quando o valor digitado não pode ser convertido para um inteiro.
  Para tratar essa exceção, o método selectPaymentType utiliza um bloco try-catch, que tenta executar o código dentro do bloco try e captura a exceção caso ela seja lançada. Se a exceção for capturada, o método exibe uma mensagem de erro e retorna um objeto InvalidPayment, indicando que a opção selecionada é inválida.

### 17. Como seria possível adicionar um novo tipo de pagamento ao programa?

  Para adicionar um novo tipo de pagamento ao programa, seria necessário criar uma nova classe que implemente a interface PaymentType e implementar os métodos da interface, getName() e isValid(). Em seguida, seria necessário adicionar a opção correspondente ao novo tipo de pagamento no método selectPaymentType() da classe PaymentTypeSelector.
  Por exemplo, para adicionar um novo tipo de pagamento chamado "Débito", seria necessário criar uma nova classe chamada DebitPayment que implemente a interface PaymentType e defina seus próprios valores para getName() e isValid(). Em seguida, seria necessário adicionar a opção correspondente ao novo tipo de pagamento no método selectPaymentType() da classe PaymentTypeSelector. Isso pode ser feito adicionando uma nova linha com a opção e a criação de uma instância da classe DebitPayment. Assim, o programa agora suporta um novo tipo de pagamento, que pode ser selecionado pelo usuário.

### 18. Qual é a importância de utilizar interfaces no desenvolvimento de sistemas orientados a objetos?

  Interfaces são importantes no desenvolvimento de sistemas orientados a objetos porque elas permitem a definição de um contrato ou um conjunto de ações que uma classe deve implementar, sem especificar como essas ações devem ser realizadas. Isso promove uma maior flexibilidade e modularidade do código, permitindo que diferentes implementações possam ser criadas sem afetar o funcionamento do sistema. Além disso, o uso de interfaces também facilita a criação de testes unitários e a manutenção do código.
  Um exemplo de uso de interface seria na criação de uma interface **`Animal`**, que poderia definir métodos como **`andar()`**, **`dormir()`**, **`comer()`**, entre outros. Dessa forma, qualquer classe que implemente essa interface deverá obrigatoriamente implementar esses métodos. Por exemplo, uma classe **`Cachorro`** poderia implementar a interface **`Animal`** e, assim, teria que implementar todos os métodos definidos na interface. Isso permite que o sistema possa trabalhar com diferentes tipos de animais sem precisar conhecer a implementação específica de cada um deles.

### 19. Qual é a diferença entre uma classe abstrata e uma interface?

  Uma classe abstrata é uma classe que não pode ser instanciada diretamente e é usada como uma classe base para outras classes. Ela pode conter implementações de métodos, mas também pode ter métodos abstratos, que são declarados, mas não implementados, e devem ser implementados nas classes derivadas. Já uma interface é uma coleção de métodos abstratos, que são definidos sem implementação. As classes que implementam uma interface devem fornecer uma implementação para cada um dos métodos da interface.
  Por exemplo, uma classe abstrata "Veículo" pode ter métodos implementados como "acelerar" e "frear", e métodos abstratos como "virar" e "parar". Já uma interface "Movimento" pode ter métodos abstratos como "moverParaFrente" e "moverParaTrás". As classes "Carro" e "Moto" podem estender a classe "Veículo" e fornecer uma implementação para os métodos abstratos, enquanto as classes "Avião" e "Barco" podem implementar a interface "Movimento".

### 20. O que é encapsulamento e como ele é aplicado em um programa?

  Encapsulamento é um princípio da programação orientada a objetos que consiste em esconder a implementação interna de uma classe e expor somente as informações e comportamentos relevantes para o uso externo da classe. Isso permite que a classe possa ser usada de forma mais segura e intuitiva, sem que os usuários precisem se preocupar com detalhes internos da implementação.
  No programa apresentado, o encapsulamento é aplicado de forma básica, já que as variáveis e métodos são definidos com níveis de acesso adequados (privado, protegido ou público) para controlar a visibilidade e o acesso aos dados e funcionalidades da classe. Por exemplo, a classe InputReader tem um método privado readDouble() que só pode ser acessado internamente pela classe, enquanto a classe PaymentTypeSelector tem um método público selectPaymentType() que pode ser acessado externamente para selecionar um tipo de pagamento.

### 21. Como seria possível melhorar a legibilidade do programa?

  Uma maneira de melhorar a legibilidade do programa é através da utilização de nomes descritivos para as classes, métodos e variáveis. Isso torna mais fácil para outras pessoas entenderem o código e suas funcionalidades. Além disso, é importante manter um código bem organizado, com identação e comentários adequados para facilitar a leitura e a manutenção do código.      Por exemplo, no código fornecido, poderia ser utilizada uma nomenclatura mais clara para os métodos e variáveis, como "promptValor" em vez de "readDouble", para deixar mais evidente o que esse método faz.
  Outra forma de melhorar a legibilidade é através da simplificação do código, evitando repetições e utilizando recursos disponíveis na linguagem de programação utilizada. Por exemplo, no código fornecido, poderia ser utilizado um array ou uma lista para armazenar os tipos de pagamento em vez de criar uma classe separada para cada tipo de pagamento, reduzindo assim a quantidade de código e tornando-o mais conciso e fácil de entender.

### 22. Qual é a finalidade da classe Main no programa?

  A classe Main é a classe principal de um programa em Java. É nela que o método main é definido e onde o programa começa sua execução. A finalidade da classe Main é fornecer um ponto de entrada para o programa e coordenar a execução das outras classes e métodos do programa.
  No código fornecido como exemplo, a classe Main é responsável por criar as instâncias das outras classes, como InputReader e PaymentTypeSelector, e chamar seus métodos para realizar a leitura de dados do usuário e selecionar o tipo de pagamento. Além disso, a classe Main imprime mensagens para o usuário na saída padrão.

### 23. O que é um construtor padrão e quando ele é utilizado?

Um construtor padrão é um método especial que é chamado automaticamente ao criar um objeto em uma classe. Ele não possui nenhum parâmetro e geralmente é utilizado para inicializar valores padrão aos atributos da classe. Se nenhum construtor for definido na classe, o construtor padrão é criado automaticamente pelo compilador.
No exemplo acima, a classe Pessoa tem um construtor padrão que define o nome como "Sem nome" e a idade como 0. Quando um objeto Pessoa é criado sem especificar um nome ou idade, o construtor padrão é chamado automaticamente e atribui esses valores padrão.

### 24. Como é possível proteger o programa contra erros de entrada do usuário?

  Uma forma de proteger o programa contra erros de entrada do usuário é através da validação de entrada de dados. Isso pode ser feito por meio de verificações de tipo de dados, faixa de valores aceitáveis, entre outras. É importante garantir que o programa informe ao usuário quando uma entrada inválida for detectada e solicite uma nova entrada.
  Por exemplo, no código apresentado, se o usuário inserir um valor não numérico ao ser solicitado para digitar um número, um erro será gerado. Para proteger o programa contra esse erro, podemos usar a classe Scanner para verificar se o valor inserido é realmente um número, e se não for, informar o usuário do erro e solicitar uma nova entrada. Isso pode ser feito adicionando uma verificação condicional após o comando "scanner.hasNextDouble()". Se o valor inserido não for um número, podemos informar o usuário do erro e solicitar uma nova entrada.

### 25. Qual é a importância de utilizar nomes descritivos para as classes, métodos e variáveis?

  Utilizar nomes descritivos para as classes, métodos e variáveis é muito importante para a legibilidade e manutenção do código. Um nome bem escolhido pode tornar o código mais fácil de ser compreendido e evita confusões. Por exemplo, ao nomear uma classe como "PaymentTypeSelector", já se tem uma ideia do que a classe faz: ela seleciona um tipo de pagamento. Da mesma forma, nomear um método como "readDouble" indica que ele faz a leitura de um valor em ponto flutuante.
  Por outro lado, nomes mal escolhidos podem dificultar a compreensão do código e até mesmo induzir a erros. Por exemplo, nomear uma variável como "a" não diz nada sobre o seu propósito e pode levar a confusões na leitura do código. Por isso, é importante sempre escolher nomes descritivos que deixem claro o propósito e a função de cada elemento do código.

### 26. O que é herança e como ela pode ser aplicada no programa?

  Herança é um conceito fundamental da programação orientada a objetos que permite que uma classe herde os atributos e comportamentos de outra classe. Isso pode ser aplicado no programa acima para criar classes de pagamento que compartilham comportamentos comuns, como nome e validade, e criar subtipos específicos de pagamento, como PixPayment, CreditPayment e BoletoPayment, que herdam esses comportamentos comuns da interface PaymentType. Dessa forma, o código fica mais organizado e modular, permitindo a fácil adição de novos tipos de pagamento no futuro, sem a necessidade de reescrever o mesmo código repetidamente.
  Um exemplo de como a herança pode ser aplicada neste programa é criar uma nova classe de pagamento chamada "DebitPayment" que estende a interface PaymentType e adiciona um novo comportamento para lidar com pagamentos por débito. A nova classe pode herdar todos os comportamentos comuns, como nome e validade, da interface PaymentType, e adicionar um novo comportamento exclusivo para lidar com pagamentos por débito. Isso tornaria o código mais modular e permitiria a fácil adição de uma nova opção de pagamento sem precisar alterar o código existente.
  
  ### 27. Como é possível utilizar a sobrecarga de métodos no programa?
  
  A sobrecarga de métodos permite ter dois ou mais métodos com o mesmo nome, mas que diferem nos parâmetros recebidos. No programa apresentado, não há exemplo de sobrecarga de métodos, pois não há dois métodos com o mesmo nome. 
  Um exemplo de sobrecarga de métodos poderia ser a criação de dois métodos chamados "readDouble", mas que recebem diferentes parâmetros. Por exemplo, um método poderia receber como parâmetro apenas uma mensagem de prompt, enquanto outro poderia receber tanto uma mensagem de prompt quanto um valor mínimo e um valor máximo permitidos. Dessa forma, seria possível chamar o método mais apropriado de acordo com a situação em que ele é necessário.
