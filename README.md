# noodle  - Noodle a custom built ALB (w/SSL) for Splunk HEC

Noodle is a combination of the following: Kubernets + Istio + Splunk HF/HEC 

The yamls provided setup deployment of the following components

 - Virtual Service + Inbound TLS Gateway 
 - Inboud/Outbound HTTPS Services #default port TCP/32088
 - 2 x Splunk Heavy Forwarders configured for HEC input
 - PV/PVC for Splunk HEC apps



