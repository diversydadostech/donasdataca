# Donas da Taça

Site estático institucional da Donas da Taça, feito com HTML e CSS.

## Pré-visualizar localmente

Abra `index.html` no navegador ou execute na raiz do projeto:

```bash
python3 -m http.server 8000
```

Depois, acesse `http://localhost:8000`.

## Publicar no Vercel

1. Envie `index.html`, `styles.css` e este README para o repositório no GitHub.
2. No Vercel, importe esse repositório.
3. Use a pasta raiz como diretório do projeto e selecione **Other** como framework.
4. Não configure comando de build nem diretório de saída: o Vercel servirá o `index.html` diretamente.

Não é necessário `vercel.json` para este site estático.
