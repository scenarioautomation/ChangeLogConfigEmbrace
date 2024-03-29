﻿# Config 2.0.0 (126) - 26/04/2023
## Features:
### - Opção de salvar preferências de Room Control
### - Adiciona Feedback de exibição nos campos de conexões
### - Exibição do caminho do projeto na barra de status
### - Adiciona confirmação ao apagar projeto da controladora

## Correções:
### - Corrige valores padrão nas preferências de Room Control
### - Corrige movimentação indesejada da árvore do projeto ao renomear dispositivos
### - Corrige nome do EB-KP6M-4R Wifi nos equipamentos

# Config 2.0.0 (125) - 25/04/2023
## Features:
### - Opção de importação de temas do editor gráfico (apenas em Windows)
### - Adiciona opção de pesquisa na tela de seleção de equipamentos

## Correções:
### - Corrige exibição de dispositivos de rede desatualizados no projeto 

# Config 2.0.0 (123) - 20/04/2023
## Features:
### - Exibição do caminho do dispositivo nas telas de configuração
### - Melhoria no campo de instruções de drivers
### - Verificação de IP existente no projeto ao alterar IP de dispositivos

## Correções:
### - Finaliza modo teste corretamente ao alternar dispositivos
### - Melhorias no carregamento de tela( Na verdade é: Corrige aberturas indesejadas de telas ao expandir itens da árvore do projeto, colocaria apenas antes do )
### - Correção na permissão de ambientes na geração de projeto gráfico com ambientes que possuem apenas Atividades

# Config 2.0.0 (121) - 17/04/2023
## Correções:
### - Otimização e correções na tela de rede
### - Ajustes de telas para MacOS

# Config 2.0.0 Build (118) - 10/04/2023
## Features:
### - Implementa importação de alterações do Constant Light Control (CLC) no envio de projeto

## Correções:
### - Corrige atualização de drivers integração

# Config 2.0.0 (120) - 12/04/2023
## Correções:
### - Otimização no carregamento de telas
### - Corrige substituição de dispositivos nas atividades AV
### - Melhorias na atualização de firmware para controladora

# Config 2.0.0 Build (117) - 10/04/2023
## Correções:
### - Corrige atualização da árvore de rede ao carregar projeto
### - Corrige ordem dos canais da MPL4 no modo teste
### - Corrige limpeza de links e remoção de sensores sem teclas
### - Corrige situações em que os dados de login removiam caracteres especiais
### - Corrige tratamento de caminho da pasta padrão de firmwares

# Config 2.0.0 Build (116) - 30/03/2023
## Features:
### - Opção de Cortina Somfy RF com funcionamento a bateria

## Correções:
### - Ajustes gerais em telas de informação e configuração
### - Exibe todas interfaces e projetos gráficos nas informações de controladora
### - Corrige otimização de rede durante envio de projeto

# Config 2.0.0 Build (114) - 27/03/2023
## Correções:
### - Corrige importação de alterações de projetos gráficos com acentuação no nome
### - Corrige importação de alterações de projetos gráficos que foram renomeados

# Config 2.0.0 Build (113) - 27/03/2023
## Features:
### - Adiciona variáveis macro na árvore do projeto na tela de macros

## Correções:
### - Corrige fechamento de telas de configuração de blocos quando o dispositivo é removido do projeto
### - Corrige importação de templates
### - Corrige geração do nome de atividades no E-App relacionados ao CAT de Ar Condicionado
### - Mantém dados de login de aplicativos importados da E-App
### - Corrige salvamento de credenciais de login no Linux
### - Corrige execução do reboot ao atualizar

# Config 2.0.0 Build (107) - 21/03/2023
## Features:
### - Backup de projetos Legado na pasta ProjetosV1
### - Exibição de dispositivos de Rede e Zigbee offline
### - Nova tela do launcher do Config

## Correções:
### - Corrige permissões no Windows para listagem de controladoras
### - Corrige opções de alterar IP, envio de firmware e identificação de dispositivos offline
### - Corrige atualização da árvore de rede ao carregar novo projeto
### - Corrige exibição de nome de variável Input na tela de Atividades
### - Corrige atualização de telas de configuração ao duplicar teclados
### - Corrige atualização de telas de configuração ao deletar dispositivos com teclas, botões, sensores ou blocos
### - Corrige carregamento de blocos de drivers integração

# Config 2.0.0 Build (106) - 16/03/2023
## Features:
### - Imagens KPView dos teclados do tipo KPUL-MOV
### - Atualiza cor do teclado na tela de KPView dinamicamente ao mudar na tela de configuração
### - Edição do nome de variáveis de tipo Input

