# Study Hub TI

Study Hub de **Felipe Rodrigues Queiroz**, estudante de Ciência da Computação no Centro Universitário de Brasília (CEUB) e desenvolvedor Full-Stack.

Este repositório organiza minha trajetória acadêmica e profissional em Tecnologia da Informação: materiais das disciplinas, atividades, anotações, projetos e certificados. A página web apresenta esse conteúdo como um **PortfolioHUB acadêmico-profissional**, desenvolvido para a etapa intermediária de Bootcamp I.

## Acesso

- **Site (endereço do GitHub Pages):** [felipethecreator.github.io/study-hub-ti](https://felipethecreator.github.io/study-hub-ti/)
- **Repositório:** [felipethecreator/study-hub-ti](https://github.com/felipethecreator/study-hub-ti)

O site está **publicado no GitHub Pages**, e o repositório é público. A versão inicial, a tag `v1.0.0` e a melhoria posterior já estão disponíveis no GitHub.

## Estrutura do repositório

```text
study-hub-ti/
├── index.html                       # Conteúdo e navegação do site
├── style.css                        # Layout responsivo e estilos
├── README.md                        # Documentação geral
├── 01_Apresentacao_e_Perfil/
│   └── README.md
├── 02_Disciplinas_Atuais/
│   ├── Bootcamp_I/
│   │   ├── Atividades_e_Entregas/
│   │   │   └── README.md
│   │   └── Anotacoes_e_Resumos/
│   │       └── README.md
│   ├── Proj_Integrador_IV/
│   │   └── README.md
│   ├── Seguranca_Digital/
│   │   └── README.md
│   ├── Sist_em_Tempo_Real_e_Emb/
│   │   └── README.md
│   └── Testes_e_Qualidade_de_Sof/
│       └── README.md
└── 03_Projetos_e_Certificados/
    ├── README.md                    # Índice de projetos e certificados
    ├── CashFlow_API/
    │   └── README.md
    ├── Swanly/
    │   └── README.md
    └── Web_Portfolio/
        └── README.md
```

A estrutura da primeira etapa foi preservada. Cada projeto destacado possui uma pasta com documentação própria em `03_Projetos_e_Certificados`. O código-fonte e seu histórico continuam nos repositórios originais, acessíveis pelos links de cada README.

## Tecnologias

- **HTML5:** conteúdo semântico, seções e navegação por âncoras.
- **CSS3:** layout com Grid e Flexbox, adaptação para celular e foco visível para navegação pelo teclado.
- **Git e GitHub:** histórico de alterações e marcação da versão inicial.
- **GitHub Pages:** hospedagem estática a partir da branch `main`, na raiz `/`.

O site não precisa de JavaScript, frameworks, instalação de dependências ou etapa de build. As fontes são locais ao sistema. Há um atalho para pular ao conteúdo e respeito à preferência de movimento reduzido.

## Principais seções

| Seção | Conteúdo |
| --- | --- |
| Início | Study Hub e apresentação de Felipe Rodrigues Queiroz. |
| Sobre mim | Formação no CEUB e atuação como desenvolvedor Full-Stack. |
| Áreas de interesse | Backend, Full-Stack, Engenharia de Software, Arquitetura de Software e Cloud. |
| Disciplinas atuais | Bootcamp I, Projeto Integrador IV, Segurança Digital, Sistemas em Tempo Real e Embarcados, Testes e Qualidade de Software. |
| Projetos | Seleção de projetos reais do perfil GitHub. |
| Study Hub | Objetivo e organização do repositório. |
| Contato | GitHub, LinkedIn e e-mail. |

## Projetos apresentados

| Projeto | Descrição | Tecnologias verificadas | Documentação no Hub |
| --- | --- | --- | --- |
| [CashFlow API](https://github.com/felipethecreator/cashFlow-api) | API de controle financeiro com autenticação e gerenciamento de categorias e despesas recorrentes. | Java, Spring Boot e PostgreSQL. | [README do projeto](03_Projetos_e_Certificados/CashFlow_API/README.md) |
| [Swanly](https://github.com/felipethecreator/Swanly-backend) | Backend de uma proposta de rede social inspirada no Twitter/X, com módulo de usuários implementado. | TypeScript, Express e MongoDB. | [README do projeto](03_Projetos_e_Certificados/Swanly/README.md) |
| [Web Portfolio](https://github.com/felipethecreator/web-portfolio) | Portfólio web pessoal. | React, Next.js e Tailwind CSS. | [README do projeto](03_Projetos_e_Certificados/Web_Portfolio/README.md) |

Os links foram verificados antes da inclusão. As descrições e tecnologias foram conferidas nos READMEs, metadados, arquivos de dependências e código dos projetos. As documentações individuais distinguem funcionalidades implementadas dos objetivos ainda não confirmados no código.

## Como abrir localmente

Abra `index.html` no navegador. Como alternativa, na raiz do repositório, execute com Python 3:

```bash
python -m http.server 8000
```

Depois acesse [localhost:8000](http://localhost:8000). Use `Ctrl+C` no terminal para encerrar o servidor.

## Publicação no GitHub Pages

**Status: publicado.** O site utiliza a branch `main` e a raiz do repositório. O procedimento abaixo fica registrado para consulta da configuração:

1. No repositório, abra **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch** em **Source**.
3. Selecione a branch **main** e a pasta **/ (root)**.
4. Clique em **Save**.
5. Aguarde a execução **pages build and deployment**, na aba **Actions**.
6. Abra [https://felipethecreator.github.io/study-hub-ti/](https://felipethecreator.github.io/study-hub-ti/).

Novos commits enviados à `main` atualizam o site automaticamente após a conclusão da publicação. Não é necessário mover as pastas das disciplinas nem usar a pasta `docs`.

## Versão 1.0 e evolução

A **versão 1.0** corresponde à primeira página funcional, com todas as seções, layout responsivo, projetos reais e documentação. Ela é identificada pelo commit `feat: cria Study Hub versão 1.0` e pela tag Git **`v1.0.0`**.

Para consultar a versão inicial e acompanhar as alterações:

```bash
git log --oneline --decorate
git show v1.0.0
git diff v1.0.0..main
```

A tag mantém a referência da versão inicial; melhorias posteriores são registradas em novos commits na `main`.

### Melhoria após a versão 1.0

O commit `feat: adiciona atalhos para materiais de Bootcamp I` inclui links diretos para **Atividades e Entregas** e **Anotações e Resumos** na seção de disciplinas. Assim, esses materiais podem ser acessados sem passar pela pasta intermediária. Os atalhos se adaptam ao celular e são acessíveis pelo teclado.

### Histórico publicado

| Marco | Referência no GitHub |
| --- | --- |
| Primeira versão funcional | [Commit `5ec311b`](https://github.com/felipethecreator/study-hub-ti/commit/5ec311bd6605e91617836555bfe93be62ed8b93c) |
| Versão 1.0 | [Tag `v1.0.0`](https://github.com/felipethecreator/study-hub-ti/tree/v1.0.0) |
| Melhoria posterior: atalhos de Bootcamp I | [Histórico de commits](https://github.com/felipethecreator/study-hub-ti/commits/main/) — commit `b945d0d` |

A tag permanece vinculada ao commit inicial, e a `main` reúne a melhoria posterior e as atualizações de documentação.

Para enviar futuras alterações já registradas em novos commits:

```bash
git push origin main
```

Não é necessário recriar ou mover a tag `v1.0.0` a cada atualização.

## Verificações realizadas

- Layout conferido em larguras de 320, 390, 768, 1024 e 1440 pixels, sem rolagem horizontal indevida.
- Navegação por âncoras, atalho para o conteúdo e foco pelo teclado verificados.
- Links dos três projetos verificados com resposta HTTP 200; atalhos acadêmicos apontam para pastas existentes.
- Estrutura da primeira etapa preservada, com atualização dos índices e inclusão da documentação de cada projeto.
- Site funcional sem JavaScript e sem dependências externas.

## Contato

- **GitHub:** [@felipethecreator](https://github.com/felipethecreator)
- **LinkedIn:** [Felipe Rodrigues Queiroz](https://www.linkedin.com/in/felipe-rodrigues-queiroz-564377171/)
- **E-mail:** [felipinhodev@gmail.com](mailto:felipinhodev@gmail.com)

Os dados de apresentação e contato têm como fonte o [perfil já documentado neste repositório](01_Apresentacao_e_Perfil/README.md).
