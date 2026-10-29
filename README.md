# Projeto 2 — Computação Visual: Seam Carving

**Opção 2 — Tutorial de teoria e prática**

Integrantes: **Beatriz Aparecida de Mello Barbosa (RA 10354067)** e **Henrique Jeam Ferreira Lima (RA 10277156)**.

## Arquivos

- `Tutorial_Seam_Carving.ipynb`: tutorial principal com teoria, implementação, testes, experimentos e referências. **Este é o arquivo da entrega da Opção 2**.
- `imagens/`: arquivos de exemplo distribuídos para funcionamento offline.
- `resultados/`: figuras exportadas automaticamente ao executar o notebook.
- `ROTEIRO_VIDEO_ATE_5_MIN.md`: roteiro de apresentação do projeto (para gravar vídeo exigido pelo enunciado).
- `requirements.txt`: bibliotecas Python usadas no notebook.

## Como executar em computador

1. Descompacte o ZIP, preservando a estrutura de pastas.
2. Abra um terminal **dentro** da pasta `Projeto2_SeamCarving`.
3. Com Python 3 instalado, execute `python -m pip install -r requirements.txt`.
4. Abra `Tutorial_Seam_Carving.ipynb` no Jupyter Notebook, JupyterLab ou VS Code com suporte a notebooks.
5. Execute **Run All / Executar todas**, de cima para baixo.

Para instalar o Jupyter, se necessário: `python -m pip install notebook` e depois `jupyter notebook`.

O tutorial contém os resultados de execução, que podem ser visualizados mesmo antes de rodar o código. Para reexecutá-lo, o diretório de trabalho deve ser a pasta que contém o notebook e a subpasta `imagens/`.

## Como executar no Google Colab

1. Envie o arquivo ZIP para a sessão do Colab (painel de arquivos ou `files.upload()`).
2. Extraia o ZIP com `!unzip -q Projeto2_SeamCarving.zip -d /content`.
3. Abra o notebook do projeto no Colab, ou carregue-o via menu Arquivo, e defina o diretório com `%cd /content/Projeto2_SeamCarving` antes de executar as demais células.

A versão mais simples e confiável é executar localmente, na estrutura original de pastas.

## Restrições e créditos

O exemplo implementa redução de dimensões; não faz ampliação. Fotos de foguete e astronauta provenientes de `skimage.data` (SpaceX / NASA), em domínio público. Fontes bibliográficas detalhadas no fim do notebook.

## Orientação para entrega

O enunciado da **Opção 2** prevê a entrega do notebook Jupyter **ou** link público do tutorial, mais um vídeo de até cinco minutos resumindo o projeto. Publicar notebook, imagens e vídeo com acesso para toda a turma. O ZIP aqui é uma conveniência; o arquivo de entrega principal é o `.ipynb` e o link para o vídeo deve ser acrescentado pelo grupo após a gravação.
