# sass-install

#Way-01: Using Terminal
==============================
>> npm i -g sass
>> sass sass/style.scss css/style.css

#If found this related Error
sass : File C:\Users\DCL\AppData\Roaming\npm\sass.ps1 cannot be loaded because running scripts is disabled on this system. For more information, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170. At line:1 char:1 + sass -watch sass/style.scss css/style.css + ~~~~ + CategoryInfo : SecurityError: (:) [], PSSecurityException + FullyQualifiedErrorId : UnauthorizedAccess

>> set-ExecutionPolicy RemoteSigned -Scope CurrentUser 
>> Get-ExecutionPolicy
>> Get-ExecutionPolicy -list

# After this line(Get-ExecutionPolicy -list) you see this in your terminal
Scope ExecutionPolicy
----------------------
MachinePolicy Undefined
UserPolicy Undefined
Process Undefined
CurrentUser RemoteSigned
LocalMachine Undefined

#Then again command line
==========================
>> sass sass/style.scss css/style.css

Now, You successfully install Sass for your project.
============================================================

#Way-01: Using VS Code Extension: Live Sass Compiler(Rittik Dey)
==================================================================
Step-01: Install 
Step-02: Open Sass -> style.scss file and Below see watch Sass --> Click --> Watching and generater style.css file in your sass folder

