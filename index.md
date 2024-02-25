<html>
  <body>
        <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DIS000000Jmjl',
				'SmartTech_Web_Messaging',
				'https://smarttechinnovationscom-dev-ed.develop.my.site.com/ESWSmartTechWebMessagin1708372474054',
				{
					scrt2URL: 'https://smarttechinnovationscom-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://smarttechinnovationscom-dev-ed.develop.my.site.com/ESWSmartTechWebMessagin1708372474054/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
