# Introduction
 1. Copy the *edd-paytm-gateway* folder into your installation's  *wp-content/plugin* folder
 2. Activate the plugin through the 'Plugins' menu in WordPress Administration.

# Configuration
 1. Login to the admin panel. Browse through till Downloads->Settings->Payment Gateways tab. 
 2. Scroll down to "Login and Pay with Paytm Settings"
 3. Fill in the necessary details for Merchant Id, Merchant Key, Select Mode, Website Name and Industry Type.
 4. Save the data.

 See Video : https://www.youtube.com/watch?v=scRNFL9bilQ

# Paytm PG URL Details
	staging	
		Transaction URL             => https://securegw-stage.paytm.in/theia/processTransaction
		Transaction Status Url      => https://securegw-stage.paytm.in/merchant-status/getTxnStatus

	Production
		Transaction URL             => https://securegw.paytm.in/theia/processTransaction
		Transaction Status Url      => https://securegw.paytm.in/merchant-status/getTxnStatus
