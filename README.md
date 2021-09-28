# JPPreference
Step 1. Declare a JPPreference in the Application Context. 
  > JPPreference preference = new JPPreference(this);

Step 2. Store Data
  > preference.addPreference({Key}, {Value});

Step 3. Restore Data
  > String str = preference.getStringFromPreference({Key});
