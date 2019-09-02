# Zabbix-Tripp-Lite-PDU-15
Supports PDUMH20ATNET - WEBCARDLX family of products

Zabbix template for SNMP monitoring Tripp Lite PDU.
 
Install the MIBS for TRIPPLITE on Zabbix box (/usr/share/snmp/mibs)

Needs to set up macros: 
{$HISTORY} 
{$TRENDS} 
{$UPDATEINT}

{$MAX_INPUTVOLTAGE}
{$MAX_OUTPUTCURRENT_CRITICAL}
{$MAX_OUTPUTCURRENT_WARNING}
{$MIN_INPUTVOLTAGE}
{$SNMP_COMMUNITY}

EXAMPLE: 

{$HISTORY} = 1w
{$TRENDS} = 182d
{$UPDATEINT} = 5m
