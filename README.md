<h1 align="center">📊 Sistema de Gerenciamento de Registros em C</h1>
<p align="center">
  Sistema de gerenciamento de registros desenvolvido em C, com operações CRUD,
  persistência em arquivos e conceitos básicos de segurança de dados.
</p>
<p align="center">
  <img src="https://img.shields.io/badge/linguagem-C-blue?style=for-the-badge&logo=c">
  <img src="https://img.shields.io/badge/status-concluído-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/plataforma-console-lightgrey?style=for-the-badge">
  <img src="https://img.shields.io/badge/foco-CRUD%20%26%20arquivos-orange?style=for-the-badge">
</p>
<hr>
<h2>🚀 Sobre o Projeto</h2>
<p>
Este é um sistema via terminal para gerenciar dados estruturados em arquivos binários,
feito para a disciplina de Algoritmos 2. Ele cobre as operações de <strong>CRUD</strong>,
além de exclusão lógica, exclusão física e uma camada simples de criptografia de arquivos.
</p>
<hr>
<h2>🧠 Funcionalidades</h2>
<ul>
  <li>➕ Criar novos registros</li>
  <li>📋 Listar registros ativos</li>
  <li>✏️ Atualizar registros existentes</li>
  <li>❌ Exclusão lógica (soft delete)</li>
  <li>🗑️ Exclusão física (remoção permanente)</li>
  <li>🔍 Buscar por ID</li>
  <li>🔎 Buscar por nome</li>
  <li>💾 Armazenamento em arquivo binário</li>
  <li>🔐 Sistema simples de criptografia de arquivos (baseado em XOR)</li>
  <li>📖 Sistema de ajuda interno com criptografia</li>
</ul>
<hr>
<h2>🛠️ Tecnologias Utilizadas</h2>
<ul>
  <li><strong>C</strong></li>
  <li>Biblioteca padrão (stdio, stdlib, string, ctype)</li>
  <li>Manipulação de arquivos binários (fread, fwrite, fseek)</li>
  <li>Modelagem de dados com structs</li>
  <li>Interação via terminal</li>
</ul>
<hr>
<h2>📂 Estrutura do Projeto</h2>
<pre>
c-record-management-system/
│── sistemaregistro.cpp
│── README.md
</pre>
<hr>
<h2>⚙️ Como Executar</h2>
<pre>
# Compilar
gcc sistemaregistro.cpp -o record-system
# Executar
./record-system
</pre>
<hr>
<h2>🎯 Objetivos de Aprendizado</h2>
<p>
Este projeto foi feito para praticar:
</p>
<ul>
  <li>Desenvolvimento de sistemas CRUD</li>
  <li>Manipulação de arquivos binários</li>
  <li>Persistência de dados sem uso de banco de dados</li>
  <li>Controle de memória e ponteiros de arquivo</li>
  <li>Conceitos básicos de segurança de dados</li>
</ul>
<hr>
<h2>👨‍💻 Autor</h2>
<p align="center">
  Desenvolvido por <strong>Daniel Augusto Silva</strong><br>
</p>
