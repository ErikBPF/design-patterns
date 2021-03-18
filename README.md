# Design Patterns

Desenvolvimento é um trabalho extremamente criativo e, por natureza, consiste em criar ferramentas e soluções que até então não existem ou não são acessíveis (ao menos não para o determinado contexto). Constrições relacionadas a escopo, performance, disponibilidade e custo fazem com que essas soluções recebam muitas customizações únicas às condições do que está sendo solucionado. Apesar da alta personalização da solução como um todo, os dilemas presentes nas várias pequenas etapas do problema são compostos por desafios lógicos bastante recorrentes no dia a dia do desenvolvedor.

Para ajudar nesses dilemas temos os **Design Patterns**. Os Design Patterns são estruturas de alto que nos ajudam a formatar esses impasses de forma a solucioná-los de forma limpa, permitindo o melhor entendimento, manutenção e expansão da solução num momento futuro, além de, em alguns casos, ajudar a evitar comportamentos não planejados. 

É importante ressaltar que os Patterns não são necessáriamente a **melhor** solução possível para todos os casos. Eles são apenas estruturas que já foram testadas por muitos times e que, consistentemente, apresentam um resultado satisfatório, além de serem fáceis de serem identificados por outra pessoa que eventualmente contribua também com o projeto.

## O que são Design Patterns

Os Design Patterns são mais uma forma de pensar do que um snippet de código pré-pronto. A ideia por trás deles é entender qual é o fundamento, entender o resultado alcançável e entender como aplicar a estrutura. Para ajudar nesses passos, é comum que os seguintes itens sejam apresentados junto a um padrão:

**Intenção**: Que tipo de benefício o pattern busca entregar.\
**Contexto**: Em que tipo de problema esse pattern pode ajudar e por que.\
**Estrutura**: Como seria esse pattern em ação e como ele ajuda no problema.\
**Exemplo**: Um exemplo genérico e funcional do pattern para ter uma referência na hora de fazer sua implementação.

## Tipos Design Patterns

Os Design Patterns são divididos em três grupos fundamentais:

1.  Patterns Comportamentais (Behavioral Patterns)
2.  Patterns Criacionais (Creational Patterns)
3.  Patterns Estruturais (Structural Patterns)

### Patterns Comportamentais

Patterns comportamentais focam na interação entre objetos, ajudando no desenho de como eles se comunicam e qual é a rensponsabilidade de cada um.

[Chain of Responsibility]()\
[Command]()\
[Iterator]()\
[Mediator]()\
[Memento]()\
[Observer]()\
[State]()\
[Strategy]()\
[Template Method]()\
[Visitor]()

### Patterns Criacionais

São patterns focados na forma de criar um objeto. O uso desses mecanismos auxilia na clareza, flexibilidade e reutilização do código.

[Abstract Factory]()\
[Builder]()\
[Factory Method]()\
[Prototype]()\
[Singleton]()


### Patterns Estruturais

Esses patterns organizam a classes e objetos na composição de estruturas maiores e mais complexas, tornando o código maleável em relação a novas interfaces e funcionalidades.

[Adapter]()\
[Bridge]()\
[Composite]()\
[Decorator]()\
[Facade]()\
[Flyweight]()\
[Proxy]()
   
