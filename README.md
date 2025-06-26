Claro! Aqui está o conteúdo completo já formatado como um arquivo `.md` — pronto para colar direto no seu `README.md`:

---

````markdown
# 🖥️ Guia Interativo do CMD, PowerShell e outros Terminais

> Um repositório criado para tornar o **terminal menos assustador** e mais divertido!  
> Aqui você encontra comandos, scripts `.bat`, comparações entre CLIs e muito mais — com imagens, gifs e exemplos ilustrados 🧠💡

---

## 📌 Comandos Essenciais do CMD

| Comando | Descrição |
|--------|------------|
| `dir` | 📄 Lista arquivos e pastas |
| `mkdir` | 📁 Cria diretório |
| `cd` | ↔️ Navega entre pastas |
| `tree` | 🌳 Estrutura de arquivos |
| `type` | 📖 Lê conteúdo de arquivos |
| `copy`, `move`, `rename` | 🛠️ Manipulação de arquivos |
| `cls` | 🧼 Limpa tela |
| `systeminfo`, `date` | 🧾 Informações do sistema |
| `shutdown`, `exit` | ❌ Desliga ou fecha terminal |


🖼️ **Veja isso visualmente:**  
![CMD Comandos](./img/cmd-comandos.png)

---

## 🧪 Scripts `.BAT`

Scripts `.bat` automatizam tarefas no Windows:

```bat
@echo off
set nome=Visitante
echo Olá %nome%!
```

💡 *Dica:* Use `IF %ERRORLEVEL% NEQ 0` para tratar erros!

---

## 🔧 Variáveis e Interação no CMD

```bat
set /p usuario=Digite seu nome: 
echo Bem-vindo(a), %usuario%!
```

🎥 Exemplo em ação:
![Variáveis em .BAT](https://media.giphy.com/media/3o6Mbbs879ozZ9Yic0/giphy.gif)

---

## 📦 Winget – O gerenciador de pacotes do Windows

```bash
winget install -e --id <pacote>
winget --info
```

📌 *Disponível no Windows 10+*

---

## 🍫 Chocolatey via PowerShell

### 🛠 Instalação:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force;
iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

### Exemplos úteis:

* 📥 Instalar: `choco install nodejs`
* 📋 Ver lista: `choco list`
* ❌ Remover: `choco uninstall <nome>`

---

## ⚖️ Comparativo entre Terminais

| Terminal          | Sistema         | Vantagens                    |
| ----------------- | --------------- | ---------------------------- |
| 🐧 **Bash**       | Linux/macOS     | Scripts leves, automação     |
| 🪟 **CMD**        | Windows         | Legado, simples              |
| ⚡ **PowerShell**  | Win/Linux/macOS | Baseado em objetos, poderoso |
| 🐘 **Zsh**        | Linux/macOS     | Customizável                 |
| 🌍 **Fish**       | Linux/macOS     | Interface moderna            |
| 🐍 **Python CLI** | Multiplataforma | Scripts avançados            |

---

## 🧰 Ferramentas que facilitam sua vida

| Nome               | Descrição                                       |
| ------------------ | ----------------------------------------------- |
| `CMDer`            | Terminal mais bonito e completo                 |
| `Windows Terminal` | Terminal com múltiplas abas (oficial Microsoft) |
| `WSL`              | Roda Linux dentro do Windows                    |
| `apt` + `sudo`     | Pacotes e permissões no WSL                     |

---

## 📸 Galeria

| Visualização                                  | Descrição                  |
| --------------------------------------------- | -------------------------- |
| ![Variáveis](./img/variaveis.png)             | Criando variáveis no CMD   |
| ![Winget](./img/winget.png)                   | Instalando com winget      |
| ![CLI comparativo](./img/cli-comparativo.png) | Comparação entre terminais |

---

## 🧠 Contribua!

Se você curte terminal, automação ou design técnico — contribua com melhorias, correções ou novas artes!

---

## 🌟 Curtiu?

⭐ Dê uma estrela nesse repositório se esse conteúdo te ajudou!
📣 Compartilhe com seus amigos que querem aprender CMD e automações!

---

> Feito com carinho por [@cssbreno](https://github.com/cssbreno)

```