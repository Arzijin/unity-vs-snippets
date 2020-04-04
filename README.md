# Code snippets
- dlog.snippet : Snippet to format logging instructions 
### Debug (dlog.snippet)

Each command will import <code>UnityEngine</code> because of dependency of <code>Debug.Log*</code> functions.

#### Standard Log

##### dlog : Log without variable

Command : *dlog* <br/>
Variables : Message <br/>
Resulting Format : <code> Debug.Log("[ClassName] Message"); </code>

##### dlogm : Log with one variable

Command : *dlogm* <br/>
Variables : Message, Variable <br/>
Resulting Format : <code> Debug.Log("[ClassName] Message {Variable}"); </code>

#### Warning Log

##### wlog : Log warning without variable

Command : *wlog* <br/>
Variables : Message <br/>
Resulting Format : <code> Debug.LogWarning("[ClassName] Warning : Message"); </code>

##### wlogm : Log warning with one variable

Command : *wlogm* <br/>
Variables : Message, Variable <br/>
Resulting Format : <code> Debug.LogWarning("[ClassName] Warning : Message {Variable}"); </code>

#### Error Log

##### erlog : Log error without variable

Command : *erlog* <br/>
Variables : Message <br/>
Resulting Format : <code> Debug.LogError("[ClassName] Error : Message"); </code>

##### erlogm : Log error with one variable

Command : *erlogm* <br/>
Variables : Message, Variable <br/>
Resulting Format : <code> Debug.LogError("[ClassName] Error : Message {Variable}"); </code>
