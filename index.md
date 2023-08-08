<html>
  <body>
    <script type='text/javascript'>
  	function initEmbeddedMessaging() {
  		try {
  			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
  
  			embeddedservice_bootstrap.init(
  				'00DMT0000000PyO',
  				'XC_ITA_WebChatDeployment',
  				'https://enelxconsumer--devpr3.sandbox.my.site.com/ESWXCITAWebChatDeployme1691416118801',
  				{
  					scrt2URL: 'https://enelxconsumer--devpr3.sandbox.my.salesforce-scrt.com'
  				}
  			);
  		} catch (err) {
  			console.error('Error loading Embedded Messaging: ', err);
  		}
  	};
  </script>
  <script type='text/javascript' src='https://enelxconsumer--devpr3.sandbox.my.site.com/ESWXCITAWebChatDeployme1691416118801/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
