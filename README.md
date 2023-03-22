# xerrada-IA-generativa
Xerrada sobre IA Generativa - ChatGPT | StableDiffusion

[Tecnoateneu Vilablareix](https://www.tecnoateneu.cat/) - 22 Març 2023

## Presentació

* PDF amb els slides de la xerrada: [slides_ia_generativa_tecnoateneu.pdf](slides_ia_generativa_tecnoateneu.pdf)

## Demo - Text-to-Text - ChatGPT

* [Codi per extendre ChatGPT amb Langchain](chatGPT_langchain.ipynb)

Instruccions per executar-ho en l'entorn local:

* Instal.lar les dependències `pip install -r requirements.txt` (millor en un virtualenv!)
* Crear el fitxer `.env` i afegir els API Keys de OpenAI i Google Search (veure `.env-example`)
* Executar el notebook [chatGPT_langchain.ipynb](chatGPT_langchain.ipynb): `jupyter notebook chatGPT_langchain.ipynb`

## Demo - Text-to-Image - StableDiffusion

* [Codi per carregar al collab](https://colab.research.google.com/github/TheLastBen/fast-stable-diffusion/blob/main/fast_stable_diffusion_AUTOMATIC1111.ipynb#scrollTo=PEgQywdJJK8L )

* Dreambooth
  * [Repositori a Github](https://github.com/TheLastBen/fast-stable-diffusion)
  * [Manual pas a pas per entrenar amb les teves fotos](https://github.com/Excalibro1/fast-stable-diffusionwik/wiki/fast-stable-diffusion-wiki)
* ControlNet
  * [Repositori a Github](https://github.com/camenduru/controlnet-colab)
  * [Manual per controlar stablediffusion](https://stable-diffusion-art.com/controlnet/)

## Enllaços d'interès

* [ChatGPT is everywhere. Here’s where it came from](https://www.technologyreview.com/2023/02/08/1068068/chatgpt-is-everywhere-heres-where-it-came-from/)
* [ChatGPT Explained: A Normie's Guide To How It Works](https://www.jonstokes.com/p/chatgpt-explained-a-guide-for-normies)
* [Understanding latent space in machine learning](https://towardsdatascience.com/understanding-latent-space-in-machine-learning-de5a7c687d8d)
* [Embeddings - Google Foundational Courses](https://developers.google.com/machine-learning/crash-course/embeddings/video-lecture)
* [Illustrated Stable Diffusion](https://jalammar.github.io/illustrated-stable-diffusion/)
