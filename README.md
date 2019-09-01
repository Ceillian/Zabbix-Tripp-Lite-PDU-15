# Zabbix-Tripp-Lite-PDU-15
Zabbix template for SNMP monitoring Tripp Lite PDU with 15th firmware
 
Has been created in Zabbix 4.0, but exported from Zabbix 4.2

Supports PDUMH20ATNET - WEBCARDLX family of products

Needs to set up macroses: 
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
