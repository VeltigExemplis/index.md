<html> 
  <body>
    <script type='text/javascript'>
    	function initEmbeddedMessaging() {
    		try {
    			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
          			embedded_svc.settings.prepopulatedPrechatFields = {
			  FirstName:,
			  LastName:,
			  Email:,
			  Subject:
        };

    			embeddedservice_bootstrap.init(
    				'00DO400000C6iHG',
    				'SitOnIt_Messaging_Chat',
    				'https://exemplis--partial.sandbox.my.site.com/ESWSitOnItMessagingChat1749155554156',
    				{
    					scrt2URL: 'https://exemplis--partial.sandbox.my.salesforce-scrt.com'
    				}
    			);
    		} catch (err) {
    			console.error('Error loading Embedded Messaging: ', err);
    		}
    	};
    </script>
    <script type='text/javascript' src='https://exemplis--partial.sandbox.my.site.com/ESWSitOnItMessagingChat1749155554156/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
