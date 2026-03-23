# 📦 Gestão de Stock de Materiais Escolares

## 📖 Descrição

Este projeto consiste no desenvolvimento de um programa em Python que permite gerir o stock de materiais escolares de uma escola.

A aplicação funciona através de um menu interativo no terminal e utiliza funções para organizar as diferentes operações, garantindo um código modular, simples e eficiente.

O sistema permite registar novos materiais, consultar quantidades disponíveis, atualizar o stock e exportar os dados para um ficheiro.

---

## 🎯 Objetivos

* Desenvolver um programa estruturado com funções
* Permitir a gestão eficiente de materiais escolares
* Facilitar o controlo de stock
* Aplicar conceitos básicos de programação em Python

---

## ⚙️ Funcionalidades

✅ **Adicionar Material**
Permite registar novos materiais no stock com uma quantidade inicial.

✅ **Consultar Stock**
Permite verificar a quantidade disponível de um material específico.

✅ **Atualizar Stock**
Permite:

* Adicionar unidades ao stock
* Remover unidades do stock (com validação)

✅ **Exibir Stock Geral**
Mostra todos os materiais e respetivas quantidades.

✅ **Exportar Stock**
Guarda os dados do stock num ficheiro `.csv`.

---

## 🧠 Estrutura do Programa

O programa está organizado nas seguintes funções:

* `adicionar_material()`
* `consultar_stock()`
* `atualizar_stock()`
* `exibir_stock()`
* `exportar_stock()`
* `main()`

---

## 💾 Exportação de Dados

Ao escolher a opção de exportação, será criado um ficheiro `.csv` com o seguinte formato:

```
Material,Quantidade
lápis,50
cadernos,30
borrachas,20
```

Este ficheiro pode ser aberto no Excel ou Google Sheets.

---

## 🛠️ Tecnologias Utilizadas

* Python 3
* Programação estruturada (funções)
* Manipulação de ficheiros (I/O)

---

## 🚀 Melhorias Futuras

* Importação de stock a partir de ficheiros
* Interface gráfica (GUI)
* Base de dados para persistência de dados
* Sistema de autenticação de utilizadores

---

## 👨‍💻 Autor

Projeto desenvolvido no âmbito de aprendizagem de programação em Python.

---

## 📄 Licença

Este projeto é de uso livre para fins educativos.
