# SOLID

![Solid](https://thedavidmasters.files.wordpress.com/2018/10/solid-principles.jpg)

## Principios da Orientação a Objetos

### Coesão

* É quando se tem uma harmonia entre os elementos. 
* No caso de uma classe, a coesão está nos seus atributos e metodos, ambos devem estar unidos e devem representar coisas em comum. 
* Classes não coesas tendem a a crescer indefinidiamente, o que as tornam difíceis de se manter.
* Uma classe coesa faz bem uma única coisa
* Classes coesas não devem ter várias responsabilidades

### Encapsulamento

* No contexto da orientação a objetos, o emcapsulamento consiste em blindar uma classe contra infuências externas que podem danificar a consistência das informações.
* Classes não encapsuladas permitem violação de regras de negócio, além de aumentarem o acoplamento.
* Getters e setters não são formas eficientes de aplicar encapsulamento
* É interessante fornecer acesso apenas ao que é necessário em nossas classes
* O encapsulamento torna o uso das nossas classes mais fácil e intuitivo

### Acoplamento

* O acoplamento é a situação em que se tem dois componentes que estão interligados entre si, causando uma depêndencia entre eles.
* Classes acopladas causam freagilidade no código da aplicação, o que dificulta sua manutenção.
* Acoplamento é a dependência entre classes
* Acoplamento nem sempre é ruim, e que é impossível criar um sistema sem nenhum acoplamento
* Devemos controlar o nível de acoplamento na nossa aplicação

## Single Responsabilty Principle 

![Single Responsabilty Principle](https://thedavidmasters.files.wordpress.com/2018/10/single-responsibility-principle.jpg)

* Uma classe deveria ter apenas um único motivo para mudar;
* O foco desse principio é a coesão;
* Quando se aplica este conceito, foca-se em manter uma alta coesão no código, deixando as classes pequenas e enxutas;
* Com isso, as alterações no código serão feitas em um único ponto do código.
* Classes/métodos/funções/módulos devem ter uma única responsabilidade bem definida;
* Segundo o Princípio de Responsabilidade Única (SRP), uma classe deve ter um e apenas um motivo para ser alterada.

## Open Closed Principle

![Open Closed Principle](https://thedavidmasters.files.wordpress.com/2018/10/open-closed-principle.png)

* O código pode ser mexido caso ocorra uma mudança na regra de negócio, já quando é uma nova funcionalidade deve ser adicionada de forma que extenda o que  já existe, mas não modificando;
* Cada classe deve conhecer e ser responsável por suas próprias regras de negócio;
* O princípio Aberto/Fechado (OCP) diz que um sistema deve ser aberto para a extensão, mas fechado para a modificação. Isso significa que devemos poder criar novas funcionalidades e estender o sistema sem precisar modificar muitas classes já existentes;
* Uma classe que tende a crescer "para sempre" é uma forte candidata a sofrer alguma espécie de refatoração.
 
## Liskov Substituition Principle

![Liskov Substituition Principle](https://thedavidmasters.files.wordpress.com/2018/10/liskov-substitution-principle.jpg)

* Embora a herança favoreça o reaproveitamento de código, ela pode trazer efeitos colaterais quando não utilizada da maneira correta;
* O Princípio de Substituição de Liskov (LSP) diz que devemos poder substituir classes base por suas classes derivadas em qualquer lugar, sem problema.

## Interface Segregation Principle

![Interface Segregation Principle](https://thedavidmasters.files.wordpress.com/2018/10/interface-segregation-principle.jpg)

* As interfaces devem definir apenas os métodos que fazem sentido para seu contexto;
* O Princípio de Segregação de Interfaces (ISP) diz que uma classe não deve ser obrigada a implementar um método que ela não precisa.

## Dependency Inversion Principle

![Dependency Inversion Principle](https://thedavidmasters.files.wordpress.com/2018/10/dependency-inversion-principle.jpg)

* É mais interessante e mais seguro para o nosso código depender de interfaces (classes abstratas, assinaturas de métodos e interfaces em si) do que das implementações de uma classe;
* As interfaces são menos propensas a sofrer mudanças enquanto implementações podem mudar a qualquer momento;
* O Princípio de Inversão de Dependência (DIP) diz que implementações devem depender de abstrações e abstrações não devem depender de implementações.


## Fontes 

* [SOLID com Java: Princípios da programação orientada a objetos](https://cursos.alura.com.br/course/solid-orientacao-objetos-java)
* [SOLID Design Principles](https://thedavidmasters.com/2018/10/27/solid-design-principles/)