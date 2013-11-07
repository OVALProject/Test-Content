****************************************************

                  OVAL Test Content

 Copyright (c) 2002 - 2013 - The MITRE Corporation

****************************************************

The MITRE Corporation developed the OVAL Test Content to provide 
the OVAL Community with a simple way to test the capability of 
OVAL Definition Evaluators. After running the OVAL Test Content 
through an OVAL Definition Evaluator, the OVAL Results will show 
the user which tests are properly supported by that tool. This 
allows users to perform unit testing of tools against the OVAL
Language. Over time, the OVAL Test Content will cover the basic 
behavior of all tests and capabilities in the OVAL Language.

You may download the OVAL Test Content to any computer you wish, 
and to as many computers as you wish.  

BY USING THE OVAL TEST CONTENT, YOU SIGNIFY YOUR ACCEPTANCE OF THE 
TERMS AND CONDITIONS OF USE.  IF YOU DO NOT AGREE TO THESE TERMS, 
DO NOT USE THE OVAL TEST CONTENT.  SEE THE TERMS.TXT FILE INCLUDED 
WITH THE OVAL TEST CONTENT.

-- CONTENTS --
	
  I     SUPPORTED PLATFORMS
         A. Red Hat Linux 
         B. Sun Solaris
         C. Microsoft Windows
         D. Mac OS
  II    USING THE OVAL TEST CONTENT
         A. Preparing the System
         B. Running the Content
         C. Expected Results
  III   REQUESTING NEW CONTENT
  IV    REPORTING PROBLEMS
  V     USEFUL LINKS

-- I -- SUPPORTED PLATFORMS --

  A. Red Hat Linux

	  The OVAL Test Content is currently developed and tested on 
	  the 32-bit version of Red Hat Enterprise Linux 5.
  
  B. Sun Solaris
  
	  The OVAL Test Content is currently developed and tested on 
	  the 32-bit version of Sun Solaris 10.
  
  C. Microsoft Windows
  
	  The OVAL Test Content is currently developed and tested on 
	  the 64-bit version of Microsoft Windows 7.  

  D. Mac OS  

	  The OVAL Test Content is currently developed and tested on 
	  the 32-bit version of Apple Mac OSX 10.6.

-- II -- USING THE OVAL TEST CONTENT --

  A. Preparing the System
	  
	  First, extract the OVAL Test Content to a directory of your 
	  choice. Then unzip support.zip to the following location
	  depending on the platform of the system being tested.
	  
	  Windows: C:\support
	
	  Linux, Mac OS, Solaris: /tmp/support

  B. Running the Content
  
	  Run each of the OVAL Definition documents in the platform 
	  directory of the system being tested against your OVAL 
	  Definition Evaluator.
  
  C. Expected Results

	 Each OVAL Definition document is written to evaluate to true unless
	 otherwise specified.
  
-- III -- REQUESTING NEW CONTENT --

To request new OVAL Test Content, please add a feature request 
tracker item (https://github.com/OVALProject/Test-Content/issues/new?&labels=feature%20request), 
with a brief description of the content that you would like to see
created. We will be adding new OVAL Test Content as we implement new
features in the OVAL Interpreter, however, if the OVAL Community
would like to see certain content get created, we would be happy to 
accommodate that need.
	  
-- IV -- REPORTING PROBLEMS --

To report a problem with the OVAL Test Content, please add a bug 
tracker item (https://github.com/OVALProject/Test-Content/issues/new?&labels=bug), 
with a brief description of the problem. Please include the platform 
and version of the OVAL Test Content, the name of the OVAL Definitions 
document, and the identifier of the affected construct.

-- V -- USEFUL LINKS --

OVAL Web site -- http://oval.mitre.org

OVAL Test Content GitHub Site -- https://github.com/OVALProject/Test-Content

OVAL Terms of Use -- http://oval.mitre.org/oval/about/termsofuse.html

OVAL Test Content Wiki -- https://github.com/OVALProject/Test-Content/wiki

Making Security Measurable - http://msm.mitre.org

----------------------------------------------------------
OVAL is co-sponsored by the office of Cybersecurity and Communications at the U.S. Department of Homeland Security. OVAL and the OVAL logo are trademarks of The MITRE 
Corporation. Copyright 2002-2013, The MITRE Corporation (www.mitre.org).