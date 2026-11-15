# Documentação do PyNexo

Esta pasta contém os ficheiros que compõem a documentação e as páginas de navegação do website PyNexo.

É aqui que serão organizadas as páginas que os visitantes irão consultar através da plataforma web.

O objectivo é manter uma documentação clara, organizada, consistente e fácil de navegar, independentemente de quem cria ou actualiza os conteúdos.

## O que deve ser colocado nesta pasta?

Esta pasta destina-se às páginas que serão apresentadas no website, incluindo:

- Página inicial da documentação.
- Páginas de apresentação e informação.
- Páginas de navegação.
- Páginas de orientação para os visitantes.
- Outras páginas necessárias ao funcionamento e à organização do website.

Os materiais educativos sobre Python devem respeitar a organização definida para a pasta `content/`.

## Como criar uma página?

As páginas devem ser criadas utilizando o formato Markdown (`.md`).

O Markdown permite escrever conteúdos com títulos, parágrafos, listas, tabelas, ligações e blocos de código de forma simples.

Exemplo de criação de uma página:

```text
docs/
├── README.md
├── index.md
├── sobre.md
└── como-utilizar.md
```

Cada ficheiro Markdown representa uma página que poderá ser apresentada no website.

## Regras para nomear os ficheiros

Para manter a documentação organizada, todos os contribuidores devem seguir estas orientações:

- Utilizar nomes claros e relacionados com o conteúdo da página.
- Escrever os nomes dos ficheiros em letras minúsculas.
- Utilizar hífen (`-`) para separar palavras.
- Evitar espaços, acentos e caracteres especiais nos nomes.
- Utilizar a extensão `.md` para páginas de documentação.

Exemplos:

| Correcto | Evitar |
|---|---|
| `introducao.md` | `Introdução.md` |
| `como-utilizar.md` | `Como Utilizar.md` |
| `sobre-o-pynexo.md` | `Sobre_O_PyNexo.md` |

## Como estruturar o conteúdo de uma página?

Cada página deve apresentar a informação de forma organizada e fácil de compreender.

Recomendamos a seguinte estrutura:

```markdown
# Título da página

Breve apresentação do assunto que será abordado.

## Primeiro tópico

Explicação do primeiro assunto.

## Segundo tópico

Desenvolvimento da informação.

## Exemplos

Quando necessário, apresentar exemplos
que ajudem a compreender o conteúdo.

## Referências

Indicar as fontes utilizadas, quando aplicável.
```

Nem todas as páginas precisam de seguir exactamente este modelo. A estrutura deve adaptar-se à finalidade e ao tipo de informação apresentado.

## Organização das páginas

Inicialmente, os ficheiros devem ser mantidos directamente nesta pasta, sem criar subpastas desnecessárias.

À medida que a documentação crescer, poderão ser criadas novas pastas para agrupar páginas relacionadas.

Quando isso acontecer:

- Agrupar páginas com assuntos relacionados.
- Evitar criar pastas para apenas um ficheiro.
- Utilizar nomes claros para identificar cada grupo.
- Actualizar a navegação do website sempre que forem adicionadas novas páginas.

## Ligações entre páginas

Sempre que uma página fizer referência a outra página da documentação, utiliza ligações relativas em Markdown.

Exemplo:

```markdown
Consulta também a página
[Sobre o PyNexo](sobre.md).
```

Isto facilita a navegação e permite que os visitantes encontrem informações relacionadas.

## Boas práticas

Ao criar ou actualizar páginas, procura respeitar os seguintes princípios:

- Escrever em língua portuguesa.
- Utilizar linguagem clara e acessível.
- Organizar os assuntos através de títulos e subtítulos.
- Evitar textos desnecessariamente extensos.
- Utilizar listas e tabelas quando facilitarem a compreensão.
- Verificar as ligações entre páginas.
- Rever a ortografia antes de enviar uma contribuição.
- Evitar conteúdos duplicados.

## Como contribuir?

Qualquer pessoa pode ajudar a melhorar a documentação.

Para isso:

1. Identifica uma página que precisa de melhoria ou propõe uma nova.
2. Cria ou actualiza o respectivo ficheiro Markdown.
3. Verifica a organização e as ligações.
4. Envia as alterações através de um Pull Request.
5. Aguarda a revisão da contribuição.

Consulta o ficheiro [CONTRIBUTING.md](../CONTRIBUTING.md) para conhecer as orientações gerais de participação.

---

**PyNexo — Documentação construída com conhecimento partilhado.**