### FRAGMENTS	
**Def:** Work like a sub-activity. Because it will act like a **child** of the **main activity** so the lifetime of it depend on it's mother.

**Example**
A app which is used to read paper has 2 columns: 1 is the list of papers and 2 is the detail view of it
![Fragments Example](/pic/fragments.png)
The phone layout will not have enough space for viewing details so define 2 fragments (meaning 2 activities) will be reasonable.

**How to create**
	- Extend **Fragments**
	- Declare it in main activity layout file (*activity_main.xml*)

#### FRAGMENT LIFE ECYCLE



### INTENTS AND  FILTERS
**Def** An Android Intent play a role transiting the *data* from components. 

**Example**
 Your activy want to open the web brower. The step would be sending "ACTION_WEB_SEARCH" Intent to *Android intent resolver*. So the Android intent resolver will check all the intents to match your command to do.

Messenger command the camera to start

### Structute of intent
	- Action
	- Data
	- Category
	- Extras
	- Flags
	- Conponent Name

#### Types of Intents
##### Explicit Intents 
It is the fixed action that the activity A point to activity B
'''java
Intent i = new Intent(this, TargetActivity.class);
'''



