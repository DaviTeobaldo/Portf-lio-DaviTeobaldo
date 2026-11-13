# Davi Oliveira Teobaldo — Portfólio

Portfólio profissional em português brasileiro, desenvolvido com HTML5, CSS3 e JavaScript puro. O projeto foi pensado para apresentar a trajetória acadêmica e técnica de Davi Oliveira Teobaldo, com ênfase na intersecção entre Matemática Aplicada e Computacional, Ciência de Dados, Machine Learning e Inteligência Artificial Generativa.

## Estrutura

```text
portfolio-davi/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── favicon.svg
    └── og-cover.svg
```

## Executar localmente

Não há dependências, etapa de build ou instalação de pacotes.

1. Clone o repositório.
2. Abra `index.html` no navegador.

Opcionalmente, execute um servidor local na raiz do projeto:

```bash
python -m http.server 8000
```

Acesse `http://localhost:8000`.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub, por exemplo `portfolio`.
2. Copie os arquivos deste projeto para a raiz do repositório.
3. Faça commit e push para a branch `main`.
4. No GitHub, acesse **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**.
6. Escolha a branch `main` e a pasta `/ (root)`, depois salve.
7. Aguarde a publicação. O endereço será exibido na própria página de configurações do GitHub Pages.

## Personalização antes da candidatura

Revise especialmente os itens abaixo antes de tornar o endereço público:

- **Links de projetos:** confirme se os cinco repositórios estão públicos e se os endereços continuam corretos.
- **Imagens dos projetos:** as ilustrações em `assets/projects/` são representativas e conceituais; não são capturas de tela, resultados experimentais nem interfaces reais dos sistemas.
- **README dos projetos:** cada cartão direciona ao respectivo repositório, onde ficam a descrição técnica, os métodos e os resultados.
- **Pesquisa PICME:** atualize o texto quando o recorte metodológico estiver definido e houver resultados verificáveis.
- **Contato e idiomas:** confira e-mail, LinkedIn, GitHub e níveis linguísticos.

## Decisões de implementação

- HTML semântico e navegação por âncoras.
- CSS responsivo, sem framework ou dependência de runtime.
- JavaScript limitado ao menu mobile, ano do rodapé e animações de entrada.
- Respeito à preferência `prefers-reduced-motion`.
- Metadados básicos de SEO, Open Graph e dados estruturados Schema.org.
- Links externos com `rel="noopener noreferrer"`.

## Observação sobre precisão

O conteúdo evita atribuir técnicas, métricas ou funcionalidades não confirmadas no briefing. Onde a análise integral dos repositórios ainda é necessária, a redação permanece deliberadamente descritiva e recomenda consulta ao código-fonte. Antes de enviar a candidatura, valide cada afirmação técnica contra a versão pública e atual dos respectivos projetos.