## Correções:
### - Corrige instabilidade no teste de comandos RF433
### - Corrige carregamento de KPULs
### - Corrige salvamento de conexões de Entradas e teclas
### - Corrige carregamento de links de ambiente
### - Ajusta valores padrão do Módulo Harvesting
### - Corrige geração de Inteligencia Embrace para Ar condicionado e Iluminação
### - Corrige renomeação do projeto apagar as imagens de projetos gráficos de usuário
### - Corrige atualização dos dados de rede ao realizar varredura
### - Corrige exibição de Dispositivos Guia TV
### - Corrige copia do offset de temperatura na duplicação de sensores
### - Corrige foco no campo de nome ao abrir tela de atividades áudio e vídeo
### - Muda controle de aplicativos externos para combo box filtrável
### - Ordena aplicativos externos por ordem alfabética
### - Corrige caracteres especiais na geração do KPView
### - Corrige volume fixo de drivers integração afetarem projeto gráfico
### - Corrige tratamento de campos de edição de comandos IR

# Config 2.0.0 Build (104) - 10/03/2023
## Correções:
### - Corrige carregamento de cidades
### - Corrige ordenação da Pasta Atividades Globais na árvore do projeto
### - Corrige tipo de conexão salva no Sensor de Movimento
### - Corrige verificação de sensores na geração do cat de Iluminação
### - Corrige atributo de GuiaTV em Projeto gráfico Custom
### - Corrige salvamento da macro de Guia TV dos dispositivos
### - Corrige comandos de assistente virtual para atividades Globais e cortinas
### - Corrige substituição de blocos de drivers integração
### - Corrige nome de dispositivos de rede vinculados ao projeto no teste das funções de Driver
### - Corrige acionamento dos leds do modo teste da EB-MPL4-4R
### - Corrige verificação de mensagem de driver editado
### - Corrige conversão de funções em String para Hexadecimal
### - Corrige remoção da pasta atividades da árvore do projeto quando ela está vazia
### - Corrige exibição do nome de blocos de drivers integração no projeto gráfico
### - Corrige exibição de NTL em estado Bootloader após envio de firmware
### - Corrige comparação de modelo de dispositivo (Impedia o envio de firmware para alguns itens wifi)
### - Corrige fechamento da tela de carregamento ao abrir tela de login
### - Corrige identificação de dispositivos do mesmo tipo
### - Corrige limites de valores para comandos condicionais nos links de Dia, Hora, Minuto e Segundo
### - Corrige ligação de AC-Kpul-Mov na IPM36
### - Corrige mudança de cenas exibirem um botão vazio nos controles da Fita Led no projeto gráfico
### - Corrige salvamento de conexões de teclas e sensores de KPUL
### - Corrige carregamento de AC-KPUL

# Config 2.0.0 Build (103) - 06/03/2023
## Features: 
### - Protótipo da tela de abertura do Config
### - Permite seleção de comandos condicionais com Dia da semana por Combobox
### - Permite seleção de comandos condicionais com Mês por Combobox
### - Teste de dispositivo de rede
### - Habilita seleção de Localização personalizada na tela de informações
### - Habilita seleção de todos os dispositivos do projeto na árvore de Desliga Geral
### - Opção de sensibilidade nos Sensores SMT

## Correções:
### - Corrige carregamento de blocos integração na geração e edição de atividades áudio/vídeo
### - Corrige analógicos links do módulo dia noite que se comportam apenas como saída (dia, mês, hora, etc.)
### - Corrige geração de Guia TV em ambientes com atividades que chamam dispositivos GuiaTV de outros ambientes
### - Corrige ordenação de dispositivos de atividades em ambientes na App
### - Corrige salvamento das Observações do Projeto
### - Corrige salvamento das Auxiliares dos módulos
### - Corrige salvamento do interlock dos reles dos módulos RLY2 e RLY2DC Wifi
### - Corrige exibição de mensagens de erro no envio de projeto

# Config 2.0.0 Build (102) - 24/02/2023
## Features:
### - Modo teste de drivers IR, IP e Serial
### - Modo teste da MPL4-4R

## Correções:
### - Corrige falha de carregamento de projetos custom
### - Corrige exibição das etapas de envio de projeto
### - Corrige exibição de componentes da tela de atividades AV
### - Corrige atualização de itens Power/Input de drivers integração na geração de atividades AV
### - Corrige recortar comandos de macro
### - Corrige campos de edição de conexões dos drivers
### - Corrige fechamento da tela de driver ao alternar entre as abas do Config
### - Corrige carregamento de cortinas sem link de cortina fechada
### - Corrige salvamento dos atributos de BaudRate, tempo de desconexão e bits de dados dos drivers
### - Corrige geração de projeto gráfico com links dos botões de Keypad E-App
### - Corrige salvamento de saídas seriais de IRS

