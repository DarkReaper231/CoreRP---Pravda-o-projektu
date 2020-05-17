@@ -1,26 +0,0 @@
# CoreRP---Pravda-o-projektu

Aby jste mohli hostovat tento web tak je potřeba udělat pár věcí
V první řadě musíte mít PHP na serveru. Nebudu zde uplně vysvětlovat jak si nainstalovat Apache a PHP ale na internetu je hromada tutoriálů


Jinak aby to správně fungovalo tak je potřeba v souboru /etc/apache2/apache2.conf přepsat

<Directory /var/www/>
        Options Indexes FollowSymLinks
        AllowOverride None
        Require all granted
</Directory> 

na

<Directory /var/www/>
        Options Indexes FollowSymLinks
        AllowOverride All
        Require all granted
</Directory>

Na Windowsu bude pravděpodobně lokace tohoto souboru jinde, tudíž opět strýček Google pomůže


Nebudu tento projekt nějak moc extrémně aktualizovat. Když mě něco napadne nebo přijdou nové informace, přidám je. Takže pokud máte zájem, můžete čas od času sledovat tento branch