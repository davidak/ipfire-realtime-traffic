IPFire Realtime-Traffic Monitor
===============================

displays external traffic with gauges.

.. image:: http://davidak.de/tmp/ipfire-realtime-traffic.png

Install
-------

#. Download Repo or Archive from Github
#. Unzip Archive
#. Upload the File to your IPFire: /srv/web/ipfire/html/realtime-traffic.html
#. Download newest Version https://github.com/Mikhus/canv-gauge
#. Upload that file to /srv/web/ipfire/html/include/gauge.min.js
#. And this folder to /srv/web/ipfire/html/fonts
#. Open with the domain of your ipfire https://ipfire.lan:444/realtime-traffic.html
#. Maybe adjust the maximun bandwidth in realtime-traffic.html: download_limit = 100; upload_limit = 8;

Feel free to send me an e-mail if you need help or have suggestions to improve it: post at davidak dot de