# Config 2.0.0 Build (101) - 17/02/2023
## Correções:
### - Corrige comparação de data no envio de projeto gráfico.
### - Corrige carregamento de projeto gráfico com nome vinculado ao projeto.
### - Otimiza extração de zip do projeto gráfico.
### - Corrige alteração de projeto após salvamento durante envio.

# Config 2.0.0 Build (99) - 16/02/2023
## Correções:
### - Corrige geração de projeto gráfico com a mudança de atributos dos itens do projeto. Agora caso um item seja alterado, ele só afeta aos projetos em que ele está inserido
### - Substituição de drivers RF copiam o respectivo HUB e frequência do driver substituído
### - Suporte a versão 2 de atividades AV para drivers de integração
### - Remove senha dos projetos enviados para AC
### - Corrige títulos e textos dos relatórios do Config

# Config 2.0.0 Build (98) - 16/02/2023
## Feature:
### - Implementa copiar dados da controladora pelo atalho CTRL+C
### - Implementa verificação de nome de projeto vazio, evitando assim problemas na AC

## Correções:
### - Corrige falha no envio de projeto gráfico devido ao salvamento do projeto durante o envio. O problema ocorria com projetos gráficos Custom
### - Corrige exibição do nome dos itens de rede na árvore de dispositivos
### -  Corrige unidade de frequência de comandos IR de MHz para KHz
### - Corrige icones desaparecendo das árvores com checkbox
### - Corrige validação de textos nos condicionais de comandos com links Data/Hora
### - Corrige remoção de ambientes e pastas com blocos deslocados

# Config 2.0.0 Build(97) - 14/02/2023
## Correções:
### - (10) Seta movimenta itens na árvore mas não atualiza na tela central do Config
### - Corrige seleção de logs na controladora nas Preferências de Projeto
### - Corrige tamanho e exibição dos ícones na árvore de canais DVR
### - (04) Corrige geração de projeto gráfico a partir do link de Ativador Modo Dormir de Room Control
### - Corrige exibição de dispositivos Integração no projeto gráfico. Em algumas situações drivers que não deveriam aparecer eram exibidos
### - Corrige alteração de IP na tela de rede

# Config 2.0.0 Build(96) - 14/02/2023
## Correções:
### - Corrige geração de CAT de Ar Condicionado
### - Corrige comandos exibidos vazios na tela de configuração de Macros
### - Corrige carregamento da árvore de projeto na tela de Macros
### - (09) Corrige scroll horizontal na lista de NTLs da Controladora
### - (07) Corrige exibição de ícones desaparecendo das árvores
### - (08) Na tela de projeto grafico, os indices de blocos de driver de integração não são exibidos
### - (12) Corrige barras de rolagem horizontais nas telas de configuração

# Config 2.0.0 Build(95) - 13/02/2023
## Correções:
### - Corrige o salvamento de blocos deslocados
### - Corrige a atualização de dados da controladora exibidos na tela
### - Corrige problemas na edição/renomear itens do projeto pela tecla TAB
### - Permite renomear cenas de Room Control pela tecla F2
### - Corrige envio de projeto com cortina associada ao RLY2-Wifi

# Config 2.0.0 Build(93) - 10/02/2023
## Correções:
### - Melhora o tratamento de desconexão e reconexão da AC com Config
### - Adiciona aviso de NTL com mais de 80 dispositivos no envio de projeto
### - Melhora busca de IP na rede antes da alteração de IP de Controladora e Dispositivos

# Config 2.0.0 Build(92) - 09/02/2023
## Feature:
### - Proteção no tamanho de nome de projetos do Config 

## Correções:
### - Corrige lentidão ao carregar árvore de rede com muitos itens
### - Corrige exibição de pasta de DVR do na listagem de atividades
### - Corrige movimentação de itens na árvore utilizando o MAC

# Config 2.0.0 Build(90) - 09/02/2023
## Correções:
### - Melhoria nas cores de seleção de itens na treeview 
### - Força validação de campos de cliente no inicio do projeto
### - Corrige exibição e atualização de comandos de drivers IP e Serial quando o usuário altera o formato de exibição
### - Corrige auto rolagem ao adicionar itens no projeto

