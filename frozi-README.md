# Frozí Eventos — Site Institucional

Site estático da **Frozí Eventos** — recepção de alto padrão, casting e staff para eventos corporativos, sociais, palcos e premiações no Rio Grande do Sul.

## Conteúdo do pacote

| Arquivo/Pasta | Descrição |
| --- | --- |
| `index.html` | Página única do site (abra no navegador) |
| `assets/` | JavaScript, CSS, logo e símbolo da marca |
| `media/` | Todas as 49 fotos originais e o vídeo do hero |
| `favicon.png` | Ícone do site |

## Seções do site

- **Início** — vídeo de fundo com a identidade da marca
- **Serviços** — carrossel 3D giratório com os 10 serviços (arraste, setas ou bolinhas de navegação)
- **Portfólio** — galeria de fotos dos trabalhos realizados
- **Diferenciais** — treinamento, idiomas e palco
- **Contato** — WhatsApp e e-mail

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `frozi-site`).
2. Envie todos os arquivos deste pacote para a raiz do repositório:
   ```sh
   git init
   git add .
   git commit -m "Site Frozí Eventos"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/frozi-site.git
   git push -u origin main
   ```
3. No GitHub, vá em **Settings → Pages**.
4. Em **Source**, selecione **Deploy from a branch**, branch `main`, pasta `/ (root)` e salve.
5. O site ficará disponível em `https://SEU-USUARIO.github.io/frozi-site/` em alguns minutos.

## Testar localmente

Basta abrir o `index.html` em um navegador, ou servir a pasta:

```sh
python3 -m http.server 8000
# acesse http://localhost:8000
```

## Tecnologias

HTML, CSS e JavaScript estáticos (build de produção gerado com Vite + React + TanStack + Tailwind CSS). Nenhum servidor ou banco de dados é necessário.

---

Frozí Eventos · Rio Grande do Sul, Brasil · frozieventos@gmail.com
