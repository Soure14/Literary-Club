# Sociedade Literária — versão inicial

## Como abrir
1. Extraia a pasta `literary-society-club`.
2. Abra `index.html` no navegador para visualizar o site.
3. Abra `admin.html` para gerenciar o conteúdo de demonstração.

Para evitar limitações de alguns navegadores com arquivos locais, recomenda-se executar a pasta com um servidor local (por exemplo, a extensão Live Server do VS Code).

## Painel administrativo
O painel permite adicionar, editar e excluir livros, concursos/notícias, vencedores, produtos e pessoas. Em Configurações, é possível alterar a apresentação, o texto do Caso Elisabet, links sociais, WhatsApp e fotografia.

Os dados são salvos no `localStorage` do navegador. Isso é adequado para protótipo e demonstração em um único dispositivo, mas **não é um sistema multiusuário seguro**. Não coloque dados privados nele. Para publicar com vários administradores, é necessário adicionar backend, autenticação e banco de dados (por exemplo, Supabase ou Firebase), além de regras de acesso.

## Personalização pendente
- Substituir textos de exemplo pela história oficial da fundadora e equipe.
- Adicionar fotografia autorizada de Elisabet em `assets/` e informar o caminho no painel.
- Adicionar capas e imagens dos livros/produtos.
- Inserir links oficiais das redes sociais e link de convite do WhatsApp.
- Confirmar regulamento dos concursos e critérios do pódio.
