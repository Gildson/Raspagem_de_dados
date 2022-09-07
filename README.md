# Raspagem de dados

Esse é o início de uma jornada de aprendizado, não sou expecte no assunto, mas gosto muito da área e estou seguindo no caminho para ser Cientista de dados

Bibliotecas utilizadas
import requests
import pandas as pd
import numpy as np
import re
from bs4 import BeautifulSoup

Dicas de um iniciante
1) Buscar padrões:
  Procurar padrões de repetição nas tags que julgar relevantes para a raspagem.
2) Simular que está enviando a busca por um navegador:
  Passando um headers = {'user-agent': 'navegador'}, usei o Mozilla/5.0 como navegador.
3) Ter cuidado com a quantidade de requisições, se não o servidor derruba o robô.
4) Testa se a requisição teve êxito (200).
5) Usar expressão regular:
  Ajuda muito a otimizar a raspagem.
  Ex: (.) definir qualquer caracter (*) define uma ou mais vezes de repetição
6) Pegar sempre o nó pai:
  Isso vai ajudar muito na hora de buscar dentro da tag escolhida
