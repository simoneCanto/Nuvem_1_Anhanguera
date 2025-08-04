# Nuvem_1_Anhanguera

# 🖥️ Introdução à Computação em Nuvem – Atividade Prática

Este repositório contém os arquivos gerados durante a **primeira atividade prática** da disciplina **Computação em Nuvem**, utilizando o **Google Cloud Shell** e o **GitHub**.

A proposta é demonstrar, de forma simples e prática, que é possível **criar, manipular e armazenar arquivos diretamente na nuvem**, sem instalar nenhum software no computador local.

---

## 📚 Objetivos da Atividade
- Apresentar o **Google Cloud Shell** como ferramenta prática de acesso à nuvem.
- Criar e manipular arquivos de texto na nuvem.
- Entender a diferença entre sobrescrever (`>`) e acrescentar (`>>`) conteúdo em arquivos.
- Salvar o **histórico de comandos** executados.
- Realizar o download de arquivos do Cloud Shell.
- Publicar arquivos no GitHub como forma de versionamento e portfólio.

---

## 🚀 Passo a Passo Realizado

### 1️⃣ Acessando o Google Cloud Shell
1. Entrar no **[Google Cloud Console](https://console.cloud.google.com)**.
2. Clicar no ícone do **Cloud Shell** (terminal) no canto superior direito.
3. Aguardar o provisionamento da máquina virtual.

---

### 2️⃣ Criando o arquivo `mensagem.txt`
```bash
echo "Meu primeiro comando na nuvem" > mensagem.txt

-O comando echo imprime texto.

-O operador > cria ou sobrescreve um arquivo.

-O arquivo foi salvo diretamente na máquina virtual da nuvem.

3️⃣ Adicionando novas linhas
bash
Copiar
Editar
echo "Adicionando uma segunda linha no arquivo" >> mensagem.txt
echo "Feito pelo Cloud Shell" >> mensagem.txt
O operador >> acrescenta texto ao final do arquivo, sem apagar o conteúdo anterior.

4️⃣ Visualizando o conteúdo do arquivo
bash
Copiar
Editar
cat mensagem.txt
Mostra o conteúdo do arquivo no terminal.

5️⃣ Registrando o histórico de comandos
bash
Copiar
Editar
history > comandos.txt
Salva no arquivo comandos.txt todos os comandos executados na sessão atual.

Pode ser editado com:

bash
Copiar
Editar
nano comandos.txt
6️⃣ Download dos arquivos
No Cloud Shell, clicar nos três pontos (⋮) do canto superior direito.

Selecionar Download file.

Digitar o nome do arquivo (mensagem.txt ou comandos.txt).

Os arquivos são baixados para o computador local.

7️⃣ Upload para o GitHub
Criar um repositório no GitHub chamado computacao-nuvem.

Clicar em Add file → Upload files.

Selecionar os arquivos mensagem.txt e comandos.txt.

Clicar em Commit changes.

📂 Arquivos deste Repositório
mensagem.txt → Arquivo criado e manipulado no Google Cloud Shell.

comandos.txt → Histórico de todos os comandos executados durante a prática.

📌 Conceitos Praticados
-Computação em Nuvem: uso de recursos computacionais via internet.

-Google Cloud Shell: terminal remoto que roda em uma máquina virtual no Google Cloud.

-Manipulação de arquivos via terminal.

-Infraestrutura como Serviço (IaaS): uso de máquina virtual provisionada pelo provedor de nuvem.

-Versionamento com GitHub para portfólio acadêmico e profissional.


 📌Quando você criou o mensagem.txt no Google Cloud Shell, ele foi criado e armazenado diretamente em uma máquina virtual do Google Cloud, ou seja, na nuvem, não no seu computador.

🔍 Como isso funciona

-Ao abrir o Cloud Shell, o Google provisiona (cria automaticamente) uma máquina virtual Linux para você.

-Essa VM está rodando dentro da infraestrutura do Google, em um data center.

Quando você executou:

bash
Copiar
Editar

echo "Meu primeiro comando na nuvem" > mensagem.txt

o arquivo foi salvo no sistema de arquivos dessa VM remota.

Você só visualizou e manipulou o arquivo pelo terminal, mas ele não existia no seu computador até você fazer o download.

💡 Por isso, essa atividade já é um exemplo prático de IaaS (Infraestrutura como Serviço):

-O Google fornece uma máquina virtual.

-Você cria e gerencia arquivos/programas nela.

-Não precisou instalar nada localmente.




✍️ Autora
Simone Tatiane do Canto – Professora de Computação em Nuvem
📧 Contato: simone.canto@cogna.com.br
