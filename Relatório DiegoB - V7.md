
# **RELATÓRIO DE ATIVIDADES DE ESTÁGIO**




### **AGRADECIMENTOS**

Agradeço primeiramente a Deus, pela vida e por estar presente em todos os momentos dando-me força, persistência e sabedoria. A minha mãe Clair e meu irmão Dionatan, por estarem ao meu lado, tanto nos momentos bons quanto nas dificuldades, e, pela compreensão dos momentos de minha ausência.

Agradeço ao meu professor orientador Cleitom Richter pela orientação, pelos ensinamentos, paciência e compreensão ao longo desta trajetória, e a todos os professores das disciplinas técnicas que contribuíram para minha formação. 

Agradeço aos demais professores que tiveram importante papel na minha formação acadêmica, bem como aos funcionários da instituição, em especial a organização da escrita acadêmica, pois, favoreceu o desenvolvimento do relatório, através das oficinas de formatação de textos, citações e referências em trabalhos acadêmicos de acordo com a Associação Brasileira de Normas Técnicas.

Aos colegas, pela amizade e trocas de experiências, em especial Camila, Davi e Otávio, pelo incentivo, apoio e conselhos. Estas pessoas que fizeram parte de minha formação e sem dúvida, vão continuar presentes em minha vida.


### **LISTA DE FIGURAS**

