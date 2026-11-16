# 🌲FlorestEye

Sistema Inteligente de Cadastro de Denúncias Ambientais.

## Integrantes do grupo
Os integrantes que compõe esse projeto são:
- Beatriz Gabrielle
- Fábio Henrique
- Glaydson Sanches
- Guilherme Nascimento
- Lucas Brito
- Murillo Eltz

## Instituição e disciplina
O projeto faz parte da disciplina de Projeto e Desenvolvimento II - Sistemas de Informação, na Universidade Paulista (UNIP)

## Sobre o projeto

O FlorestEye foi desenvolvido para facilitar o registro e o acompanhamento de ocorrências ambientais. Em um canal simples para comunicar casos como desmatamento, poluição e descarte irregular de resíduos, informações importantes podem deixar de chegar a quem pode analisá-las.

O sistema permite registrar denúncias ambientais com local, data, descrição e imagem. Cada denúncia recebe um status para que o usuário acompanhe seu andamento, enquanto administradores podem consultar e atualizar os registros.

## Objetivo
Criação de um Sistema de monitoramento e fiscalização de áreas ambientais, com foco no registro de ocorrência relacionadas às queimadas e ao desmatamento. O sistema dará fácil acesso para pessoas que desejam contribuir para a monitoramento em áreas ambientais.

## Funcionalidades

- Cadastro de usuários e acesso por e-mail e senha.
- Registro de denúncias com local, data da ocorrência, descrição e imagem.
- Consulta das próprias denúncias e de seus status.
- Painel administrativo para consultar denúncias, filtrar por status ou data e atualizar o status.
- Armazenamento de senhas com hash e criptografia de alguns dados das denúncias.

## Instalação e execução

É necessário ter o Python instalado. No terminal, na pasta do projeto:

1. Crie e ative um ambiente virtual:

   **Windows (PowerShell):**

   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

   **Linux/macOS:**

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

2. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

3. Inicie a aplicação:

   ```bash
   streamlit run app.py
   ```

4. Acesse o endereço local exibido no terminal pelo Streamlit.

## Principais telas 
Principais telas que compõe o sistema são:

<p align="left">
  <img src="fotos projeto/foto4.jpeg" width="1200">
</p>

<p align="left">
  <img src="fotos projeto/foto1.jpeg" width="1200">
</p>

<p align="left">
  <img src="fotos projeto/foto3.jpeg" width="1200">
</p>

<p align="left">
  <img src="fotos projeto/foto2.jpeg" width="1200">
</p>