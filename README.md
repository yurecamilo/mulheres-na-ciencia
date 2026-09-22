# Mulheres na Ciência

Versão independente do site da Feira de Ciências 2026 do IFSP — Câmpus São José dos Campos.

## Publicar na Vercel

### Pelo painel da Vercel

1. Extraia o arquivo ZIP.
2. Envie a pasta para um repositório no GitHub, GitLab ou Bitbucket.
3. Na Vercel, selecione **Add New > Project** e importe o repositório.
4. Em **Framework Preset**, escolha **Other**.
5. Deixe **Build Command** e **Output Directory** vazios.
6. Clique em **Deploy**.

### Pela Vercel CLI

Com Node.js instalado, abra o terminal nesta pasta e execute:

```bash
npx vercel
```

Para publicar diretamente em produção:

```bash
npx vercel --prod
```

## Executar localmente

Você pode abrir o arquivo `index.html` diretamente no navegador ou iniciar um servidor local:

```bash
npx serve .
```

## Estrutura

- `index.html`: conteúdo, estilos e interações do site.
- `assets/fonts/`: fontes locais.
- `assets/images/`: retratos das cientistas.
- `vercel.json`: configuração de publicação e cache da Vercel.

O site é estático e não depende de banco de dados, variáveis de ambiente ou serviços do ChatGPT.

## Créditos de imagens

- Neusa Amato: PET Física UEM.
- Sônia Guimarães: Sociedade Brasileira de Física.
- Carmen Portinho: CREA-DF.
- Bertha Lutz: Wikimedia Commons.
- Enedina Marques: Revista Aluvião.
