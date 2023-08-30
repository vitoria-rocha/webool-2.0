<div align="center">

<img alt="Cabeçalho UFMS" src="/.assets/cabecalho_docs.png" />

## Especificação de Requisitos de Software

</div>

### 1. Introdução

Este documento registra os requisitos detalhados do Sistema `WEBOOL 2.0 - Reengenharia estratégica e ampliação do Website para apoio ao ensino de pessoas com Deficiência Intelectual`, na forma de requisitos textuais do produto.

### 2. Classes de usuários

#### 2.1 Aluno

A classe de usuário "Aluno" compreende os alunos que possuem deficiência intelectual e utilizam o WEBOOL como parte de seu processo educacional. Esses estudantes têm características e responsabilidades específicas:

- **Responsabilidades:** Acessar atividades educacionais adaptadas às suas necessidades, interagir com o conteúdo por meio de elementos visuais e interativos, utilizar o recurso de Realidade Aumentada para enriquecer as experiências de aprendizado.

- **Restrições de Acesso:** O acesso é focado em atividades educacionais e interações específicas, visando a inclusão e a adaptação às suas capacidades.

- **Características Relevantes:** Necessidades especiais de aprendizado, uso de interfaces acessíveis, possíveis limitações cognitivas.

#### 2.2 Professor

A classe de usuário "Professor" engloba os educadores que trabalham com os estudantes deficientes intelectuais, utilizando o WEBOOL como ferramenta de apoio. Os professores/tutores possuem as seguintes características e responsabilidades:

- **Responsabilidades:** Criar e adaptar atividades educacionais no sistema, monitorar o progresso dos estudantes, avaliar o desempenho dos alunos, proporcionar assistência e orientação durante as atividades.

- **Restrições de Acesso:** Acesso às atividades disponíveis no website.

- **Características Relevantes:** Conhecimento pedagógico, compreensão das necessidades dos estudantes especiais.

---

### 3. Definição de conceitos

Nesta seção são descritos os principais conceitos relevantes para o domínio do sistema.

**Alunos** - Refere-se aos alunos com limitações intelectuais que utilizam o WEBOOL como uma ferramenta de aprendizado adaptada às suas necessidades. Eles interagem com atividades educacionais e recursos de Realidade Aumentada.

**Atividade Adaptada** - São atividades educacionais criadas juntamente aos professores/tutores para se adequarem às capacidades dos estudantes deficientes intelectuais. Essas atividades podem envolver diferentes formatos e níveis de interação.

**Realidade Aumentada (RA)** - Uma tecnologia que combina elementos do mundo real com elementos virtuais, oferecendo uma experiência enriquecida de aprendizado por meio da sobreposição de informações virtuais no ambiente real.

**Professor** - Educadores responsáveis por auxiliar na criação e adaptação de atividades educacionais no WEBOOL para estudantes deficientes intelectuais. Eles monitoram o progresso dos alunos e fornecem orientação aos desenvolvoderes a respeito de melhorias e ajustes.

**Inclusão Digital** - O processo de garantir que todas as pessoas, incluindo aquelas com deficiências, tenham acesso e habilidades para utilizar tecnologias digitais, como a internet e aplicativos.

---

### 4. Requisitos de Software

#### 4.1. Requisitos Funcionais

O WEBOOL foi projetado para oferecer um ambiente educacional interativo e adaptado para alunos com deficiência intelectual. Para atender às necessidades variadas dos estudantes e facilitar a gestão dos professores, foram estabelecidos requisitos funcionais específicos para cada atividade.

#### Atividade de Língua Portuguesa

1. **RF-LP01:** O sistema deve apresentar atividades de reforço em Língua Portuguesa, nas quais os estudantes serão incentivados a digitar as letras correspondentes à figura apresentada. A atividade apresentará figuras de A a Z. O propósito principal é que os alunos identifiquem imagens e as relacionem às letras correspondentes. É importante ressaltar que o intuito não é promover a alfabetização em si, uma vez que esse aspecto será abordado de maneira abrangente pelos professores em sala de aula. A atividade visa, portanto, ser um complemento ao conteúdo instruído em ambiente escolar.

