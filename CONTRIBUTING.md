# Como contribuir

Obrigado pelo interesse em contribuir com o ecossistema King's Newsletter! Este guia vale para todos os repositórios da organização, a menos que um projeto tenha o seu próprio `CONTRIBUTING.md`.

## Formas de contribuir

- **Relatar problemas** no site, no app ou na newsletter
- **Sugerir melhorias** e novas funcionalidades
- **Apontar correções de conteúdo**: informação errada, desatualizada, sem fonte ou com possível viés
- **Enviar código**, documentação ou ajustes de texto por meio de pull requests

## Abrindo uma issue

1. Procure nas issues existentes para ver se o assunto já foi relatado.
2. Clique em **New issue** e escolha o modelo adequado:
   - **Relatar um problema**: algo não funciona como deveria
   - **Sugerir uma melhoria**: ideias e novas funcionalidades
   - **Correção de conteúdo**: erros ou problemas editoriais
3. Preencha todos os campos obrigatórios com o máximo de contexto possível.

> **Falhas de segurança** não devem ser relatadas em issues públicas. Envie um e-mail para contact@kingsnewsletter.com.

## Correções de conteúdo

Todo conteúdo publicado segue nossos princípios editoriais:

- Diferenciar fato, declaração, proposta, rumor e análise
- Priorizar fontes oficiais
- Não induzir posição política nem favorecer candidatos ou partidos

Ao pedir uma correção, inclua sempre o link do conteúdo, o trecho exato e fontes que confirmem a informação correta, de preferência primárias (órgãos públicos, documentos oficiais, bases de dados). Pedidos sem fonte podem demorar mais para ser avaliados.

## Enviando código

1. Faça um fork do repositório e crie uma branch a partir da `main`:
   ```bash
   git checkout -b feat/minha-melhoria
   ```
2. Faça as alterações seguindo o estilo de código já usado no projeto.
3. Teste localmente antes de enviar, conforme as instruções do README do projeto.
4. Faça commits pequenos e com mensagens claras.
5. Envie a branch e abra um pull request para a `main`, explicando o que mudou e por quê. Se o PR resolver uma issue, mencione-a (por exemplo, `Closes #12`).

### Idioma

O projeto é brasileiro e voltado para o público brasileiro. Por isso:

- **Em português**: issues, comentários, documentação, textos da interface e conteúdo editorial.
- **Em inglês**: mensagens de commit, títulos e descrições de pull requests, e nomes no código (variáveis, funções, arquivos).

### Mensagens de commit

Usamos o padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/), em inglês e no imperativo:

```
feat: add date filter to newsletter archive
fix: correct inflation chart axis on mobile
docs: update setup instructions
```

Tipos mais comuns: `feat`, `fix`, `docs`, `style`, `refactor`, `test` e `chore`.

### Nomes de branch

Use um prefixo com o tipo da mudança e uma descrição curta, por exemplo: `feat/archive-search`, `fix/live-score-refresh`, `docs/readme-setup`.

## Revisão

Todo pull request passa por revisão antes de ser incorporado. Podemos pedir ajustes; isso é parte normal do processo. Mantenha a conversa respeitosa e focada no trabalho.

## Dúvidas

Se algo não estiver claro, abra uma issue ou escreva para contact@kingsnewsletter.com.
