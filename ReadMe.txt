De webapplicatie in deze directory kan worden gedraaid op een http-server voorzien van MySQL.
Zet daartoe de bestanden in `htdocs` over naar de htdocs-directory van de http-server.
Let op: in het bestand htdocs\MirrorMe\localSettings.php staan de database settings voor MySQL.

 * DATABASE settings
 *************************************************************************************************/
// Config::set('dbHost', 'mysqlDatabase', 'localhost');
// Config::set('dbUser', 'mysqlDatabase', 'ampersand');
// Config::set('dbPassword', 'mysqlDatabase', 'ampersand');
// Config::set('dbName', 'mysqlDatabase', '');

Zorg dat deze settings overeenkomen met MySQL, om de applicatie toegang tot de database te verschaffen.


Status:
Dit programma is een eerste probeerseltje, en lijkt nog niet in de verste verte op wat we in MirrorMe willen laten zien.

Groetjes,
Stef
0651348895