# Config 2.0.0 Build(89) - 09/02/2023
## Correções:
### - Adiciona compatibilidade de links do módulo dia/noite para projetos do Config V2 antigos
### - Corrige renomeação de item do projeto com a tecla de atalho 'F2'
### - Corrige comportamento dos controles de edição de macro 
### - Corrige modo de programação de Fita Led no projeto gráfico automático
### - Corrige otimização de rede em projetos legado com alterações no Config V2
### - Corrige carregamento de links de dispositivos integração para realização de par

# Config 2.0.0 Build(88) - 07/02/2023
## Correções:
### - Corrige edição de comandos de macro ao adicionar comandos repetidos  de hora e data

# Config 2.0.0 Build(87) - 07/02/2023
## Feature:
### - Implementa configuração de saída no modo teste da EB-MPL4-4R

## Correções:
### - Correção na ordenação de blocos no projeto gráfico

# Config 2.0.0 Build(84) - 07/02/2023
## Feature:
### - Implementa links de data e hora no módulo dia/noite
### - Implementa tratamento de condicionais de data e hora nos comandos de macro
### - Implementa valores em porcentagem e hexadecimal nos comandos de macro

## Correções:
### - Corrige atualização de atividades ao substituir dispositivos com números diferentes de blocos e funções padrões diferentes
### - Corrige validação ao editar comandos de drivers IR, em alguns casos de comandos pequenos podia gerar mais de 1 mensagem de alerta
### - Corrige tratamento de template de drivers antigos. Anteriormente existia apenas 1 template para drivers, hoje existe 1 para cada conexão.

# Config 2.0.0 Build(80) - 03/02/2023
## Correções:
### - Corrige seleção de função padrão na edição de drivers
### - Corrige texto de entrada auxiliar de módulo
### - Corrige carregamento de Fechadura

# Config 2.0.0 Build(78) - 01/02/2023
## Correções:
### - Corrige variáveis e links complementares de dispositivos bidirecionais
### - Corrige exibição de avisos de envio de projeto
### - Corrige nome da cena Dormir com Movimento
### - Corrige alinhamento e exibição dos controles da tela de cortina
### - Corrige exibição de erros ao salvar projeto gráfico custom
### - Corrige exibição de erros na importação de projetos gráficos custom

# Config 2.0.0 Build(76) - 31/01/2023
## Correções:
### - Corrige salvamento dos conectores de dispositivos Wifi
### - Corrige estrutura de ambientes para permissões de usuário na App
### - Corrige alteração de projeto gráfico ao alterar ambientes

# Config 2.0.0 Build(75) - 30/01/2023
## Correções:
### - Corrige confirmação de envio de projeto
### - Corrige validação para otimização de rede no envio de projeto
### - Corrige criação de componentes do projeto gráfico referente aos canais DVR

# Config 2.0.0 Build(74) - 30/01/2023
## Correções:
### - Corrige importação de alteração de eventos
### - Corrige importação de alteração de imagem do projeto gráfico

# Config 2.0.0 Build(73) - 27/01/2023
## Correções:
### - Corrige sobrescrever driver criado/editado
### - Corrige exportação e mensagens de erro após exportação
### - Corrige atualização de título da janela e texto de instalação da barra de status
### - Corrige leitura dos templates ao carregar projeto
### - Corrige criação de componentes do projeto gráfico
### - Corrige filtragem de dispositivos pelo número de série
### - Corrige salvamento de atributos do projeto
### - Corrige ordenação de blocos deslocados na tela de atividades AV
### - Corrige tamanho das colunas do Modo Zigbee
### - Corrige ordenamento de ambientes na geração de projeto

# Config 2.0.0 build(72) - 26/01/2023
## Correções:
### - Corrige atualização de funções padrão ao carregar drivers de novo projeto
### - Corrige atualização de atividades ao substituir macros com lista de blocos diferentes
### - Corrige deleção de comandos de atividades ao substituir drivers
### - Remove desvinculação de Rede de Itens de Rede ao realizar varredura e não encontra-los
### - Corrige alteração de projeto ao adicionar ambientes
### - Corrige alteração de projeto gráfico ao adicionar objetos em pastas

# Config 2.0.0 build(71) - 26/01/2023
## Correções:
### - Corrige seleção dos botões na árvore de drivers em equipamentos
### - Corrige substituição do arquivo de drivers no projeto
### - Corrige atualização de atividades ao substituir drivers

# Config 2.0.0 Build(70) - 25/01/2023
## Correções:
### - Corrige objetos dentro de pastas na geração do projeto gráfico
### - Corrige nome do EB-SDM2-LED-WIFI na tela de rede
### - Corrige gravação de nome de revenda
### - Corrige geração de templates para drivers genéricos
### - Corrige adição de dispositivos fonte de atividades no projeto gráfico
### - Corrige alteração de projeto ao alterar funções RF
### - Corrige dispositivos repetidos no projeto gráfico
### - Corrige acionamento de atividades AV no projeto gráfico

