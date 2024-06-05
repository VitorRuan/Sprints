<span id="topo">

<h1 align="center">Sprint 3: 29/05/2024 a 11/06/2024</h1>

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
</p>

Nesta terceira sprint, o foco principal está na implementação das funcionalidades de exportação de dados, que são essenciais para a geração de relatórios detalhados e personalizados sobre os professores. Essas funcionalidades visam proporcionar à equipe administrativa ferramentas robustas e flexíveis para criar e exportar registros e relatórios de acordo com diferentes necessidades e critérios específicos.

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Implementar as funcionalidades essenciais de gerenciamento de registros de professores no sistema:
- **RF 09:** Exportar Registro de um Objeto Específico
- **RF 10:** Exportar um Relatório Geral de todos os Objetos
- **RF 11:** Exportar um Relatório conforme as preferências do usuário
- **RNF 01:** Utilizar Javascript e Typescript
- **RNF 02:** Utilizar banco de dados NoSql (MongoDB)
- **RNF 03:** Documentação
- **RNF 04:** Autenticação

<span id="entregas">
        
## :heavy_check_mark: Entregas
As entregas desta sprint são cruciais para aprimorar a capacidade administrativa de gerar relatórios detalhados e personalizados sobre os professores. As funcionalidades de exportação de dados não apenas fornecem flexibilidade e eficiência na gestão dos dados, mas também garantem que a administração possa responder rapidamente às necessidades de relatórios específicos e detalhados. 

### RF 09: Exportar Registro de um Objeto Específico

Esta funcionalidade permite que os usuários exportem os registros de um objeto específico após a realização de uma pesquisa. Isso envolve a recuperação dos dados do objeto a partir do banco de dados e a geração de um arquivo de exportação (por exemplo, PDF, CSV) contendo essas informações. É essencial para fornecer relatórios personalizados e documentação. Isso facilita a criação de registros físicos ou digitais para fins administrativos, auditorias, ou qualquer outra necessidade que exija a apresentação formal dos dados de um objeto específico.

### RF 10: Exportar um Relatório Geral de todos os Objetos

Esta funcionalidade permite a exportação de um relatório abrangente que inclui os registros de todos os objetos cadastrados no sistema. O relatório deve ser gerado em um formato que seja fácil de ler e compartilhar, como PDF ou CSV. É fundamental para a administração, pois permite a análise completa e a apresentação dos dados de todos os objetos. Isso é útil para revisões de desempenho, planejamento de recursos, reuniões administrativas, e para manter registros atualizados para as partes interessadas.

### RF 11: Exportar um Relatório conforme as preferências do usuário

Esta funcionalidade permite que os usuários exportem dados dos objetos com base em critérios específicos definidos por eles. Por exemplo, o usuário pode filtrar os professores por disciplina, curso, data de contratação, entre outros, e exportar os resultados dessa filtragem. A capacidade de exportar dados filtrados oferece flexibilidade e personalização. Isso permite que a administração obtenha relatórios sob medida que atendam a necessidades específicas, como relatórios de professores por departamento, análise de carga horária por curso, ou qualquer outra combinação de critérios relevantes.

### RNF 01: Utilizar Javascript e Typescript

Este requisito não funcional estabelece que o sistema deve ser desenvolvido utilizando principalmente JavaScript e TypeScript como linguagens de programação. O JavaScript é uma linguagem de programação amplamente utilizada para o desenvolvimento de aplicações web, enquanto o TypeScript é uma extensão do JavaScript que adiciona recursos de tipagem estática, tornando o código mais robusto e fácil de manter.

### RNF 02: Utilizar banco de dados NoSql (MongoDB)

Este requisito não funcional estabelece que o sistema deve utilizar um banco de dados NoSQL, especificamente o MongoDB. O MongoDB é um banco de dados NoSQL amplamente utilizado que utiliza um modelo de dados flexível baseado em documentos JSON, o que o torna ideal para aplicações com requisitos de escalabilidade e flexibilidade de esquema.

### RNF 03: Documentação 

A documentação é um requisito não funcional crucial que assegura que todos os aspectos do sistema sejam claramente explicados, facilitando a compreensão, manutenção e expansão futura do projeto. No contexto do nosso sistema de cadastro de professores e cursos, a documentação envolve a criação de recursos que descrevem a arquitetura, funcionalidades, uso, e desenvolvimento do sistema.

### RNF 04: Autenticação

Este requisito não funcional estabelece que o sistema deve implementar um sistema de autenticação seguro para garantir a segurança dos dados e proteger o acesso não autorizado às funcionalidades do sistema. Isso envolve a implementação de um sistema de login e senha, com técnicas de criptografia adequadas para proteger as credenciais dos usuários durante a transmissão e armazenamento.

→ [Voltar ao topo](#topo)
