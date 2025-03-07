[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/CmlLib/CmlLib.Core/blob/master/LICENSE)
[![C#](https://custom-icon-badges.demolab.com/badge/C%23-%23239120.svg?logo=cshrp&logoColor=white)](#)

# BR-TOOLS  

O BR Tool é um software de código aberto desenvolvido em C#, projetado para modificar e adicionar jogos na Steam.  

---

# BR-TOOLS  

The BR Tool is an open-source software developed in C#, designed to modify and add games on Steam.




[![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?&logo=discord&logoColor=white)](https://discord.gg/w62NZ8WVsP)



**Registry and Installation Path of BR Tools**

BR Tools determines the Steam installation directory by checking the Windows registry. It accesses the following registry key to retrieve the correct installation path:

```
HKEY_LOCAL_MACHINE\SOFTWARE\Valve\Steam
```

**File Structure and Functionalities**

The tool follows a structured organization:

- **brtools.exe**: Main executable responsible for managing the tool’s operations.
- **/HID.DLL**: Injector placed in the Steam directory.
- **stplug-in/**: Directory containing compiled files with the `.st` extension.
- **depotcache/**: Folder where `.manifest` files are stored.

**Lua Script Compiler (LUAPACKER)**

The `luapacker.exe` utility compiles `.lua` scripts into a binary or encrypted `.st` format.

**Future Enhancements**

- Additional functionalities will be implemented in future updates.



---




**Registro e Local de Instalação do BR Tools**  

O BR Tools determina o diretório de instalação do Steam verificando o registro do Windows. Ele acessa a seguinte chave do registro para obter o caminho correto da instalação:  

```
HKEY_LOCAL_MACHINE\SOFTWARE\Valve\Steam
```

**Estrutura de Arquivos e Funcionalidades**  

A ferramenta segue uma organização estruturada:  

- **brtools.exe**: Executável principal responsável por gerenciar as operações da ferramenta.  
- **/HID.DLL**: Injetor colocado no diretório do Steam.  
- **stplug-in/**: Diretório contendo arquivos compilados com extensão `.st`.  
- **depotcache/**: Pasta onde os arquivos `.manifest` são armazenados.  

**Compilador de Scripts Lua (LUAPACKER)**  

O utilitário `luapacker.exe` compila scripts `.lua` em um formato binário ou criptografado `.st`.  

**Melhorias Futuras**  

- Funcionalidades adicionais serão implementadas em futuras atualizações.  

---







Woks on

- [![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white)](#)

Funciona em 

- [![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white)](#)
