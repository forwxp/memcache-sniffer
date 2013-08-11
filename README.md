Overview
===========

<p>A small but useful tool to sniffer memcache query</p>
<p>contact: qingqibai@gmail.com</p>

Usage summary
=============

<p>You need to install python-pypcap and python-dpkt to run this tool</P>
<p>you may: </p>
    * apt-get install python-pypcap   
    * apt-get install python-dpkt    
<p>or:   </p>
    * pip install python-pypcap   
    * pip install python-dpkt   
</p>
<p>
How to use memcache-sniffer to sniffer query:: </p>
<p>You can get help with ./memcache-sniffer -h or ./mysql-sniffer --help
    * ./memcache-sniffer -ieth1 -p11211 -r0.2   
    * ./memcache-sniffer -ieth1 -f'host 10.4.16.21 and tcp dst port 11211'   
    * -i or --interface: the interface you want to siniffer   
    * -p or --port: the memcache port you use   
    * -f or --filter: filter, defalut None, would use "dst you host and tcp dst port you port    
    * -r or --radio: filter radio, from 0 to 1, default 1 means sniffer all query     
    * -o or --output-file: output file, if set it will print the query to this file instead of stdout, defult None.   
</p>
