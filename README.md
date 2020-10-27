Azure PowerShell RM Network Stack Deployment Tool
=================================================

            

 

 

 


This script provides functions for creating Azure RM VNET components including:


 


  *  VNET 
  *  NSG 
  *  External Load Balancer 
  *  Internal Load Balancer 
  *  Site to Site VPN 
  *  VNET Peering 

 


 


**Please like if you find it valuable.**


\.AZRM-VnetDeploy.ps1 -csvimport -csvfile C:\temp\iaasdeployment.csv

\.AZRM-VnetDeploy.ps1 -ActionType Create -vnetrg ResGroup -addvnet -vnet VNET

\.AZRM-VnetDeploy.ps1 -ActionType Create -vnetrg ResGroup -vnet VNET creatensg -nsgname nsg

\.AZRM-VnetDeploy.ps1 -ActionType Create -vnetrg ResGroup -vnet VNET -createintloadbalancer -intlbname intlb -lbsubnet 4 -LBPvtIP 10.20.4.10

\.AZRM-VnetDeploy.ps1 -ActionType Create -vnetrg ResGroup -vnet VNET -createextloadbalancer -extlbname extlb






        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
