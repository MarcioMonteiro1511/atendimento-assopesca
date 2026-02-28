Relatório de Desenvolvimento: Sistema de Gestão ASSOPESCA
1. Introdução e Objetivo
O projeto consiste em uma aplicação web de página única (SPA) desenvolvida para a ASSOPESCA, com o objetivo de centralizar e automatizar a gestão de associados, colaboradores e atendimentos institucionais.
O foco principal foi substituir processos manuais por uma interface digital responsiva, garantindo que a diretoria e os colaboradores possam acessar dados críticos tanto em desktops quanto em dispositivos móveis (celulares/tablets).
________________________________________
2. Metodologia Aplicada: Ágil
O desenvolvimento seguiu os princípios do Manifesto Ágil, focando em:
•	Entrega Incremental: O sistema foi construído em ciclos (Sprints). Começamos pelo núcleo de login, seguido pelo cadastro de associados e, finalmente, relatórios avançados e funções de exportação.
•	Resposta Rápida a Mudanças: Cada ajuste solicitado (como a inclusão de campos de endereço ou funções de PDF) foi integrado imediatamente ao ciclo de desenvolvimento.
•	Foco no Usuário Final: A interface foi desenhada para ser simples, priorizando a usabilidade no dia a dia da associação.
________________________________________
3. Funcionalidades do Sistema
O sistema foi dividido em módulos integrados:
Módulo	Descrição
Autenticação	Sistema de login seguro com níveis de acesso (Diretoria e Colaborador) e atalhos de teclado.
Gestão de Associados	Cadastro completo com CPF, endereço, telefone e histórico de entrada.
Módulo de Atendimento	Registro de 17 tipos de serviços diferentes com busca dinâmica de associados.
Recursos Humanos	Gestão de Colaboradores e Diretoria com cálculo automático de tempo de serviço.
Inteligência e Relatórios	Gráficos dinâmicos em tempo real e tabelas analíticas.
Exportação e Backup	Geração de PDFs individuais, comprovantes de atendimento e relatórios gerais para impressão.
________________________________________
4. Arquitetura Técnica
Para garantir leveza e velocidade, o sistema utiliza:
•	Frontend: HTML5, CSS3 (com Media Queries para responsividade) e JavaScript Puro (Vanilla JS).
•	Gráficos: Biblioteca Chart.js para visualização de dados.
•	Documentação: Biblioteca jsPDF para geração de arquivos em PDF no lado do cliente.
•	Armazenamento: LocalStorage para persistência de dados local, eliminando a necessidade inicial de servidores de banco de dados complexos.
________________________________________
5. Funcionamento Operacional
1.	Acesso: O usuário entra com suas credenciais. O sistema identifica o nível de poder (Diretores veem as configurações e RH; Colaboradores apenas atendimentos).
2.	Operação: Ao realizar um atendimento, o sistema vincula automaticamente o associado selecionado ao serviço prestado.
3.	Saída de Dados: O administrador pode, a qualquer momento, gerar um PDF de uma ficha ou imprimir um relatório de produtividade para reuniões de diretoria.
________________________________________
6. Conclusão
O sistema ASSOPESCA atingiu sua maturidade tecnológica ao equilibrar uma interface moderna com ferramentas robustas de exportação de dados. A adoção da metodologia ágil permitiu que o software fosse personalizado exatamente para as necessidades reais da associação, resultando em uma ferramenta eficiente, rápida e totalmente móvel.
