# emacsinpython


step1:
Install "pip" with port "sudo port install-pip"


step2:Install packages like "pip" "elpy" "jedi" and "rope"

Install jedi :
Install Jedi.el via el-get, Marmalade or MELPA (see install for more info), i.e., either

M-x el-get-install RET jedi RET or

M-x package-install RET jedi RET or

(manually install...)

Configure Emacs using this:
(add-hook 'python-mode-hook 'jedi:setup)

(setq jedi:complete-on-dot t)                 ; optional
If you install Jedi.el manually (BTW, you shouldn’t!), 
you need to add more stuff to it.  
See manual install section.Install Python server (jediepcserver.py) by runningM-x jedi:install-server in Emacs

step3:Install elpy on emacs wit package mode


step4:edit .emcas file so that elpy stat with emacs edit ./emcas file more to fix with two bug 
