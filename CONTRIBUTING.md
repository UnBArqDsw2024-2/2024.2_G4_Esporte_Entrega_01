# Contributing

## Layout de Pull Request

Describe the big picture of your changes here to communicate to the maintainers why we should accept this pull request. If it fixes a bug or resolves a feature request, be sure to link to that issue.

Types of changes
What types of changes does your code introduce to <repo_name>?
Put an x in the boxes that apply

 Bugfix (non-breaking change which fixes an issue)
 New feature (non-breaking change which adds functionality)
 Breaking change (fix or feature that would cause existing functionality to not work as expected)
 Documentation Update (if none of the other choices apply)
Checklist
Put an x in the boxes that apply. You can also fill these out after creating the PR. If you're unsure about any of them, don't hesitate to ask. We're here to help! This is simply a reminder of what we are going to look for before merging your code.

 I have read the CONTRIBUTING.md doc.
 I have added necessary documentation (if appropriate).
 Any dependent changes have been merged and published in downstream modules.
Further comments
If this is a relatively large or complex change, kick off the discussion by explaining why you chose the solution you did and what alternatives you considered, etc...

## Layout de commit

<tipo>(escopo opcional): <descrição breve>

[corpo do commit opcional]

[footer opcional]

Tipo: Indica a intenção principal do commit. Exemplos:
 
Seguindo as seguintes  ideias

feat: Adiciona uma nova funcionalidade.
fix: Corrige um bug.
chore: Atualizações triviais, como mudanças no build, dependências, etc.
docs: Atualizações na documentação.
style: Mudanças de formatação, como espaços, vírgulas, etc., sem impactar a lógica.
refactor: Refatorações de código que não afetam a funcionalidade.
test: Adiciona ou modifica testes.
Escopo: (Opcional) Especifica a área afetada pelo commit (ex.: auth, api, ui).

Descrição Breve: Resumo da mudança, em até 50 caracteres, usando o imperativo. Exemplo: fix(auth): corrigir problema de login com MFA.

Corpo: (Opcional) Explicação mais detalhada sobre a mudança, se necessário. Útil para descrever o motivo da mudança e o que ela resolve.

Footer: (Opcional) Incluir informações adicionais, como referências a tickets ou issues (ex.: Closes #123 ou Relates to #456).

[Ex de contibuting](https://github.com/DNXLabs/terraform-aws-ecs/blob/master/CONTRIBUTING.md)


## Layout de branch

<tipo>(escopo opcional):<o que tá fazendo>

feat: Adiciona uma nova funcionalidade.
fix: Corrige um bug.
chore: Atualizações triviais, como mudanças no build, dependências, etc.
docs: Atualizações na documentação.
style: Mudanças de formatação, como espaços, vírgulas, etc., sem impactar a lógica.
refactor: Refatorações de código que não afetam a funcionalidade.
test: Adiciona ou modifica testes.

Exemplo:
Docs-Artefato-Storyboard