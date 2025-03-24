# 🐍 Projeto: Encontrando o Primeiro Número Duplicado

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)

## 🛠️ Descrição
Este projeto contém uma função que identifica o **primeiro número duplicado** em uma lista de números inteiros. Se não houver duplicados, ele retorna **-1**.

O código também percorre uma lista de listas e mostra o primeiro número duplicado de cada uma delas.

---

## 🧠 Como funciona o código

### 🔹 Função `primeiro_duplicado(lista)`

1. **Cria um conjunto vazio (`vistos`)** para armazenar os números já encontrados.
2. **Percorre a lista número por número.**
3. **Se o número já estiver no conjunto `vistos`, ele é retornado imediatamente** como o primeiro duplicado.
4. **Se não estiver**, o número é adicionado ao conjunto e o loop continua.
5. **Se não encontrar nenhum duplicado até o final da lista, retorna `-1`.**

### 🔹 Estrutura da lista de listas

O código contém uma lista chamada `lista_de_listas_inteiros` que possui várias sublistas com números inteiros. Cada sublista é analisada separadamente.

### 🔹 Laço principal

A linha com `enumerate()` percorre cada sublista e exibe o número da lista junto com o primeiro número duplicado encontrado.

Exemplo de saída:

```
Lista 1: Primeiro duplicado -> -1
Lista 2: Primeiro duplicado -> 9
Lista 3: Primeiro duplicado -> 2
...
```

---

## ▶️ Como executar o código

### 🔸 Clonando o repositório

Para começar, clone este repositório para sua máquina local usando:

```bash
git clone https://github.com/seuusuario/nome-do-repositorio.git
```

### 🔸 Rodando o projeto

1. Certifique-se de ter o Python instalado (versão 3.10 ou superior).
2. Navegue até a pasta do projeto:

```bash
cd nome-do-repositorio
```

3. Execute o script com o Python:

```bash
python primeiro_duplicado.py
```

---

## 🔥 Melhorias possíveis

- 📌 Adicionar suporte para listas de diferentes tipos (strings, floats, etc.).
- 📌 Melhorar a exibição do resultado.
- 📌 Permitir entrada do usuário para testar suas próprias listas.

---

### 🎯 Tecnologias usadas
- **Python 3**

---

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usá-lo e modificá-lo! 🔥

Agora é só rodar e testar! 🚀✨

