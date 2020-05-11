# My-Sap-HANA-express-LAB
Learn SAP HANA administration in a simulated environment


####
This is my LAB which i setup on my Laptop. I used the following systems:-
    1) Windows Server 2019 - MAINDC
    2) SAP HANA express server + XS Application - Prebuilt-VM from SAP.
    3) Optionally Suse Enterprise Linux 15 SP 1 - install SUSE and SAP HANA from scratch to learn this process.
    4) The network is 172.16.0.0/24 which is also in vmware - SOPHOS_UTM_Router.
    
So starting with DC (Domain Controller) i setup the windows server 2019 Evaluation Center. the ip is 172.16.0.10 on custome Net in vmware.
The plan is to use this LDAP scenario so i have a feel of SAP HANA working with LDAP server. This will give me a sort of experince in SAP and at least help me in learning SAP side of the business IT operations.

OPTIONALLY:

Install SUSE Enterprise Linux for SAP ( either SEL 12 SP 2    or    SEL 15 SP 1 ) from scratch. After this we install SAP HANA on this SEL for SAP system. We need at least 16GB Ram and 70GB Hard disk for this System to run SAP HANA express edition server + XS.

