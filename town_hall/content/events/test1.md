---
# =====
# The event must by archived if its date (when) is passed.
# archived > draft: true
# =====

title: "Event testing"
# Not sure about that
adresse: 
- address: "some adress"
- postalCode: "75000"
- city: "Paris"
- label: ""

# Today's date at default 
when: 2019-09-23T17:31:04+02:00
Description: "Some description here"
# Can contain one or several photos, that might be stored in ressources, not sure either. 
# So a tab or not, we'll have to loop.
photo: 
- "https://via.placeholder.com/150"
# true by default, true means never display the event
draft: true
important: false
# The organisation throwing the event 
association: "some association name"
---

