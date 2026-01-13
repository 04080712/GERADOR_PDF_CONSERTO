# 🧾 Gerador de PDF com Interface Gráfica (Python)

## 📌 Objetivo do Projeto

Desenvolver um **aplicativo executável em Python** que permita ao usuário **inserir dados e imagens por meio de uma interface gráfica**, e a partir dessas informações **gerar automaticamente arquivos PDF padronizados**, salvos em uma estrutura organizada de pastas no sistema.

O projeto tem como foco:
- Facilidade de uso para usuários não técnicos
- Padronização visual dos PDFs
- Automação do processo de geração de documentos
- Possibilidade de evolução para uso corporativo

---

## 👤 História do Usuário:

> quero utilizar uma interface gráfica simples para inserir textos e imagens,  
> para que eu possa gerar automaticamente um arquivo PDF profissional  
> sem precisar editar documentos manualmente.
---

## 🧠 Visão Geral da Solução

O sistema é composto por três camadas principais:

1. **Interface Gráfica (Tkinter)**  
   Responsável pela interação com o usuário, coleta de dados e seleção de imagens.

2. **Camada de Lógica e Processamento**  
   Responsável por validar os dados, organizar as informações e preparar o conteúdo do PDF.

3. **Geração de PDF**  
   Utiliza templates HTML + CSS para gerar PDFs com layout profissional por meio de uma biblioteca de renderização.

---

## 🧰 Tecnologias Utilizadas

- **Python 3**
- **Tkinter + TTK** – Interface gráfica
- **Jinja2** – Template engine para HTML
- **WeasyPrint** – Geração de PDF a partir de HTML
- **PyInstaller** – Criação do executável (.exe)

---

