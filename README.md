# 🔁 Verificador de Palíndromos em Python

Este projeto implementa duas formas diferentes de verificar se uma palavra é um palíndromo em Python:

## ✅ Abordagem iterativa

## 🔁 Abordagem recursiva

Um palíndromo é uma palavra que pode ser lida da mesma forma de frente para trás.

Exemplos:

arara

racecar

level

## 📂 Estrutura do Código

O projeto contém um único arquivo com:

Função iterativa: is_palindrome

Função recursiva: is_palindrome_recursive

Lista de palavras para teste

# ⚙️ Funcionamento
## 🔹 1. Verificação Iterativa (is_palindrome)

Essa função:

Percorre a palavra do início e do fim ao mesmo tempo

Compara os caracteres correspondentes

Conta quantas comparações deram certo

Verifica se o número de acertos é suficiente para considerar a palavra um palíndromo

is_palindrome("arara")  # True
is_palindrome("carro")  # False


# 📌 Utiliza:

Loop for

Índices (i e j)

Biblioteca math para cálculo do teto (ceil)

## 🔹 2. Verificação Recursiva (is_palindrome_recursive)

Essa função:

Compara o primeiro e o último caractere

Chama a si mesma removendo esses caracteres

Para quando a palavra tiver 0 ou 1 caractere

is_palindrome_recursive("level")  # True
is_palindrome_recursive("cama")   # False


# 📌 Conceitos aplicados:

Recursão

Caso base

Fatiamento de strings (word[1:-1])
