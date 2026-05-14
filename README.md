Caso de Teste 1: Login com credenciais válidas

Passos:
1. Acessar https://www.saucedemo.com/
2. Inserir usuário "standard_user"
3. Inserir senha "secret_sauce"
4. Clicar em login

Resultado esperado:
- Redirecionamento para página de produtos

Resultado obtido:
- Login realizado com sucesso

Status:
- Passou

Caso de Teste 2: Login com campos vazios

Passos:
1. Acessar página
2. Deixar campos em branco
3. Clicar em login

Resultado esperado:
- Exibir mensagem de erro

Resultado obtido:
- Sistema exibiu erro corretamente

Status:
- Passou

Caso de Teste 3: Fluxo de carrinho

Passos:
1. Realizar login
2. Adicionar produto
3. Acessar carrinho
4. Remover produto
5. Voltar para loja

Resultado esperado:
- Todas as ações funcionam corretamente

Resultado obtido:
- Fluxo executado com sucesso

Status:
- Passou

Caso de Teste 4: Persistência do carrinho

Passos:
1. Adicionar item ao carrinho
2. Recarregar página
3. Verificar carrinho

Resultado esperado:
- Item permanece no carrinho

Resultado obtido:
- Item permaneceu corretamente

Status:
- Passou

Bug 1: Mensagem de erro com layout comprimido

Tipo: UI / UX

Passos:
1. Inserir dados inválidos no login
2. Clicar em login

Resultado:
- Texto da mensagem aparece comprimido

Impacto:
- Dificulta leitura para o usuário

Bug 2: Cursor não indica elemento clicável no carrinho

Tipo: UI / UX

Passos:
1. Realizar login
2. Passar mouse sobre ícone do carrinho

Resultado:
- Cursor não muda para "pointer"

Impacto:
- Pode causar confusão sobre interatividade

Bug 3: Navegação inconsistente com botão voltar

Tipo: Navegação

Passos:
1. Login
2. Acessar carrinho
3. Clicar no botão voltar do navegador

Resultado:
- Redireciona para tela de login

Impacto:
- Navegação inesperada para o usuário

Descrição:
- Sistema valida um campo por vez

Sugestão:
- Exibir todos os erros simultaneamente

Impacto:
- Melhorar experiência do usuário

Melhoria 2: Controle de quantidade no carrinho

Descrição:
- Não é possível adicionar múltiplas unidades do mesmo item

Sugestão:
- Permitir ajuste de quantidade

Impacto:
- Melhor experiência de compra
