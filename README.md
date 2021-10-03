# Desafio 02 - Filtragem em listas

## 💻 Sobre o desafio
Nesse desafio, você deverá criar um novo projeto com uma função que, dada uma
lista de strings que representem números ou não (exemplo
`["1", "3", "6", "43", "banana", "6", "abc"]`), filtre todos os elementos
numéricos da lista e retorne quantos números ímpares existem nessa lista.

Diferente do desafio 01, a sua solução para esse desafio não precisa ser
recursiva. Sinta-se livre para criar a solução da melhor maneira que achar
(veja a dica sobre o módulo Enum) 🚀

Para isso, você pode iniciar um projeto usando o comando:
```bash
mix new list_filter
```

Podemos acompanhar o resultado esperado observando o seguinte exemplo de
execução da função:
```bash
iex> ListFilter.call(["1", "3", "6", "43", "banana", "6", "abc"])
...> 3
```
Se quiser testar a sua implementação a partir do terminal, rode `iex -S mix`
dentro do diretório raiz do projeto 🚀

**Dica**: Você pode usar o módulo `Enum` para realizar esse desafio.
[Clicando aqui](https://hexdocs.pm/elixir/Enum.html) você irá para a
documentação do módulo.

Feito com 💜 por Rocketseat
