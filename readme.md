# ANSI Color Escape Sequences 

* **Red** (For Error):
  * [ERROR] in Python: `print("\033[31;1;m[ERROR]\033[0m")`
  * (fail) in Python: `print("(\033[31;1;mfail\033[0m)")`
  * [ERROR] in Bash: `echo -e "\033[31;1;m[ERROR]\033[0m"`
  * (fail) in Bash: `echo -e "(\033[31;1;mfail\033[0m)"`
* **Green** (For Success)
  * (ok) in Python: `print("(\033[32;1;mok\033[0m)")` 
  * (success) in Python: `print("(\033[32;1;msuccess\033[0m)")`
  * (ok) in Bash: `echo -e "(\033[32;1;mok\033[0m)"`
  * (success) in Bash: `echo -e "(\033[32;1;msuccess\033[0m)"`
* **Bright Magenta** (For main tasks like create something)
  * (dataset) in Python: `print("(\033[35;1;mdataset\033[0m)")`
  * (dataset) in Bash: `echo -e "(\033[35;1;mdataset\033[0m)"`
* **White** (for INFO)
  * [ INFO ] in Python: `print("\033[37;1;m[ INFO ]\033[0m")`
  * [ INFO ] in Bash: `echo -e "\033[37;1;m[ INFO ]\033[0m"`
* **Combination**
  * create(ok) in Python: `print("\033[37;1;mcreate\033[0m(\033[32;1;mok\033[0m)")`
  * create(ok) in Bash: `echo -e "\033[37;1;mcreate\033[0m(\033[32;1;mok\033[0m)"`