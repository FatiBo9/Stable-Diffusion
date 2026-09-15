---

## 4. Dépôt : `Diffusion stable`

```markdown
# 🎨 Génération & Restylage d'Images - Stable Diffusion

## 📌 Présentation
Projet d'expérimentation et de déploiement de modèles de génération d'images via **Stable Diffusion**. Le système s'appuie sur une interface Gradio permettant la synthèse d'images à partir de textes (*Text-to-Image*) ainsi que le restylage conditionné par des cartes de profondeur (*Depth-to-Image*).

## 🚀 Fonctionnalités
- Génération d'images haute résolution par entrées textuelles (Prompts).
- Restylage artistique d'images guidé par l'estimation de la profondeur.
- Interface Gradio intuitive pour manipuler les paramètres (Seed, Steps, Guidance Scale).
- Notebooks d'expérimentation et benchmark de prompts inclus.

## 🛠️ Technologies & Outils
- **Framework IA :** Hugging Face Diffusers, PyTorch
- **Modèles :** Stable Diffusion (Text2Img & Depth2Img)
- **Interface :** Gradio
- **Environnement :** Python, Jupyter Notebook

## ⚙️ Installation & Lancement

```bash
# 1. Cloner le dépôt
git clone [https://github.com/FatiBo9/Diffusion-stable.git](https://github.com/FatiBo9/Diffusion-stable.git)
cd Diffusion-stable

# 2. Installer les dépendances
pip install -r requirements.txt

# 3. Lancer l'expérimentation via Jupyter Notebook
jupyter notebook SD ASS (1).ipynb