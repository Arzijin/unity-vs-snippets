# Code snippets for CINEVR
Clone this repo in your Microsoft Visual Studio custom snippets folder.

### :warning: This branch need the CINEVR.Core.Logging scripts

##### Snippets list :
- **dlog.snippet** : Formats logging instructions 

## Debug (dlog.snippet)

Each command will import <code>UnityEngine</code> because of dependency of <code>Debug.Log*</code> functions.

#### Standard Log

##### dlog : Log without variable

Command : *dlog* <br/>
Variables : Message <br/>
Resulting Format : <code> Logging.Log("[ClassName] Message"); </code>

##### dlogm : Log with one variable

Command : *dlogm* <br/>
Variables : Message, Variable <br/>
Resulting Format : <code> Logging.Log("[ClassName] Message {Variable}"); </code>

#### Warning Log

##### wlog : Log warning without variable

Command : *wlog* <br/>
Variables : Message <br/>
Resulting Format : <code> Logging.LogWarning("[ClassName] Warning : Message"); </code>

##### wlogm : Log warning with one variable

Command : *wlogm* <br/>
Variables : Message, Variable <br/>
Resulting Format : <code> Logging.LogWarning("[ClassName] Warning : Message {Variable}"); </code>

#### Error Log

##### erlog : Log error without variable

Command : *erlog* <br/>
Variables : Message <br/>
Resulting Format : <code> Logging.LogError("[ClassName] Error : Message"); </code>

##### erlogm : Log error with one variable

Command : *erlogm* <br/>
Variables : Message, Variable <br/>
Resulting Format : <code> Logging.LogError("[ClassName] Error : Message {Variable}"); </code>
