# Afraid-Update-MEO

Este script tem como função actualizar os registos de DNS no
freedns.afraid.org, para os utilizadores MEO e que utilizem o
router Technicolor TG784n v3, que por alguma razão precisem
aceder um sistema em sua casa.

# Description

Este script tem como função actualizar os registos de DNS no
freedns.afraid.org, para os utilizadores MEO e que utilizem o
router Technicolor TG784n v3, que por alguma razão precisem
aceder um sistema em sua casa.

É necessário que tenham acesso ao vosso router através de telnet,
para que seja possível ao script obter o IP actual do router e
compara-lo com o IP no afraid.org.

Caso tenham dificuldade em aceder o vosso router vejam este
artigo: https://www.ncdc.pt/2014/11/07/como-ter-acesso-total-ao-router-technicolor-tg784n-v3-da-meo/

# Installation

The manual installation of the script can be made as follows:

 # cp afraid-update-meo /usr/bin

 # chmod 750 afraid-update-meo

Create a cron job:

 # echo '*/5 * * * * /usr/bin/afraid-update-meo' > /etc/cron.d/afraid-update-meo

# License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

