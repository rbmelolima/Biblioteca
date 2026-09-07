<div align="center">

# 📚 Biblioteca Digital de Computação & Tecnologia

[![Status](https://img.shields.io/badge/Status-Ativo-success?style=for-the-badge&logo=statuspage&logoColor=white)]()
[![Livros](https://img.shields.io/badge/Livros-10%20Dispon%C3%ADveis-indigo?style=for-the-badge&logo=gitbook&logoColor=white)]()
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2D9?style=for-the-badge&logo=tailwind-css&logoColor=white)]()
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)]()

<p align="center">
  <strong>Um acervo digital moderno, acessível e organizado com os principais clássicos da Ciência da Computação e Engenharia de Software.</strong>
</p>

<p align="center">
  <a href="#-sobre-o-projeto">Sobre</a> •
  <a href="#-livros-disponíveis">Acervo</a> •
  <a href="#-interface-web">Interface Web</a> •
  <a href="#-como-utilizar">Como Utilizar</a> •
  <a href="#-estrutura-do-projeto">Estrutura</a>
</p>

---

</div>

## 💡 Sobre o Projeto

A **Biblioteca Digital de Computação** é uma plataforma estática projetada para facilitar o acesso, consulta e download de livros fundamentais para estudantes, desenvolvedores e pesquisadores de tecnologia.

### ✨ Destaques
- 🎨 **Interface Moderna & Responsiva**: Desenvolvida com Tailwind CSS e tipografia otimizada.
- ⚡ **Busca & Filtro em Tempo Real**: Encontre livros por título, assunto, tags ou filtre por categoria temática.
- 📥 **Acesso Direto**: Visualize diretamente no navegador ou faça download com apenas um clique.
- 📂 **Organização Padronizada**: Todos os arquivos centralizados no diretório `/src`.

---

## 📖 Livros Disponíveis

Abaixo está o catálogo completo das obras presentes no acervo:

| # | Capa / Título | Categoria | Edição / Autor | Tamanho | Download |
|:---:|:---|:---:|:---:|:---:|:---:|
| **01** | **Arquitetura e Organização de Computadores** | `Hardware & Arquitetura` | 8ª Edição | `20.1 MB` | [📥 Baixar](./src/Arquitetura%20e%20Organiza%C3%A7%C3%A3o%20de%20Computadores%20-%208%C2%AA%20Ed.pdf) |
| **02** | **Comunicação de Dados e Redes de Computadores** | `Redes & Comunicação` | 4ª Edição | `16.7 MB` | [📥 Baixar](./src/Comunica%C3%A7%C3%A3o%20de%20Dados%20e%20Redes%20de%20Computadores_compressed%20(1).pdf) |
| **03** | **Sistemas Operacionais: Projeto e Implementação** | `Sistemas Operacionais` | 3ª Ed. (Tanenbaum) | `3.8 MB` | [📥 Baixar](./src/Sistemas%20Operacionais%20-%20Projeto%20e%20Implementa%C3%A7%C3%A3o%20-%20Inclui%20CD-ROM%20-%203%C2%AA%20Ed.pdf) |
| **04** | **Elementos de Matemática Discreta** | `Matemática` | Para Computação | `1.4 MB` | [📥 Baixar](./src/Elementos%20de%20Matematica%20Discreta%20para%20computa%C3%A7%C3%A3o.pdf) |
| **05** | **Fundamentos de Programação** | `Algoritmos` | Algoritmos, ED & OO | `9.2 MB` | [📥 Baixar](./src/Fundamentos%20de%20Programa%C3%A7%C3%A3o.pdf) |
| **06** | **Engenharia de Software** | `Eng. de Software` | 9ª Ed. (Sommerville) | `17.7 MB` | [📥 Baixar](./src/Engenharia%20de%20Software%20-%209%20edi%C3%A7%C3%A3o.pdf) |
| **07** | **Estruturas de Dados Usando C** | `Algoritmos` | A. Tenenbaum | `6.8 MB` | [📥 Baixar](./src/Estruturas%20de%20Dados%20Usando%20C%20(Tenenbaum).pdf) |
| **08** | **Interação Homem-Computador** | `Design & IHC` | UX / Usabilidade | `5.7 MB` | [📥 Baixar](./src/Intera%C3%A7%C3%A3o%20Homem%20Computador.pdf) |
| **09** | **Introdução à Arquitetura e Design de Software** | `Eng. de Software` | Casa do Código | `3.1 MB` | [📥 Baixar](./src/Introdu%C3%A7%C3%A3o%20%C3%A0%20Arquitetura%20e%20Design%20de%20Software%20-%20Casa%20do%20Codigo.pdf) |
| **10** | **Sistemas Digitais: Princípios e Aplicações** | `Hardware & Arquitetura` | 11ª Edição | `33.5 MB` | [📥 Baixar](./src/Sistemas%20Digitais%20-%20Princ%C3%ADpios%20e%20Aplica%C3%A7%C3%B5es.pdf) |

---

## 🖥️ Interface Web

O projeto conta com uma interface estática pronta para uso em qualquer navegador.

```
📁 Biblioteca
├── 🌐 index.html       # Página principal da biblioteca (HTML5 + Tailwind CSS + JS)
├── 📖 README.md        # Documentação do repositório
└── 📂 src/             # Diretório contendo os livros em formato PDF
```

---

## 🚀 Como Utilizar

### Opção 1: Abrir diretamente no navegador
Basta dar dois cliques no arquivo [`index.html`](./index.html) ou arrastá-lo para qualquer navegador moderno (Chrome, Edge, Firefox, Brave, Safari).

### Opção 2: Servidor local rápido

Com **Python**:
```bash
# Iniciar servidor na porta 8000
python -m http.server 8000
```
Em seguida, acesse no navegador: `http://localhost:8000`

Com **Node.js / npx**:
```bash
npx serve .
```

Com extensão **Live Server** (VS Code):
> Clique com o botão direito no `index.html` e selecione **"Open with Live Server"**.

---

## 📌 Categorias Temáticas

- ⚙️ **Arquitetura & Hardware**: Funcionamento de processadores, memória e eletrônica digital.
- 🌐 **Redes & Comunicação**: Protocolos, modelos OSI/TCP-IP e infraestrutura.
- 💻 **Sistemas Operacionais**: Estrutura de kernels, processos, memória e threads.
- 🧩 **Algoritmos & Estruturas de Dados**: Técnicas de programação, listas, árvores e grafos.
- 📐 **Matemática & Teoria**: Lógica proposicional e matemática discreta.
- 🛠️ **Engenharia de Software**: Boas práticas, requisitos, arquitetura e testes.
- 🎨 **Design & Experiência**: IHC, usabilidade e experiência do usuário.

---

<div align="center">

Desenvolvido para fins de estudo e disseminação de conhecimento em Ciência da Computação 🚀

</div>