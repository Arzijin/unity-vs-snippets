# Code snippets
- dlog.snippet : Snippet to format logging instructions 
### Debug (dlog.snippet)

Each command will import <code>UnityEngine</code> because of dependency of <code>Debug.Log*</code> functions.

#### Standard Log

##### dlog

Command : *dlog* 
Variables : Message
Resulting Format : <code> Debug.Log("[ClassName] Message"); </code>

##### dlogm

Command : *dlogm* 
Variables : Message, Variable
Resulting Format : <code> Debug.Log("[ClassName] Message {Variable}"); </code>

#### Warning Log

##### wlog

Command : *wlog* 
Variables : Message
Resulting Format : <code> Debug.LogWarning("[ClassName] Warning : Message"); </code>

##### wlogm

Command : *wlogm* 
Variables : Message, Variable
Resulting Format : <code> Debug.LogWarning("[ClassName] Warning : Message {Variable}"); </code>

#### Error Log

##### erlog

Command : *erlog* 
Variables : Message
Resulting Format : <code> Debug.LogError("[ClassName] Error : Message"); </code>

##### erlogm

Command : *erlogm* 
Variables : Message, Variable
Resulting Format : <code> Debug.LogError("[ClassName] Error : Message {Variable}"); </code>