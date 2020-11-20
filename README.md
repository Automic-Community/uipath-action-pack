## Getting Started:


###### Description

UiPath is a leading solution in the Robotic Process Automation market. UiPath helps you gain time and reliability by automating fastidious manual tasks.

By integrating UiPath with CA Continuous Delivery Automation, CA Automic Service Orchestration or CA Automic Workload Automation, you benefit from fully automated workflows that contains tasks operated by the different products.

Integration examples:

**Continuous Delivery**

1. Towards the end of a CI/CD pipeline orchestrated by CA Continuous Delivery Automation, run a functional test with UiPath and use the result as a gatekeeper in your application deployment workflow
2. Handle UiPath packages with a DevOps approach, create a CI/CD pipeline inside UiPath to accelerate the delivery of your business applications that involve UiPath

**Service Orchestration**

1. In the middle of a provisioning workflow operated by CA Automic Service Orchestration, use UiPath to log in the user interface of your tool for obtaining an IP address, and pass it to successor tasks in CA Automic Service Orchestration for setting the IP address in a technical component that is being provisioned

**Workload Automation**

1. Perform web scraping with UiPath and process the harvested data by running a series of IT operations with CA Automic Workload Automation
		
###### Actions

1. Get Environments
2. Upload Package
3. Get Releases
4. Create New Release
5. Rollback Release to Previous Version
6. Get Processes
7. Start Job
8. Get Robots
9. Get Robot Logs
		
###### Compatibility:

1. UIPath UIPath 2018.2  

###### Prerequisite:

1. Automation Engine should be installed.
2. Automic Package Manager should be installed.
3. RA REST action pack should be installed.

###### Steps to install action pack source code:

1. Clone the code to your machine.
2. Go to the package directory.
3. Run the command apm upload in the directory which contains package.yml (source/):
   Ex. **apm upload -force -u <Name>/<Department> -c <Client-id> -H <Host> -pw <Password> -S AUTOMIC -y -ia -ru**


###### Package/Action Documentation

Please refer to the link for [package documentation](source/ae/DOCUMENTATION/PCK.AUTOMIC_UIPATH.PUB.DOC.xml)

###### Third party licenses:

The third-party library and license document reference.[Third party licenses](source/ae/DOCUMENTATION/PCK.AUTOMIC_UIPATH.PUB.LICENSES.xml)

###### Useful References

1. [About Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_AboutPacksandPlugins.htm?Highlight=Action%20packs)
2. [Working with Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_WorkingWith.htm#link10)
3. [Actions and Action Packs](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#_Common/ReleaseHighlights/RH_Plugin_PackageManager.htm?Highlight=Action%20packs)
4. [PACKS Compatibility Mode](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#AWA/Variables/UC_CLIENT_SETTINGS/UC_CLIENT_PACKS_COMPATIBILITY_MODE.htm?Highlight=Action%20packs)
5. [Working with actions](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/AB_WorkingWith.htm#link4)
6. [Installing and Configuring the Action Builder](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/install_configure_plugins_AB.htm?Highlight=Action%20packs)

###### Distribution: 

In the distribution process, we can download the existing or updated action package from the Automation Engine by using the apm build command.
Example: **apm build -y -H AE_HOST -c 106 -u TEST/TEST -pw password -d /directory/ -o zip -v action_pack_name**
			
			
###### Copyright and License: 

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)

###### Questions or Need Help? 

Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
