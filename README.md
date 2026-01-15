# Message pour le développeur IA

Le but est de proposer une interface intuitive à des utilisateurs non
techniques, (un grand parent et son petit fils, par exemple) sur la base de
TOTP/HOTP, pour déterminer un "code" qui leur permettra de s'identifier
ultérieurement, et de s'assurer que personne n'usurpe une identité

- l'interface doit être facile d'utilisation, intuitive, permettre aux
utilisateurs de personaliser les noms/identifiant de leur token (papy,
stéphane, Bonne Maman...), et expliquer simplement comment l'utiliser pour
générer les codes et les employer dans une application totp
- elle doit tourner entierement localement dans le browser des utilisateurs.
pas de transit de données avec le serveur
- qrcode en premiere option, mais les données sous-jacentes accessible au
besoin
- accent +++ sur l'accessibilité, la facilité d'usage et la pédagogie de
l'utilisation sécuritaire
- l'application doit pouvoir être déployée facilement avec docker-compose, et
exposée publiquement (aucune data, aucun compute sur le serveur)
