Country Code Picker Library

How to add to your project
--------------





How to set default country?

 Using xml
   app:ccp_defaultNameCode="US"
 
 Using phone code
   app:ccp_defaultPhoneCode="81"
   
 Programmatically
   setDefaultCountryUsingNameCode() method.
   
   
How to set country preference?

 Using xml
   app:ccp_defaultNameCode="US"
   app:ccp_countryPreference="US,IN,NZ"
   
 Programmatically
   setCountryPreference() method.
   
How to set custom list?

 Using xml
   app:ccp_defaultNameCode="US"
   app:ccp_customMasterCountries="US,IN,NZ,BD,PL,RO,ZW"
 
 Programmatically
   setCustomMasterCountries() method.
   


 

## License

[Apache Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

    Copyright (C) 2016 Harsh Bhakta

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
