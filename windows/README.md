#Windows Test Content#
##Microsoft Windows##

    The OVAL Test Content is currently developed and tested on the 64-bit version of Microsoft Windows 7.  

<strong>1. Preparing the System</strong>  
First, extract the OVAL Test Content to a directory of your choice. Then unzip support.zip to C:\support.

<strong>2. Running the Content</strong>  
Run each of the OVAL Definition documents in the platform directory of the system being tested against your OVAL Definition Evaluator.

<strong>3. Expected Results</strong>  
Each OVAL Definition document is written to evaluate to true unless otherwise specified.

##Supported Constructs##
* ind-def:environmentvariable_test
* ind-def:family_test
* ind-def:filehash_test
* ind-def:filehash58_test
* ind-def:ldap_test
* ind-def:sql_test
* ind-def:textfilecontent_test
* ind-def:textfilecontent54_test
* ind-def:unknown_test
* ind-def:variable_test
* ind-def:xmlfilecontent_test
* oval:binary datatype
* oval:boolean datatype
* oval:check enumeration (entity_check)
* oval:check enumeration (test)
* oval:check enumeration (var_check)
* oval:evr_string datatype
* oval:existence enumeration
* oval:float datatype
* oval:int datatype
* oval:ipv4address datatype
* oval:ipv6address datatype
* oval:string datatype
* oval:version datatype
* oval-def:arithmetic function
* oval-def:begin function
* oval-def:concat function
* oval-def:constant_variable
* oval-def:criteria
* oval-def:criterion
* oval-def:end function
* oval-def:escape_regex function
* oval-def:extend_definition
* oval-def:external_variable
* oval-def:literal_component
* oval-def:local_variable
* oval-def:object_component
* oval-def:regex_capture function
* oval-def:set
* oval-def:split function
* oval-def:substring function
* oval-def:time_difference function
* oval-def:variable_component
* win-def:accesstoken_test
* win-def:activedirectory_test
* win-def:auditeventpolicy_test
* win-def:auditeventpolicysubcategories_test
* win-def:file_test
* win-def:fileauditedpermissions_test
* win-def:fileauditedpermissions53_test
* win-def:fileeffectiverights_test
* win-def:fileeffectiverights53_test
* win-def:group_sid_test
* win-def:group_test
* win-def:interface_test
* win-def:lockoutpolicy_test
* win-def:metabase_test
* win-def:passwordpolicy_test
* win-def:port_test
* win-def:printereffectiverights_test
* win-def:process_test
* win-def:process58_test
* win-def:registry_test
* win-def:regkeyeffectiverights_test
* win-def:regkeyeffectiverights53_test
* win-def:regkeyauditedpermissions_test
* win-def:regkeyauditedpermissions53_test
* win-def:serviceeffectiverights_test
* win-def:sharedresource_test
* win-def:sid_sid_test
* win-def:sid_test
* win-def:uac_test
* win-def:user_sid55_test
* win-def:user_test
* win-def:volume_test
* win-def:wmi_test
* win-def:wmi57_test
* win-def:wuaupdatesearcher_test
