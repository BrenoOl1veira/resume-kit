# Breno Juan Resume Kit

Repositório pessoal com versões do meu currículo em português e inglês, estruturadas em LaTeX.

Este projeto foi reorganizado para funcionar como uma base profissional única para candidaturas, atualização de currículo e posicionamento técnico. O foco principal está em destacar experiência com integração de sistemas, ETL/ELT, automação de processos, SQL, Python, Power BI e ecossistemas TOTVS.

## Objetivo

Centralizar em um só lugar:

- currículo em inglês para vagas internacionais;
- currículo em português para vagas no mercado brasileiro;
- estrutura reutilizável em LaTeX;
- prompts de apoio para melhorar textos, bullets e comunicação profissional;
- uma base fácil de adaptar para novas vagas em dados.

## Perfil profissional destacado no projeto

O conteúdo atual do projeto posiciona meu perfil para vagas como:

- Data Engineer
- Data Analyst
- Analytics Engineer
- BI Analyst
- Systems Analyst com foco em dados

Principais temas reforçados nos currículos:

- pipelines e rotinas ETL/ELT;
- integração entre sistemas via REST, SOAP e web services;
- automação de processos com SQL, Python e C#;
- modelagem e estruturação de dados para análise;
- dashboards e visualização com Power BI;
- experiência de negócio em Financeiro, Contabilidade, Compras, Estoque e RH;
- atuação com TOTVS Protheus e TOTVS RM.

## Estrutura do projeto

```text
resume-template-main/
├── .github/
│   └── workflows/
│       └── build.yml
├── prompts/
│   ├── prompt_en.md
│   └── prompt_pt-br.md
├── resumes/
│   ├── en/
│   │   ├── README.md
│   │   └── resume.tex
│   └── pt-br/
│       ├── README.md
│       └── curriculo.tex
├── .gitignore
├── LICENSE.md
└── README.md
```

## Arquivos principais

### Currículo em inglês

Arquivo: `resumes/en/resume.tex`

Uso recomendado:

- vagas internacionais;
- empresas globais;
- posições remotas;
- processos com ATS em inglês.

Destaques:

- resumo profissional orientado a dados;
- experiência estruturada para leitura rápida;
- foco em stack técnica e integração de dados;
- linguagem mais alinhada ao mercado internacional.

### Currículo em português

Arquivo: `resumes/pt-br/curriculo.tex`

Uso recomendado:

- vagas no Brasil;
- processos seletivos em português;
- aplicações para áreas de dados, BI e sistemas com foco analítico.

Destaques:

- texto mais natural para recrutadores do mercado brasileiro;
- terminologia adaptada para contexto local;
- manutenção do mesmo posicionamento técnico do currículo em inglês.

### Prompts auxiliares

Arquivos:

- `prompts/prompt_en.md`
- `prompts/prompt_pt-br.md`

Esses prompts ajudam a:

- revisar descrições de experiências;
- melhorar bullets;
- adaptar o currículo para vaga específica;
- preparar entrevistas e comunicação profissional.

## Como editar

Os currículos estão em LaTeX, mas a edição é simples porque o conteúdo principal está concentrado em blocos fáceis de localizar:

- cabeçalho com nome e contatos;
- resumo profissional;
- experiência;
- competências técnicas;
- formação acadêmica;
- idiomas.

Se quiser adaptar para uma vaga específica, o ideal é ajustar principalmente:

1. o título profissional;
2. o resumo profissional;
3. os bullets da experiência;
4. a ordem e o texto das competências técnicas.

## Como gerar PDF

Você pode gerar os PDFs com qualquer compilador LaTeX compatível, como:

- `pdflatex`
- `xelatex`
- Overleaf
- editores online compatíveis com LaTeX

Exemplo de compilação local:

```bash
pdflatex resumes/en/resume.tex
pdflatex resumes/pt-br/curriculo.tex
```

Se preferir, também é possível abrir os arquivos em plataformas online e exportar o PDF diretamente.

## Decisões de estrutura

Este projeto foi ajustado para ficar mais forte para vagas de dados e mais limpo para recrutadores e ATS.

Melhorias aplicadas:

- remoção de conteúdo genérico do template original;
- personalização completa do conteúdo para o meu perfil;
- organização do texto com foco em clareza e leitura rápida;
- alinhamento dos currículos em PT-BR e EN;
- ênfase em Data Engineering e Data Analytics;
- README principal reescrito para documentar o projeto como repositório pessoal.

## Estratégia de posicionamento

Os currículos foram estruturados para comunicar três pilares:

1. base técnica sólida em dados e automação;
2. experiência prática com sistemas empresariais e integrações;
3. capacidade de gerar valor para áreas de negócio com dados confiáveis e utilizáveis.

Esse posicionamento ajuda a conectar meu perfil com vagas que exigem alguém capaz de:

- extrair e transformar dados;
- integrar fontes diversas;
- automatizar fluxos;
- apoiar tomada de decisão;
- atuar entre times técnicos e áreas de negócio.

## Próximas melhorias possíveis

Este projeto já está utilizável, mas pode evoluir ainda mais com:

- versões específicas por tipo de vaga;
- seção de projetos de dados;
- versão voltada para LinkedIn/About;
- cartas de apresentação por idioma;
- variações para Data Engineer, Data Analyst e BI Analyst.

## Licença

O projeto mantém a licença já presente no repositório:

- `LICENSE.md`

## Autor

**Breno Juan de Oliveira Pinto**

- LinkedIn: [linkedin.com/in/brenool1veira](https://www.linkedin.com/in/brenool1veira)
- Portfólio: [portfolio-breno-oliveira.netlify.app](https://portfolio-breno-oliveira.netlify.app)
- E-mail: [brenojuandeoliveirapinto@gmail.com](mailto:brenojuandeoliveirapinto@gmail.com)
