# Captcha Number Recognition

## Pré-processamento, Extração de Características e Classificação de Números.
![Badge](https://img.shields.io/badge/Octave-v%206.1.1-lightgrey)

<!-- Table of Contents -->
<details open="open">
  <summary>Sumário</summary>
  <ol>
    <li><a href="#sobre">Sobre</a></li>
    <li><a href="#status-do-projeto">Status do Projeto</a></li>
    <li><a href="#modelo">Modelo</a></li>
    <li><a href="#arquivos">Arquivos</a></li>
    <li><a href="#testes">Testes</a></li>
    <li><a href="#tecnologias">Tecnologias</a></li>
  </ol>
</details>

# Sobre
Na etapa de pré-processamento, os dados de entrada passam por diversos métodos que realizam operações como remoção de ruído, segmentação e melhoria da qualidade. Na extração de características, o objetivo é representar os dados de entrada em medidas quantificáveis utilizáveis na etapa de classificação.

# Status do Projeto
<h4 align="center"> 
	🚧 ...  Concluído ✅
</h4>

### Funcionalidades

- [x] Construção do modelo
- [x] Extração de Momentos de HU
- [x] Treino e teste
- [x] Aprendizagem
- [x] Taxa de acerto
- [x] Matriz de confusão
- [x] Teste do classificador

# Modelo
1. Para cada imagem de números fornecida, foram geradas 19 imagens adicionais com diferentes graus de rotação.
2. Cada imagem rotacionada foi escalada em sete proporções diferentes: 0.5, 0.75, 1, 1.25, 1.5, 1.75 e 2.
3. Em cada imagem escalada, foi inserido ruído do tipo sal e pimenta com os seguintes valores: 0, 0.01, 0.02, 0.03 e 0.04.

# Arquivos
Os arquivos estão localizados na pasta "numbers" dentro do diretório do projeto. Foram utilizadas 10 imagens, uma para cada caractere numérico. 
Segue uma visualização:

# Testes

# Tecnologias
