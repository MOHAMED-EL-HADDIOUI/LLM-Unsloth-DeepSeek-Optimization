# LLM-Unsloth-DeepSeek-Optimization

## Description
Ce projet implémente un pipeline complet pour le fine-tuning du modèle DeepSeek-R1-Distill-Llama-8B en utilisant la technique LoRA (Low-Rank Adaptation) via la bibliothèque Unsloth. Le modèle fine-tuné est ensuite converti au format GGUF et déployé localement avec Ollama pour une inférence efficace.

## Fonctionnalités
- Fine-tuning efficace avec la quantification 4-bit et LoRA
- Préparation de données à partir du dataset Alpaca-GPT4
- Conversion du modèle au format GGUF
- Déploiement local avec Ollama
- Interface simple pour l'inférence

## Prérequis
- Python 3.8+
- PyTorch
- GPU avec CUDA (recommandé)
- 16+ GB de RAM

## Utilisation
Exécutez le notebook Jupyter ou le script Python pour:
1. Charger et préparer le modèle DeepSeek
2. Configurer et exécuter le fine-tuning
3. Exporter le modèle au format GGUF
4. Déployer et tester avec Ollama

## Cas d'utilisation
- Personnalisation de modèles LLM pour des domaines spécifiques
- Déploiement local de LLMs pour des applications nécessitant une faible latence
- Expérimentation avec différentes configurations de fine-tuning
