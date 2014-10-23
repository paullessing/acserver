Access Control Server
=====================

A RESTful server that works with the Access Control Nodes (https://github.com/solexious/ACNode)
Protocol loosely based on http://wiki.london.hackspace.org.uk/view/Project:Tool_Access_Control/Solexious_Proposal

Status: Done, but not yet fully tested

Progress:

- [X] Sync with membership json file
- [X] [Get Card Permission](http://wiki.london.hackspace.org.uk/view/Project:Tool_Access_Control/Solexious_Proposal#Get_card_permissions)
- [X] [Add Card](http://wiki.london.hackspace.org.uk/view/Project:Tool_Access_Control/Solexious_Proposal#Add_card)
- [X] [Check DB Sync](http://wiki.london.hackspace.org.uk/view/Project:Tool_Access_Control/Solexious_Proposal#Check_DB_sync)
- [X] [Report Tool Status](http://wiki.london.hackspace.org.uk/view/Project:Tool_Access_Control/Solexious_Proposal#Report_tool_status)
- [X] [Check Tool Status](http://wiki.london.hackspace.org.uk/view/Project:Tool_Access_Control/Solexious_Proposal#Check_tool_status)
- [X] [Tool Usage (live)](http://wiki.london.hackspace.org.uk/view/Project:Tool_Access_Control/Solexious_Proposal#Tool_usage_.28live.29)
- [X] [Tool Usage (usage time)](http://wiki.london.hackspace.org.uk/view/Project:Tool_Access_Control/Solexious_Proposal#Tool_usage_.28usage_time.29)
- [X] [Case Alter](http://wiki.london.hackspace.org.uk/view/Project:Tool_Access_Control/Solexious_Proposal#Case_alert)

Roadmap

- [ ] show maintainers per tool: web gui to show maintainers per tool


Install:
========
* Requires nginx, php5, php5-mysql, php5-fpm, mysqld
* Copy acserver.nginx to /etc/nginx/sites-available/acserver
* Run ln -s /etc/nginx/sites-enabled/acserver /etc/nginx/sites-available/acserver
* Start php5-fpm and nginx

Usage:
======
* See the comments in application/controllers/api.php for usage examples.
