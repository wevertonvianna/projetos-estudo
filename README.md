#📚 Projetos de Estudo

Repositório que reúne meus projetos de estudo (cursos, exercícios e projetos pessoais).

## Estrutura
- `/alura` — projetos de cursos (Alura)
- `/cursos-livres` — cursos gratuitos/outros
- `/pessoais` — projetos próprios
- `/faculdade` — projetos acadêmicos

---

## Como rodar um projeto local
Cada pasta de projeto deve ter um `README.md` próprio com instruções (ex.: requisitos, como criar virtualenv e como executar). Exemplo de padrão para cada projeto:

```markdown
# Nome do Projeto

Descrição curta.

## Tecnologias
- Python 3.10
- Flask / Django / Pandas

## Como rodar
1. python -m venv venv
2. source venv/bin/activate  # ou venv\Scripts\Activate.ps1 no Windows PowerShell
3. pip install -r requirements.txt
4. python app.py

## Observações
Arquivos grandes (.db, datasets pesados) não estão versionados 
