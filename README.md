com.pogstone.fancyparticipantsearch
===================================

Great custom search for searching and filtering on event participants in CiviCRM.

Current features:

 - you can filter/view individual priceset options. (Such as search on participants who registered for a certain priceset session.)
  - Choice of 3 layouts: one row per participant, or one row per line item, or summary totals for each line item option. 
  - Choose which columns to include in the results
  - Includes memberhsip type and membership status in the results
  - Includes information about who the participant was registered by.
  - Includes age of the participant. (You can control the date used to calculate the age, such as using Sept. 1 for school/youth events. ) 
  

Version info: I have tested this successfully under CiviCRM versions 4.2.x and 4.3.x.   

Installation Steps: 

1) Copy the PHP file "FancyParticipantListing.php" in your "civicrm_custom_code" folder, under a directory structure of "CRM/Contact/Form/Search/Custom" 

2) Register the search at: http://myorganization.org/civicrm/admin/options/custom_search?reset=1&group=custom_search

Author Info:
This was created by Sarah Gladstone at Pogstone Inc.  http://pogstone.com
