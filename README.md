# sqlcutie
sqli dork scanner
* Wide detection range (MySQL, MsSQL, PostgreSQL, JDBC/Oracle, Access, MariaDB, DB2, Sybase)
* Regconize dynamic dork queries (e.g. asp?id+site:us, (asp|aspx)?id=)
* Works through Tor

## usage

git pull https://github.com/madfedora/sqlcutie.git

cd sqlcutie

chmod +x sqlcutie-1.8a.pl

./sqlcutie-1.8a.pl -d php?id=

./sqlcutie-1.8a.pl -c

## menu

     -d           Dorking function (dh)
     -c           See dork list (press Q to quit)
     -p           Define a proxy to use (ph)
     -o           Save result in a file
     -h           Print this help manual
     -r           Change log, description & term
     -dh          Print dork manual
     -ph          Print proxy manual
     -u           Update to latest version
