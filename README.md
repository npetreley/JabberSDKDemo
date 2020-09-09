# JabberSDKDemo
Demo of the Jabber IM Web SDK

## Instructions

1. Download the entire project as with the top directory (JabberSDKDemo) in whichever directory your web server uses for HTML files. Make sure your web server has permission for user(s) to access the contents of this directory.

2. Start your web server.

3. Browse to <your web server URL>/JabberSDKDemo/JabberDemo.html

4. You can fill in the login details yourself, but if it's just you testing this, you can pre-set the values in JabberDemo.html as follows: 
 

Set the default values in JabberDemo.html here:

			var demoConfig = {
				httpBindingURL: "http[s]://<your CIMP server>:5280/httpbinding",
				username: "<username>",
				password: "<password>",
				unsecureAllowed: true,
				domain: "<domain used in JID such as someone@SOMEDOMAIN>",
				resource: "caxl_",
				appTag: "app-data-8",
			};

If your Cisco IM&P server is set to use https, then you'll need to set unsecureAllowed to false.

The username: is simply your login jabber name, not a full JID.  For example, enter <yourname> not <yourname@domain.com>.  The code adds the domain based on what you enter in the domain: setting.
  
 
