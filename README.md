# 💬 All-ChatLLM

> **Um playground de conversação focado em produtividade, que consome seus endpoints locais para oferecer uma interface de chat intuitiva, com histórico persistente, ferramentas de exportação de documentos e suporte a múltiplos modelos de IA em uma única tela.**

---

## 📝 Descrição do Projeto

O **All-Chat-LLM** é uma interface gráfica de Playground inspirada na experiência de chat da OpenAI, feita exclusivamente para atuar como cliente. Ele interage diretamente com o seu roteador local ou qualquer API compatível, oferecendo uma experiência de uso fluida e multilíngue (Português e Inglês).

O aplicativo conta com uma barra lateral retrátil para gerenciamento completo e persistente de sessões anteriores. Na área de interação central, o usuário pode selecionar o provedor e o modelo desejado através de droplists dinâmicos, enviar prompts textuais, anexar documentos de referência e contar com ferramentas instantâneas para copiar as respostas da IA ou exportá-las com formatação rica para arquivos `.md`, `.pdf` e `.txt`.

---

## 🛠️ Tecnologias Utilizadas

O projeto foca em uma interface responsiva, desacoplada e rica em utilitários de produtividade:

* **Gerenciamento:** Configurado e isolado utilizando **uv** para resolução imediata de dependências.
* **Interface Gráfica (GUI):** Construída de forma nativa em **PyQt6**, garantindo janelas, menus laterais deslizantes e diálogos de salvamento integrados ao Windows de forma fluida.
* **Comunicação e Serviços:** Implementado com o cliente oficial da **OpenAI** (apontado para o localhost) para o motor de chat, **fpdf2** para geração robusta de PDFs e o módulo **markdown** para tratamento de texto.
* **Persistência:** Histórico de conversas gerenciado localmente via banco de dados leve **SQLite**.

---

## 🚀 Como Executar o App Localmente

Por ser uma aplicação focada na experiência local, ela pode ser instalada diretamente no seu computador para uso imediato. Baixe a versão correspondente ao seu sistema operacional através dos links oficiais abaixo:

Windows: 📥 Baixar executável para Windows (x64)

Linux: 📥 Baixar binário para Linux (x64)

Após o download, basta executar o arquivo para iniciar o aplicativo.

---
<p align="center">Developed by <b>Ldov - AI & IT Solutions</b> </p>
