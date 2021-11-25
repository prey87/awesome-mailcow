# awesome-mailcow
delightful resources for the [mailcow](https://mailcow.email/) project

## Table of contents
- [Deployment](#deployment)
- [API](#api)
- [Monitoring](#monitoring)
- [Backup](#backup)
- [Archiving](#archiving)
- [Other](#other)

### Deployment
- [mailcow-ansiblerole](https://github.com/mailcow/mailcow-ansiblerole) The official ansible role to setup mailcow using [Ansible](https://www.ansible.com/)

### API
- [python-mailcow](https://github.com/derJD/python-mailcow) (python) python-mailcow allows you to interact with the MailCow API
- [mailcowtools](https://github.com/appcoders/mailcowtools) (Node) Mailcow tools - simple tools that use the mailcow API 

### Monitoring
- [mailcow-dockerized postfix](https://docs.librenms.org/Extensions/Applications/#mailcow-dockerized-postfix) for [librenms](https://www.librenms.org/)
- [mailcow content pack](https://marketplace.graylog.org/addons/54cc459f-ddf4-4034-bd5c-a7008183b338) for [graylog](https://www.graylog.org/)
- [mailcow-exporter](https://github.com/j6s/mailcow-exporter) for [prometheus](https://prometheus.io/)
- [parsedmarc-dockerized by @patschi](https://github.com/patschi/parsedmarc-dockerized) with [parsedmarc](https://domainaware.github.io/parsedmarc/) (Open source DMARC report analyzer and visualizer) & [elasticsearch](https://www.elastic.co/en/elasticsearch/) & [kibana](https://www.elastic.co/en/kibana/)
- [parsedmarc-dockerized by @dragoangel](https://github.com/dragoangel/parsedmarc-dockerized) with [parsedmarc](https://domainaware.github.io/parsedmarc/) (Open source DMARC report analyzer and visualizer) & [elasticsearch](https://www.elastic.co/en/elasticsearch/) & [kibana](https://www.elastic.co/en/kibana/)

### Backup
- [docker-borgmatic](https://github.com/b3vis/docker-borgmatic) Backup with [Borgbackup](https://github.com/borgbackup) using [borgmatic](https://github.com/witten/borgmatic) docs at [mailcow docs -> borgmatic backup](https://mailcow.github.io/mailcow-dockerized-docs/third_party-borgmatic/)
- [mailcow-backup](https://github.com/rescaled/mailcow-backup-borg) singe [Borgbackup](https://github.com/borgbackup) script
- [MailcowBackup](https://github.com/asifbacchus/MailcowBackup) alternative [Borgbackup](https://github.com/borgbackup) for mailcow

### Archiving
- [mailpiler-mailcow-integration](https://github.com/patschi/mailpiler-mailcow-integration) archiving mails with [mailpiler](https://www.mailpiler.org/) docs at [mailcow docs -> Mailpiler Integration](https://mailcow.github.io/mailcow-dockerized-docs/u_e-mailpiler-integration/)

### Other
- [Mailcow Privacy Alias CLI](https://github.com/schemen/privacycow) create aliases with cli
- [mailcow-ldap-sync](https://github.com/myOmikron/mailcow-ldap-sync) synchronize your LDAP users into mailcow
