# reputation-db-scripts-for-phish-analysis

Scripts to jumpstart reputation database for phishing-analysis (https://github.com/initconf/phish-analysis)

Configure your variables in 
(1) for http, smtp, smturl reputation run: 
	- configure: config_log_replay.py 
	- run: ./logs-replay-reputation.py

(2) for addresbook generation 
	- config_addressbook.py
	- ./generate-addressbook.py


You need to also configure postgres connection string inside (./generate-addressbook.py and ./logs-replay-reputation.py)


(Please note: this is a really beta code and somewhat ugly. pylint has stopped talking to be after looking at this code. but it works for my tests. If you are using this, feel free to talk to me or improve. I'd appreciate that. - asharma@lbl.gov ) 


