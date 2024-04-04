1. Add inventory by going to inventory and filling out the form.
2. Now goto hosts and click add
3. Enter a name and select the inventory created in step 1.
4. Add the following to the variables as JSON

{
  "ansible_host": "163.74.88.66",
  "ansible_user": "itzuser",
  "PYZ": "/usr/lpp/IBM/cyp/v3r11/pyz",
  "ZOAU": "/usr/lpp/IBM/zoautil",
  "ansible_python_interpreter": "/usr/bin/python3",
  "environment_vars": {
    "_BPXK_AUTOCVT": "ON",
    "ZOAU_HOME": "/usr/lpp/IBM/zoautil",
    "LIBPATH": "/usr/lpp/IBM/zoautil/lib:/usr/lpp/IBM/cyp/v3r11/pyz/lib:/lib:/usr/lib:.",
    "PATH": "/usr/lpp/IBM/zoautil/bin:/usr/lpp/IBM/cyp/v3r11/pyz/bin:/bin:/var/bin",
    "_CEE_RUNOPTS": "FILETAG(AUTOCVT,AUTOTAG) POSIX(ON)",
    "_TAG_REDIR_ERR": "txt",
    "_TAG_REDIR_IN": "txt",
    "_TAG_REDIR_OUT": "txt",
    "LANG": "C",
    "PYTHONSTDINENCODING": "cp1047"
  }
}