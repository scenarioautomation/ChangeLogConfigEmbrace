﻿# Problemas conhecidos
### 01 - Problema ao mover\reposicionar um item dentro de um ambiente
### 02 - Falta implementação de modo teste de drivers
### 03 - Problema ao salvar arquivo de login em alguns casos especificos no MAC, sendo necessário login toda abertura do Config
### 04 - Ao remover um link de modo dormir, o projeto gráfico não é gerado novamente
### 05 - Filtro da árvore de ambientes, manter estado da árvore antes do filtro
### 06 - Adição da opção de varredura de rede\dispositivos ao abrir tela de rede
### 07 - OK - Icone de alguns itens desaparem da árvore em situações especificas 
### 08 - OK - Na tela de projeto grafico, os indices de blocos de driver de integração não são exibidos  
### 09 - OK - Remover scroll da barra horizontal de NTL(tela de informações) 
### 10 - Seta movimenta itens na árvore mas não atualiza na tela central do Config
### 11 - Algumas vezes as progressbar somem
### 12 - OK - Algumas vezes na tela de RC e Cenas as scroll bar aparecem em ambas as treeview(deveria ser 1 global) 
### 13 - Importação de driver JAVA("esquema usuario")
### 14 - Modo Teste de driver
### 15 - Função de "Teste de dispositivo"
### 16 - Ao remover e adicionar links no ativador do modo dormir não está gerando projeto gráfico
### 17 - Mostrar RLY e outros dispositivos na tela de info do Config quando se conecta na AC
### 18 - Modo teste demora para exibir os Dbs e consumo no rly2 no modo teste

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

