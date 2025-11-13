Funções são blocos de código reutilizáveis que realizam uma tarefa específica. Elas permitem organizar o código, evitar repetições e facilitar a manutenção. As funções são um dos conceitos fundamentais da programação e um pilar da programação modular.

## Definindo funções
Em Python, funções são definidas com a palavra-chave `def`, seguida do nome da função e de parênteses que podem conter parâmetros.
### Sintaxe e exemplo simples
```python
def nome_da_funcao(parametro1, parametro2, ...):
    """Docstring: documentação da função."""
    # Corpo da função
    # Código que será executado quando a função for chamada
    return valor  # Opcional
```

```python
def saudacao():
    """Imprime uma saudação simples."""
    print("Olá, mundo!")

# Chamando a função
saudacao()  # Saída: Olá, mundo!
```
