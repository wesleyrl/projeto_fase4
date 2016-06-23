#Persistência de dados
<b>Nessa última fase do projeto, você, ao invés de trabalhar com arrays, você deverá persistir essas informações no banco de dados.</b>

<hr>

 - Em suas fixtures, você deverá criar uma classe com métodos específicos para persistirem dados no banco. Você terá que injetar no construtor dessa classe um objeto PDO (somente PDO).

 - Crie um método chamado persist dentro dessa mesma classe; esse método deverá receber como dependência um objeto do tipo Cliente.

 - E para finalizar, crie um método chamado flush. Quando o método for executado, os dados devem ser persistidos no banco de dados.

 - Perceba que a responsabilidade de gravar os dados no banco são especificamente dessa classe, sem adicionar nenhuma outra responsabilidade a ela.


PS: Depois disso implementado, a listagem dos clientes devem ser chamadas a partir do banco de dados e não mais de um conjunto de arrays.

#Fase 3 do Projeto
<b>Refatoração</b>

<hr>


- Refatore as classes utilizadas de seu projeto para que as mesmas trabalhem com namespaces.

- Verifique se dentro de seu projeto há a necessidade de se trabalhar com classes abstratas.

- Não se esqueça de criar a estrutura de diretórios, nome de arquivos e classes seguindo a PSR-0 (www.php-fig.org).

- Faça a implementação do autoload para que você não precise mais trabalhar com require/include para a chamada de suas classes.

- Deixe todo o fonte de sua aplicação no mesmo nível que o DocumentRoot do servidor web. Deixe a pasta que está visível para web (seu DocumentRoot) apenas com o index.php e os demais assets(css, javascript e imagens).