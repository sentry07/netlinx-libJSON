# netlinx-libJSON
A Netlinx library for validating, parsing, modifying, and creating JSON data

# Latest Updates
- Changed JSON_ParseObject to JSON_ParseValidObject and removed the JSON_Validate call in that function
- Added a new JSON_ParseObject that calls JSON_Validate and then calls JSON_ParseValidObject if it's valid
- Added a new JSON_FindObjectInString function that runs a validation routine on an input string and returns the first valid JSON string it finds