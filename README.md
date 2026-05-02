# Quadratica

Calcula as raízes de uma equação de segundo grau e devolve o discriminante junto com o par de soluções.

## Instalação

Adicione a dependência ao manifesto da aplicação:

```ruby
gem 'quadratica'
```

Depois rode a instalação:

    $ bundle install

Ou instale direto na máquina:

    $ gem install quadratica

## Uso

```
require 'quadratica'

puts Quadratica.raizes(1, 2, 1)
```

O retorno é um par com as duas raízes; quando o discriminante é negativo, vem nulo no lugar da segunda.

## Referências

Há dois artigos que usei como guia: um explicando como empacotar uma biblioteca, outro sobre como publicar versões novas no índice.

## Ambiente de desenvolvimento

Depois de clonar, rode o script de preparação para instalar as dependências. A bateria de testes sai por uma tarefa do rake. Para experimentar interativamente existe um console pronto.

Para instalar a versão local, use a tarefa de instalação do bundle. Para publicar, atualize o número da versão no arquivo correspondente e rode a tarefa de publicação — ela cria a marcação, envia os commits e sobe o pacote.

## Contribuindo

Relatos de problema e contribuições são bem-vindos no repositório. O espaço é aberto e todos que participam seguem o código de conduta do projeto.


## Licença

Distribuído sob os termos da licença MIT.


### Observacao

Os nomes de arquivo e pasta foram mantidos como no projeto original.

## Código de conduta

Quem participa do projeto — em código, no rastreador de problemas, em conversas ou em listas — segue o mesmo código de conduta.