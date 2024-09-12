Requirements:
-	Ubuntu 20.04 machine with network connection
-	Odoo 14 repository is up
-	The setup script: install-20.04.sh (get it from repository at setup/ubuntu/install-20.04.sh)
-	The configuration file: odoo14.conf (get it from repository at setup/ubuntu/odoo14.conf)


How to install?
-	Put the script & configuration file to somewhere, e.g: setup/
-	cd setup/
-	sudo chmod +x install-20.04.sh
-	Run: `./install-20.04.sh <target>`

    Here: 
	    target: may be `staging` for staging environment and get from staging repo; `uat` for UAT environment and get from uat branch; `prod` for production environment and get from master repo; or nothing for odoo 14 public github repo
