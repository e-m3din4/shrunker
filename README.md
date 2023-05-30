# Shrunker
## URL Shortener CLI

This is a command-line interface (CLI) tool for interacting with shrtco.de API. It allows you to shorten URLs and retrieve information about shortened links.

### Prerequisites

- Python 3.x
- requests library 

### Usage

1. Clone or download this repository to your local machine.

2. Install the required dependencies:

	`pip3 install requests`

3. Open a terminal or command prompt and navigate to the project directory.

4. Run the script using the following commands:

python3 Shrunker.py --help     

     ██████████████████████████  ▀██████████████████████████████████████████████████      
     ██████████████████████████ ║ ▀█████████████████████████████████████████████████      
     ██████████████████████████ ▓▓ ▀████████  ,█████████████████████████████████████      
     ██████████████████████████ ▓▐▓ ▀█████▀ ▓ ▐█████████████████████████████████████      
     ██████████████████████████ ╟ ▓▓ ████ ┌▓▓ ██████████████████████████████████████      
     ██████████████████   ▀████ I▓ ▓æ ██ J╣Ñ ▐██████████████████████████████████████      
     ███████████████████ ╙▓─  █ └▓ ▓▓ ▐ /╜eΓ ███████████████████████████████████████      
     ████████████████████  ▓▓▓,  ▓▓ ÑÆ ,H Ñ ████████████████████████████████████████      
     █████████████████████▄ + ▓▓┐ D fφ ╫┌╫ ▄████████████████████████████████████████      
     ███████████████████████  ┐ ▓@ ∞ ╫  ▒  █████████████████████████████████████████      
     ████████████████████████▄ ╙╖ ╣  [ J    > ~   ▀█████████████████████████████████      
     ██████████████████▀▀ `  ╓╓⌐┐  └     `     ¼▒▒┐  ▀██████████████████████████████      
     ██████████████▀ .;[@╫╢╢.∞▒▒▒.⌐┐ ∩∩  ░`     ╞░░▒H  █████████████████████████████      
     ████████████ ┌▓╫╫╫Ö╝╫@╫╢ ª~,░ `░ª░▒ ░░░ ▒   u░æ░▒ ▐████████████████████████████      
     ████████████ ├╢╣╢╢@╢╫╫╫╫╫.▒░░░ ▒░░░░ `░,░,   ▒▒└`▄ ▀███████████████████████████      
     ████████████▌ ╫╢╫╢@@╫╫╫╫╢╫ ░░ ▒░`░   ░   ▒░   -███▌ ███████████████████████████      
     █████████████ ▓╫╫╫╫`▄▄▄▄▄▄▄  ╜░░▒.,     ░  `-██  █Γ▐███████████████████████████      
     █████████████ └╫╫╫╢ ██████████▄ ─  . . `   ██████▀ ████████████████████████████      
     ██████████████ ╢╣╫Ñ ▀█████ ▄▐████    `    █████▀   ████████████████████████████      
     ██████████████ \╗Ö╙▒ ▀████████████ ∩ ²ª ∩      ⁿº ▐████████████▀  ,  ` ▀▀██████      
     ███████████████ Ñ▒@╜╢1┌Z▀▀███▀▀▀      ▄  ∩╖  ` ╫@ ▐███████████ ┌╢ÑÑD¡,▓ &  ████      
     ███████████████▄`▒&╫╢░▒╫╝*=```┌¬ ∩  ∩▐██       jM ⁿ██████████┘,@╫M    ,    ████      
     ████████████████ \▒╫▒▒¥▒╖  ∩ ⌐ >∩.~~ ⁿⁿ∩░░,     ╚  ▄█████████ ╢╫╝ ╚ %┐║ ╫ ,▐███      
     █████████████████ ½▒║@║╥╣Ñ▒░≥          ∞╝`   ▄▄█▌ ██████████ J▀Ñ ╚╚= µ╞┐╟╡[ ███      
     ██████████████████ ╜╢▓╫╢╫╫@▒j ▒ º` `-▄▄████Γ▄▀██ ▐█████████▀.▀▒╫ ▒  ¥H⌡╡[▓└L▐██      
     ███████████████████ ╢╢▒░╙ª,`√▄▄████ ▌ª█████ █▄▀█ ▐████████▀ b░%╫ ▒  ╠&└▓[╢ ▓ ██      
     ████████████████████ ╚å▒┐▐█▌▄▀█████ ██▄▀██▌▐██▄▀ ████████▀.╢╫╫ÑM ▒`╡╞N┌▒└▒ ╫ ██      
         █████████████████ º@æ ██▐█▄████▐████ª█ ████  ██████  +Ñ▒Ñ╬╝  ▒ æ╒╝ ╚ ░ ▒ ▐█      
     ▄ ▓.\█████████████████  ▓▓ █ ███▄▀█▐█████  █████.█████ ╓▒░░░▒    ╝   ⌂ ╖╓  ª  █      
     █▌ █ ▐██████████████▀ ,-,└▓ ╛█████  ▀` ╖|  █ ▒▒  ▓▓ -≥▒Ñ░░▒╜ ,▌- ,║░an╫▓╣▒▒ß╖∩█      
     ███ █ ▀████████████▀ - ▐▓▌.╚▓╖╓╓╖[`▒▒░▒▒α ▒▒▒░  ▒▒╫╢─º ▄K² ┌██   ╙╢╝,▄▄╫Ñ╫`▄┐t█      
     ████ ▓ ██████████ -▓ τ▓█▓▓█▌ └╣║╫%L╘░▒▒ª▒▒░░⌐ ▓▀▒▒▒╖   -▄█████   Lⁿu▀╨▀▓ ╚ ▀Ö █      
     █████ ▌ ███████ -▓▓l▓² ▄▓██▓▓▓ `¥╫╫ ▒░▒▒∩▒  ┌╫▒▒▒▒▄▒▌ █████████ ª╙e╖▄▒U▒∞=▀ÑÑ,█      
     ██████ L █████ ▄▓▓▓▀      ▓▓▓██▓▓▄ ╛ª▒░▒╝  ▓▒╫Ñ▒▒▄▓▒▓ ███████████ └╖²Ñ└ ∞─² }╢█      
     ██████▌  ▐███ ▓▓▀M ▄████▌ ▓▓▓▓▓███▓█▄   ▄██▓╫▄▓█╫▀Ñ▓▒ ████████████ ; ╒>-╓ √** █      
     ███████▄  ▀█ ▓▓Ñ ,██████ ▐▓▓▓╫▄█████▓▓▓▒╫▓▀▄╫▀▀╫▌▒4▀▓ ▐███████████ Ñ▓└┘¿└   τ██      
     ████████▄   4▓▓  ███████ ▐▓▓▓▓╫▓▓▓▓╫▓▒▀╫▓██▓╣▒▒▒▒ÑÑ▒▒╕ ███████████. ª%╖`ºh  ███      
     █████████   ▀▓▌ ████████ ╠▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▒▒╣Æ▒▓▒▒╫▌▀▒▀ ████████████▌`   ▄▄█████      
     ████████▌ ▄τ@  , ███████ ║▓▓▓▓▓▓▓▓▓▌▓╫▓@╫▀╫▓&╣▒╫▀▓▓▄▒▄ ▀████████████  █████████      
     █████████ ,  ┌ º ███████ ╟▓▓▓▓@▓▓▓▓▓▓▓▓Ñ╫@▒╫▓▀▓╫M▒  ╫▒ ▐███████████████████████      
     ██████████   2√  ███████ ╟█▀▀▓╫▓▓▓▓╫▓╫▓▓▓▓▓▒@▄╫╝▒▄ ▄  ╡ ███████████████████████      
     ████████████┐ =  ███████ [╫▓  ▓▄▓▓▓▓▓▓▀▀╫▓▀▓▒▀▒▒╫┘, █,  ███████████████████████      
     ██████████████   ███████L└▓┘  \▓▓▀ ▀  ╜Ñ▀╜ ▄  ╝Ñ╝┌▒. █▄  ██████████████████████      
     ███████████████ .`██████▌   █ ,▐▀ , ██▄   ████▄  ╟M╫ ▐█████████████████████████      
     ████████████████ ┐ ██████▄▄██ ╫.Æ ██████████████▌ ▌▒▄ █████████████████████████      
     ████████████████▌ , █████████ ▄▓@ ███████████████ ª▒Ü ▐▀███████████████████████      
     █████████████████▄   █▀███  . º╫╫ ███████████████▌ ╫▄ea@  █████████████████████      
     ██████████████████▄`L   █, ⁿ╙*¬º  ▐███████████████  ---──▄█████████████████████      
     ███████████████████▄ L ┐ ██████████████████████████████████████████████████████      
     ███████████████████▀  . - █████████████████████████████████████████████████████      
     ██████████████████   ⁿ÷   █████████████████████████████████████████████████████      
     ██████████████████████▄   █████████████████████████████████████████████████████      
     ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀²  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀      
              ____    _   _   ____    _   _   _   _   _  __  _____   ____                 
             / ___|  | | | | |  _ \  | | | | | \ | | | |/ / | ____| |  _ \                
             \___ \  | |_| | | |_) | | | | | |  \| | |   /  |  _|   | |_) |               
              ___) | |  _  | |  _ <  | |_| | | |\  | | . \  | |___  |  _ <                
             |____/  |_| |_| |_| \_\  \___/  |_| \_| |_|\_\ |_____| |_| \_\               
                                                           p o w e r e d by               
                                                                          shrtco.de       
     ████████████████████████████████████████████████████████████████████████████████     
     ████████████████████████████████████████████████████████████████████████████████     
     ████████████████████████████████████████████████████████████████████████████████     

     usage: Shrunker.py [-h] {shorten,info} ...

     URL shortener CLI

     options:
        -h, --help      show this help message and exit

     Commands:
       {shorten,info}
         shorten       Shorten a URL
         info          Get information about a shortened URL


- To shorten a URL:
  
  `python3 Shrunker.py shorten --url <URL>`
  

- To get information about a shortened link:
  
  `python3 Shrunker.py info --code <CODE>`
  

Replace `<URL>` with the URL you want to shorten and `<CODE>` with the code of the shortened link you want to retrieve information about.

5. The script will communicate with the shrtcode API and display the relevant information or error message based on the response.
