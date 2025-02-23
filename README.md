# transformar-uma-imagem-colorida-em-n-veis-de-cinza

---

# Conversão de Imagens Coloridas para Níveis de Cinza e Binarizadas

Este projeto demonstra como converter uma imagem colorida para níveis de cinza (escala de cinza) e para uma imagem binarizada (preto e branco) usando a biblioteca OpenCV em Python.

## Visão Geral

O objetivo deste projeto é processar imagens coloridas, transformando-as em:
1. **Imagem em Níveis de Cinza**: Uma imagem onde cada pixel tem um valor entre 0 (preto) e 255 (branco), representando diferentes tons de cinza.
2. **Imagem Binarizada**: Uma imagem onde cada pixel é apenas preto (0) ou branco (255), com base em um limiar (threshold).

## Requisitos

Para executar este projeto, você precisará das seguintes bibliotecas Python:

- OpenCV (`opencv-python`)
- Matplotlib (`matplotlib`)

Você pode instalar as dependências usando o seguinte comando:

```bash
pip install opencv-python-headless matplotlib
```

## Estrutura do Projeto

O projeto consiste em um único script Python que realiza as seguintes etapas:

1. **Carregar a Imagem Colorida**: A imagem é carregada usando o OpenCV.
2. **Converter para Níveis de Cinza**: A imagem colorida é convertida para tons de cinza.
3. **Binarizar a Imagem**: A imagem em tons de cinza é binarizada (transformada em preto e branco) usando um limiar.
4. **Exibir as Imagens**: As imagens original, em tons de cinza e binarizada são exibidas lado a lado usando Matplotlib.

## Como Executar

1. Clone o repositório (se aplicável) ou baixe o script Python.

2. Coloque uma imagem colorida no diretório do projeto ou atualize o caminho da imagem no script.

3. Execute o script Python:

   ```bash
   python converter_imagem.py
   ```

4. O script exibirá três imagens:
   - **Imagem Original**: A imagem colorida carregada.
   - **Imagem em Níveis de Cinza**: A imagem convertida para tons de cinza.
   - **Imagem Binarizada**: A imagem binarizada (preto e branco).


## Resultados Esperados

- **Imagem Original**: A imagem colorida carregada.
- **Imagem em Níveis de Cinza**: A imagem convertida para tons de cinza, com valores de pixel entre 0 e 255.
- **Imagem Binarizada**: A imagem transformada em preto e branco, com pixels apenas 0 (preto) ou 255 (branco).


## Referências

- [Documentação do OpenCV](https://docs.opencv.org/)
- [Documentação do Matplotlib](https://matplotlib.org/stable/contents.html)

---

### Como Usar o README.md

1. Crie um arquivo chamado `README.md` no diretório do seu projeto.
2. Copie e cole o conteúdo acima no arquivo.
3. Personalize o conteúdo conforme necessário (por exemplo, adicionando instruções específicas para o seu ambiente).

