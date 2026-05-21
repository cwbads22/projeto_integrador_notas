
**Introdução Geral sobre as Metodologias

Integrar o Design Thinking ao ITIL ==transforma a gestão de serviços de TI, mudando o foco da infraestrutura puramente técnica para a experiência do usuário (UX) e a criação de valor real==. Essa fusão prioriza a empatia e a inovação para resolver problemas complexos na área de TI. 

A abordagem se encaixa perfeitamente nas práticas do framework através das seguintes etapas de inovação e entrega de valor: [1

## 1. Empatia e Imersão (Entendendo o Usuário)

- Conceito: Investiga as dores, sentimentos e reais necessidades do cliente ou colaborador antes de propor qualquer mudança ou ferramenta.
- No ITIL: Alinha-se diretamente com o Princípio Orientador do ITIL: _Focar no valor_ e _Progredir iterativamente com feedback_. Em vez de presumir o que a área de negócio precisa, a TI entrevista e mapeia a jornada do usuário. 

## 2. Definição (Focalizando o Problema)

- Conceito: Filtra a massa de informações coletadas na imersão para declarar qual é o verdadeiro problema a ser resolvido.
- No ITIL: Essencial para a prática de Desenho de Serviço e gestão de portfólio. Evita o desperdício de tempo e recursos desenvolvendo ou alterando serviços de TI pelos motivos errados. 

## 3. Ideação e Prototipagem (Soluções Colaborativas)

- Conceito: Gera múltiplas soluções criativas em grupo e constrói protótipos rápidos e de baixo custo (mockups, testes de fluxo, mapas de tela) para validação.
- No ITIL: Fortalece o Sistema de Valor de Serviço (SVS), promovendo a _colaboração e visibilidade_. Equipes multifuncionais de TI trabalham juntas com o cliente para desenhar novos incidentes, requisições ou catálogos de serviços. 

## 4. Teste e Implementação (Valor Digital)

- Conceito: O protótipo é testado pelo usuário final em um ambiente seguro, permitindo aprendizado contínuo e ajustes antes do lançamento oficial.
- No ITIL: Integra-se perfeitamente às práticas de Gerenciamento de Mudanças, _Otimização e Automação_, garantindo que a nova solução seja não apenas tecnicamente viável, mas usável e desejada pelos negócios. 

Para aprofundar a aplicação dessa metodologia na sua empresa, me conte:

- Qual é o principal desafio que você está enfrentando no momento (ex: demora no atendimento, aprovação de novos serviços, adoção de novas ferramentas)?
- Qual etapa do ITIL você está tentando otimizar?

Com essas informações, posso detalhar ferramentas práticas de Design Thinking (como mapas de empatia ou jornadas do usuário) aplicáveis ao seu cenário.

 ---

## Aplicação das metodologias às idéias do PI

**A solução será uma plataforma (ainda não definida se será um site, app, extensão de navegador) que tem por objetivo instruir as pessoas sobre golpes virtuais: engenharia social, links falsos, etc.

Para esse cenário, a integração do Design Thinking com o ITIL 4 foca na fase de Desenho de Serviço (Service Design) e na cocriação de valor, garantindo que a plataforma seja intuitiva e útil antes mesmo de você escrever a primeira linha de código.

A abordagem prática para estruturar esse projeto envolve as seguintes etapas:

## 1. Empatia: Mapear o Perfil das Vítimas

- Ação: Entrevistar pessoas que já caíram em golpes e pessoas com baixa familiaridade digital.
- Foco: Entender o sentimento delas (vergonha, medo, confusão) ao lidar com links falsos ou engenharia social.
- Ferramenta: Mapa de Empatia. O que elas ouvem de amigos? O que veem na internet? Quais são suas maiores dores?

## 2. Definição: O Ponto de Contato Ideal

- Ação: Cruzar o comportamento do usuário com o momento em que o golpe acontece.
- Foco: Descobrir o formato ideal da solução.
    
    - Se o usuário clica por impulso, uma extensão de navegador que avisa "Link Suspeito" em tempo real pode ser mais eficaz do que um site educativo que ele precisa lembrar de acessar.
    
- No ITIL: Isso define a _Utilidade_ (o que o serviço faz) e a _Garantia_ (como ele é entregue) dentro da estratégia do serviço.

## 3. Ideação: Cocriação de Conteúdo e Alertas

- Ação: Reunir especialistas em segurança (TI), designers e usuários comuns para um brainstorming.
- Foco: Como traduzir termos técnicos como "Phishing" ou "Engenharia Social" em alertas simples que uma avó ou um jovem ansioso consigam entender instantaneamente.
- No ITIL: Alinha-se ao princípio de _Colaborar e promover visibilidade_.

## 4. Prototipagem Rápida: Testar o Formato

- Ação: Criar protótipos de baixa fidelidade (desenhos no papel ou telas simples no Figma) simulando as três opções: o site, o app e a extensão.
- Foco: Validar o formato com usuários reais. Peça para eles simularem que receberam um link falso no WhatsApp e veja qual das interfaces gera a reação correta de proteção.
- No ITIL: Isso mitiga riscos na prática de _Gerenciamento de Mudança e Liberação_, evitando gastar orçamento desenvolvendo o produto errado.

---

**Criar as Personas (exemplos) e o Mapa de Empatia dos Usuários a Serem Protegidos pela solução.

Para construir uma plataforma eficaz contra golpes virtuais, precisamos entender duas pontas frágeis do comportamento humano: a falta de familiaridade técnica (vulnerabilidade por desconhecimento) e a urgência/ansiedade (vulnerabilidade por impulsividade).

Abaixo, estruturei duas Personas distintas e seus respectivos Mapas de Empatia para guiar o design da sua solução.

---

## Persona 1: O Inexperiente Digital

_Quem queremos proteger: Pessoas mais velhas ou com pouco contato histórico com tecnologia, que usam a internet apenas para o básico._

- Nome: Seu Carlos, 63 anos.
- Perfil: Aposentado, usa o smartphone principalmente para o WhatsApp, aplicativos de banco e assistir a vídeos.
- Comportamento: É muito educado e prestativo, confia nas pessoas e tem medo de "estragar" o celular ou perder dinheiro.

## Mapa de Empatia: Seu Carlos

- O que vê? Amigos compartilhando promoções imperdíveis no WhatsApp; notícias na TV sobre golpes financeiros; interfaces cheias de botões pequenos e termos em inglês que ele não entende.
- O que ouve? Os filhos dizendo: _"Pai, não clica em nada estranho!"_; mensagens de áudio alarmantes em grupos da família alertando sobre novos perigos.
- O que pensa e sente? Pensa: _"Será que o banco está me ligando mesmo?"_; sente medo de ser passado para trás, vergonha de pedir ajuda aos filhos toda hora e ansiedade ao lidar com transações digitais.
- O que fala e faz? Compartilha links de sorteios sem saber se são reais; atende ligações de números desconhecidos; pede ajuda ao caixa eletrônico ou a vizinhos.
- Dores (Fraquezas): Não sabe distinguir uma URL real de uma falsa; confia em logotipos oficiais copiados por golpistas.
- Necessidades (Ganhos): Um sistema visual muito simples (como uma luz vermelha/verde); alertas diretos e em português claro, sem jargões técnicos.

---

## Persona 2: O Jovem Imediatista

_Quem queremos proteger: Nativos digitais que dominam a tecnologia, mas caem em golpes devido à pressa, ganância ou engenharia social sofisticada._

- Nome: Júlia, 22 anos.
- Perfil: Estudante universitária e estagiária, vive conectada, faz compras online e usa redes sociais constantemente.
- Comportamento: Multitarefa, faz tudo correndo pelo celular enquanto anda ou estuda. Busca independência financeira rápida.

## Mapa de Empatia: Júlia

- O que vê? Anúncios no Instagram de produtos muito baratos; influenciadores divulgando jogos de apostas ou oportunidades de renda extra rápida; e-mails de rastreamento de encomendas.
- O que ouve? Amigos falando sobre como compraram roupas baratas em sites internacionais; tendências do TikTok.
- O que pensa e sente? Pensa: _"Preciso aproveitar essa promoção antes que acabe"_ ou _"Se o influenciador postou, deve ser seguro"_; sente a urgência de não perder uma oportunidade (FOMO) e excesso de confiança em sua própria capacidade digital.
- O que fala e faz? Compra por impulso digitando o cartão de crédito em qualquer checkout; clica em links de SMS para "liberar entrega de mercadoria" sem checar o remetente.
- Dores (Fraquezas): Cegueira por desatenção (não repara no link modificado por estar na correria); vulnerável a gatilhos de urgência e escassez.
- Necessidades (Ganhos): Uma barreira de proteção automática (que bloqueie a ação antes do clique); educação rápida em pílulas (ex: vídeos de 15 segundos sobre como o golpe funciona).

---

## O Impacto no Formato da Solução

Analisando essas duas personas através do olhar do Design Thinking e ITIL (Utilidade do Serviço), podemos notar um padrão:

- Para o Seu Carlos, um _site educativo_ exige que ele lembre de acessá-lo, o que dificilmente acontecerá. Ele se beneficiaria de um aplicativo de segurança ou suporte assistido.
- Para a Júlia, uma extensão de navegador ou um mecanismo de alerta em tempo real no celular que barre o clique impulsivo seria o ideal, pois ela não vai parar a rotina para ler um manual.

---

**Mapeamento da Jornada de Usuário

Mapear a Jornada do Usuário permite identificar o exato momento de vulnerabilidade (o "ponto de infecção") onde a sua plataforma deve intervir para evitar o golpe. No ITIL, isso equivale a mapear os pontos de contato para garantir a Utilidade do serviço no momento certo.

Abaixo estão as jornadas detalhadas para o Seu Carlos e para a Júlia.

---

## Jornada 1: Seu Carlos e o Golpe do "Falso Ponto/Brinde" no WhatsApp

O objetivo aqui é entender como o golpista usa a confiança e a falta de atenção técnica.

|Fase da Jornada|Ação do Seu Carlos|O que ele está pensando/sentindo?|O Momento do Golpe (Gatilho)|Onde a Plataforma deve agir?|
|---|---|---|---|---|
|1. Estímulo|Recebe uma mensagem de um amigo no WhatsApp: _"O Boticário está dando brindes de Natal, clica aqui!"_.|_"Que bom, vou garantir um presente para a minha esposa."_ (Sentimento: Alegria/Confiança).|O link parece real porque veio de um amigo de confiança.|Prevenção: Se fosse uma extensão ou app integrado, emitiria um aviso de link suspeito no chat.|
|2. Ação|Clica no link e abre uma página idêntica à do site oficial, com um cronômetro e um formulário.|_"Preciso correr antes que os brindes acabem."_ (Sentimento: Ansiedade leve).|A cópia visual perfeita engana o olhar não treinado dele.|Bloqueio Visual: A plataforma bloqueia a tela com um aviso: _"Atenção: Este site NÃO é oficial"_.|
|3. O Golpe|Digita o nome, CPF e, no final, o site pede o código enviado por SMS para "confirmar o brinde".|_"Só falta isso para ganhar o prêmio."_ (Sentimento: Expectativa).|O MOMENTO EXATO: Ele insere o código do SMS (que na verdade é o PIN de ativação do WhatsApp dele).|Alerta Crítico: Um pop-up flutuante avisa: _"Nunca compartilhe códigos de SMS. Isso vai roubar sua conta!"_.|
|4. Impacto|O WhatsApp dele desconecta. Ele tenta abrir e não consegue. Amigos começam a ligar dizendo que ele está pedindo Pix.|_"O que eu fiz de errado? Que vergonha."_ (Sentimento: Desespero, culpa).|O golpe foi consolidado.|Remediação (ITIL Restauração): Guia rápido em 3 passos na tela inicial de como recuperar o WhatsApp.|

---

## Jornada 2: Júlia e o Golpe da "Falsa Entrega/Taxação" por SMS

O objetivo aqui é entender como o golpista usa a pressa e a rotina multitarefa.

|Fase da Jornada|Ação da Júlia|O que ela está pensando/sentindo?|O Momento do Golpe (Gatilho)|Onde a Plataforma deve agir?|
|---|---|---|---|---|
|1. Estímulo|Recebe um SMS enquanto estuda: _"Sua encomenda da Shein foi retida. Pague a taxa de R$ 27,90 para liberação: [link-falso.com]"_.|_"Ah não, minhas roupas! Sabia que ia ser taxada."_ (Sentimento: Frustração/Pressa).|O golpista acertou o hábito de consumo dela (ela sempre tem encomendas).|Filtro Ativo: A plataforma intercepta o SMS e o move para uma pasta de "Spam/Fraude".|
|2. Ação|Clica no link pelo celular. Abre uma página com o logotipo dos Correios e um código Pix copia e cola.|_"Vou pagar logo isso para chegar antes do fim de semana."_ (Sentimento: Impulsividade).|Ela não olha a URL (está escrita `correios-taxa-gov.com` em vez de `.gov.br`) porque está com pressa.|Alerta de Contexto: A extensão de navegador/app sinaliza: _"Este domínio foi criado há 2 dias. Risco de fraude alto"_.|
|3. O Golpe|Abre o app do banco, cola o código Pix e confirma o pagamento de R$ 27,90 sem checar o nome do recebedor.|_"Pronto, resolvido."_ (Sentimento: Alívio momentâneo).|O MOMENTO EXATO: Ela clica em "Confirmar Pix" para uma conta de pessoa física (laranja) e não para os Correios.|Barreira de Confirmação: O app de segurança gera uma notificação: _"Você está enviando dinheiro para [Nome Estranho]. Empresas públicas não recebem Pix em nomes de pessoas físicas."_|
|4. Impacto|Dois dias depois, entra no site real dos Correios e descobre que não havia taxa nenhuma. Perdeu o dinheiro.|_"Que raiva, como eu fui cair nisso? Sou burra."_ (Sentimento: Frustração, impotência).|O golpe foi consolidado.|Educação pós-incidente: Micro-conteúdo (vídeo de 15s) explicando o golpe da taxa para ela nunca mais cair.|

---

## Insights do Design Thinking para o seu Negócio

Olhando para o momento exato de cada golpe, descobrimos duas coisas cruciais:

1. O Seu Carlos precisa de Proteção Passiva: Ele precisa que a plataforma avise ele _antes_ dele digitar dados, pois ele confia no que está na tela.
2. A Júlia precisa de Quebra de Padrão: Ela age no piloto automático. A plataforma precisa dar um "choque de realidade" (um alerta disruptivo) bem na hora de pagar ou clicar para fazê-la parar e pensar.

---

**Listar as funcionalidades mínimas (MVP) para criar as barreiras para as duas jornadas.

Para criar o MVP (Produto Mínimo Viável) ideal com base no Design Thinking e no ITIL, o foco deve ser a máxima utilidade com o mínimo de esforço de desenvolvimento. Não precisamos de um sistema complexo de Inteligência Artificial logo no início, mas sim de barreiras simples e visuais que resolvam os "momentos exatos" do golpe para o Seu Carlos e para a Júlia.

Aqui estão as funcionalidades mínimas divididas pelos pilares de Proteção Passiva (Seu Carlos) e Quebra de Padrão (Júlia):

## 1. Motor de Checagem Rápida (A Funcionalidade Central)

- O que é: Um validador de links e chaves Pix.
- Como funciona no MVP: Uma barra simples onde o usuário cola o link suspeito ou a chave Pix recebida. O sistema cruza com bancos de dados públicos de fraudes e uma lista de domínios confiáveis (ex: sites de bancos, `.gov.br` reais, correios).
- Resultado esperado: Retorna imediatamente uma cor: Verde (Seguro), Amarelo (Atenção/Domínio Novo) ou Vermelho (Golpe Confirmado).

## 2. Barreira para o Seu Carlos: "O Semáforo Digital"

- O que é: Um sistema de alertas visuais extremamente simples e sem termos técnicos.
- Como funciona no MVP: Quando a plataforma identifica um link falso, ela não diz _"Este site contém um script de Phishing"_. Ela exibe uma tela inteira vermelha com a mensagem: "PARE! Este site é FALSO e quer roubar o seu WhatsApp. Feche esta página agora."
- Regra de Ouro (ITIL Utilidade): Uso de áudio explicativo curto. Um botão de "Ouvir Alerta" para que o Seu Carlos, caso tenha dificuldade de leitura ou compreensão, escute o aviso em português claro.

## 3. Barreira para a Júlia: "O Choque de Realidade"

- O que é: Um validador rápido de dados de pagamento (Pix) baseado em gatilhos de urgência.
- Como funciona no MVP: Antes de fazer o Pix da "taxa", a Júlia cola a chave Pix na plataforma. O sistema analisa o CNPJ/CPF receptor.
- Mensagem Disruptiva: Se o receptor for uma pessoa física ou uma empresa fantasma, o app exibe um pop-up piscante: "Empresas como Correios, Shein ou Bancos NÃO recebem dinheiro em nome de pessoas físicas. Você está prestes a enviar dinheiro para um golpista." Isso quebra o piloto automático dela.

## 4. Central de Pílulas de Conhecimento (Pós-Incidente / Educacional)

- O que é: Uma biblioteca muito enxuta de conteúdos educativos preventivos.
- Como funciona no MVP: Em vez de textos longos ou cartilhas em PDF, o MVP terá:
    
    - Para a Júlia: Vídeos de até 30 segundos (estilo Reels/TikTok) mostrando a tela de um golpe real acontecendo.
    - Para o Seu Carlos: Imagens estáticas grandes comparando o topo de um site real (com cadeado e URL certa) versus o site falso.
    

---

## Definição do Formato do MVP (Com base nas jornadas)

Para viabilizar essas funcionalidades de forma rápida e cobrir ambas as personas, o formato ideal para o lançamento do MVP é um Web App Otimizado para Celular (Mobile-First Website).

- Por que não um App de baixar na loja (Google Play/App Store)? Exige download, o que cria fricção para o Seu Carlos e afasta a Júlia que está com pressa.
- Por que não uma Extensão de Navegador? Funciona bem no computador, mas a maioria esmagadora dos golpes mapeados (WhatsApp e SMS) ocorre diretamente no celular.
- Como funcionará na prática: Um site leve (`://checapra-mim.com.br` ou similar) com um botão gigante na tela: _"Cole o link ou Pix aqui"_. O usuário pode fixar um atalho na tela inicial do celular com um clique, funcionando como um aplicativo.



