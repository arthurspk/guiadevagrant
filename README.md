<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="./images/guia.png" alt="Guia de Vagrant" width="160" height="160">
  </a>
  <h1 align="center">Guia de Vagrant</h1>
</p>

## :dart: O guia para alavancar a sua carreira

> Vagrant é a ferramenta da HashiCorp para criar e descartar máquinas virtuais de desenvolvimento com um único arquivo de configuração, o `Vagrantfile`: você descreve o sistema operacional, a rede, as pastas compartilhadas e o provisionamento, e reproduz o mesmo ambiente em qualquer máquina com `vagrant up`. Antes dos containers dominarem o mercado, o Vagrant foi a porta de entrada de uma geração inteira para "infraestrutura como código"; hoje ele segue vivo e mantido pela HashiCorp, principalmente para laboratórios, homologação local, automação de rede e cenários que realmente precisam de uma VM completa (kernel próprio, múltiplos SOs, testes de provisionamento) em vez de um container. Este guia reúne documentação oficial, cursos, canais, ferramentas, projetos práticos e um capítulo dedicado a usar IA na prática com Vagrant — tudo verificado e organizado para quem quer sair do primeiro `vagrant init` até montar laboratórios reais em VirtualBox, libvirt ou Hyper-V.

<sub> <strong>Siga nas redes sociais para acompanhar mais conteúdos: </strong> <br>
[<img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">](https://github.com/arthurspk)
[<img src = "https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white">](https://www.facebook.com/seixasqlc/)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/arthurspk/)
[<img src = "https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white">](https://twitter.com/manotoquinho)
[![Discord Badge](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/NbMQUPjHz7)
[<img src = "https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/guiadevbrasil/)
[![Youtube Badge](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCzmXzz_VR0Li8-YOvWN_t3g)
</sub>

## ⚠️ Aviso importante

> Antes de tudo você pode me ajudar e colaborar, deu bastante trabalho fazer esse repositório e organizar para fazer seu estudo ou trabalho melhor, portanto você pode me ajudar das seguintes maneiras:

- Me siga no [Github](https://github.com/arthurspk)
- Acesse as redes sociais do [Guia Dev Brasil](https://linktr.ee/guiadevbrasil)
- Mande feedbacks no [LinkedIn](https://www.linkedin.com/in/arthurspk/)

## 💡 Nossa proposta

> A proposta deste guia é dar uma ideia sobre o atual panorama e guiá-lo se você estiver confuso sobre qual será o seu próximo aprendizado, sem influenciar você a seguir os 'hypes' e 'trends' do momento. Acreditamos que com um maior conhecimento das diferentes estruturas e soluções disponíveis poderá escolher a ferramenta que melhor se aplica às suas demandas. E lembre-se, 'hypes' e 'trends' nem sempre são as melhores opções.

## :beginner: Para quem está começando agora

> Não se assuste com a quantidade de conteúdo apresentado neste guia. Acredito que quem está começando pode usá-lo não como um objetivo, mas como um apoio para os estudos. <b>Neste momento, dê enfoque no que te dá produtividade e o restante marque como <i>Ver depois</i></b>. Ao passo que seu conhecimento se torna mais amplo, a tendência é este guia fazer mais sentido e ficar fácil de ser assimilado. Bons estudos e entre em contato sempre que quiser! :punch:

## 🚨 Colabore

- Abra Pull Requests com atualizações
- Discuta ideias em Issues
- Compartilhe o repositório com a sua comunidade

## 🌍 Tradução

> Se você deseja acompanhar esse repositório em outro idioma que não seja o Português Brasileiro, você pode optar pelas escolhas de idiomas abaixo, você também pode colaborar com a tradução para outros idiomas e a correções de possíveis erros ortográficos, a comunidade agradece.

<img src = "https://i.imgur.com/lpP9V2p.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>English — </b> [Click Here](https://github.com/arthurspk/guiadevagrant)<br>
<img src = "https://i.imgur.com/GprSvJe.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Spanish — </b> [Click Here](https://github.com/arthurspk/guiadevagrant)<br>
<img src = "https://i.imgur.com/4DX1q8l.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Chinese — </b> [Click Here](https://github.com/arthurspk/guiadevagrant)<br>
<img src = "https://i.imgur.com/6MnAOMg.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Hindi — </b> [Click Here](https://github.com/arthurspk/guiadevagrant)<br>
<img src = "https://i.imgur.com/8t4zBFd.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Arabic — </b> [Click Here](https://github.com/arthurspk/guiadevagrant)<br>
<img src = "https://i.imgur.com/iOdzTmD.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>French — </b> [Click Here](https://github.com/arthurspk/guiadevagrant)<br>
<img src = "https://i.imgur.com/PILSgAO.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Italian — </b> [Click Here](https://github.com/arthurspk/guiadevagrant)<br>
<img src = "https://i.imgur.com/0lZOSiy.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Korean — </b> [Click Here](https://github.com/arthurspk/guiadevagrant)<br>
<img src = "https://i.imgur.com/3S5pFlQ.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Russian — </b> [Click Here](https://github.com/arthurspk/guiadevagrant)<br>
<img src = "https://i.imgur.com/i6DQjZa.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>German — </b> [Click Here](https://github.com/arthurspk/guiadevagrant)<br>
<img src = "https://i.imgur.com/wWRZMNK.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Japanese — </b> [Click Here](https://github.com/arthurspk/guiadevagrant)<br>

## 📚 ÍNDICE

[🗺️ Roadmap](#️-roadmap) <br>
[🚀 Por onde começar](#-por-onde-começar) <br>
[📖 Documentação oficial](#-documentação-oficial) <br>
[🔤 Sites e cursos para aprender Vagrant](#-sites-e-cursos-para-aprender-vagrant) <br>
[📚 Livros](#-livros) <br>
[🎥 Canais no Youtube](#-canais-no-youtube) <br>
[📰 Sites, blogs e newsletters](#-sites-blogs-e-newsletters) <br>
[🛠️ Ferramentas](#️-ferramentas) <br>
[🧪 Projetos práticos e desafios](#-projetos-práticos-e-desafios) <br>
[🤖 IA na prática](#-ia-na-prática) <br>
[💼 Carreira e vagas](#-carreira-e-vagas) <br>
[👥 Comunidades](#-comunidades) <br>

## 🗺️ Roadmap

O Vagrant não publica um "roadmap.sh" próprio como algumas linguagens, e não é um projeto de desenvolvimento acelerado: a versão estável mais recente é a série 2.4.x (a última tag, `v2.4.9`, é de agosto de 2025), com builds noturnas (`.dev`) contínuas no repositório. O jeito mais confiável de acompanhar o que muda é direto na fonte oficial abaixo.

- [CHANGELOG.md (oficial)](https://github.com/hashicorp/vagrant/blob/main/CHANGELOG.md) — Histórico completo de versões do Vagrant, é o jeito mais confiável de acompanhar novidades e correções.
- [Releases do hashicorp/vagrant](https://github.com/hashicorp/vagrant/releases) — Todas as versões publicadas, incluindo a mais recente estável (`v2.4.9`) e as builds noturnas (`.dev`) em andamento.
- [Issues do repositório oficial](https://github.com/hashicorp/vagrant/issues) — Onde bugs, pedidos de feature e discussões técnicas sobre o futuro do projeto acontecem publicamente.
- [Building Vagrant 3.0 (canal oficial da HashiCorp)](https://www.youtube.com/watch?v=H6RRfhi3v0E) — Vídeo do canal oficial da HashiCorp sobre o trabalho, à época, em uma futura versão 3.0; útil como contexto histórico do projeto, mas nenhuma versão 3.0 estável foi publicada até a data desta revisão (a série atual continua sendo a 2.4.x).
- [DevOps Roadmap (roadmap.sh)](https://roadmap.sh/devops) — Roadmap geral de DevOps da comunidade; Vagrant aparece como uma das ferramentas de virtualização local ao lado de VirtualBox e VMware.

## 🚀 Por onde começar

1. [Install Vagrant (documentação oficial)](https://developer.hashicorp.com/vagrant/install) — Baixe o instalador para Windows, macOS ou Linux.
2. Instale um provider de virtualização, o mais comum é o [Oracle VirtualBox](https://www.virtualbox.org/) (gratuito).
3. [Get Started with Vagrant (tutorial oficial)](https://developer.hashicorp.com/vagrant/tutorials/get-started) — Passo a passo oficial: `vagrant init`, `vagrant up`, `vagrant ssh` e `vagrant destroy`.
4. [Vagrantfile (referência oficial)](https://developer.hashicorp.com/vagrant/docs/vagrantfile) — Entenda a estrutura do arquivo de configuração central de todo projeto Vagrant.
5. [Vagrant CLI (referência oficial)](https://developer.hashicorp.com/vagrant/docs/cli) — Todos os comandos do `vagrant` explicados um a um.
6. [Vagrant Cloud — descobrir boxes](https://portal.cloud.hashicorp.com/vagrant/discover) — Catálogo oficial de "boxes" (imagens de VM prontas) publicadas pela comunidade e por distribuições como Ubuntu e Debian.
7. [Vagrant Aula 01 — O que é e para que serve? (Videos de Ti)](https://www.youtube.com/watch?v=W530u7lTZ_k) — Primeira aula de uma série completa em português para quem nunca usou Vagrant.
8. [Vagrant Crash Course (Traversy Media)](https://www.youtube.com/watch?v=vBreXjkizgo) — Curso rápido em vídeo cobrindo os fundamentos do zero, em inglês.

## 📖 Documentação oficial

- [Vagrant by HashiCorp (portal oficial)](https://developer.hashicorp.com/vagrant) — Página inicial de toda a documentação oficial do Vagrant.
- [Vagrant Documentation](https://developer.hashicorp.com/vagrant/docs) — Índice completo da documentação: conceitos, comandos e configuração.
- [Vagrantfile](https://developer.hashicorp.com/vagrant/docs/vagrantfile) — Referência completa da sintaxe Ruby usada para configurar máquinas.
- [CLI — Command-Line Interface](https://developer.hashicorp.com/vagrant/docs/cli) — Documentação de cada subcomando do `vagrant` (up, halt, ssh, provision, destroy…).
- [Multi-Machine](https://developer.hashicorp.com/vagrant/docs/multi-machine) — Como definir e orquestrar várias VMs em um único `Vagrantfile`.
- [Networking](https://developer.hashicorp.com/vagrant/docs/networking) — Configuração de rede: forwarded ports, private network e public network.
- [Synced Folders](https://developer.hashicorp.com/vagrant/docs/synced-folders) — Como compartilhar pastas entre a máquina anfitriã e a VM.
- [Provisioning](https://developer.hashicorp.com/vagrant/docs/provisioning) — Visão geral dos provisionadores suportados (Shell, Ansible, Chef, Puppet, Docker).
- [Providers](https://developer.hashicorp.com/vagrant/docs/providers) — Como o Vagrant se conecta a diferentes back-ends de virtualização.
- [VirtualBox Provider](https://developer.hashicorp.com/vagrant/docs/providers/virtualbox) — Documentação oficial do provider mais usado, incluído por padrão no Vagrant.
- [Docker Provider](https://developer.hashicorp.com/vagrant/docs/providers/docker) — Como o Vagrant também pode gerenciar containers Docker com a mesma interface de VMs.
- [Boxes](https://developer.hashicorp.com/vagrant/docs/boxes) — O que é uma box, como adicionar, atualizar e remover imagens base.
- [Triggers](https://developer.hashicorp.com/vagrant/docs/triggers) — Como executar ações customizadas antes ou depois de comandos do Vagrant.
- [Plugins](https://developer.hashicorp.com/vagrant/docs/plugins) — Como instalar, criar e distribuir plugins para estender o Vagrant.
- [Vagrantfile — Version](https://developer.hashicorp.com/vagrant/docs/vagrantfile/version) — Controle de versão do formato do Vagrantfile.
- [Vagrant no WSL (Windows Subsystem for Linux)](https://developer.hashicorp.com/vagrant/docs/other/wsl) — Guia oficial para rodar Vagrant dentro do WSL no Windows.
- [hashicorp/vagrant (repositório oficial)](https://github.com/hashicorp/vagrant) — Código-fonte completo do Vagrant no GitHub, com issues e histórico de commits.
- [CHANGELOG.md](https://github.com/hashicorp/vagrant/blob/main/CHANGELOG.md) — Notas de cada versão lançada, mantidas pela própria HashiCorp.
- [Wiki oficial do projeto](https://github.com/hashicorp/vagrant/wiki) — Documentação complementar mantida pela comunidade e pelo time do Vagrant.
- [Available Vagrant Plugins (wiki oficial)](https://github.com/hashicorp/vagrant/wiki/Available-Vagrant-Plugins) — Lista mantida pela comunidade com dezenas de plugins de terceiros para o Vagrant.

## 🔤 Sites e cursos para aprender Vagrant

> Cursos para aprender Vagrant em Português

- [Vagrant Aula 01 — O que é e para que serve? (Videos de Ti)](https://www.youtube.com/watch?v=W530u7lTZ_k) — Primeira aula de uma série completa e gratuita sobre Vagrant, do zero.
- [Vagrant Aula 02 — Requisitos para o uso do Vagrant (Videos de Ti)](https://www.youtube.com/watch?v=j7SOK5ppaTQ) — Segunda aula da série: o que instalar antes de começar.
- [Vagrant Aula 05 — Configurando/instalando uma nova Box (Videos de Ti)](https://www.youtube.com/watch?v=isLlLbTGTwk) — Parte da mesma série, sobre como adicionar boxes ao Vagrant.
- [Vagrant Aula 06 — Iniciando e acessando uma Box (Videos de Ti)](https://www.youtube.com/watch?v=oKuw-ff0s2w) — Como subir e acessar por SSH a primeira máquina virtual.
- [Vagrant — #1 — Instalando o Vagrant para integração com VirtualBox (Diogo Godoi)](https://www.youtube.com/watch?v=gZmw41X8B2w) — Primeiro vídeo de uma série prática sobre Vagrant e VirtualBox.
- [Vagrant — #2 — Aprendendo a configurar o Vagrant com VirtualBox (Diogo Godoi)](https://www.youtube.com/watch?v=835IHuWFwf0) — Continuação da série, já configurando o ambiente.
- [Iniciando com Vagrant (Diego Fernandes — Rocketseat)](https://www.youtube.com/watch?v=gx50Kv6-2KA) — Introdução prática ao Vagrant por um dos fundadores da Rocketseat.
- [Vagrant 101 — Infraestrutura como Código para Desenvolvimento e Estudo (Caio Delgado)](https://www.youtube.com/watch?v=PX6OmeIbjC4) — Primeiros passos com Vagrant aplicados a infraestrutura como código.
- [Vagrant do Zero: Deploy Automático de VMs em Minutos (José Henrique de Oliveira)](https://www.youtube.com/watch?v=LKTr5smYX38) — Guia prático de ponta a ponta para quem nunca usou a ferramenta.
- [Como Instalar e Usar o Vagrant para Criar Laboratórios Virtuais (Felipe Padilha)](https://www.youtube.com/watch?v=MXqiDGqpZso) — Passo a passo de instalação e primeiro laboratório com Vagrant.
- [Vagrant: Criando Máquinas Virtuais — Fácil, Automático e Codificado (4TWO)](https://www.youtube.com/watch?v=NoO09mSs_ks) — Introdução ao Vagrant como ambiente de desenvolvimento codificado.
- [Vagrant: Criando Máquinas Virtuais com um Comando (Mateus Muller)](https://www.youtube.com/watch?v=VRzjkUJz-9U) — Demonstração direta de como subir uma VM completa com um único comando.
- [Como Instalar o Vagrant (Estação DBA)](https://www.youtube.com/watch?v=wGbBSmmb0sg) — Instalação do Vagrant explicada por um canal focado em administração de banco de dados.
- [Projeto Vagrant — Instalação do Ambiente (Yuri Iwagoe)](https://www.youtube.com/watch?v=08GuNX2ISxo) — Configuração de um ambiente de projeto usando Vagrant.
- [Vagrant — Como Criar uma VM (LITUX)](https://www.youtube.com/watch?v=4_YZAhi1urE) — Tutorial direto sobre a criação de uma máquina virtual com Vagrant.
- [Vagrant + Ubuntu: Criando um Servidor Linux do Zero (DeltaOps)](https://www.youtube.com/watch?v=74th6vOAaO0) — Provisionamento de um servidor Ubuntu completo usando Vagrant.
- [Vídeo 01 — Comandos Básicos Vagrant (Paulo Sérgio Sausen)](https://www.youtube.com/watch?v=5D5JYyCxYaQ) — Comandos essenciais do dia a dia com Vagrant.

> Cursos para aprender Vagrant em Inglês

- [Vagrant Crash Course (Traversy Media)](https://www.youtube.com/watch?v=vBreXjkizgo) — Curso rápido e direto cobrindo os fundamentos do Vagrant, de um dos canais mais respeitados de programação.
- [Vagrant Tutorial for Beginners 1 — Introduction to Vagrant (ProgrammingKnowledge)](https://www.youtube.com/watch?v=67Z2uYPp0LA) — Primeiro vídeo de uma série extensa para iniciantes.
- [Getting Started with Vagrant (ProgrammingKnowledge)](https://www.youtube.com/watch?v=u8ilG1YSyhg) — Continuação prática da série de introdução ao Vagrant.
- [Vagrant 101 Tutorial — All You Need to Know to Get Started (DevOps Journey)](https://www.youtube.com/watch?v=a6W1hF9CgDQ) — Visão geral completa dos conceitos essenciais do Vagrant.
- [Vagrant 101 — Setup Multiple Machines in One Vagrantfile (DevOps Journey)](https://www.youtube.com/watch?v=a9pHnOkhcds) — Como declarar e orquestrar múltiplas VMs no mesmo arquivo.
- [Vagrant 101 — Advanced Options (DevOps Journey)](https://www.youtube.com/watch?v=XLnzCElgE9U) — Opções avançadas de configuração do Vagrantfile.
- [Everything a Beginner Needs to Know About Vagrant — Parte 1 (Automation Step by Step)](https://www.youtube.com/watch?v=czMCO1w-xQU) — Primeira parte de uma série completa voltada para automação e DevOps.
- [Getting Started with Vagrant Setup for Beginners — Parte 2 (Automation Step by Step)](https://www.youtube.com/watch?v=7DLfOGt8YvA) — Continuação prática da série anterior.
- [Automated Virtual Machine Deployment with Vagrant (Christian Lempa)](https://www.youtube.com/watch?v=sr9pUpSAexE) — Uso real de Vagrant para automatizar deploy de VMs em ambiente de homelab.
- [Automate Your Virtual Lab Environment with Ansible and Vagrant (Christian Lempa)](https://www.youtube.com/watch?v=7Di0twyxw1M) — Combinação de Vagrant com Ansible para laboratórios de estudo.
- [Build Your First DevOps Lab Using Vagrant in Minutes (CloudBits by Rajan)](https://www.youtube.com/watch?v=54h0mqFb7eo) — Montagem rápida de um laboratório de estudo de DevOps com Vagrant.
- [Vagrant in 5 Minutes (Opensource.com)](https://www.youtube.com/watch?v=cx79jOpZVE8) — Resumo rápido do que é Vagrant e por que ele existe.

## 📚 Livros

Vagrant tem poucos livros dedicados — o ecossistema de publicações se concentrou majoritariamente em conteúdo online e na própria documentação oficial. Os dois títulos abaixo continuam sendo referência.

- [Vagrant: Up and Running (Mitchell Hashimoto)](https://archive.org/details/vagrantuprunning0000hash) — Livro oficial escrito pelo próprio criador do Vagrant (O'Reilly, 2013); disponível para empréstimo digital gratuito no Internet Archive. Livro pago nas livrarias.
- [Vagrant Virtual Development Environment Cookbook (Chad Thompson)](https://openlibrary.org/works/OL27686685W/Vagrant_Virtual_Development_Environment_Cookbook) — Livro de receitas práticas com Vagrant, publicado pela Packt (2015). Livro pago.

## 🎥 Canais no Youtube

> Em português

- [Videos de Ti](https://www.youtube.com/@videosdeti1954) — Autor da série completa "Vagrant Aula 01" a "06", uma trilha estruturada do zero em português.
- [Diogo Godoi](https://www.youtube.com/@dggodoi) — Série prática de instalação e configuração do Vagrant com VirtualBox.
- [Rocketseat](https://www.youtube.com/@rocketseat) — Uma das maiores plataformas de ensino de programação do Brasil, com conteúdo introdutório sobre Vagrant.
- [Caio Delgado](https://www.youtube.com/@caiodelgadonew) — Conteúdo sobre infraestrutura como código, incluindo Vagrant 101.
- [José Henrique de Oliveira](https://www.youtube.com/@jh.oliveira1993) — Guias práticos de deploy automático de VMs com Vagrant.
- [Felipe Padilha](https://www.youtube.com/@FelipePadilha) — Tutoriais sobre criação de infraestruturas e laboratórios virtuais com Vagrant.
- [4TWO](https://www.youtube.com/@4TWO42) — Conteúdo sobre ambientes de desenvolvimento automatizados com Vagrant.
- [Mateus Muller](https://www.youtube.com/@MateusMuller) — Demonstrações diretas de automação de máquinas virtuais com Vagrant.
- [Estação DBA](https://www.youtube.com/@estacaodba3291) — Canal focado em administração de banco de dados, com tutorial de instalação do Vagrant.
- [Yuri Iwagoe](https://www.youtube.com/@yuriiwagoe1661) — Configuração de ambientes de projeto usando Vagrant.
- [LITUX](https://www.youtube.com/@LITUX_Henrique) — Tutoriais diretos sobre criação de VMs com Vagrant.
- [DeltaOps](https://www.youtube.com/@deltaopslabs) — Conteúdo de infraestrutura e provisionamento de servidores Linux com Vagrant.

> Em inglês

- [Traversy Media](https://www.youtube.com/@TraversyMedia) — Um dos canais de programação mais respeitados, autor do "Vagrant Crash Course".
- [ProgrammingKnowledge](https://www.youtube.com/@ProgrammingKnowledge) — Série extensa de tutoriais para iniciantes em Vagrant.
- [DevOps Journey](https://www.youtube.com/@DevOpsJourney) — Série "Vagrant 101" cobrindo do básico a opções avançadas do Vagrantfile.
- [Automation Step by Step (Raghav Pal)](https://www.youtube.com/@RaghavPal) — Canal de referência em automação e DevOps, com série dedicada a Vagrant para iniciantes.
- [Christian Lempa](https://www.youtube.com/@christianlempa) — Um dos maiores canais de homelab e self-hosting, com Vagrant como parte central de vários vídeos.
- [HashiCorp](https://www.youtube.com/@HashiCorp) — Canal oficial da empresa criadora do Vagrant, Terraform e Packer.

## 📰 Sites, blogs e newsletters

Assim como os livros, a produção de artigos dedicados especificamente a Vagrant é escassa hoje em dia — a maior parte do conteúdo novo migrou para vídeo (seção acima). Os sites abaixo ainda mantêm tutoriais e um acervo relevante sobre o tema.

- [DigitalOcean Community — tag Vagrant](https://www.digitalocean.com/community/tags/vagrant) — Coleção de tutoriais da comunidade DigitalOcean sobre Vagrant, incluindo os dois artigos abaixo.
- [How To Use Vagrant to Create Virtual Development Environments (DigitalOcean)](https://www.digitalocean.com/community/tutorials/how-to-use-vagrant-to-create-virtual-development-environments) — Tutorial clássico e completo sobre os fundamentos do Vagrant.
- [How To Use Vagrant to Create a Simple LAMP Stack (DigitalOcean)](https://www.digitalocean.com/community/tutorials/how-to-use-vagrant-to-create-virtual-development-environments-a-simple-lamp-stack-example) — Aplicação prática: provisionando um ambiente LAMP completo com Vagrant.
- [Blog de Jeff Geerling](https://www.jeffgeerling.com/blog/) — Autor do livro "Ansible for DevOps" e criador de dezenas de exemplos que usam Vagrant para laboratórios locais.

## 🛠️ Ferramentas

> Providers (back-ends de virtualização)

- [Oracle VirtualBox](https://www.virtualbox.org/) — Hypervisor gratuito e o provider padrão do Vagrant, disponível para Windows, macOS e Linux.
- [QEMU](https://www.qemu.org/) — Emulador de máquinas usado como base de providers alternativos ao VirtualBox, especialmente em Linux e Apple Silicon.
- [libvirt](https://libvirt.org/) — Framework de virtualização do Linux (KVM/QEMU) usado pelo provider `vagrant-libvirt`.
- [vagrant-libvirt](https://github.com/vagrant-libvirt/vagrant-libvirt) — Plugin que adiciona suporte a KVM/libvirt como provider, alternativa mais leve ao VirtualBox em Linux.

> Plugins essenciais

- [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) — Mantém as VirtualBox Guest Additions sempre atualizadas dentro da VM automaticamente. Repositório arquivado pelo mantenedor, mas o plugin ainda funciona e é amplamente usado.
- [vagrant-hostmanager](https://github.com/devopsgroup-io/vagrant-hostmanager) — Gerencia entradas de `/etc/hosts` automaticamente para múltiplas VMs.
- [vagrant-disksize](https://github.com/sprotheroe/vagrant-disksize) — Permite redimensionar o disco de uma box diretamente pelo Vagrantfile.
- [vagrant-reload](https://github.com/aidanns/vagrant-reload) — Adiciona um provisionador para reiniciar a VM no meio do processo de provisionamento.
- [Available Vagrant Plugins (wiki oficial)](https://github.com/hashicorp/vagrant/wiki/Available-Vagrant-Plugins) — Lista comunitária com dezenas de outros plugins por categoria.

> Boxes e ferramentas complementares da HashiCorp

- [Vagrant Cloud — descobrir boxes](https://portal.cloud.hashicorp.com/vagrant/discover) — Catálogo oficial de boxes publicadas por distribuições Linux e pela comunidade.
- [chef/bento](https://github.com/chef/bento) — Templates Packer usados para construir as boxes oficiais do Vagrant de várias distribuições Linux.
- [Packer](https://developer.hashicorp.com/packer) — Outra ferramenta da HashiCorp, usada para criar as próprias boxes/imagens que o Vagrant consome.
- [Terraform](https://github.com/hashicorp/terraform) — Ferramenta irmã do Vagrant no ecossistema HashiCorp, focada em provisionar infraestrutura em nuvem em vez de VMs locais.

> Alternativas e ambientes complementares

- [Multipass (Canonical)](https://canonical.com/multipass) — Alternativa da Canonical para subir VMs Ubuntu leves via linha de comando, comparável em propósito ao Vagrant.
- [WSL — Windows Subsystem for Linux](https://learn.microsoft.com/en-us/windows/wsl/install) — Alternativa nativa do Windows para muitos dos casos de uso que antes dependiam só de Vagrant.
- [Test Kitchen — kitchen-vagrant](https://github.com/test-kitchen/kitchen-vagrant) — Driver que integra o Vagrant ao Test Kitchen para testar automaticamente roles/cookbooks de configuração.
- [Visual Studio Code](https://code.visualstudio.com/) — Editor recomendado para escrever Vagrantfiles e scripts de provisionamento, com boa integração ao terminal e ao Remote-SSH.

## 🧪 Projetos práticos e desafios

- [awesome-vagrant (iJackUA)](https://github.com/iJackUA/awesome-vagrant) — Lista curada de recursos, boxes, plugins e exemplos de projetos com Vagrant. Sem commits recentes; útil como ponto de partida, mas alguns links internos podem estar desatualizados.
- [DevOps Exercises](https://github.com/bregman-arie/devops-exercises) — Milhares de exercícios e perguntas de entrevista sobre Linux, Vagrant, Ansible, Docker e mais.
- [90 Days of DevOps](https://github.com/MichaelCade/90DaysOfDevOps) — Projeto de aprendizado estruturado em público, cobrindo virtualização e ferramentas de laboratório como Vagrant.
- [Ansible Vagrant Examples (geerlingguy)](https://github.com/geerlingguy/ansible-vagrant-examples) — Exemplos reais de uso de Vagrant junto com Ansible para provisionar VMs locais — ótimo projeto para estudar e reproduzir.
- [kitchen-vagrant](https://github.com/test-kitchen/kitchen-vagrant) — Use como projeto prático para aprender testes automatizados de infraestrutura com Vagrant.
- [chef/bento](https://github.com/chef/bento) — Estude como as boxes oficiais são construídas do zero com Packer, um ótimo projeto avançado para entender o "outro lado" do Vagrant.
- [Killercoda](https://killercoda.com/) — Sandbox interativo gratuito no navegador com cenários de DevOps e infraestrutura para praticar sem instalar nada localmente.

## 🤖 IA na prática

Vagrantfile é Ruby, mas na prática funciona como configuração declarativa — um formato que assistentes de IA leem e escrevem bem. O ganho real está em usar a IA para gerar e revisar Vagrantfiles mais rápido, mas sempre validando contra o comportamento real da VM: a IA não roda `vagrant up` por você, e detalhes de rede, provider e box erram com frequência.

**Para aprender**
- Cole um `Vagrantfile` que não sobe e o erro completo do `vagrant up`, e peça: *"explique o que esse erro significa linha por linha e como corrigir sem reescrever o arquivo inteiro"*.
- Peça para **gerar um Vagrantfile multi-máquina do zero** (ex.: uma VM de banco de dados e uma de aplicação) e depois pergunte o porquê de cada bloco `config.vm.define`.
- Peça exercícios com gabarito sobre um tópico específico (redes `private_network` vs `public_network`, synced folders, provisionadores) para fixar a sintaxe.
- Peça para explicar a diferença entre provisionar com Shell script, Ansible e Chef dentro do mesmo `Vagrantfile`, com prós e contras de cada um.

**Para trabalhar**
- Use [GitHub Copilot](https://github.com/features/copilot), [Cursor](https://cursor.com/) ou [Claude Code](https://code.claude.com/docs/en/overview) para: gerar o esqueleto de um `Vagrantfile` novo, converter um script de setup manual em provisionamento Shell/Ansible, e documentar as portas e pastas compartilhadas de um projeto legado.
- Depois de **cada** sugestão aceita, rode `vagrant validate` (verifica a sintaxe do Vagrantfile) e depois `vagrant up --provision` de verdade — se a VM não sobe ou o provisionamento falha, a sugestão estava errada.
- Peça para a IA revisar se o `Vagrantfile` gerado está usando IPs de rede privada reservados (RFC 1918) corretamente e se não há portas expostas desnecessariamente para `0.0.0.0`.
- O [Model Context Protocol](https://modelcontextprotocol.io/), especificação aberta mantida no [GitHub](https://github.com/modelcontextprotocol), permite conectar agentes de IA a ferramentas externas; já existem servidores MCP comunitários (não oficiais) para Vagrant/VirtualBox, mas são projetos pequenos e em estágio inicial — trate-os como experimentais, não como ferramentas prontas para produção.

**Limites e boas práticas**
- IA **inventa opções de configuração** que não existem no `Vagrantfile` (principalmente para providers menos comuns). Confirme sempre na [documentação oficial](https://developer.hashicorp.com/vagrant/docs/vagrantfile).
- Modelos tendem a sugerir provisionamento que funciona na primeira execução mas quebra em um `vagrant reload --provision` (não é idempotente). Rode o provisionamento duas vezes seguidas e confira se nada quebra na segunda.
- **Nunca cole credenciais, tokens de nuvem ou chaves privadas** usados dentro da VM em ferramentas de IA sem a política de segurança da sua empresa.
- Entenda o que você aceita: quem sobe a VM contra a sua máquina (ou contra um provider remoto) é você, não o modelo.

## 💼 Carreira e vagas

Vagrant raramente é o requisito principal de uma vaga — ele aparece como habilidade complementar em vagas de DevOps, SRE, QA/automação de testes, infraestrutura e suporte técnico, quase sempre ao lado de VirtualBox, Ansible, Docker e Linux. Dica: nos repositórios de vagas abaixo, pesquise por "DevOps", "Infraestrutura" ou "SysAdmin" nas issues abertas.

- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — Pesquisa anual sobre o ecossistema de tecnologia, incluindo ferramentas de virtualização e DevOps.
- [Vagas de DevOps (Vagas.com)](https://www.vagas.com.br/vagas-de-devops) — Vagas de DevOps no Brasil, área em que noções de Vagrant costumam aparecer como diferencial.
- [Vagas de Infraestrutura (Vagas.com)](https://www.vagas.com.br/vagas-de-infraestrutura) — Vagas de infraestrutura no Brasil, onde laboratórios locais com Vagrant são habilidade comum.
- [Vagas de Infraestrutura (Programathor)](https://programathor.com.br/jobs-infraestrutura) — Vagas de tecnologia focadas em infraestrutura publicadas na Programathor.
- [Coodesh](https://coodesh.com/) — Vagas de tecnologia no Brasil com processos seletivos padronizados.
- [Remotar](https://remotar.com.br/) — Vagas 100% remotas para profissionais brasileiros de tecnologia.

## 👥 Comunidades

- [HashiCorp Discuss — categoria Vagrant](https://discuss.hashicorp.com/c/vagrant/24) — Fórum oficial da HashiCorp para tirar dúvidas e discutir Vagrant com a comunidade e mantenedores.
- [Issues do hashicorp/vagrant](https://github.com/hashicorp/vagrant/issues) — Acompanhe e participe de discussões técnicas reais sobre bugs e novas funcionalidades.
- [Vagrant no GitHub Topics](https://github.com/topics/vagrant) — Milhares de repositórios marcados com o tópico Vagrant — ótimo para descobrir Vagrantfiles e projetos reais.
- [r/vagrant](https://www.reddit.com/r/vagrant/) — Subreddit da comunidade Vagrant, com dúvidas e discussões técnicas.
- [Viva o Linux](https://www.vivaolinux.com.br/) — Uma das maiores comunidades brasileiras de Linux e código aberto, boa para tirar dúvidas de virtualização e infraestrutura local.

## 🚨 Como contribuir

Toda sugestão de recurso, correção de link ou melhoria de texto é bem-vinda. Veja os critérios de aceitação e o passo a passo completo em [CONTRIBUTING.md](./CONTRIBUTING.md).

## 📄 Licença

Este projeto está sob a licença [MIT](./LICENSE). Sinta-se livre para usar, adaptar e compartilhar, mantendo o crédito ao [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil).

## 💙 Apoie o projeto

<sub> <strong>Se este guia te ajudou, considere apoiar o projeto: </strong> <br>
[<img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/arthurspk/)
[<img src = "https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white">](https://x.com/manotoquinho)
[<img src = "https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/guiadevbrasil/)
[<img src = "https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white">](https://www.facebook.com/seixasqlc/)
</sub>

⭐ E não esqueça de deixar uma estrela no [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil)!