2. **RF-LP02:** O sistema deve automatizar o avanço do cursor do teclado para a próxima letra assim que o usuário inserir corretamente a letra requerida no campo de texto.

3. **RF-LP03:** O sistema deve ser capaz de automatizar a reprodução de áudio no início e no término de cada palavra, ao mesmo tempo em que possibilita ao professor reproduzir manualmente o áudio quando requerido, por meio da implementação de um botão dedicado.

#### Atividade de Matemática

1. **RF-MAT01:** O sistema deve exibir figuras geométricas básicas, incluindo triângulo, retângulo, quadrado e círculo, permitindo que os estudantes reconheçam visualmente as formas.

2. **RF-MAT02:** O sistema deve permitir ir para a proxima figura pressionando qualquer tecla

3. **RF-MAT03:** O sistema deve incorporar a funcionalidade de reprodução automática de áudio ao iniciar cada atividade, ao mesmo tempo em que possibilita ao professor reproduzir manualmente o áudio quando requerido, por meio da implementação de um botão dedicado.

#### Atividade de História com Realidade Aumentada

1. **RF-HIST01:** O sistema deve integrar a tecnologia de Realidade Aumentada para proporcionar uma experiência interativa, permitindo aos estudantes explorar pontos turísticos de Aquidauana-MS.

2. **RF-HIST02:** O sistema deve permitir que os estudantes interajam de forma tátil e visual com elementos virtuais relacionados a cada ponto turístico durante a atividade de História.

3. **RF-HIST03:** O sistema deve integrar a capacidade de iniciar a reprodução de áudio automaticamente ao iniciar cada ponto turístico da atividade de história. Além disso, deve permitir que o professor controle manualmente a reprodução do áudio conforme necessário, com a inclusão de um botão específico para essa função. O conteúdo de áudio em questão deve estar vinculado ao ponto turístico em foco, sendo conciso e breve, oferecendo uma visão sucinta da história do local.

#### Atividade de Artes - Jogo da Memória

1. **RF-ARTES01:** O sistema deve oferecer um jogo da memória com três estilos distintos: Pintores brasileiros, Arte rupestre e Arte gótica, desafiando os estudantes a combinar pares de cartas.

2. **RF-ARTES02:** O sistema deve reproduzir áudios informativos sobre a história das obras de arte correspondentes sempre que os estudantes completarem pares corretos no jogo da memória.

**RF-ARTES02:** O sistema deve possibilitar a virada de uma carta aleatória ao pressionar qualquer tecla.

#### Perfil de usuário
**RF-PERFIL01:** O sistema deve possuir um módulo de "Perfil de Usuário" que permita armazenar o progresso dos alunos nas atividades, facilitando a análise do desempenho e fornecendo informações relevantes para os professores. O perfil de usuário conterá as seguintes informações:

1. Nome Completo: O nome completo do aluno.
2. Turma: A turma à qual o aluno está associado.
3. Data de Atividade: A data em que a atividade foi realizada.

O sistema deverá permitir aos professores:

1. **Criar Turmas**: Os professores poderão criar turmas e associar alunos a essas turmas.
2. **Associar Perfil do Aluno à Turma**: Os professores poderão atribuir o perfil de um aluno a uma turma específica.
3. **Visualizar Progresso Individual**: Os professores terão acesso ao perfil de cada aluno, onde poderão visualizar o progresso nas atividades, incluindo erros e acertos.
4. **Identificar Dificuldades**: O sistema fornecerá insights sobre as áreas nas quais cada aluno apresenta mais dificuldade, permitindo que os professores forneçam suporte personalizado.
5. **Respeitar a Privacidade**: O perfil de usuário não conterá informações pessoais sensíveis, garantindo a privacidade dos alunos. Apenas o nome completo, a turma e a data das atividades serão armazenados.
6. **Gerar Relatórios**: Os professores poderão gerar relatórios consolidados com base no desempenho dos alunos em cada atividade, auxiliando na avaliação do progresso da turma como um todo.