# Config 2.0.0 Build(69) - 25/01/2023
## Feature:
### - Implementa tratamento para templates de drivers integração

## Correções:
### - Corrige associação de itens v2 depois de carregar
### - Corrige criação de componentes AV no projeto gráfico

# Config 2.0.0 Build(67) - 24/01/2023
## Correções:
### - Corrige exibição do botão de atividor modo dormir quando possuir link
### - Corrige adição, remoção e substituição de drivers do projeto
### - Corrige links de Hold e Release com funcionamento invertido

# Config 2.0.0 Build(66) - 24/01/2023
## Features:
### - Implementa opção de deletar comando de macro pela tecla DELETE
### - Movimentação de comandos para macro realizado pelos botões de Subir/Descer

## Correções:
### - Corrige abertura da tela de configuração ao expandir ou contrair itens da árvore do projeto
### - Corrige macros exibindo mais de uma atividade na árvore
### - Corrige seleção dos campos ao editar comandos da macro
### - Corrige árvore de macro sendo removida ao recarregar a tela de configuração
### - Corrige corte a opção "Domingo" na tela de configuração de Evento
### - Corrige nome exibido ao editar teclas e botões com KPView personalizado
### - Corrige atualização de projetos e projetos gráficos ao mover blocos
### - Corrige criação do comando de macro em modo de edição
### - Altera a opção informativa de tensão DC (12V ou 24V) para a MPL4-4R
### - Corrige criação de novos dispositivos no projeto em modo de edição
### - Corrige criação de novas funções de Driver em modo de edição
### - Corrige criação de novas funções RF em modo de edição
### - Corrige comportamento de edição de cenas de Room Control
### - Corrige exibição de canais DVR deslocados do ambiente original
### - Corrige erros ao adicionar múltiplos itens
### - Corrige ocasióes raras onde alguns a árvore do projeto selecionava itens aleatórios após outro item ser renomeado
### - Corrige exibição de cenas de madrugada na tela de Cenas de Room Control
### - Corrige edição de atividades AV apagando os outros comandos da atividade
### - Corrige cortes em campos das telas de Teclados e Sensores
### - Corrige para não adicionar atividade renomeando
### - Corrige duplicação de atividades para manter comandos e a respectiva ordem
### - Corrige ocasiões em que era possível adicionar comandos dentro do comando "Atividade Audio e Vídeo" 
### - Corrige problema com importação de projeto com redes com IP alterado
### - Corrige carregamento de redes Offline na tela de varredura
### - Corrige Salvamento de projeto após enviar para a controladora
### - Corrige opção de reiniciar iluminação após envio
### - Corrige vínculos de rede que eram refeitos sem necessidade

# Config 2.0.0 Build(65) - 19/01/2023
## Correções:
### - Circuito de luminárias na árvore do projeto
### - Corrige atualização de informações da controlador ao conectar manualmente
### - Cria botão do ativador modo dormir no projeto gráfico
### - Corrige acentuação de nome "Instalação"
### - Remove possibilidade de criar pasta Atividades manualmente
### - Corrige caminho de salvamento de projeto após importação
### - Reseta os icones na tela de rede após uma nova varredura
### - Corrige duplicação de atividade AV
### - Corrige exibição de auxiliares de módulos após salvar e carregar projeto
### - Corrige conexões padrão para dispositivos que vinculam na IPM10
### - Corrige exibição do nome do HUB
### - Corrige movimentação de pasta entre ambientes diferentes 

# Config 2.0.0 Build(62)  Release Candidate- 17/01/2023
## Correções:
### - Ordenação da árvore de rede na tela de varredura

# Config 2.0.0 Build(61)  Release Candidate- 17/01/2023
## Correções:
### - Alterada a exibição de mensagem de atualização do sistema
### - Alterada forma do change log


# Config 2.0.0 Build(59)  Release Candidate- 17/01/2023
## Correções:
### - Corrige movimentação dos blocos na árvore do projeto
### - Corrige geração de comandos IR Classic na atualização de drivers
### - Corrige edição de funções na tela de drivers
### - Corrige tratamento de imagens dos ambientes do projeto gráfico
### - Remove campos de programação de macros por blocos
### - Correção no scroll de instruções de uso do "Instrução de uso" de driver em alguns casos com várias linhas de instrução
### - Atualização da barra de titulo do Config com nome\caminho do projeto aberto

