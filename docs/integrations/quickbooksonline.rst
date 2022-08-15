=================
Quickbooks Online
=================

Integrate Quickbooks Online accounting with CIBOS by going to Settings -> Accounting.

1. Click **Connect to Quickbooks Online**
2. Select your QB Corporate Account, click **Next**
3. Click **Connect** and do NOT close window
4. Once back into CIBOS
	
	- CIBOS will try and make sure your QB settings are ready for syncing
	- Please go to QB Settings page for guidance

Understanding CIBOS QB setup
"""""""""

CIBOS syncs with Quickbooks Online and process orders through it. The following is the standard QB workflow that CIBOS uses.


.. list-table:: Sales Orders Sync
	:widths: 25 25
	:header-rows: 1

	* - CIBOS Order status
	  - Quickbooks Online
	* - Open Order
	  - Estimate
	* - Received
	  - Invoice

.. list-table:: Manufacturing/Purchase Orders Sync
	:widths: 25 25
	:header-rows: 1

	* - CIBOS status
	  - Quickbooks Online type
	* - Open Order
	  - Purchase Order
	* - Bill
	  - Billed
	* - Paid
	  - Payment
