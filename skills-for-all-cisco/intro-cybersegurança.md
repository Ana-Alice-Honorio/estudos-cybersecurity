# Segurança Cibernética

## Particular

Como indivíduo, você precisa proteger sua identidade, seus dados e seus dispositivos de computação.

## Corporativo

No nível corporativo, é responsabilidade de todos proteger a reputação, os dados e os clientes da empresa.

## Governo

À medida que mais informações digitais são coletadas e compartilhadas, sua proteção se torna ainda mais vital no nível do governo, onde estão em jogo a segurança nacional, a estabilidade econômica, a segurança e o bem-estar dos cidadãos.

## Tipos de malware

### SpyWare

 Projetado para rastrear e espionar você, o spyware monitora sua atividade on-line e pode registrar todas as teclas que você pressiona no teclado, bem como capturar quase todos os dados, incluindo informações pessoais confidenciais, como detalhes bancários online. O spyware faz isso modificando as configurações de segurança dos dispositivos.Muitas vezes, o spyware se junta ao software legítimo ou a cavalos de Troia.

### AdWare

O adware é frequentemente instalado com algumas versões de software e é projetado para fornecer anúncios automaticamente a um usuário, na maioria das vezes em um navegador da Web. Você sabe quando vê! É difícil ignorar quando você se depara com anúncios pop-up constantes na tela. É comum o adware vir com spyware.

### Backdoor

Esse tipo de malware é usado para obter acesso não autorizado, ignorando os procedimentos normais de autenticação para acessar um sistema. Como resultado, os hackers podem obter acesso remoto a recursos em uma aplicação e emitir comandos de sistema remoto. Um backdoor funciona em segundo plano e é difícil de detectar.

### ramsomware

Malware projetado para manter um sistema de computador, ou os dados incluídos nele, presos até que o pagamento seja feito. O ransomware geralmente funciona criptografando os dados para que você não possa acessá-los.

Algumas versões de ransomware podem tirar proveito de vulnerabilidades específicas do sistema para bloqueá-lo. O ransomware é frequentemente disseminado por e-mails de phishing que o incentivam a baixar um anexo mal-intencionado ou uma vulnerabilidade de software.

### Scareware

Este é um tipo de malware que usa táticas de "medo" para induzi-lo a tomar uma ação específica. O Scareware consiste principalmente em janelas com estilo de sistema operacional que aparecem para alertar que seu sistema está em risco e precisa executar um programa específico para que ele retorne à operação normal.

Se você concordar em executar o programa específico, seu sistema será infectado por malware.

### rootkit

Esse malware foi projetado para modificar o sistema operacional para criar um backdoor, que os invasores podem usar para acessar seu computador remotamente. A maioria dos rootkits utiliza as vulnerabilidades do software para escalonar privilégios e modificar arquivos de sistema.

Também é comum os rootkits modificarem a computação forense do sistema e as ferramentas de monitoramento, o que os torna muito difíceis de ser detectados. Na maioria dos casos, um computador infectado por um rootkit precisa ser apagado e qualquer software necessário reinstalado.

### Vírus

Um vírus é um tipo de programa de computador que, quando executado, se replica e se anexa a outros arquivos executáveis, como um documento, ao inserir seu próprio código. A maioria dos vírus necessita de ativação do usuário final e pode ser ativada em uma hora ou data específica.

Os vírus podem ser relativamente inofensivos, como aqueles que exibem uma imagem divertida. Ou podem ser destrutivos, como os que modificam ou excluem dados.

Os vírus também podem ser programados para se modificar e evitar a detecção. Agora, a maioria dos vírus é espalhada por unidades de USB, discos ópticos, compartilhamentos de rede  ou e-mail.

### Cavalo de Troia

Esse malware realiza operações mal-intencionadas mascarando sua verdadeira intenção. Pode parecer legítimo, mas é, de fato, muito perigoso. Os cavalos de troia exploram os privilégios de usuário e são encontrados com mais frequência em arquivos de imagem, arquivos de áudio ou jogos.

