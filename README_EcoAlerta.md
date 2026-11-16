# 🌱 EcoAlerta

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-2C5E3B?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Protótipo_Acadêmico-orange?style=for-the-badge)

Aplicação acadêmica desktop desenvolvida em **Python + Tkinter**. Nesta versão, os dados são persistidos localmente em arquivos `JSON` e as imagens de registro ficam armazenadas no diretório `ecoalerta_dados/evidencias`.

---

## 📋 Requisitos

Antes de rodar o projeto, certifique-se de ter instalado:

* **Python 3.10** ou superior *(o Tkinter normalmente já acompanha a instalação oficial do Python para Windows)*.
* **Visual Studio Code** *(opcional, recomendado para editar e executar o código)*.
* **Bibliotecas externas:** `Pillow` e `cryptography`.

---

## 🚀 Como Executar

1. Baixe o arquivo `ecoalerta.py` para o seu computador.
2. Abra a pasta onde o arquivo foi salvo no **VS Code**.
3. No menu superior, acesse **Terminal > Novo Terminal**.
4. Instale as dependências necessárias executando:
   ```bash
   python -m pip install Pillow cryptography
