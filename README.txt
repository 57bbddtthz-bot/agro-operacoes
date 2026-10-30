AGRO OPERAÇÕES — VERSÃO 3 (PROTÓTIPO DE VALIDAÇÃO)

O que há nesta versão:
- Tela de entrada com seleção de perfil demonstrativo.
- Painel do chefe/administrador, técnico e dosador.
- Estrutura Empresa > Fazenda > Sede > Talhão.
- Cadastro de fazendas, sedes, talhões e funcionários.
- Ordens de serviço com atribuição de dosador e técnico.
- Registro individual de voos e fechamento diário.
- Fluxo demonstrativo de aprovação de fechamentos e pedidos de alteração.
- Ocorrências, relatórios e histórico de atividades.
- Backup e restauração local em JSON.

IMPORTANTE:
Este é um protótipo local para testes de navegação e validação do fluxo. Os dados ficam no armazenamento do navegador/aparelho. O login é demonstrativo (senha 1234), não é autenticação real. Não há servidor, sincronização entre aparelhos, isolamento seguro entre empresas, criptografia de dados em repouso, controle de sessão ou auditoria inviolável. Não use dados operacionais sensíveis ou credenciais reais. Para produção será necessário backend, autenticação, permissões validadas no servidor, banco de dados, sincronização offline, backups e testes de segurança.

Como testar:
1. Abra index.html em um navegador moderno.
2. Selecione o perfil (Chefe, Técnico ou Dosador).
3. Use a senha 1234.
4. A tela de login permite escolher perfil para demonstração; os dados de exemplo são locais.
5. Faça backup em Backup e dados.

Para instalar como PWA no iPhone, o app precisa ser publicado em um endereço HTTPS com service worker. Esta pasta ainda não inclui hospedagem ou servidor.

Idealizado e fundado por Guilherme Paiao A. Ribeiro.