[Figura 1 - Fachada da Prefeitura Municipal de Tenente Portela	13](#_Toc115277395)

[Figura 2 – Captura de tela: Hardware do Servidor	16](#_Toc115277396)

[Figura 3 - Rack que comporta o servidor	17](#_Toc115277397)

[Figura 4 - Captura de tela: Criação do *pendrive* *bootável*	18](#_Toc115277398)

[Figura 5 - Computador para ser limpo	20](#_Toc115277399)

[Figura 6 - Captura de tela: Kaspersky Rescue Disk	21](#_Toc115277400)

[Figura 7 - Captura de tela: AOMEI Backupper	22](#_Toc115277401)

[Figura 8 - Gabinete a ser instalado as peças	23](#_Toc115277402)

[Figura 9 - Instalação de placa de vídeo	24](#_Toc115277403)

[Figura 10 - Troca de pasta térmica	24](#_Toc115277404)

[Figura 11 - Verificação de disco com HDD Regenerator	25](#_Toc115277405)

[Figura 12 - HDs não-funcionais	26](#_Toc115277406)

[Figura 13 - Captura de tela: Modificação de propriedades de rede	27](#_Toc115277407)

[Figura 14 - Captura de tela: Processo de *Backup*	28](#_Toc115277408)

[Figura 15 - Computador formatado	30](#_Toc115277409)

[Figura 16 - Impressora	31](#_Toc115277410)

[Figura 17 - Captura de tela: Planilha feita no Excel	32](#_Toc115277411)

[Figura 18 - Cabo UTP	32](#_Toc115277412)

[Figura 19 - Conector 8P8C (RJ-45)	33](#_Toc115277413)

[Figura 20 - Alicate crimpador	33](#_Toc115277414)

[Figura 21 - Sequências de cores padrão T-568A e T-568B	34](#_Toc115277415)

[Figura 22 - Cabo de rede par trançado	35](#_Toc115277416)

[Figura 23 - Impressora instalada	36](#_Toc115277417)

[Figura 24 - Captura de tela: Active Directory	37](#_Toc115277418)

[Figura 25 - Captura de tela: Windows Password Unlocker	38](#_Toc115277419)

[Figura 26 - Captura de tela: Atualização do programa	39](#_Toc115277420)

[Figura 27 - Fluxo de processos linear	41](#_Toc115277421)

[Figura 28 - Diagramas UML (Unified Modeling Language)	41](#_Toc115277422)

[Figura 29 – Diagrama: Caso de uso	42](#_Toc115277423)

[Figura 30 – Diagrama: Diagrama de classe	43](#_Toc115277424)

[Figura 31 - Tela de Login	44](#_Toc115277425)

[Figura 32 - Tela de Logado	45](#_Toc115277426)

[Figura 33 - Tela de Erro	45](#_Toc115277427)

[Figura 34 - Tela Principal	46](#_Toc115277428)

[Figura 35 - Tela de Cadastro	46](#_Toc115277429)

[Figura 36 - Captura de tela: Visual Studio Code	47](#_Toc115277430)

[Figura 37 - Captura de tela: Repositório no GitHub	48](#_Toc115277431)


### **LISTA DE ABREVIATURAS**

AD	= *Active Directory*

BIOS	= *Basic Input/Output System*

CD	= *Compact Disc*

DTI	= Departamento de Tecnologia da Informação

DVD	= *Digital Versatile Disc*

GB	= *Gigabyte*

HD	= *Hard Disk*

IP	= *Internet Protocol*

ISO 	= *International Organization for Standardization*

MB	= *Megabyte*

NBR	= Norma Brasileira

PC	= *Personal Computer*

ROM	= *Read Only Memory*

RSAT	= Ferramentas de Administração de Servidor Remoto

SATA	= *Serial ATA*

STP	= *Shielded Twisted Pair*

TI	= Tecnologia da Informação

UEFI 	= *Unified Extensible Firmware Interface*

UML	= *Unified Modeling Language*

USB 	= *Universal Serial Bus*

UTP	= *Unshielded Twisted Pair*


### **SUMÁRIO**

[1 	INTRODUÇÃO	11****](#_TOC115277432)**

[**2 	APRESENTAÇÃO DA EMPRESA	13****](#_TOC115277433)

[**3 	ATIVIDADES REALIZADAS	15****](#_TOC115277434)

[3.1 	VISITA À ESTAÇÃO DE COMUNICAÇÃO DA PREFEITURA	15](#_TOC115277435)

[3.2 	CRIAÇÃO DE UM PENDRIVE INICIALIZÁVEL	17](#_TOC115277436)

[3.3 	MANUTENÇÃO DE EQUIPAMENTOS	18](#_TOC115277437)

[3.3.1 	Manutenção Preventiva	19](#_Toc115277438)

[3.3.2 	Manutenção Corretiva	22](#_Toc115277439)

[3.4 	BACKUP DE ARQUIVOS	27](#_TOC115277440)

[3.5 	FORMATAÇÃO E INSTALAÇÃO DE SISTEMA OPERACIONAL	28](#_TOC115277441)

[3.6 	CONSTRUÇÃO DE PLANILHA	31](#_TOC115277442)

[3.7 	MONTAGEM E CRIMPAGEM DE CABOS DE REDE	32](#_TOC115277443)

[3.8 	INSTALAÇÃO DE IMPRESSORA WIRELESS E DRIVERS	35](#_TOC115277444)

[3.9 	RECUPERAÇÃO DE SENHA DE SISTEMA OPERACIONAL	36](#_TOC115277445)

[3.10 	ATUALIZAÇÃO DE SOFTWARE INTERNO	38](#_TOC115277446)

[**4 	PROPOSTA DE SOLUÇÃO	40****](#_TOC115277447)

[4.1 	PLANEJAMENTO DE SOFTWARE	40](#_TOC115277448)

[4.1.1 	Diagrama de caso de uso	42](#_Toc115277449)

[4.1.2 	Diagrama de classe	42](#_Toc115277450)

[4.2 	PROTÓTIPO DE TELA	43](#_TOC115277451)

[4.2.1 	Telas do sistema	44](#_Toc115277452)

[4.3 	IMPLEMENTAÇÃO	47](#_TOC115277453)

[**5 	CONSIDERAÇÕES FINAIS	49****](#_TOC115277454)

[REFERÊNCIAS	50****](#_TOC115277455)**

[ANEXOS	53****](#_TOC115277456)**

[ANEXO A - CRIANDO UM *PENDRIVE* *BOOTÁVEL* COM O RUFUS	54](#_TOC115277457)

[ANEXO B - CONFIGURANDO A BIOS PARA *BOOT*	56](#_TOC115277458)

[APÊNDICES	58****](#_TOC115277459)**

[APÊNDICE A - INSTALAÇÃO WINDOWS 7	59](#_TOC115277460)

[APÊNDICE B - INSTALAÇÃO WINDOWS 10	62](#_TOC115277461)


# **1 INTRODUÇÃO** 

Com o advento da Revolução Técnico-Científica e Informacional, a tecnologia se desenvolveu em ritmo cada vez maior e levou a profundas mudanças na forma como o ser humano interage com o mundo. Nesse sentido, o indivíduo passou a estar cada vez mais conectado em rede, diversas atividades, que antes deviam ser feitas presencialmente, hoje podem ser efetivadas com apenas alguns cliques.

Sob essa ótica, para acompanhar esses avanços é imprescindível ter profissionais capacitados a trabalharem nessa área. Por isso, o Instituto Federal Farroupilha – Campus Santo Augusto, entre diversos cursos, oferta o Técnico de Informática Integrado ao Ensino Médio. 

De acordo com o Projeto Pedagógico do Curso Técnico em Informática (BRASIL, 2016), um de seus objetivos é desenvolver um profissional acostumado a lidar com as demandas de um nível técnico de TI, com capacidades concretas de prosseguir os estudos, ao mesmo tempo em que desempenha atividades profissionais qualificadas.

Diante disso, o presente relatório, tem como objetivo descrever as atividades realizadas no decorrer do Estágio Curricular Obrigatório Supervisionado, o qual é um dos instrumentos de prática profissional na formação. Segundo o referencial pedagógico, a prática do estágio:
> [...] terá duração de 100 horas relógio e deverá ser realizado a partir da conclusão com êxito do segundo ano de curso. Deverá ser realizado em empresas do ramo da Informática, com profissional disponível para supervisionar e orientar o estudante durante as atividades realizadas no estágio. (BRASIL, 2016, p. 28). 

Destarte, a prática se desenvolveu de forma presencial na Prefeitura Municipal de Tenente Portela, durante 100 horas, efetuado entre 03 de Janeiro de 2022 e 25 de Janeiro de 2022. O estágio decorreu no Departamento de Informática da prefeitura do município, que atua na área de suporte técnico de informática à prefeitura, escolas e suas secretarias.

Durante as atividades de estágio, foi possível colocar em prática os diversos conhecimentos obtidos no decorrer dos primeiros dois anos de formação do técnico de informática, como: manutenção de equipamentos, atividades relacionadas a redes de computadores, atividades relacionadas a *software* e analise de projeto de sistema.

Após a prática e, conforme preconiza o regulamento de estágio do curso, realizou-se uma análise crítica das rotinas da empresa para propor uma solução envolvendo tecnologia da informação e comunicação, eixo tecnológico do curso e, para isso, propôs-se uma solução de software que automatiza as demandas de serviço que, antecedentemente, era feita de maneira manual.

Para conduzir este relatório, os textos seguintes estão redigidos em cinco seções, incluindo esta: a segunda seção identifica a empresa e detalha suas atividades; já a terceira irá retratar as atividades realizadas durante o estágio; a quarta seção apresenta o projeto de software feito para solução de um problema identificado na empresa; por fim, as considerações finais deste trabalho são apresentadas na última seção.


# **2 APRESENTAÇÃO DA EMPRESA**

O município de Tenente Portela localiza-se na região noroeste do Estado do Rio Grande do Sul, fazendo divisa com os municípios de Vista Gaúcha, Derrubadas e Miraguaí. O estágio decorreu no Departamento de Informática da prefeitura do município, sendo o setor com maior equiparação aos conhecimentos do curso de Técnico em Informática.

A Prefeitura Municipal de Tenente Portela, localiza-se na Praça Tenente Portela, N° 23. Conta com cerca de 450 funcionários ativos, incluindo os que trabalham em escolas e outros setores do funcionalismo municipal. O horário de atendimento é realizado de segunda a sexta-feira durante horário comercial (Manhã 8h às 12h - Tarde 13h30min às 17h30min).

Figura 1 - Fachada da Prefeitura Municipal de Tenente Portela

Fonte: Prefeitura Municipal de Tenente Portela (2022)

O setor onde foi realizado o Estágio Curricular Obrigatório Supervisionado é composto pelo chefe de departamento e supervisor do estágio, Marcelo Castro, que assume o papel de técnico em informática. Esse departamento é responsável por prestar suporte técnico de informática à prefeitura, escolas e suas secretarias[^1]:

1) Secretaria de Administração, Planejamento e Comunicação Social: responsável por administrar e organizar as ações administrativas do Poder Executivo;
1) Secretaria de Assistência Social e Promoção Humana: responsável por organizar, acompanhar e fiscalizar os programas sociais e de proteção à criança, ao adolescente, ao idoso e ao portador de necessidades especiais;
1) Secretaria de Finanças: responsável por organizar, controlar e executar a política financeira e tributária do município;
1) Secretaria de Educação, Cultura e Desporto: responsável por fortalecer ações que garantam a permanência dos alunos em tempo integral na maioria das escolas municipais, garantindo os direitos das crianças, dos jovens e dos adultos à aprendizagem;
1) Secretaria de Desenvolvimento Econômico e Turismo: responsável por promover o desenvolvimento econômico do Município, relativamente às áreas de indústria, comércio e turismo, de modo em geral ao incentivo e incremento do desenvolvimento econômico municipal;
1) Secretaria de Políticas Estruturantes e Zeladoria: responsável por executar e coordenar e as ações e serviços essenciais à área urbana como, limpeza, conservação e ampliação de vias públicas, iluminação, segurança pública, dentre outros;
1) Secretaria de Saúde e Saneamento: responsável por planejar, organizar, gerir, controlar e avaliar as ações e os serviços públicos de saúde, vigilância sanitária, e saneamento básico.


# **3 ATIVIDADES REALIZADAS**

Inicialmente foi apresentado o Departamento de Tecnologia da Informação (DTI) da prefeitura, onde o estágio viria a acontecer. Esse primeiro momento foi de extrema importância para analisar toda a estrutura computacional do local e como as tarefas iriam ser realizadas.

Após uma breve conversa com o supervisor de estágio, foi acordado que o ciclo de estágio seria constituído da efetivação de demandas técnicas, e também para o estudo de determinadas linguagens de programação, que por sua vez seriam usadas como ferramentas para a criação de um *software*. A função dessa aplicação seria computar as demandas de assistência técnica que antes eram feitas manualmente.

As seções a seguir, apresentam em síntese as atividades que foram realizadas durante o desenvolvimento do estágio, e o referencial teórico de conceitos técnicos.

## 3.1 VISITA À ESTAÇÃO DE COMUNICAÇÃO DA PREFEITURA

Desde o ano de 2014, a empresa Meganet (Provedor de internet de Tenente Portela) disponibiliza para o município uma estação de comunicação de alta tecnologia e velocidade. Composta por um servidor central que conecta todas as secretarias e departamentos internos da prefeitura, o modelo de rede é o cliente/servidor, esse tipo de rede “possui um ou mais servidores, responsáveis por prover serviços de rede aos demais computadores conectados a ele que são chamados clientes”( FRANCISCATTO, 2014, p. 20).

Foi realizado o acesso ao servidor da prefeitura, que estava em operação, com o AnyDesk[^2], um software que ”conecta e sincroniza áreas de trabalho com o intuito de espalhá-las em outros dispositivos para que se consiga acompanhar e gerar uma interação entre computadores em tempo real” (LIRA, 2021, s/n). Após a conexão remotamente foi utilizado o *software* CPU-Z[^3][^4], buscando informações de *hardware*.

Figura 2 – Captura de tela: Hardware do Servidor

Fonte: elaborado pelo autor (2022).

A infraestrutura localiza-se no 1° pavimento da Prefeitura em uma sala em que apenas pessoas autorizadas podem fazer o ingresso. O servidor, PowerEdge R620, é organizado em um rack aberto. Segundo Dicomp Distribuidora (2020, s/n):

Rack é uma estrutura geralmente feita de metal no formato de gabinete ou parede, que permite armazenar e organizar os diferentes componentes de instalações da rede, como servidores, sistemas de armazenamento, switches, cabos, entre outros equipamentos.

Nesse sentido, o rack comporta o servidor e todos os componentes necessários para o seu funcionamento. A internet é distribuída através de dois *switches* (ambos 48 portas), de acordo com Torres (2010, p. 403) são pontes contendo várias entradas que podem enviar informações simultaneamente para os dispositivos com uma conexão estabelecida.

O cabeamento estruturado sob a ótica da NBR 16264 (2014) avalia técnicas e métodos para identificar e gerenciar a infraestrutura de telecomunicações, sendo um dos requisitos necessários o uso de identificadores para os componentes da infraestrutura. Contudo, os cabos conectados nos *switches* da prefeitura não possuem nenhum tipo de identificação de departamentos e/ou secretarias.

Figura 3 - Rack que comporta o servidor

Fonte: elaborado pelo autor (2022).

A falta desses identificadores causa algumas problemáticas referentes a conservação e manutenção da estação de comunicação. Com o cabeamento padronizado, o tempo de manutenções reduziria significativamente juntamente com a localização do cabo defeituoso, evitando assim que o cabo errado seja desconectado.

## 3.2 CRIAÇÃO DE UM PENDRIVE INICIALIZÁVEL

Foi orientado ao estagiário a criação de um *pendrive* de *boot* com o Windows PE (WinPE) para realização de operações futuras com o *software*. O Windows PE é usado para “instalar, implantar e reparar edições da área de trabalho do Windows, Windows Server e outros sistemas operacionais Windows” (MICROSOFT, 2022, s/n). Com uma diversidade de aplicações embutidas para facilitar a manutenção e otimizar o tempo.

O programa escolhido para realização do *pendrive* *bootável* foi o Rufus[^5], pois o mesmo tem uma simples utilização e é uma aplicação portátil, ou seja, não sendo necessário efetuar uma instalação. Segundo o portal do programa, o Rufus possui outra característica importante, pois, os instaladores de sistemas operacionais criados por ele são compatíveis somente com *motherboards* configuradas no padrão UEFI. Portanto, este *pendrive* será compatível com máquinas mais novas que operam nesta configuração. Há restrições também com sistemas operacionais, principalmente distribuições LINUX, que são projetadas para o padrão *Legacy*.

Conforme salienta Pimenta (2021), a BIOS padrão *Legacy* é executada pela opção ROM, que é limitada a um total de 64 KB de espaço de armazenamento. Portanto, a escolha das ROMs nas quais os sistemas *Legacys* rodam só são válidas se forem compatíveis com o hardware em que são executados. O mesmo afirma que o padrão UEFI resolve esse problema incorporando drivers no sistema no lugar de ROMs opcionais. Dessa forma, o *driver* quase não tem restrições de espaço e é compatível com atualizações de *hardware*. Além disso, o driver é escrito separadamente e pode ser carregado usando uma unidade *flash*.

Por conseguinte, a confecção da mídia inicializável veio a ser realizada. Já com o *pendrive* conectado foi aplicado o passo-a-passo do Anexo A, tal qual anexado nos elementos pós-textuais.

Figura 4 - Captura de tela: Criação do *pendrive* *bootável*

Fonte: elaborado pelo autor (2022).

## 3.3 MANUTENÇÃO DE EQUIPAMENTOS

A manutenção de equipamentos eletrônicos é uma prática comum no DTI, e foi realizada em diversas ocasiões durante o estágio, trivialmente atrelada a microcomputadores, que possuíam uma demanda maior. Segundo Souza (2011) existem duas principais categorias de manutenção de microcomputadores: a Manutenção Preventiva e a Manutenção Corretiva. 

Ambas relacionadas a *hardware*, definido por Morimoto (2002, p. 18), como “toda a parte física do micro: processadores, memória, discos rígidos, monitores, ou seja, tudo que se pode tocar”, quanto *software*, definido pelo autor como sendo “os programas e arquivos armazenados”.

De acordo com a norma NBR 5462, a Manutenção Preventiva é definida como: “Manutenção efetuada em intervalos predeterminados, ou de acordo com critérios prescritos, destinada a reduzir a probabilidade de falha ou a degradação de um item.” (ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS, 1994, p.7), ou seja, uma manutenção que busca prevenir falhas. 

A mesma, define Manutenção Corretiva como: “Manutenção efetuada após a ocorrência de um pane, destinada a recolocar um item em condições de executar uma função requerida” (ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS, 1994, p.7). Isto é, uma manutenção realizadas para corrigir determinados problemas no equipamento.

Diante do exposto, serão apresentadas as atividades relacionadas às manutenção, na seção terciária que sucede:

### **3.3.1 Manutenção Preventiva**

No aspecto que incorpora as ações a serem tomadas para prevenir defeitos nos equipamentos à nível de *hardware*, foram realizadas limpezas nos computadores que não apresentavam defeito iminente.

Segundo Souza (2011, p. 110): “A poeira pode gerar mau contato ou até mesmo danificar algum componente, o que prejudica o funcionamento do micro. Por isso é importante, periodicamente, realizar uma limpeza interna no gabinete”. Nesse sentido, usava-se um soprador de ar para limpeza do gabinete, enquanto nos componentes mais sensíveis eram usados pincéis e a aplicação de um Limpa Contato.

Figura 5 - Computador para ser limpo

Fonte: elaborado pelo autor (2022).

No âmbito de *software*, as medidas preventivas executadas, eram a instalação de atualizações do Windows, atualizações de *softwares* (Seção 2.10), verificações e remoções de vírus e backups de recuperação do Windows.

Segundo Torres (2001), vírus são programas mal intencionados, criados com a intenção de alterar e corromper dados. O autor salienta que, quando observado que o micro está agindo de forma incoerente com o normal, é imprescindível uma verificação de sua integridade através do uso de um antivírus.

Nesse sentido, em computadores que não possuíam um antivírus era instalados *softwares* como o Avast Antivírus[^6] ou Kaspersky Antivírus[^7], para uma proteção em tempo real da máquina. No entanto, além desses softwares em computadores no DTI, os arquivos são inspecionados regularmente com mais profundidade devido ao tráfego de download mais intenso nesses computadores.

Para essa verificação profunda, era utilizado do Kaspersky Rescue Disk, que segundo o site do fabricante “é uma imagem do disco de inicialização que permite iniciar um computador infectado e realiza um escaneamento do sistema a um nível BIOS” (BOLSHAKOVA, 2014, s/n).

Figura 6 - Captura de tela: Kaspersky Rescue Disk

Fonte: elaborado pelo autor (2022).

Os backups de recuperação do sistema operacional, eram realizados nos computadores com cunho administrativo que possuíam dados importantes e precisavam de uma seguridade maior, caso houvesse uma pane no micro. Semelhante ao backup de arquivos (Seção 2.4), nessa conjuntura, utiliza-se de um *software* para realizar essa ação, a ferramenta do AOMEI Backupper[^8].





Mensagem ultra secreta escondida: https://youtu.be/dQw4w9WgXcQ

Figura 7 - Captura de tela: AOMEI Backupper

Fonte: elaborado pelo autor (2022).

### **3.3.2 Manutenção Corretiva**

No aspecto que incorpora as ações a serem tomadas para corrigir defeitos nos equipamentos à nível de hardware, foram realizadas, manutenções referentes a problemas de funcionamento, instalação e troca de componentes e verificações da integridade de discos rígidos.

Quando requerido a manutenção de um microcomputador que não estava inicializando o sistema operacional deduzia-se que o problema era referente à nível de hardware interno. Com isso, iniciava-se o processo de teste dos principais erros de máquina.

Segundo Gogoni (2019) o *hardware* subdivide-se em interno e externo. Os componentes internos correspondem ao: processador que “é o cérebro do sistema, encarregado de processar todas as informações” (MORIMOTO, 2002, p. 17); Memória RAM que “é usada pelo processador para armazenar os dados que estão sendo processados” (MORIMOTO, 2002, p. 17); Disco rígido que é “onde ficam guardados programas e dados enquanto não estão em uso ou quando o micro é desligado” (MORIMOTO, 2002, p. 18); Placa de vídeo “que permite que o micro possa gerar imagens a serem mostradas no monitor” (MORIMOTO, 2002, p. 22); Placa mãe que “é o sistema que une todos os componentes de um computador, permitindo que eles funcionem de forma organizada” (KAZUK HARDWARE, 2020, s/n); E a fonte de alimentação que “é a peça responsável em fornecer energia para todos os componentes” (CAMARGO, 2009, s/n).

`	`Os principais testes realizados diziam respeito à verificação da conexão dos cabos e componentes, em especial à memória RAM, pois, ela majoritariamente era a causadora de problemas relacionados à falta de vídeo do computador. Em casos de que esses testes não solucionavam o problema, ocorriam uma análise mais apurada dos fatos.

Como em uma das situações, que após uma mudança de local do computador, ele não estava ligando como anteriormente. Para resolver esse problema, foi aberto o gabinete para verificar os componentes internos e constatado que tudo estava de acordo com o normal. Que não foi identificado é que a motherboard não estava encaixada corretamente e, em contato no gabinete, causando assim um curto-circuito que impedia o computador de ligar. Resolveu-se o problema substituindo o gabinete.

Figura 8 - Gabinete a ser instalado as peças

Fonte: elaborado pelo autor (2022).

Referente a instalação de componentes essa prática foi realizada no computador do setor de contabilidade que estava com problemas de superaquecimento e baixa velocidade, assim, foi instalado uma placa de vídeo, pois, esse PC não possuía um dispositivo gráfico. Após realizou-se uma limpeza interna no computador, buscando reduzir os altos níveis de temperatura que essa máquina estava obtendo. A temperatura dos componentes do gabinete reduziu significativamente, entretanto a placa de vídeo estava atingindo temperaturas extremas. Como forma de solucionar esse outro problema, buscou-se reduzir os altos níveis de temperatura substituindo a pasta térmica da placa de vídeo.

Figura 9 - Instalação de placa de vídeo

Fonte: elaborado pelo autor (2022).

Figura 10 - Troca de pasta térmica

Fonte: elaborado pelo autor (2022).

Após isso, a temperatura do componente estava atingindo níveis aceitáveis cerca de 46°C, no entanto, para ainda melhor desempenho, pesquisou-se sobre a possibilidade de realizar um *overclock* no processador, visto que era possível a realização, foi aplicada.
> O overclock é, basicamente, um processo no qual a velocidade de componentes específicos de um computador pessoal é manualmente aumentada, através de configurações e instruções diretas para o hardware. A melhora de desempenho que é atingida após o processo pode variar, mas entusiastas conseguem fazer componentes antigos funcionarem como os últimos lançamentos, assim como fazem as peças mais modernas superarem os limites da tecnologia atual (TECMUNDO, 2009, s/n).

Por fim, monitorou-se o comportamento do computador no software HWMonitor[^9], expondo a testes de uso cotidiano, percebeu-se melhora significativa no desempenho do computador.

Também, foi realizada a verificação dos HDs presentes no departamento, verificando quais ainda estavam em funcionamento e poderiam ser utilizados na montagem ou manutenção de outros micros. Para isso, os discos rígidos foram separados e testados individualmente no *software* HDD Regenerator, que escaneia o disco rígido, localizando e setores defeituosos.

Figura 11 - Verificação de disco com HDD Regenerator

Fonte: elaborado pelo autor (2022).

Segundo Bot Recuperação de Dados (s.d.) “Um HD é formado por vários setores que armazenam os dados. [...] Se algum setor do HD apresentar defeito, significa que os dados daquele setor não estão mais acessíveis”. Dos oito discos rígidos testados, seis apresentavam muitos setores danificados e foram descartados.

Figura 12 - HDs não-funcionais

Fonte: elaborado pelo autor (2022).

No âmbito de software, as medidas corretivas executadas, eram a formatação de disco e instalação do sistema operacional Windows. O processo de formatação de um computador era muito frequente. Reinstalar o sistema operacional da máquina geralmente é a única opção para corrigir erros de software identificados.

Além do mais, problemas de conexão com websites e sites locais (que rodam na estação de comunicação da prefeitura) ocorriam com frequência em alguns computadores externos à prefeitura, que era manifestado no escopo de configurações de rede do Sistema Operacional Windows. Sendo, facilmente solucionável, modificando as propriedades de protocolos TCP/IPv4[^10], direcionando-o às credenciais do servidor via acesso remoto.

Figura 13 - Captura de tela: Modificação de propriedades de rede

Fonte: elaborado pelo autor (2022).

## 3.4 BACKUP DE ARQUIVOS


*Backup*, ou cópia de segurança de uma tradução direta do inglês, é um termo, como aponta PontoTel (2022, s/n), de atividade que inclui fazer cópias de dados digitais de um dispositivo, como documentos, software ou quaisquer arquivos digitais, a fim de restaurá-los em circunstância de perda acidental ou falha do sistema onde estão armazenados. Esse processo, é muito utilizado durante a realização de uma formatação em *notebooks, smartphones* ou *desktops* (seção 2.5).

As requisições de *backups* eram realizadas produzindo uma cópia dos arquivos presentes na pasta “usuário” do computador, com o *software* FastCopy[^11], e com a conexão de um HD externo na máquina, ou seja, conectando-o via USB. 

No entanto, isso era feito apenas em *desktops* com USB 3.0, pois possuem “transmissão de 4,8 Gbps, o que dá cerca de 600 MB por segundo, em conversão direta. E como resultado, essa tecnologia consegue transferir dados até 10 vezes mais rápido do que a versão 2.0, que vem com 480 Mbps” (TECHTUDO, 2015, s/n). Em casos contrários, optava-se pela remoção do disco rígido da máquina, e conexão via cabo SATA no computador do departamento para realização do procedimento.

Figura 14 - Captura de tela: Processo de *Backup*

Fonte: elaborado pelo autor (2022).

## 3.5 FORMATAÇÃO E INSTALAÇÃO DE SISTEMA OPERACIONAL

Durante o estágio, foram realizadas formatações e instalações do Sistema Operacional Windows e suas respectivas versões. Segundo a Editora Conceitos.com, a formatação é conhecida como o processo que permite que o disco rígido seja devidamente esvaziado para posterior reutilização. É frequentemente usado para substituir arquivos do sistema que podem estar infectados ou corrompidos.

Existem dois tipos de formatação: a formatação física, ou formatação de baixo nível, e a formatação lógica. De acordo com Morimoto (2010) a formatação física é realizada no final do processo de fabricação do disco rígido, incluindo a divisão do disco rígido em trilhas, setores cilíndricos e isolamento de danos no disco rígido, e é realizada apenas uma vez e não pode ser desfeita ou refeita por software. Para acessar o disco rígido pelo sistema operacional, o disco rígido deve ser formatado de outro tipo. Isso é feito por meio da formatação lógica que apaga todos os dados da partição e pode ser utilizada quantas vezes for preciso.

A formatação lógica foi uma das atividades do estágio mais realizadas. Primeiramente realizava-se um *backup* dos arquivos (Seção 2.4). Em seguida, conectava-se *o pendrive bootável* na entrada USB e reiniciava-se o computador, durante a reinicialização mudava-se a prioridade de boot (Anexo B). Então, instalava-se o sistema operacional, seguindo o passo-a-passo do Apêndice A para Windows 7, ou do Apêndice B para Windows 10. Por fim, instalavam-se os *drivers* e copiava-se o *backup* dos dados para o computador formatado.

Figura 15 - Computador formatado

Fonte: elaborado pelo autor (2022).

## 3.6 CONSTRUÇÃO DE PLANILHA

Foi realizado um levantamento das impressoras usadas na prefeitura para posteriormente realizar um pedido de licitação para compra dos toners de tinta. Com a listagem pronta, seria organizado com todos esses dados, uma planilha eletrônica separando entre modelo da impressora, o toner de tinta e a quantidade do produto. 

Figura 16 - Impressora

Fonte: elaborado pelo autor (2022).

O programa escolhido para realização da planilha foi “O Microsoft Excel que é um dos programas do Pacote Office. [...] No Excel, são montadas planilhas eletrônicas que organizam dados e automatizam cálculos” (EXCEL-ME, 2020, s/n). 

Por fim, um arquivo feito pelo Excel com as respectivas informações foi enviado ao setor municipal de licitações via *e-mail* para efetuação da compra dos toners.

Figura 17 - Captura de tela: Planilha feita no Excel

Fonte: elaborado pelo autor (2022).

## 3.7 MONTAGEM E CRIMPAGEM DE CABOS DE REDE

O par trançado é o tipo de cabo de rede mais utilizado atualmente, segundo Torres (2018), existem dois tipos de cabo par-trançado, o que não possui nenhum tipo de blindagem, denominado *Unshielded Twisted Pair* (UTP), e com blindagem, chamado *Shielded Twisted Pair* (STP). Esse tipo de cabo utiliza um conector chamado 8P8C, popularmente conhecidos como “RJ-45”. 

Figura 18 - Cabo UTP

Fonte: MAXITELECOM[^12] (2022)

Figura 19 - Conector 8P8C (RJ-45)

Fonte: FURUKAWA ELECTRIC[^13] (2022)

A confecção desse cabo foi realizada buscando pôr em prática o conhecimento adquirido durante o curso Técnico em Informática na disciplina de Redes de Computadores. A montagem do cabo UTP é relativamente simples, além do cabo, necessita-se de um conector 8P8C de pressão para cada extremidade do fio e de um alicate de pressão para conectores 8P8C, também chamado de “alicate de crimpagem”.

Figura 20 - Alicate crimpador

Fonte: ASTEMAR[^14] (2015)

O cabo do tipo par trançado, como o nome sugere, é composto de 4 pares, trançados entre si, com um total de 8 fios. Existem duas maneiras de ordenar esses fios para encaixá-los no conector 8P8C, os padrões de cores: T-568A e T-568B. O padrão de cores usado foi T568B.

Figura 21 - Sequências de cores padrão T-568A e T-568B

Fonte: Mardey Costa[^15] (2022)

Visto isso, antes de tudo, é necessário realizar um desencape do cabo cuidadosamente, para não danificar os fios internos. Isso pode ser feito com o alicate de crimpagem, que possui uma saliência cortante para tal processo.

Em seguida, ordena-se os seguindo o padrão escolhido, contudo, antes de introduzi-los ao conector, deve-se cortar todos os fios em suas pontas, de forma que fiquem retos e com o mesmo tamanho. De acordo com Gabriel Torres, “para cada pino existe um pequeno ‘tubo’, onde o fio deve ser inserido [...] até que atinja o final do conector.” (TORRES, 2018, p. 519).

Por fim, ao terminar de inserir os fios no conector, utiliza-se do alicate para realizar a crimpagem dos fios, ou seja, para pressionar os pinos do mesmo. Com o cabo pronto é necessário testá-lo, utiliza-se do testador de cabos Hikari HTC-31, esse “equipamento envia um sinal por meio do cabo, o que permite a retransmissão e verificação da qualidade.” (MEDEIROS, 2021, s/n). Entretanto, caso o sinal não esteja sendo transmitido corretamente os conectores 8P8C são trocados, repetindo-se assim o processo de confecção do cabo par trançado.

Figura 22 - Cabo de rede par trançado

Fonte: elaborado pelo autor (2022).

## 3.8 INSTALAÇÃO DE IMPRESSORA WIRELESS E DRIVERS 


A manutenção relacionada às impressoras tem alta demanda no departamento de TI, no entanto, a maioria dessas atividades é terceirizada, ou as impressoras acabam ficando em determinados espaços do departamento, pois são consideradas não funcionais. 

Durante o estágio realizou-se a instalação de uma impressora *wireless*[^16], que tinha sido transferida do Centro Cultural para Secretária da Educação. A multifuncional da marca Lexmark modelo, requisita de alguns *drivers* para seu funcionamento. Segundo Brito:
> Drivers são programas responsáveis pela comunicação entre o sistema operacional de computador e o hardware conectado a ele. Este hardware pode ser uma impressora, um mouse, placas de vídeo e rede, caixas de som, monitor, pen drives etc. Já a plataforma deve ser o Windows, Linux, MS-DOS, Unix, FreeBSD, OS X, entre outros (2013, s/n).

Os *drivers* foram facilmente encontrados no site da fabricante[^17], do dispositivo. Após concluir as etapas de instalação, o computador reconheceu a impressora, contudo, ela não estava totalmente funcional devido à falta de cartuchos de tinta.

Figura 23 - Impressora instalada

Fonte: elaborado pelo autor (2022).

## 3.9 RECUPERAÇÃO DE SENHA DE SISTEMA OPERACIONAL

`	 `Os perfis de usuários dos departamentos, secretarias e servidores que possuem um *desktop* homologado na rede, tem seus dados de identificação mantidos em uma Ferramentas de Administração de Servidor Remoto (RSAT), presente na estação de comunicação.

A ferramenta da Microsoft, Active Directory (AD), é utilizada para esse gerenciamento de usuários de rede, denominada serviço de diretório. De acordo com Rodrigues (2022, s/n) “um diretório nada mais é do que um banco de dados contendo informações dos usuários de uma organização, tais como nome, login, senha, cargo, perfil e etc.”.

Sendo assim, foi requisitado a realização de uma recuperação da senha de usuário de um dos computadores do Centro de Referência Especializado de Assistência Social (CREAS). Onde realizou-se o acesso diretamente de um dos computadores do departamento, ao sistema de AD, e foi recuperada a senha. 

Figura 24 - Captura de tela: Active Directory

Fonte: elaborado pelo autor (2022).

Todavia, nos computadores que não estavam presentes no Active Directory e a recuperação da senha não era possível, optava-se pela redefinição das credenciais de usuário. Por meio do *software* Windows Password Unlocker, presente no WinPE. Com as devidas permissões, realizou-se uma simulação de redefinição de senha em um dos computadores do DTI. 

Figura 25 - Captura de tela: Windows Password Unlocker

Fonte: elaborado pelo autor (2022).

## 3.10 ATUALIZAÇÃO DE SOFTWARE INTERNO

O sistema utilizado por todos os setores do município é distribuído pela Betha Sistemas, empresa com anos de serviço no ramo de software para gestão pública. Por consequência, os sistemas são produzidos especialmente para cada setor, tendo muitas vezes a possibilidade de um vínculo entre ambos, como o Setor de Licitações e o Setor de Contabilidade.

De acordo com Raphadev (2022) os maiores benefícios da atualização de software são as correções de bugs, maior estabilidade e a melhor proteção contra ameaças digitais, cada vez mais poderosas e destrutivas. Nesse sentido, durante o estágio realizou-se a atualização de um dos componentes do sistema utilizado pelos departamentos da prefeitura. 

Tal demanda foi atendida seguindo as instruções da empresa fabricante. A qual disponibiliza em seu site[^18] o pacote de arquivos necessários para o *update*. Após o *download* dos arquivos, incrementou-se as atualizações em um dos computadores, que a partir desse ponto de acesso atualizou os demais na rede.

Figura 26 - Captura de tela: Atualização do programa

Fonte: elaborado pelo autor (2022).


# **4 PROPOSTA DE SOLUÇÃO**

Durante o estágio, foram observadas algumas características negativas em relação ao setor de TI, as quais serão descritas brevemente a seguir:

` `A primeira delas se relaciona ao controle de manutenções efetuadas em equipamentos eletrônicos pertencentes ao patrimônio, que é feito de forma manuscrita. Tendo em vista que o Departamento de Informática é composto apenas por um funcionário, e que ele realiza muitas manutenções em todos os setores e em prédios descentralizados pertencentes a prefeitura. Logo não há um controle efetivo sobre as assistências realizadas.

Pontua-se também a falta de um mapeamento da infraestrutura de rede da prefeitura, como foi observado durante o estágio, sua infraestrutura não possuía uma identificação dos cabos que advêm do servidor. Tal qual, dificulta a resolução de problemas relacionados à conexão de rede.

A desordem que persistia no setor seria outro aspecto a ser analisado, pois muitos dos objetos que ali estavam poderiam ser reorganizados e até descartados, por meio de testes para avaliação de cada equipamento. Desse modo, durante o estágio, foi realizado um processo de organização, mas como uma atividade temporária, pois logo, o local voltou ao seu estado de desorganização.

Nesse sentido, a partir das problemáticas verificadas durante o estágio, faz-se necessário selecionar uma para dedicar todo empenho na sua solução. Para tanto, escolheu-se solucionar o problema do registro das demandas, através de uma ferramenta de software desenvolvida posteriormente.

## 4.1 PLANEJAMENTO DE SOFTWARE

O planejamento está diretamente relacionado ao processo de software. O processo de criação de software é resultado de um planejamento associado a um modelo de processo. Um modelo de processo indica quais atividades devem ser executadas e as dependências entre elas. Por exemplo, segundo no modelo *Waterfall*, proposto por Royce em 1987 (PRESSMANN, 2016), são especificados os requisitos, projeta-se a arquitetura, faz-se o projeto detalhado, implementa-se a unidade, integra-se a unidade e, finalmente, entrega-se o *software*.

Figura 27 - Fluxo de processos linear

Fonte: Pressman (2016, p. 33).

Definido o ciclo de vida, define-se a metodologia para ser utilizada, a partir dos requisitos que são levantados durante a etapa de comunicação. 
> A UML (*Unified Modeling Language*) é uma linguagem-padrão para a elaboração da estrutura de projetos de software. Ela poderá ser empregada para a visualização, a especificação, a construção e a documentação de artefatos que façam uso de sistemas complexos de software (BOOCH; RUMBAUGH; JACOBSON, 2012, p. 34).

Essa linguagem, portanto, dispõe de nove tipos de diagramações que são usadas para documentar e modelar diversos aspectos dos sistemas. Ademais, nas seções 4.1.1 e 4.1.2 são documentados os diagramas desenvolvidos para este plano de *software*.

Figura 28 - Diagramas UML (Unified Modeling Language)

Fonte: MICROSOFT. **Diagramas UML no Visio** - Microsoft Support. [S.l.: s.n.]. Disponível em: <https://bit.ly/3DhdKke>. Acesso em: 29 ago. 2022. 
### **4.1.1 Diagrama de caso de uso**

Em um projeto de *software*, a modelagem de interação do usuário, de acordo com Marinho (2016), é imprescindível para identificar os requisitos do usuário. Esse sistema de modelagem contribui para se compreender a estrutura idealizada do sistema requerido.

A modelagem de caso de uso faz parte dos modelos de requisitos e possui uma descrição comportamental dos atores externos com o sistema através de fluxogramas. Esse modelo de “diagrama documenta o que o sistema faz do ponto de vista do usuário. Em outras palavras, ele descreve as principais funcionalidades do sistema e a interação dessas funcionalidades com os usuários do mesmo sistema.” (DEVMEDIA, 2012, s/n).

Figura 29 – Diagrama: Caso de uso

[^19] 

Fonte: elaborado pelo autor (2022).
### **4.1.2 Diagrama de classe**

De todos os diagramas da *Unified Modeling Language*, esse é o mais rico em termos de notações. O diagrama de classes é empregado na construção de modelos de classes desde o nível de análise até o nível de especificação, é assim definido por Fowler (2007, p. 20) com o que:
> [...] descreve os tipos de objetos presentes no sistema e os vários tipos de relacionamentos estáticos existentes entre eles. Os diagramas de classes também mostram as propriedades e as operações de uma classe e as restrições que se aplicam à maneira como os objetos estão conectados. A UML utiliza a palavra característica como um termo geral que cobre as propriedades e operações de uma classe 

Figura 30 – Diagrama: Diagrama de classe

[^20]

Fonte: elaborado pelo autor (2022).

## 4.2 PROTÓTIPO DE TELA

A prototipagem da interface de usuário é fundamental para um bom desenvolvimento de software, de acordo com Digital House (2021, s/n), é uma representação inicial do projeto. Pode acontecer em diferentes níveis de fidelidade, baixa, média ou alta. A diferença é o custo envolvido e o nível de detalhamento da ideia do produto. O principal objetivo de um protótipo de tela é a interação entre o usuário e a interface final.

### **4.2.1 Telas do sistema**

O protótipo foi desenvolvido na ferramenta Adobe Photoshop, tendo uma disposição dos elementos na tela de forma que possam ser de fácil acesso para o usuário. 

Na tela de login, é apresentado de forma minimalista, os campos de credenciais de usuário e senha. Os quais devem ser preenchidos corretamente para o acesso no sistema.

Figura 31 - Tela de Login

Fonte: elaborado pelo autor (2022).

Após ser realizado o login, o ingresso à plataforma é efetuado automaticamente pelo sistema e uma mensagem no canto inferior direito torna-se visível indicando o sucesso do ocorrido.

Figura 32 - Tela de Logado

Fonte: elaborado pelo autor (2022).

Caso algum erro ocorra no preenchimento dos campos, uma mensagem é apresentada na tela impedindo o usuário de efetuar o login, o levando a realizar o preenchimento dos campos novamente.

Figura 33 - Tela de Erro

Fonte: elaborado pelo autor (2022).

Na interface os registros podem ser filtrados individualmente pelo patrimônio do equipamento, e ser efetuada a impressão do mesmo, além da criação de novas demandas através do botão no canto inferior esquerdo.

Figura 34 - Tela Principal

Fonte: elaborado pelo autor (2022).

A criação de uma demanda, é realizada através de um simples formulário, no qual, o usuário deve informar: data, patrimônio, departamento, atividade, estado do equipamento e defeito constatado.

Figura 35 - Tela de Cadastro

Fonte: elaborado pelo autor (2022).


## 4.3 IMPLEMENTAÇÃO

Entre as ferramentas previstas para confecção da aplicação, posteriormente desenvolvida, o editor de código Visual Studio Code foi escolhido para o desenvolvimento de código. Para testar o código, o servidor Apache Xampp deve ser usado. Além disso, no desenvolvimento do banco de dados, será utilizado o ambiente MySQL do Sistema de gerenciamento de banco de dados (BDSM) PHPMyAdmin.

Figura 36 - Captura de tela: Visual Studio Code

Fonte: REDDIT (2020).

Para codificação o versionamento é fundamental. De acordo com Sacramento “versionamento de código consiste em estratégias para gerenciar as diferentes versões de um código. É uma forma de administrar as mudanças que são feitas e de garantir mais segurança na transição de uma versão para outra” (2021, s/n). A plataforma GitHub de foi utilizada para esse controle de versão, um repositório público, disponível em: <https://github.com/dbreskovit/DTI>.

Figura 37 - Captura de tela: Repositório no GitHub



Fonte: elaborado pelo autor (2022).


# **5 CONSIDERAÇÕES FINAIS**

A redação do relatório, assim como o estágio, são momentos em que os alunos colocam em prática os conhecimentos adquiridos no curso. Além disso, os estágios proporcionam aos alunos uma perspectiva mais ampla sobre o futuro mercado de trabalho, permitindo-os estar um passo à frente de outros que estão prestes a entrar no mundo profissional. 

O conhecimento difundido no curso de Informática oferecido na instituição é de grande valia para a realização do estágio, contemplando grande parte das necessidades que surgem durante o processo de realização e, reconhecendo que no curso, as várias áreas abrangidas estão inter-relacionadas. 

As atividades aqui apresentadas foram de suma importância no âmbito profissional e pessoal do estagiário, tendo em vista que as experiências vividas concederam ao discente uma postura mais madura perante os seus deveres em uma jornada de trabalho. Além dessas experiências favorecerem de forma geral em seu crescimento acadêmico. 

Por fim, vale salientar que a obrigatoriedade do estágio não serve apenas para praticar o que já tenha sido ensinado, mas também, e principalmente, para aprender coisas novas. Dessa forma, essa aprendizagem é essencial para a formação do aluno, pois mostra novas dificuldades e, portanto, novas formas de resolução de problemas.



# **REFERÊNCIAS**

ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **NBR 16264**: cabeamento estruturado residencial. Rio de Janeiro, 2014.

ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **NBR 5462**: confiabilidade e mantenabilidade. Rio de Janeiro, 1994.

BOLSHAKOVA, Maria. **Dica da semana: Kaspersky Rescue Disk, é melhor prevenir do que remediar**. Kaspersky, 2014. Disponível em: <https://bit.ly/3Rg9XaK>. Acesso em: 29 ago. 2022.

BOOCH, Grady; RUMBAUGH, James; JACOBSON, Ivar; **UML:** guia do usuário / Grady Booch, James Rumbaugh, Ivar Jacobson; tradução de Fábio Freitas da Silva e Cristina de Amorim Machado. – Rio de Janeiro: Elsevier, 2006.

BOT RECUPERAÇÃO DE DADOS**. O que são bad sectors no HD, o que pode causar e como recuperar?**. s.d. Disponível em: <https://bit.ly/3cxsqAE>. Acesso em: 29 ago. 2022.

BRASIL. MINISTÉRIO DA EDUCAÇÃO. INSTITUTO FEDERAL FARROUPILHA. CAMPUS SANTO AUGUSTO. **Projeto Pedagógico do Curso Técnico em Informática Integrado**. Santa Maria, 2014. Disponível em: <https://bit.ly/3xRTG4l>. Acesso em: 24 set. 2022.

BRITO, Edivaldo. **Entenda o que são drivers, para que servem e como instalá-los**. Techtudo, 2013. Disponível em: <http://glo.bo/3KxKl76>. Acesso em: 25 ago. 2022.

CAMARGO, Camila. **Fontes: Você dá a devida importância à sua?**. TecMundo, 2009. Disponível em: <https://bit.ly/3wGuYmR>. Acesso em: 29 ago. 2022.

DEVMEDIA**. O que é UML e Diagramas de Caso de Uso: Introdução Prática à UML.** Devmedia, 2012. Disponível em: <https://bit.ly/3ADrW3V>. Acesso em: 29 ago. 2022.

DICOMP. **O que são racks? 12 características para entender mais e escolher o ideal para seu servidor**. Dicomp, 2020. Disponível em: <https://bit.ly/3AaTAFx>. Acesso em: 15 ago. 2022.

DIGITAL HOUSE. **Protótipo de tela: o que é e quais as principais ferramentas.** Digital House, 2021. Disponível em: <https://bit.ly/3Uqer0N>. Acesso em: 15 set. 2022.

EDITORA CONCEITOS.COM. **Conceito de Formatação.** Conceitos.com, 2014. Disponível em: <https://bit.ly/3PPmX65>. Acesso em: 27 ago. 2022.

EXCEL-ME. **O que é planilha eletrônica? Para que servem?**. Excel-me, 2020. Disponível em: <https://bit.ly/3K7QCG8>. Acesso em: 20 ago. 2022.

FOWLER, Martin. **UML essencial:** um breve guia para a linguagem-padrão de modelagem de objetos; tradução João tradução João Tortello. 3. ed. Porto Alegre : Bookman, 2007. 162 p.

FRANCISCATTO, Roberto. **Redes de computadores / Roberto Franciscatto, Fernando de Cristo, Tiago Perlin.** – Frederico Westphalen : Universidade Federal de Santa Maria, Colégio Agrícola de Frederico Westphalen, 2014. 

GOGONI, Ronaldo. **O que é hardware?**. Tecnoblog, 2019. Disponível em: <https://bit.ly/3TnaPw9>. Acesso em: 29 ago. 2022.

GUSSO, Luciano. **Como criar pen drive bootável com o programa Rufus.** Profissionais TI, 2018. Disponível em: <https://bit.ly/3AAujpD>. Acesso em: 12 ago. 2022.

KAZUK HARDWARE. **O que é a placa mãe e como funciona?**.** Kazuk Hardware, 2020.** Disponível em: <https://bit.ly/3Av3VfD>. Acesso em: 29 ago. 2022.

LIRA, Marcia. **AnyDesk: Guia de como ele pode ajudar no home office**. B2B Stack, 2021. Disponível em: <https://bit.ly/3c6rXVW>. Acesso em: 10 jan. 2022.

MARINHO, Antonio. **Analise e modelagem de sistemas.** – São Paulo: ELT Importado Pearson, 2016. 159 p.

MEDEIROS, Tiago Dante. **Melhores Testadores de Cabos RJ45**. Geek360, 2021. Disponível em: <https://bit.ly/3PVS5R6>. Acesso em: 27 ago. 2022. 

MICROSOFT. **Windows PE (WinPE)**, 2022. Disponível em: <https://bit.ly/3CgHb5l>. Acesso em: 9 de jan. 2022.

MORIMOTO, Carlos Eduardo. **Hardware II**: O Guia Definitivo. Porto Alegre: Sul Editores, 2010. 1086 p.

MORIMOTO, Carlos Eduardo. **Hardware, Manual Completo**. 3. ed. 2002. *E-book*. 786 p. Disponível em: <https://bit.ly/3KuoPQt>. Acesso em: 29 ago. 2022.

TECMUNDO. **O que é Overclock?**. TecMundo, 2009. Disponível em: <https://bit.ly/3cA3d8T>. Acesso em: 29 ago. 2022.

PIMENTA, Rafael. **UEFI ou Legacy: entenda as diferenças!**. Geek Blog, 2021. Disponível em: <https://bit.ly/3pMOOsT>. Acesso em: 25 ago. 2022.

PONTOTEL, Redator**. Saiba o que é um backup, como funciona e sua importância na rotina das empresas!**. PontoTel, 2022. Disponível em: <https://bit.ly/3Arf7dd>. Acesso em: 20 ago. 2022.

PREFEITURA MUNICIPAL DE TENENTE PORTELA. **Estrutura física da prefeitura**, 2022. Disponível em: <https://bit.ly/3RfwF2u>. Acesso em: 9 de jan. 2022. il. color.

PRESSMAN, Roger S. **Engenharia de software :** uma abordagem profissional / Roger S. Pressman, Bruce R. Maxim; tradução: João Eduardo Nóbrega Tortello. 8. ed. – Porto Alegre : AMGH, 2016. 968 p.

RAPHADEV. **A importância de ter um software ou hardware atualizado na sua empresa**. Centric Solution, 2022. Disponível em: <https://bit.ly/3dMhzD9>. Acesso em: 20 ago. 2022.

RODRIGUES, André. **O que é o Active Directory e o que são domínios: 02 videoaulas**. Portal GSTI, 2017. Disponível em: <https://bit.ly/3ApsMRP>. Acesso em: 27 ago. 2022.

RUFUS. **Crie drives USB bootaveis facilmente**. Traduzido por Guilherme Hastenreiter. Disponível em: <https://bit.ly/3dD9Rex>. Acesso em: 08 jan. 2022.

SACRAMENTO, Gabriel. **Versionamento de código e de software: entenda cada processo.** Somostera, 2021. Disponível em: <https://bit.ly/3qReCor>. Acesso em: 15 set. 2022.

SOUZA, Janaina. **Montagem e manutenção de computadores / Janaina Silva de Souza.** – Manaus : Centro de Educação Tecnológica do Amazonas, 2011.

SYOZI, Ricardo. **O que é TCP/IP?**. Tecnoblog, 2022. Disponível em: <https://bit.ly/3q2iiTz>. Acesso em: 29 ago. 2022.

TECHTUDO**. Como configurar a BIOS para dar boot pelo USB**. Techtudo, 2014. Disponível em: <http://glo.bo/3CBzMh5>. Acesso em: 25 ago. 2022.

TECHTUDO**. Como usar o CPU-Z: Descubra informações completas sobre seu computador**. Techtudo, 2015. Disponível em: <http://glo.bo/3AKmOfM>. Acesso em: 20 ago. 2022.

TECHTUDO**. Vale a pena comprar um pendrive com USB 3.0? Confira nossa análise**. Techtudo, 2015. Disponível em: <http://glo.bo/3PSCOAS>. Acesso em: 20 ago. 2022.

TORRES, Gabriel. **Hardware Curso Completo**. 4. ed. Rio de Janeiro: Axcel Books, 2001.1440 p.

TORRES, Gabriel. **Redes de Computadores** - Versão Revisada e Atualizada. 1. ed. Rio de Janeiro: Nova Terra, 2009. 832 p.

TORRES, Gabriel. **Redes de Computadores** - Versão Revisada e Atualizada. 2. ed. Clube do Hardware, 2018. 1022 p.

VALERI, Vitor. **O que é Wireless e quais as diferenças entre redes A B G N AC AX?**. Oficina da Net, 2012. Disponível em: <https://bit.ly/3coGcpp>. Acesso em: 25 ago. 2022.















# **ANEXOS**













## ANEXO A - CRIANDO UM *PENDRIVE* *BOOTÁVEL* COM O RUFUS

`	`A seguir será elaborado um passo a passo para a criação de uma mídia bootável usando a imagem de ISO do Windows PE. Lembrando que, essa etapa é comum para ambas as imagens de Sistemas Operacionais criadas a partir do Rufus: 

1) No Explorador de Arquivos do Windows 10, acesse no diretório que foi baixado o aplicativo e então dê duplo clique para executá-lo.

1) Com o Rufus já iniciado e o *pendrive* conectado, automaticamente o programa irá identificar o dispositivo USB conectado para ser utilizado. Após isso, selecione a imagem do sistema.

1) Ao clicar em iniciar irá aparecer uma janela avisando da perda dos arquivos contidos no *pendrive*, caso seja o disco correto, e as devidas precauções foram tomadas referente ao *backup* dos arquivos, basta clicar em “OK” para prosseguir.

1) A criação do pendrive bootável (USB de Boot) acontecerá automaticamente pode demorar alguns minutos, o progresso pode ser visualizado pela barra de status, localizada na parte inferior do programa. 

1) O processo terá sido finalizado, quando a barra verde estiver completamente preenchida. Podendo assim, clicar em fechar para encerrar a aplicação, com o pendrive bootável já funcional. 
## ANEXO B - CONFIGURANDO A BIOS PARA *BOOT*

Há possibilidade de configurar o componente que será inicializado no computador, através de uma configuração no BIOS do dispositivo. Como existem BIOS de diferentes marcas, o procedimento abaixo utiliza de uma forma genérica para contemplar as mais conhecidas:

1) Ligue o computador e imediatamente comece a pressionar a tecla que dá acesso a BIOS. A indicação de tecla pode ser vista em alguma parte da tela;

1) Na tela principal da BIOS, procure pela opção que leva a configuração da sequência de boot;
1) Em BIOS da marca “American Megatrends”, vá na opção “Advanced Setup”, após isso, em “Boot Device Priority”;

1) Na tela seguinte, vá para a opção “1st Boot Device” e quando estiver sobre ela, tecle “enter”;

1) Serão exibidas as opções disponíveis. Vá até ao item correspondente a unidade desejada e dê enter nele;
1) Para salvar a alteração, pressione a tecla “F10″.














# **APÊNDICES**














## APÊNDICE A - INSTALAÇÃO WINDOWS 7

O Windows 7 pode ser instalado usando CDs, DVDs ou *pendrive*, o tópico a seguir aborda a instalação desse Sistema Operacional:

Na primeira tela, escolha o idioma a ser instalado e o *layout* do teclado. Depois, clique no botão “Avançar”.

Clique no botão “Instalar agora”.

Aceite os termos de uso do sistema. Depois, clique no botão “Avançar”.

Selecione o tipo de instalação personalizada.

Escolha o disco rígido onde deseja instalar o Sistema. Depois, clique no botão “Avançar”.

`	`Aguarde a finalização da instalação do Sistema Operacional.

`	`O sistema irá inicializar, necessitando de algumas configurações de usuário. Depois disso estará pronto para uso.


## APÊNDICE B - INSTALAÇÃO WINDOWS 10

O Windows 10 pode ser instalado usando CDs, DVDs ou *pendrive*, a seção a seguir abrange a instalação desse Sistema Operacional:

Na primeira tela, escolha o idioma a ser instalado e o *layout* do teclado. Depois, clique no botão “Avançar”.

Clique no botão “Instalar agora”.

`	`Clique em “Não tenho a chave do produto”.

Selecione “Windows 10 Home”. Depois, clique no botão “Avançar”.

Aceite os termos de uso do sistema. Depois, clique no botão “Avançar”.

Selecione o tipo de instalação personalizada.

Escolha o disco rígido onde deseja instalar o Sistema. Depois, clique no botão “Avançar”.

Aguarde a finalização da instalação do Sistema Operacional.

O sistema irá inicializar, necessitando de algumas configurações de usuário. Depois disso estará pronto para uso.

[^1]: PREFEITURA MUNICIPAL DE TENENTE PORTELA. **Secretarias**, 2022. Disponível em: <https://www.tenenteportela.rs.gov.br/>. Acesso em: 08 jan. 2022.
[^2]: AnyDesk Desktop remoto. Disponível em: <https://anydesk.com/>. Acesso em: 08 jan. 2022.
[^3]: “[...] ferramenta que permite visualizar informações completas sobre o *hardware* e software do seu computador.”(Techtudo, 2015)
[^4]: CPU-Z. Disponível em: <https://www.cpuid.com/>. Acesso em: 08 jan. 2022.
[^5]: RUFUS. Disponível em: <https://rufus.ie/pt_BR/>. Acesso em: 08 jan. 2022.
[^6]: Disponível em: [https://www.avast.com](https://www.avast.com/)/
[^7]: Disponível em: <https://www.kaspersky.com.br/> 
[^8]: AOMEI BACKUPPER. Disponível em: <https://www.capterra.com.br/software/144769/aomei-backupper> 
[^9]: HWMONITOR. Disponível em: <https://www.cpuid.com/softwares/hwmonitor.html> 
[^10]: “O TCP (Protocolo de Controle de Transmissão) e o IP (Protocolo de Internet) são conjuntos de protocolos que visam a interconexão dos mais diversos dispositivos na internet. Ou seja, eles especificam como a comunicação deve ser feita dentro da rede.” (SYOZI, 2022)
[^11]: FASTCOPY. Disponível em: <https://fastcopy.br.uptodown.com/windows> 
[^12]: Disponível em: <https://bit.ly/3PQxyxn>. Acesso em: 27 ago. 2022.
[^13]: Disponível em: <https://bit.ly/3PVSvqL>[](https://www.furukawalatam.com/pt-br/catalogo-de-produtos-detalhes/conector-rj45-macho-cat5e-para-cabo-solido-e-flexivel)[](https://maxitelecom.com.br/2015/cabo-utp-cat6-solido-lszh). Acesso em: 27 ago. 2022.
[^14]: Disponível em: <https://bit.ly/3PV1mJi> [](https://www.furukawalatam.com/pt-br/catalogo-de-produtos-detalhes/conector-rj45-macho-cat5e-para-cabo-solido-e-flexivel)[](https://maxitelecom.com.br/2015/cabo-utp-cat6-solido-lszh). Acesso em: 27 ago. 2022.
[^15]: Disponível em: <https://bit.ly/3CTcFiz> [](https://www.furukawalatam.com/pt-br/catalogo-de-produtos-detalhes/conector-rj45-macho-cat5e-para-cabo-solido-e-flexivel)[](https://maxitelecom.com.br/2015/cabo-utp-cat6-solido-lszh). Acesso em: 27 ago. 2022. 
[^16]: “Wireless, em tradução livre, sem fio, nada mais é que do que qualquer tipo de conexão para transmissão de informações sem o uso de fios ou cabos.” (VALERI, 2012, s/n)
[^17]: LEXMARK. Disponível em: <https://support.lexmark.com/pt_br/drivers-downloads.html>. Acesso em: 27 ago. 2022.
[^18]: Betha Sistemas. Disponível em: <https://www.betha.com.br/>. Acesso em: 20 ago. 2022.
[^19]: Disponível com maior resolução em: [Lucidchart.com](https://lucid.app/lucidchart/45622858-ee47-403b-a152-20a2df84027a/edit?viewport_loc=-919%2C-490%2C4130%2C1973%2C0_0&invitationId=inv_4f7e5216-cf68-47ee-9957-e9f21f8bff4f)
[^20]: Disponível com maior resolução em: [Lucidchart.com](https://lucid.app/lucidchart/d760599d-425f-46b5-8f09-bfa42904999e/edit?viewport_loc=-103%2C-92%2C2430%2C887%2C0_0&invitationId=inv_f03c8cfa-131f-4e19-8c31-650ec2a435e7)
