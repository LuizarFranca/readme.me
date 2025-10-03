# readme.me
Iniciando o mundo cloud

- Computação em nuvem com a AWS

A Amazon Web Services (AWS) é a plataforma Cloud mais adquirida e mais abrangente pelo mundo, oferecendo mais de varios tipos de serviços completos de datacenters em todo o mundo.
Os serviços que são oferecidos pela AWS como de tecnologias de infraestrutura, computação, armazenamento e bancos de dados, a tecnologias emergentes como machine learning e inteligência artificial, data lakes, análises e Internet das Coisas.

Benefícios da computação em nuvem

- Agilidade
A nuvem oferece acesso fácil a uma grande variedade de tecnologias para que você possa inovar, implantar serviços, criar praticamente tudo o que puder imaginar e gerar recursos conforme a necessidade.

- Economia de custo
A nuvem permite que você troque despesas fixas (datacenters e servidores físicos) por despesas variáveis e pague apenas pelo serviço consumido. 

- Implantação global em questão de minutos
a AWS tem infraestrutura em todo o mundo, você pode ampliar e implantar as atividades pelo mundo em minutos.

 Modelos de computação em nuvem: Os Tres tipos de computação em nuvem são de infraestrutura  (IaaS) , plataforma (PaaS) e software (SaaS). Para cada tipo de serviço são oferecidos diferentes niveis de controle, flexibilidade e gerenciamento.

 - A IaaS contém os componentes básicos de TI em nuvem e, geralmente, fornece acesso a recursos de rede e computadores (virtuais ou em hardware dedicado), além de espaço para armazenamento de dados.

- Com a PaaS, Os fornecedores de PaaS eliminam a necessidade de as organizações gerenciarem a infraestrutura subjacente (geralmente hardware e sistemas operacionais), e essa integração permite que você se concentre na implantação e no gerenciamento de suas aplicações sem se preocupara com os recursos, planejamento e manutenção.

- Já o SaaS, os fornecedores SaaS disponibilizam aplicações de software executadas e gerenciadas por eles. Na maioria dos casos, quando as pessoas mencionam SaaS, estão falando de aplicações de usuários finais.Não é necessário se preocupar em como o serviço é mantido ou como a infraestrutura é gerenciada, você só precisa pensar em como usará esse tipo específico de software.

Modelos de implantação em nuvem:

- Nuvem
 Uma aplicação baseada na nuvem é totalmente implantada na nuvem e todos os aspectos da aplicação são executados nela. As aplicações na nuvem foram criadas nela ou foram migradas de uma infraestrutura existente para aproveitarem os benefícios da computação em nuvem.
 
- Híbrida
Uma implantação híbrida é uma maneira de conectar infraestrutura e aplicações entre recursos da Web e recursos atuais que não se encontram na nuvem.

- On-premises
A implantação de recursos on-premises, usando a virtualização e fornecendo ferramentas de gerenciamento de recursos, não oferece muitos dos benefícios de computação em nuvem, mas, às vezes, é procurada por sua capacidade de fornecer recursos dedicados. Na maioria dos casos, este modelo de implantação é igual à infraestrutura de TI antiga, pois usa tecnologias de gerenciamento e virtualização de aplicações para tentar aumentar a utilização de recursos.

Computação na Nuvem com EC2

O Amazon EC2 oferece uma ampla seleção de tipos de instâncias otimizadas para atender a diferentes casos de uso. Os tipos de instâncias consistem em várias combinações de CPU, memória, armazenamento e capacidade de rede e oferecem flexibilidade de escolha da composição adequada de recursos para os seus aplicativos.
O EC2 permite a implantação de aplicações ao prover um Web service através do qual um usuário pode iniciar uma Amazon Machine Image para criar uma máquina virtual, que a Amazon chama uma "instância", contendo qualquer software desejado.
As Instancias fornecem um equilíbrio de recursos de computação, memória e rede e podem ser usadas para diversas cargas de trabalho. Essas instâncias são ideais para aplicações como servidores web e repositórios de código. 

- A Amazon possui várias opções de armazenamento um deles é volume EBS, os volumes do Amazon EBS persistem independentemente da vida útil de uma instância do Amazon EC2. Após a criação, um volume pode ser conectado a qualquer instância do Amazon EC2. Depois de conectado ou desconectar, o volume aparecerá como um dispositivo montado, semelhante a qualquer disco rígido ou outro dispositivo de bloco. O EBS é a opção de armazenamento recomendada para executar um banco de dados no Amazon EC2.

- Além do armazenamento em blocos por meio do Amazon EBS ou de instâncias, também pode ser usado o Simple Storage Service (Amazon S3) para obter um armazenamento de objetos altamente durável e altamente disponível. O S3 fornece acesso a uma infraestrutura de armazenamento de dados confiável e de baixo custo. Ele foi criado para facilitar a computação em web, permitindo que armazene e recupere qualquer quantidade de dados, a qualquer momento, de dentro do Amazon EC2.

- Enquanto o Lambda é uma plataforma sem servidor que executa seu código em resposta a eventos sem que você precise se preocupar com os servidores subjacentes.
  
Gerenciando EC2 instâncias da Amazon

Iniciando uma instância do EC2

Vá para a guia EC2, caso não encontre, pode realizar pesquisa por "EC2" na seção Pesquisar no canto superior direito do seu portal Amazon AWS ou selecionando-o entre os serviços no Console Início.
Em seguida começará a ver as instancias ja alocadas na sua conta. Clique em iniciar Instacia para que comece a configurar.

Selecione uma imagem de maquina virtual da Amazon (AMI), ja pré configurada com o software que precisa. Ao escolher uma AMI, está escolhendo o KIT Inicial para sua instancia, semelhando ao aluguel de um computador com sistema operacional Linux ou Windows instalado.
