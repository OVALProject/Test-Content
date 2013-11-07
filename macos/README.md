#Mac OS Test Content#
##Mac OS##

    The OVAL Test Content is currently developed and tested on the 32-bit version of Apple Mac OSX 10.6.

<strong>1. Preparing the System</strong>  
First, extract the OVAL Test Content to a directory of your choice. Then unzip support.zip to /tmp/support.

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
* macos-def:accountinfo_test
* macos-def:inetlisteningservers_test
* macos-def:nvraminfo_test
* macos-def:pwpolicy_test
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
* unix-def:file_test
* unix-def:inetd_test
* unix-def:interface_test
* unix-def:password_test
* unix-def:process_test
* unix-def:process58_test
* unix-def:runlevel_test
* unix-def:shadow_test
* unix-def:uname_test
* unix-def:xinetd_test
