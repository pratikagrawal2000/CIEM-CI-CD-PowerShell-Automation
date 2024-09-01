##Purpose
This script will create New Role Assignment in the given Subscription.

##Input Parameters
SubscriptionId - The Azure subscription ID
usersPermissionList - User and Permission List in JSON format.  <br>

Json Structure : {'data':[{'user': 'firstname.lastname@wolterskluwer.com',  'role': ['PermissionName1','PermissionName2']},{'user': 'firstname1.lastname1@gmail.com',  'role': ['PermissionName1','PermissionName2']}]}

##Output
The status of the script will be displayed on pipeline logs
