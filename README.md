# claude-skills-pt

![Claude](https://img.shields.io/badge/Claude-Skills-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![Portuguese](https://img.shields.io/badge/Language-Portuguese_(PT)-006600?style=for-the-badge)

A collection of skills for Claude, written in European Portuguese. I started this because I'm studying IT programming and wanted Claude to help me the same way every time with the things I keep repeating: studying, writing reports, understanding errors, working on GitHub, and preparing CVs and interviews.

Each skill is a folder with a `SKILL.md` file where I explain to Claude how to do that task.

## Skills

- **estudo**: takes my notes and turns them into summaries, study points and review questions
- **revisor-relatorios**: reviews reports (like my final project report) and points out problems with structure, clarity and Portuguese
- **explicador-erros**: explains error messages step by step and says how to fix them
- **gerador-readme**: writes READMEs for my projects
- **preparacao-entrevistas**: simulates technical and behavioural interviews for internships
- **adaptador-cv**: tailors my CV and cover letter to each job offer
- **revisor-codigo**: does code review and flags bad practices
- **commits-prs**: writes commit messages and Pull Request descriptions
- **planeador-projetos**: breaks an idea down into tasks and milestones
- **tom-estilo**: changes the tone of a text (more formal, simpler, more technical)
- **gerador-exercicios**: makes up programming exercises at different difficulty levels

## Structure

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

Each folder in `skills/` has at least a `SKILL.md`. Some will also have examples or checklists.

## How to use

Clone the repo and copy the folder of the skill you want into your Claude skills:

```bash
git clone https://github.com/TMseabra/claude-skills-pt.git
```

Then just ask for the task as usual. If your request matches the skill's description, Claude will use it. More detailed steps will go in `docs/como-instalar.md`.

## What a SKILL.md looks like

```markdown
---
name: skill-name
description: When to use this skill and what for.
---

# Skill name

## What it does
...

## Steps
1. ...
2. ...

## How to respond
...
```

The `description` matters most, because it's what Claude uses to decide whether to use the skill or not.

## Status

Still a work in progress. To do:

- [ ] write the `SKILL.md` for each skill
- [ ] add examples
- [ ] write `docs/como-instalar.md`
- [ ] test each skill with real requests and tweak the descriptions

## Contributing

If you have ideas or find something that could be better, open an issue or a Pull Request.

## Author

Tomás Seabra, student of the Programming Technician course (IT).

## License

MIT. See the `LICENSE` file.
