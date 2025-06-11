# Projeto Checklist

Este é um projeto de aplicação de checklist criado com o objetivo de aplicar boas práticas de desenvolvimento, versionamento, testes e automação. Ideal para portfólio e demonstração de habilidades DevOps, CI/CD e organização de projeto.

---

## Funcionalidades

- Criação e gerenciamento de tarefas
- Marcar itens como concluídos
- Organização por categorias (trabalho, estudos, pessoal, etc.)
- Interface simples e intuitiva
- Estrutura pensada para testes manuais e automatizados

---

## Mapeamento da Aplicação

O projeto foi iniciado com um **mapa mental**, definindo a estrutura lógica e a divisão de módulos e responsabilidades.

---

## Tecnologias utilizadas

- Python `3.12.3`
- Framework (ex: Flask ou FastAPI) → *(inserir se estiver usando)*
- HTML/CSS e JavaScript (se houver interface)
- Postman (para testes manuais de API)
- Robot Framework (para testes automatizados)
- GitHub Actions (para CI/CD)
- Docker (opcional, para ambiente isolado de testes)

---

## Organização do Projeto

```bash
projeto_checklist/
│
├── app/                   # Código-fonte da aplicação
│   ├── __init__.py
│   └── ...
├── tests/                 # Testes automatizados
│   └── ...
├── docs/                  # Documentação do projeto
│   └── mapa_mental.png
├── .github/workflows/     # Pipelines CI/CD
│   └── ci.yml
├── README.md
└── requirements.txt
