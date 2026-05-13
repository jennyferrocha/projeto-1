# **Sistema de Biblioteca Pessoal** 

## 📝 **Descrição**
API desenvolvida para gerenciar uma coleção pessoal de livros, permitindo o acompanhamento do progresso de leitura e avaliação das obras concluídas.

## 🚀 **Funcionalidades (Status de Leitura)**
- 📖 **Quero ler**: Lista de desejos para futuras leituras.
- 📘 **Lendo**: Leitura atual.
- ✅ **Já li**: Livros concluídos.
- ⭐ **Avaliação**: Notas de 1 a 5 estrelas para livros lidos.

## 🛠️ **Classes de Domínio**
- **Livro**: título, ISBN, Editora.
- **Progresso Leitura**: status (quero ler, lendo, lido).
- **Avaliação**: 1 a 5 estrelas.
- **Autor**: nome.
- **Categoria**: gênero do livro.

## 🔗 **Relações**
- **Composição**: Livro e Avaliação (a nota é vinculada diretamente à obra).
- **Agregação**: Livro e Autor (o autor é uma entidade independente que compõe o livro).
- **Associação**: Livro e Categoria (vinculação para fins de classificação por gênero).

---
*Projeto desenvolvido para a disciplina de Programação Web.*