# JPPreference
Step 1. Declare a JPPreference in the Application Context. 
  > JPPreference preference = new JPPreference(this);

Step 2. Store/Restore Data
  > preference.addPreference({Key}, {Value});\n
  > String str = preference.getStringFromPreference({Key});