Essa funcionalidade permitirá uma abordagem mais individualizada no ensino, fornecendo informações relevantes aos professores para auxiliá-los na identificação de áreas de dificuldade dos alunos e no planejamento de estratégias pedagógicas mais eficazes.

#### Plataforma Geral

1. **RF-PLAT01:** A plataforma deve incluir funcionalidades de acessibilidade que permitam aos professores determinar o modo de navegação nas atividades (por meio do teclado ou mouse). Essa flexibilidade deve ser ajustável de acordo com as necessidades individuais de cada aluno e o plano de ensino da escola. 

2. **RF-PLAT02:** A plataforma deve disponibilizar interfaces adaptadas que permitam ampliar letras ou imagens das atividades, garantindo a participação inclusiva de todos os estudantes nas tarefas.

#### 4.2. Requisitos não-funcionais

O WEBOOL é projetado com um foco na usabilidade, desempenho, segurança e acessibilidade. Além dos requisitos funcionais, os seguintes requisitos não-funcionais são essenciais para garantir uma experiência eficiente e inclusiva:

1. **Usabilidade e Acessibilidade:**
   - A plataforma WEBOOL deve ser de fácil utilização e intuitiva, garantindo que os alunos com deficiência intelectual possam navegar e interagir sem dificuldades.
   - A interface deve ser adaptável a diferentes dispositivos e tamanhos de tela para possibilitar o acesso em uma variedade de dispositivos.
   - A plataforma deve seguir diretrizes de acessibilidade, como a WCAG, para garantir que seja acessível para pessoas com diferentes tipos de deficiência.

2. **Desempenho:**
   - A plataforma WEBOOL deve ser responsiva e apresentar um desempenho eficiente, mesmo quando utilizada por um grande número de usuários simultaneamente.
   - O tempo de carregamento das atividades e recursos multimídia deve ser minimizado para evitar atrasos e proporcionar uma experiência fluida aos alunos.

3. **Segurança:**
   - A segurança dos dados pessoais dos alunos e professores deve ser assegurada, incluindo medidas para proteção contra acesso não autorizado e possíveis ameaças cibernéticas.
   - As informações confidenciais dos alunos devem ser protegidas de acordo com as regulamentações de privacidade.

4. **Compatibilidade:**
   - A plataforma WEBOOL deve ser compatível com uma variedade de navegadores web, garantindo uma experiência consistente para os usuários independentemente do navegador escolhido.

5. **Disponibilidade:**
   - A plataforma deve estar disponível de forma contínua e confiável, com um tempo de inatividade mínimo para que as atividades possam ser acessadas pelos alunos sempre que necessário.

6. **Adaptabilidade:**
   - As atividades e conteúdos multimídia devem ser adaptáveis para diferentes níveis de deficiência intelectual, permitindo a personalização para atender às necessidades individuais dos alunos.

9. **Integração com Laboratórios de Informática:**
   - A plataforma deve ser compatível com os sistemas e equipamentos presentes nos laboratórios de informática das instituições de ensino, garantindo uma experiência perfeita durante as atividades.

10. **Feedback dos Usuários:**
    - A plataforma deve permitir a coleta de feedback dos usuários, incluindo professores e alunos, a fim de melhorar continuamente a qualidade das atividades e da experiência geral.

---

### 5. Rastreabilidade de requisitos

A rastreabilidade bidirecional entre os requisitos aqui descritos e os demais artefatos do sistema está definida em `<inserir link para o documento de rastreabilidade do projeto>`. Todos elementos rastreados, incluindo os requisitos, utilizam seus identificadores únicos como referência no documento de rastreabilidade.
