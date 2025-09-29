# Copy HEX – Multi (4 modelos)

Site simples para copiar um hexadecimal a partir de:
- **?name=ALIAS** (lendo de `tokens.json`), ou
- **?v=%23HEX** (passando o valor direto).

## Configurar os 4 modelos
Edite o arquivo `tokens.json` com os **nomes** e **hex** desejados, por exemplo:
```json
{
  "primaria": "#123456",
  "acento": "#FF6600",
  "sucesso": "#10B981",
  "aviso": "#F59E0B"
}
```

## Links para usar no Figma
Para cada botão:
- Por nome (lendo do `tokens.json`):
  `https://SEU_USUARIO.github.io/copy-hex-multi/copy.html?name=primaria`
- Por valor direto:
  `https://SEU_USUARIO.github.io/copy-hex-multi/copy.html?v=%23FF6600`

> Dica: use `Open link` nos protótipos.

## Publicando no GitHub Pages
1. Crie um repositório público chamado **copy-hex-multi**.
2. Suba os arquivos `index.html`, `copy.html` e `tokens.json` (você pode editar `tokens.json` direto no GitHub).
3. Vá em **Settings → Pages** e selecione:
   - **Source:** Deploy from a branch
   - **Branch:** `main` e pasta `/ (root)` → **Save**
4. A URL ficará: `https://SEU_USUARIO.github.io/copy-hex-multi/`

## Via linha de comando (git)
```bash
git init
git add .
git commit -m "publish: copy-hex-multi"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/copy-hex-multi.git
git push -u origin main
```
