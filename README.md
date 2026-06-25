# Calendário de Cobertura In Loco | Brasileiras

Este pacote está pronto para publicar no **GitHub Pages**.

## Como publicar

1. Crie um repositório no GitHub.
2. Envie estes arquivos para a raiz do repositório:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. No GitHub, vá em **Settings** > **Pages**.
4. Em **Build and deployment**, selecione:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/root`
5. Salve.
6. O GitHub vai gerar um link parecido com:
   `https://seu-usuario.github.io/nome-do-repositorio/`

## Observação importante sobre edição

Este HTML funciona como site estático no GitHub Pages. As edições feitas dentro do dashboard usam armazenamento local do navegador (`localStorage`). Isso significa que:

- cada pessoa verá e salvará alterações apenas no próprio navegador;
- as alterações não são sincronizadas automaticamente para todos;
- para edição exclusiva real, é necessário adicionar login e banco de dados, como Supabase ou Firebase.

## Para atualizar o site

Substitua o arquivo `index.html` por uma nova versão e faça commit no GitHub.