Ao contrário dos vírus, os cavalos de troia não se replicam automaticamente, mas agem como um engodo para enganar o software mal-intencionado e passar por usuários desavisados.

### Worms

Esse é um tipo de malware que se replica para se espalhar de um computador para outro. Ao contrário de um vírus, que requer um programa host para ser executado, os worms podem ser executados por si próprios. Além da infecção inicial do host, eles não exigem a participação do usuário e podem se espalhar rapidamente pela rede.

Os worms compartilham padrões semelhantes: eles exploram vulnerabilidades do sistema, têm uma maneira de se propagar e contêm código mal-intencionado (payload) para causar danos a redes ou sistemas de computador.

Os worms são responsáveis por alguns dos ataques mais devastadores na Internet. Em 19 horas, o worm infectou mais de 300.000 servidores em 2001.

## Engenharia social

Engenharia social – manipulação do indivíduo para executar ações ou divulgar informações confidenciais

## DoS Distribuída

Um ataque de negação de serviço distribuída (DDoS) é semelhante a um  ataque de negação de serviço (DoS), mas é proveniente de várias fontes coordenadas. Por exemplo:

- Um invasor cria uma rede (botnet) de hosts infectados chamados zumbis, que são controlados por sistemas de tratamento.
- Os computadores zumbis examinam e infectam constantemente mais hosts, criando mais zumbis.
- Quando está pronto, o hacker instrui os sistemas controlador para fazer com que o botnet de zumbis execute um ataque de negação de serviço distribuído (DDoS).
  
- Buffers -> Os buffers são áreas de memórias alocadas a um aplicativo. Uma vulnerabilidade ocorre quando os dados são gravados além dos limites de um buffer. Ao alterar os dados além dos limites de um buffer, o aplicativo pode acessar a memória alocada para outros processos. Isso pode levar a uma falha do sistema ou  comprometimento de dados ou fornecer escalonamento de privilégios.
- Entrada não validada -> Os programas geralmente exigem entrada de dados, mas esses dados recebidos podem ter conteúdo malicioso, projetado para forçar o programa a se comportar de maneira não intencional.
Por exemplo, considere um programa que recebe uma imagem para processamento. Um usuário mal-intencionado pode criar um arquivo de imagem com dimensões de imagem inválidas. As dimensões criadas de forma mal-intencionada podem forçar o programa a alocar buffers de tamanhos incorretos e inesperados.
- Condição de corrida -> Esta vulnerabilidade descreve uma situação em que a saída de um evento depende de saídas ordenadas ou cronometradas. Uma condição de corrida se torna uma fonte de vulnerabilidade quando os eventos ordenados ou cronometrados necessários não ocorrem na ordem correta ou na sincronização apropriada.
- Fragilidade nas práticas de segurança -> Sistemas e dados confidenciais podem ser protegidos por meio de técnicas como autenticação, autorização e criptografia. Os desenvolvedores devem manter o uso de técnicas de segurança e bibliotecas que já foram criadas, testadas e verificadas e não devem tentar criar seus próprios algoritmos de segurança. É provável que elas introduzam novas vulnerabilidades.
- Problemas de controle de acesso -> O controle de acesso é o processo de controlar quem faz o quê e abrange desde o gerenciamento do acesso físico ao equipamento até ditar quem tem acesso a um recurso, como um arquivo, e o que pode ser feito com ele, como ler ou alterar o arquivo. Muitas vulnerabilidades de segurança são criadas com o uso indevido de controles de acesso.

Quase todos os controles de acesso e as práticas de segurança poderão ser superados se o invasor tiver acesso físico ao equipamento de destino. Por exemplo, não importa as configurações de permissão em um arquivo, um hacker pode ignorar o sistema operacional e ler os dados diretamente do disco. Para proteger a máquina e os dados que ela contém, o acesso físico deve ser restrito e as técnicas de criptografia devem ser usadas para proteger dados contra roubo ou danos.
