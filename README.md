# Report semanal de QA

Ferramenta simples, que roda direto no navegador, para montar um report semanal em formato de flyer e enviar por e-mail para gestores.

## Como usar

1. Abra o `index.html` no Chrome ou Edge (ou acesse a versão online, se estiver publicada no GitHub Pages).
2. Preencha nome, período, números da semana, entregas, reuniões, próximos passos e pontos de atenção.
3. Clique em **Copiar imagem para o e-mail** e cole no corpo do e-mail, ou use **Baixar PNG**.
4. Na semana seguinte, clique em **Começar nova semana**: as datas avançam 7 dias e os campos são limpos.

## Detalhes

- Os dados ficam salvos só no seu navegador (localStorage). Nada é enviado para servidor nenhum.
- Use **Salvar backup** para guardar cada semana em um arquivo `.json` e **Abrir backup** para recuperar.
- Precisa de internet para carregar a fonte e a biblioteca que gera a imagem ([html2canvas](https://html2canvas.hertzen.com/)).
- Em listas, escreva um item por linha. Seções vazias não aparecem no flyer.

## Tecnologias

HTML, CSS e JavaScript puro, sem instalação e sem build.
