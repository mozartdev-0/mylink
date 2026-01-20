# 🔗 MyLink | Workspace Inteligente

O **MyLink** é uma plataforma de workspace inteligente projetada para desenvolvedores e criadores. Ele combina uma interface de chat assistida por IA (Gemini/OpenAI) com um ambiente de visualização em tempo real (Canvas), permitindo gerar, editar e visualizar interfaces HTML/Tailwind instantaneamente.

![MyLink Preview](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## ✨ Funcionalidades

* **🤖 Multi-Engine AI:** Suporte integrado para Gemini 2.0 Flash e GPT-4o.
* **🎨 Live Preview:** Visualize o código gerado em tempo real com suporte a modo Desktop, Tablet e Mobile.
* **🔐 Autenticação Nativa:** Sistema de login e cadastro gerenciado via Appwrite.
* **💾 Histórico & Backup:** Salve suas conversas e projetos localmente ou na nuvem (Appwrite Databases).
* **🌓 Dark Mode:** Interface adaptativa para maior conforto visual.
* **🌐 Internacionalização:** Suporte total para Português (PT), Inglês (EN) e Espanhol (ES).

## 🚀 Tecnologias Utilizadas

* **Frontend:** HTML5, Tailwind CSS, FontAwesome.
* **Backend as a Service (BaaS):** [Appwrite](https://appwrite.io/) (Auth & Database).
* **AI SDKs:** Integração direta com Google AI e OpenAI.
* **Fonts:** Inter & Fira Code.

## 🛠️ Como Executar o Projeto

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/seu-usuario/mylink.git](https://github.com/seu-usuario/mylink.git)
    ```
2.  Abra o arquivo `index.html` em seu navegador ou use uma extensão como o *Live Server*.
3.  No aplicativo, clique no ícone de engrenagem (Configurações) e insira suas chaves de API do Gemini ou OpenAI.

## ⚙️ Configuração do Appwrite

Para habilitar a persistência de dados, configure um projeto no Appwrite com:
* **Endpoint:** `https://nyc.cloud.appwrite.io/v1`
* **Project ID:** `696bf27100194d72c011`
* **Database ID:** `696bf9420003fad299e2`
* **Collection ID:** `backups`

## 🤝 Contribuição

Desenvolvido por **mozart_dev**. Sinta-se à vontade para abrir uma *Issue* ou enviar um *Pull Request*.

---
By [Mozart_Dev](https://github.com/mozartdev-0)
