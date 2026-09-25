# Aquila — site institucional

Site estático em português, responsivo, em HTML e CSS. Sem npm, build, banco de dados ou variáveis de ambiente. As imagens são locais e as fontes são do sistema.

## Publicar na Vercel

1. Extraia o ZIP e envie o conteúdo desta pasta para um repositório GitHub, com index.html na raiz.
2. Na Vercel, use Add New → Project e importe o repositório.
3. Selecione Framework Preset: Other. Root Directory: pasta que contém index.html. Deixe Build Command e Install Command sem comando. Output Directory: `.`.
4. Clique em Deploy. Depois, configure seu domínio em Settings → Domains, se desejar.

Alternativa com a CLI, dentro desta pasta:

```sh
npx vercel --prod
```

A CLI solicitará autenticação e seleção/criação do projeto. O projeto foi preparado para deploy, mas não publicado em uma conta Vercel.

## Visualizar e editar

Abra index.html diretamente no navegador, ou execute `python3 -m http.server 8000` nesta pasta e abra http://localhost:8000.

- index.html: textos, links, metadados e dados institucionais.
- styles.css: cores, tipografia e layout.
- assets/: imagens locais e favicon.
- vercel.json: configuração de publicação.

## Fontes de conteúdo

Consultadas em 25/09/2026:
- https://sofanacaixa.com.br/ — categorias e imagem Sofá Modular Pelion.
- https://littleduck.com.br/ — categorias e imagem Cama Montessoriana Solteiro Linho.
- https://ecoflamegarden.com.br/ — categorias, imagem Zimma e dados institucionais da Aquila (bloco Contato).

CNPJ Aquila: 60.024.830/0001-80. Endereço: Rua Emilio Vendramim, 206, Distrito Industrial de Rafard Doutor Alcides Brun, Rafard/SP, CEP 13370-406.
A associação das três marcas à Aquila segue o escopo informado pelo solicitante. A página usa “grupo” e “indústria moveleira”, sem afirmar uma classificação jurídica de holding. Não foram inventados datas de fundação, indicadores, certificações, contatos corporativos ou garantias.
As fotografias são provenientes das lojas das respectivas marcas. A identidade tipográfica “aquila” foi criada para esta página e pode ser substituída pelo logotipo oficial.
