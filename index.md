<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DEc000000JMmP',
				'AW_Test',
				'https://rethinkfirst--sept23.sandbox.my.site.com/ESWAWTest1702455833559',
				{
					scrt2URL: 'https://rethinkfirst--sept23.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://rethinkfirst--sept23.sandbox.my.site.com/ESWAWTest1702455833559/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
