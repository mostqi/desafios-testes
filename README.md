# Desafio de Testes

## Introdução
Desenvolvimento de software, não importa quão pequeno seja, nunca é o
trabalho de uma pessoa só. Códigos são incorporados por módulos
diferentes, são reescritos para serem mantidos a par dos novos recursos
que são disponibilizados pelas ferramentas utilizadas e também podem ser
desenvolvidos a partir de um trabalho conjunto entre desenvolvedores.

Os nossos serviços são compostos por diversos módulos, funções e
projetos que conversam entre si para gerar o resultado mais preciso e
ágil possível. Entretanto, essa integração faz com que seja muito fácil
que erros pequenos possam desencadear uma série de falhas que tornariam
difícil a identificação da causa.

Para isso é necessário que cada um destes módulos esteja bem testado,
para que, tanto seja possível garantir a precisão do resultado do código
atualmente em execução, como identificar rapidamente quaisquer
alterações que quebrem o funcionamento de um código previamente em
funcionamento.

## Desafio

Visando identificar erros, *bugs* e casos de borda, o foco deste desafio
será criar uma bateria de testes que corretamente identifique *Code
Smells* localizados nos códigos dispostos por nós. É importante notar
que intencionalmente colocamos erros no código, então, caso um teste não
tenha funcionado, tente identificar se houve algo que entendeu errado ou
se é realmente um dos *Code Smells* mencionados.

Tal desafio terá duas etapas obrigatórias:

1.  Implementação dos testes das classes *MockPerson* e *MockDate*,
    indicada em [*Python*](http://python.org/) (versão 3.9 ou superior)
    utilizando, primariamente, do pacote do [*Pytest*](pytest.org) para
    *Python*.
2.  Implementação dos testes das funções que terá acesso através de uma
    aplicação *Flask*, disponível no
    [*PyPI*](https://pypi.org/project/Flask/), que fará conexão com um
    servidor da Most para verificar a documentação da função e fazer
    requisições. Há um limite de 100 testes por requisição e 10 testes
    por segundo. Caso estes limites sejam ultrapassados será retornada
    uma mensagem de erro pela requisição.

Além destas, existe 1 etapa bônus, opcional:

-   Identificação dos *Code Smells* localizados nos códigos e elaboração
    de possíveis causas e casos do problema.

Tanto os pacotes utilizados quanto as versões dos mesmos e de
compiladores, interpretadores, etc, ficam a cargo do desenvolvedor. Não
será permitido usar um pacote de alto nível que faça as funcionalidades
requisitadas, nem copiar código do mesmo. Todo o histórico do
desenvolvimento deverá ser mantido, através de *commits* em um
repositório privado do *git* que será criado pelo desenvolvedor e
disponibilizado para os avaliadores antes do início do desafio. **Pontos
Importantes**:

-   A aplicação requer a utilização de seu token através do parâmetro
    Param-Auth no cabeçalho da requisição. No caso dos exemplos
    fornecidos substitua as ocorrências de \<TOKEN\> pelo valor do seu
    token individual.
-   São permitidas apenas 10 requisições por segundo pelo token
    fornecido. Caso mais requisições sejam realizadas o token será
    temporariamente desabilitado.
-   É interessante que o desenvolvedor descreva o processo criativo que
    o levou até os casos de borda encontrados.

## O que será avaliado

Em ordem de importância:

-   Identificação correta dos casos de borda e cobertura dos códigos;
-   Organização do código, dos testes e *commits*.
-   Processo criativo;
-   Qualidade dos resultados;
-   Afinidade com as linguagens e tecnologias requisitadas;
-   Capacidade de pesquisar e identificar soluções para os problemas que
    poderão aparecer;

## O que será disponibilizado

-   O código das classes dos testes inciais, *MockPerson* e *MockDate*;
-   Código de exemplo para comunicação com a aplicação *Flask*, por onde
    ocorrerá o acesso às funções a serem testadas, assim como um token
    de acesso à aplicação;
-   Acesso *ssh* com permissão de administrador para uma máquina recém
    formatada onde a solução deverá ser implementada e testada.

Os prazos podem ser estendidos a pedido do desenvolvedor.

## mostQI

Acesse nosso [linkedin](https://www.linkedin.com/company/mobile-solution-technology/posts/?feedView=all) para mais informações sobre vagas e novidades.
