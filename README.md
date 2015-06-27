Command Manager Plugin for BigBrotherBot
========================================

## Description

BigBrotherBot plugin which allows admins to manage b3 commands in-game.<br />
It is capable of modifying commands level and commands aliases while without having to reboot the b3.<br/>
If specified in the plugin configuration file, it will also keep your plugins configuration files up to date (works with both **xml** and **ini** formats).<br /><br />

******
*NOTE: since B3 v1.10.1 beta this plugin has been included in the standard plugins set, thus all patches and updates will be performed in the official B3 repository.*
******

## How to install

### Installing the plugin

* Copy **cmdmanager.py** into **b3/extplugins**
* Copy **plugin_cmdmanager.ini** into **b3/extplugins/conf**
* Load the plugin in your **b3.xml** configuration file

## In-game user guide

* **!cmdlevel &lt;command&gt; [&lt;level&gt;]** - *get/set the level of a command*
* **!cmdalias &lt;command&gt; [&lt;alias&gt;]** - *get/set the alias of a command*

## Credits

The original idea of this plugin belongs to BlackMamba (https://github.com/bmamba/b3-plugin-cmdlevel).<br />
However his Command Level plugin got outdated and it's not working with the new configuration files supported by b3: because of this I decided to rewrite it from scratch.

## Support

For support regarding this very plugin you can find me on IRC on **#goreclan** @ **Quakenet**<br>
For support regarding Big Brother Bot you may ask for help on the official website: http://www.bigbrotherbot.net
