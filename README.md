# Carbonblack_Splunk
re-working the two old CB apps from splunkbase 

essentially recreating the app without knowing what it looks like. 

I personally don't have the file catalog so I've dropped that from the dashboards. 

Not updated(but I'll update later, if the file catalog isnt needed):
  1. bit9user
  2. bit9newunapproved
  3. bit9fileactivity
  4. bit9hash
  5. bit9pivots

investigation.xml is new, based on what our techs needed


Make sure you edit the macro 'cb_index' to your index 

[cb_index]

definition = index=carbonblack
