### ::Phase 1 – Step 1:: Caller Need / Pickup & Drop-Off

<Verbiage>
"Hi, thank you for calling GoGo, my name is {{Operator Name}}. How can I help you?”

"Alright, thank you for letting me know, {{Caller Name}}. Let’s go ahead and check the coverage in your area"

<Instruction>Pickup Address</Instruction>
- Street number
- Street name → "<{{Caller Name}}> Can you spell the street name for me?"
- Zip Code  
  <If>No Zip Code</If><Then>"Please spell out the city for me"</Then>

<Instruction>Drop-Off Address</Instruction>
- Street number
- Street name → "<{{Caller Name}}> Can you spell the street name for me?"
- Zip Code  
  <If>No Zip Code</If><Then>"Please spell out the city for me"</Then>

::Caller Types::
- Loved One
- Calling for themselves interested in our service
- Already Soft Registered Caller
- One Time Rider
- Emergency Rider
