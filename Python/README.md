```
OS : Ubuntu 14.04.5 LTS (GNU/Linux 3.13.0-105-generic x86_64)
Language : Python
Language Version : 2, 2.7, 3 and 3.4
Development Env :  virtualenv 15.1.0

--- How to create virtual environment for a Project. ---

$ cd <folder_path_to_project>

$ virtualenv <virtualenv_name>
            OR
$ virtualenv -p /usr/bin/pythonX.X <virtualenv_name> // Assuming path to python compiler is /usr/bin/, 
                                                    // if not sure about path use "which pythonX.X" 
                                                    // [where X.X => version Number]

Activate / Enable Virtual Environment
$ source <folder_path_to_project>/<virtualenv_name>/bin/activate
                                    OR
$ cd <folder_path_to_project>
$ source ./<virtualenv_name>/bin/activate

Deactivate / disable
$ deactivate
