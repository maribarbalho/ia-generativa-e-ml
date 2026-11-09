# IA Generativa e Machine Learning

Projetos do curso **Programação de IA Generativa (Senai)** e estudos de machine learning com Python: modelos de regressão, geração de imagens e texto e classificação de notícias.

| Projeto | O que faz | Ferramentas |
|---|---|---|
| [01 · Preço de casas](01-regressao-preco-de-casas) | Regressão linear que estima o preço de um imóvel pela área e pelo número de quartos | scikit-learn, Pandas, Matplotlib |
| [02 · Consumo de combustível](02-regressao-consumo-de-combustivel) | Regressão linear que estima o consumo (km/L) pelo peso, pela potência e pelos cilindros do carro | scikit-learn, Pandas, Matplotlib |
| [03 · Gerador de imagens](03-gerador-de-imagens) | Gera imagens a partir de um texto com Stable Diffusion | Diffusers, PyTorch, Hugging Face |
| [04 · Gerador de texto](04-gerador-de-texto) | Continua um texto em português com um modelo GPT-2 treinado em português | Transformers, Hugging Face |
| [05 · Detector de fake news](05-detector-de-fake-news) | Ajusta um modelo BERT para classificar declarações da base LIAR quanto à veracidade | Transformers, Datasets, scikit-learn |

## Observações

- Os notebooks foram executados no Google Colab. Os projetos 03 a 05 precisam de GPU para rodar em tempo razoável.
- No projeto 03, o token do Hugging Face não fica no código: ele é solicitado na execução.
- O projeto 05 traz a estrutura de treino e avaliação; as métricas finais não ficaram registradas no notebook.
- Base do projeto 05: [LIAR (Hugging Face)](https://huggingface.co/datasets/liar).
