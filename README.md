# Detecção de Câncer Bucal por Imagem

Projeto de classificação automática de lesões orais usando ResNet50 com transfer learning. Classifica imagens da cavidade oral em 4 categorias: Healthy, Benign, OPMD e OCA (carcinoma oral).

**Disciplina:** Técnicas Computacionais de Apoio ao Diagnóstico - Informática Biomédica (UFCSPA)  
**Autora:** Rafaela Laura Ribeiro

## Resultados

- Acurácia no teste: 75,97%
- Dataset: 3.000 imagens (privado/restrito)
- F1-score: Healthy (0,89), OPMD (0,76), Benign (0,67), OCA (0,48)

## Como Rodar

```bash
# Instale as dependências
pip install -r requirements.txt

# Inicie o Jupyter Notebook
jupyter notebook
```

## Requisitos

- Python 3.9 - 3.12
- TensorFlow >= 2.13.0
- NumPy < 2.0.0
- GPU (opcional, mas recomendado)

Ver `requirements.txt` para lista completa.