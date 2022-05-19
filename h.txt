: use "h.bat <adress>"
: run "ping" and "tracert"
: please, set needed params

ipconfig/all
@echo =======================================
@echo ======  p i n g =======================
@echo =======================================
ping %1
@echo =======================================
@echo ======== t r a c e r t ================
@echo =======================================
tracert %1

::for %%i in (%*) do (set /a ArgCount+=1)
::echo %ArgCount%

::echo %2