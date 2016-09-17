Comandos:
=========

X Especifica um número  
Argumentos entre ( ) são opcionais


Manager
-------

|Commando | Argumentos |  Descrição |
|:------:|:---------:|:--------------------------------------:|
|!afklimit | X | define o tempo máximo de AFK |
|!botname |  (nome do bot)  | altera o nome padrão do bot |
|!bouncer+ | | alterna o bouncer+ |
|!skippos | X | define a posição para mover pelo lockskip ao pular um DJ |
|!clearchat | |limpa todo o chat |
|!cycle | | alterna o ciclo de Djs |
|!cycletimer | X | define o tempo máximo de ciclo de DJ quando o cycleguard estiver ativado |
|!locktimer | X | define o tempo máximo que a lista de espera pode ser travada se Lockguard estiver ativado |
|!maxlength | X | especifica a duração máxima de uma música |
|!logout | | da log out na conta que estiver hospedando o bot |
|!refresh | | refresca o navegador de quem estiver carregando o bot |
|!usercmdcd | X | define o delay sobre os comandos para usuários cinzas |
|!usercommands | | ativa/desativa os comandos de usuários cinzas |
|!voteskip | (X) | especifica o limite de voteskip, quando nenhum argumento é especificado, retorna para o limite de voteskip correto|

Bouncer+
--------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!add | @user | add usuário à lista de espera |
|!afkremoval | | alterna a verificação AFK |
|!autoskip | | pula as músicas automaticamente após terminarem (usado quando circulo-bug aparece) |
|!deletechat | @user | deleta todo o chat de um determinado usuário |
|!lock | | trava a lista de espera |
|!move | @user (X) | move o usuário para posição X na lista de espera, posição padrão 1 |
|!remove | @user | remove usuário da lista de espera |
|!roulette | | inicia a roleta |
|!songstats | | alterna as estatísticas de músicas  |
|!unlock | | destrava a lista de espera |
|!welcome | | alterna a mensagem de boas vindas |

Bouncer
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default |
|!afkreset | @user | resets the afk time of user |
|!afktime | @user | shows how long user has been afk |
|!autodisable | | toggle the autodisable |
|!ban | @user | bans user for 1 day |
|!blacklist / !bl | blacklistname | add the song to the specified blacklist |
|!commanddeletion | | toggles if bot commands gets deleted |
|!blinfo | | get information required to blacklist a song |
|!cycleguard | | toggles the cycleguard |
|!dclookup / !dc | (@user) | do dclookup for user |
|!english | @user | ask user to speak english (asked in the language they set plug to) |
|!eta | (@user) | shows when user will reach the booth |
|!filter | | toggles the chat filter |
|!forceskip | | forceskips the current song |
|!historyskip | | toggles the history skip |
|!jointime | @user | shows how long the user has been in the room |
|!kick | (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds) |
|!kill | | shut down the bot |
|!lockguard | | toggle the lockguard |
|!lockskip | (reason) | skips, locks and moves the dj back up (the position can be set with !skippos) |
|!motd | (X)/(message) | when no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message |
|!mute | @user/(X) | mute user, for X minutes if X is specified, otherwise for an undefined period |
|!reload | | reload the bot |
|!restricteta | | toggles the restriction on eta: grey users can use it once an hour |
|!sessionstats | | display stats for the current session |
|!skip | (reason) | skips the dj using smartskip. actions such as locking and moving user depends on various factors (the position the dj is moved to can be set with !skippos) |
|!status | | display the bot's status and some settings |
|!timeguard | | toggle the timeguard |
|!togglebl | | toggle the blacklist |
|!togglemotd | | toggle the motd |
|!togglevoteskip | | toggle the voteskip |
|!unban | @user | unban user |
|!unmute | @user/all | unmute user |
|!voteratio | @user | display the vote statistic for a user |
|!whois | @user | returns plug related information about user |

Resident DJ
-----------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!link | | give a link to the current song



User
----

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!8ball | (message) | ask the bot a question, the bot will return random variations of a yes or no answer. |
|!autowoot | | links to PlugCubed, the advised script/plugin to use for autowooting |
|!ba | | explains the Brand Ambassador rank |
|!commands | | gives a link to the commands |
|!cookie | (@user) | give a cookie to user |
|!dclookup / !dc | | use dclookup on yourself |
|!emoji | | a link to a list with emoji's |
|!eta | | shows how long before you reach the booth |
|!fb | | links to the room's Facebook page (if set in the settings) |
|!ghostbuster | @user | checks if user is ghosting |
|!gif | (message) | returns gif (from giphy) related to the tag provided. Returns a random gif if no tags are provided. |
|!help | | links to an image to help get people started on plug |
|~~!join~~ | | ~~join the roulette if it's up~~ |
|~~!leave~~ | | ~~leave the roulette if you joined~~ |
|!link | | when the user is the DJ, give a link to the current song |
|!op | | links to the OverPlayed list (if set in the settings) |
|!ping | | pong! |
|!purchase | | returns link to purchase more plug notes |
|!rules | | links to the rules (if set in the settings) |
|!theme | | links to the room's theme (if set in the settings) |
|!thor | | users get moved to position 1 in the waitlist if they're worthy of Thor's hammer. |
|!website | | links to the room's website (if set in the settings) |
|!youtube | | links to the room's youtube page (if set in the settings) |
