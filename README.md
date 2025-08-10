# Il2CppDumper

[![Release](https://img.shields.io/github/v/release/Litch666/Il2cppDumper)](https://github.com/Litch666/Il2cppDumper/releases)
[![Issues](https://img.shields.io/github/issues/Litch666/Il2cppDumper)](https://github.com/Litch666/Il2cppDumper/issues)
[![License](https://img.shields.io/github/license/Litch666/Il2cppDumper)](https://github.com/Litch666/Il2cppDumper/blob/master/LICENSE)

SDK Generator para jogos Unity.

---

## Sobre Unity3D e Il2Cpp

<p align="center">
  <img src="https://pt.m.wikipedia.org/wiki/Ficheiro:Unity_2021.svg" alt="Unity Logo" width="120" style="margin-right: 20px;">
  <img src="https://raw.githubusercontent.com/KhronosGroup/SPIRV-Tools/master/images/spirv-logo.png" alt="Il2Cpp Logo" width="120" />
</p>

*Unity3D é uma das engines mais usadas para desenvolvimento de jogos.*  
*Il2Cpp é a tecnologia da Unity para converter C# em código nativo para melhor desempenho.*

---

## Versões Compatíveis da global-metadata.dat
- 5.6.4 ~ 2021.3.1

## Como usar  
- Baixe a versão mais recente.  
- Para usuários do MT Manager:  
  - Utilize os arquivos `libil2cpp.so` e `global-metadata.dat`.  

- Mova os arquivos `dumper.so` e `dumper.sh` para o diretório `/data/user/0/bin.mt.plus/`.  
- Toque no arquivo `dumper.sh` e pressione "EXECUTE".  
- Aguarde alguns segundos até o processo ser concluído.  

- O executavel registra todas as falhas e erros em um arquivo gerado em `/data/user/0/bin.mt.plus/home/Documents/dumper.log`.

## Problemas  
Se você encontrar problemas usando o Dumper, por favor, crie uma issue neste repositório e descreva o problema:  
**[Issues](https://github.com/Litch666/Il2cppDumper/issues)**  

- Se o jogo travar durante o dump, experimente usar outra versão do Dumper.  
- Caso o jogo trave durante o dump, vá até o diretório do jogo e abra a pasta `dumper`, que contém o arquivo `dumper.log`. Tente identificar as falhas e erros por lá.

## Créditos  
- Luis

**Após o lançamento, este projeto será descontinuado!**

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

