# DBforBIX

# Project is not supported anymore and was moved to 
# https://github.com/vagabondan/node-db4bix


DBforBix is the DB monitoring tool for Zabbix. It works like an active Zabbix Proxy by getting configuration from Zabbix Server and sending results back.
Just copy dist https://github.com/smartmarmot/DBforBIX/tree/master/dist/ to your server, edit configuration and run<br>

See Wiki for DBforBix as Zabbix Proxy configuration instructions: https://github.com/smartmarmot/DBforBIX/wiki<br>

DBforBIX is licensed under the GNU General Public License  V.3. <br>
You can obtain a full copy of the licese here: https://www.gnu.org/licenses/gpl-3.0.txt <br>

The project's documentation is available here: http://www.smartmarmot.com/wiki/index.php?title=DBforBIX2 <br>

# Github directory structure
The github repository is organized as follow:
* dists: contains the packages ready to be used
* items: contains all the itemfiles developed (also included in the distribution package)
* template: contains all the templeates developed (also included in the distribution package)
* conf: contains a sample configuration (also included in the distribution package)
* src: contains all the source code


## Notes about the the structure
In the dists directory you find the source code package that has generated a specific distribution. In this way you have all the code who generated a distribution.
The template and items are available within the distributions files but also in a separate location to make it easy to pull change requests as well as the src and conf.

## Object Model
Constructed with ![ObjectAid](http://www.objectaid.com/) (Eclipse plug-in)
![Object Model current diagram](https://github.com/vagabondan/DBforBIX/blob/master/src/ObjectModel.png)
![Object Model source](https://github.com/vagabondan/DBforBIX/blob/master/src/ObjectModel.ucls)
