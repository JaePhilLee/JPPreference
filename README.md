# JPPreference
Step 1. Declare a JPPreference in the Application Context. 
  > Declare ex) JPPreference preference = new JPPreference(this);

Step 2. Store/Restore Data
  > Store Data ex) preference.addPreference({Key}, {Value});
  > Restore Data ex) String str = preference.getStringFromPreference({Key});
