# ZED SDK - SVO to PNG Export 🔧🌐

Este repositório fornece um script Python para exportar quadros de um arquivo SVO (Stereo Video Object) gerado com o ZED SDK para imagens no formato PNG. 🎥🖼

## Requisitos ✅

1. **Python 3.9** 🔢
   - Certifique-se de que a versão 3.9 do Python está instalada.

2. **ZED SDK** 🚀
   - Instale o ZED SDK a partir do site oficial:
     [https://www.stereolabs.com/en-br/developers/release](https://www.stereolabs.com/en-br/developers/release)

3. **PyZED** 🔗
   - Configure o PyZED de acordo com as instruções na documentação oficial:
     [https://www.stereolabs.com/docs/app-development/python/install](https://www.stereolabs.com/docs/app-development/python/install)

4. **Ambiente Conda** 🌍
   - Crie um ambiente Conda para gerenciar as dependências do projeto:
     ```bash
     conda create --name export python=3.9
     conda activate export
     ```

## Instalação e Configuração 🔧

1. Clone este repositório ou copie o arquivo principal. 🔄
2. Certifique-se de que o arquivo SVO que deseja processar esteja no mesmo diretório ou especifique o caminho no script. 🔐
3. Altere o nome do arquivo SVO e o diretório de saída no script conforme necessário:
   ```python
   input_svo = "teste.svo"
   output_folder = "output_frames"
   max_frames = 100  # Número máximo de quadros a exportar
   ```

## Execução do Script 🔄⚡

1. Execute o script com o Python:
   ```bash
   python script.py
   ```

2. O script irá processar o arquivo SVO e salvar os quadros no diretório especificado (`output_frames`). 🔑🖼

## Funcionalidades do Script ✨

- Exporta quadros de arquivos SVO para imagens PNG. 🖼
- Possibilita configurar o número máximo de frames a serem exportados. ➡️🔢
- Verifica automaticamente se o diretório de saída existe e o cria, caso necessário. 🏢

## Suporte ❓

Se encontrar problemas ou tiver dúvidas, consulte a documentação oficial do ZED SDK ou entre em contato pelo sistema de issues deste repositório. ✨🛠

