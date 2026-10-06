# claude-skills-pt

Uma coleção de skills para o Claude, em português de Portugal. Comecei isto porque estou a fazer o curso de Técnico de Informática e queria que o Claude me ajudasse sempre da mesma maneira nas coisas que repito muito: estudar, escrever relatórios, perceber erros, mexer no GitHub, preparar CVs e entrevistas.

Cada skill é uma pasta com um ficheiro `SKILL.md` onde explico ao Claude como fazer aquela tarefa.

## Skills

- **estudo**: pega nos meus apontamentos e faz resumos, pontos de estudo e perguntas para rever
- **revisor-relatorios**: revê relatórios (como o da PAF) e aponta problemas de estrutura, clareza e português
- **explicador-erros**: explica mensagens de erro passo a passo e diz como corrigir
- **gerador-readme**: cria READMEs para os meus projetos
- **preparacao-entrevistas**: simula entrevistas técnicas e de comportamento para estágios
- **adaptador-cv**: ajusta o CV e a carta de apresentação a cada oferta
- **revisor-codigo**: faz code review e chama a atenção para más práticas
- **commits-prs**: escreve mensagens de commit e descrições de Pull Requests
- **planeador-projetos**: parte uma ideia em tarefas e marcos
- **tom-estilo**: muda o tom de um texto (mais formal, mais simples, mais técnico)
- **gerador-exercicios**: inventa exercícios de programação com vários níveis

## Estrutura

```
claude-skills-pt/
├── README.md
├── LICENSE
├── skills/
│   ├── estudo/
│   ├── revisor-relatorios/
│   ├── explicador-erros/
│   ├── gerador-readme/
│   ├── preparacao-entrevistas/
│   ├── adaptador-cv/
│   ├── revisor-codigo/
│   ├── commits-prs/
│   ├── planeador-projetos/
│   ├── tom-estilo/
│   └── gerador-exercicios/
└── docs/
    └── como-instalar.md
```

Cada pasta em `skills/` tem pelo menos um `SKILL.md`. Algumas vão ter também exemplos ou checklists.

## Como usar

Clona o repo e copia a pasta da skill que queres para as tuas skills no Claude:

```bash
git clone https://github.com/TMseabra/claude-skills-pt.git
```

Depois é só pedir a tarefa normalmente. Se o pedido encaixar na descrição da skill, o Claude usa-a. Os passos mais detalhados vão ficar em `docs/como-instalar.md`.

## Como é um SKILL.md

```markdown
---
name: nome-da-skill
description: Quando usar esta skill e para quê.
---

# Nome da skill

## O que faz
...

## Passos
1. ...
2. ...

## Como responder
...
```

A `description` é o que mais importa, porque é por ela que o Claude decide se usa a skill ou não.

## Estado

Ainda estou a escrever isto. Por fazer:

- [ ] escrever o `SKILL.md` de cada skill
- [ ] adicionar exemplos
- [ ] escrever o `docs/como-instalar.md`
- [ ] testar cada skill com pedidos reais e afinar as descrições

## Contribuir

Se tiveres ideias ou encontrares algo que possa melhorar, abre uma issue ou um Pull Request.

## Autor

Tomás Seabra, formando de Técnico/a Programador/a de Informática.

## Licença

MIT. Vê o ficheiro `LICENSE`.
