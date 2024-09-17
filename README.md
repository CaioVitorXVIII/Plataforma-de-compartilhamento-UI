# Plataforma-de-compartilhamento-UI
Documentação da Aplicação: Interface de Plataforma de Compartilhamento de Arquivos 
1. Introdução
Propósito: Esta aplicação é uma interface web para uma plataforma de compartilhamento de arquivos, permitindo aos usuários acessar, visualizar e gerenciar documentos, fotos, vídeos e outros arquivos.
Tecnologias Utilizadas:
HTML5: Estrutura da página.
CSS3: Estilos e layout da interface.
JavaScript (DOM Manipulation): Interação e funcionalidade do usuário.
2. Estrutura de Diretórios
index.html: Arquivo principal de marcação HTML que define a estrutura da interface.
style.css: Arquivo de estilos que controla a aparência visual da aplicação.
script.js: Contém os scripts de interação da interface, como manipulação de eventos e controle de elementos dinâmicos.
3. Arquitetura
HTML (Estrutura): O arquivo index.html é a espinha dorsal da aplicação, organizando seções como a barra lateral, cabeçalho, tabela de arquivos e widgets laterais.
CSS (Estilos): O arquivo style.css estiliza todos os elementos da página para criar uma interface limpa, responsiva e interativa.
JavaScript (Interatividade): O arquivo script.js adiciona comportamento dinâmico, como seleção de itens, ocultação/exibição do menu lateral e seleção de arquivos na tabela.
4. Funcionalidades Principais
Navegação na Barra Lateral:
A barra lateral contém itens como "Painel de Controle", "Seus Arquivos", "Protegidos", etc. Cada item pode ser clicado para ser ativado visualmente​(index).
Seleção de Arquivos:
A tabela central lista arquivos recentes. Os arquivos podem ser selecionados, e o estilo muda conforme o arquivo é clicado​(style).
Exibição de Menu Responsivo:
O botão de menu no cabeçalho permite ocultar/exibir a barra lateral em telas menores, tornando a interface adaptável para diferentes dispositivos​(script)​(index).
Widgets Informativos:
Na seção direita, há widgets que exibem o uso do disco e opções para upload de arquivos e compras de plano premium​(index)​(style).
5. Componentes Principais
Barra Lateral (left-section): Contém links para navegar por diferentes seções do sistema de arquivos do usuário.
O JavaScript manipula a classe active para destacar o item selecionado​(script)​(style).
Tabela de Arquivos (main > table): Lista os arquivos recentes e permite selecionar um arquivo ao clicar em uma linha da tabela​(index).
Botão de Menu (#menu-btn): Exibe ou oculta a barra lateral em telas menores quando clicado​(script).
6. Fluxo de Dados
HTML e JavaScript: Não há fluxo de dados persistente (back-end ou API). O JavaScript manipula apenas o DOM da página, alterando classes e propriedades de estilo em resposta aos cliques dos usuários​(script)​(index).
7. Configuração e Ambiente
Pré-requisitos: Para rodar a aplicação localmente, basta abrir o arquivo index.html em um navegador web.
Ambiente de Desenvolvimento:
Um editor de texto, como VS Code, é recomendado para editar o HTML, CSS e JavaScript.
A aplicação não possui dependências externas além da biblioteca de ícones RemixIcon carregada via CDN​(index).
8. Instalação e Execução
Instalação:
Faça o download de todos os arquivos e abra o index.html diretamente no navegador.
Execução Local:
Nenhum servidor é necessário, já que a aplicação é puramente estática.
9. Testes
Testes Manuais:
Navegue pela interface clicando nos itens da barra lateral para verificar se a classe active é aplicada corretamente.
Clique nas linhas da tabela de arquivos para garantir que o comportamento de seleção funcione conforme o esperado.
10. Contribuição e Desenvolvimento
Como Contribuir:
Qualquer melhoria de código pode ser feita modificando os arquivos index.html, style.css ou script.js. Se desejar adicionar funcionalidades mais complexas, como upload real de arquivos ou autenticação, será necessário integrar um back-end.
11. Manutenção e Suporte
Contato de Suporte: Não especificado. No entanto, qualquer desenvolvedor familiarizado com HTML, CSS e JavaScript pode dar manutenção.

