# HAILHYDRA
# how to hydra  </br>
$ hydra -L username.txt -p aaa 192.168.x.x -V http-form-post "/PATH/login:username=^USER^&password=^PASS^:Invalid username" </br>

--username </br>
-l ชื่อหนึ่งชื่อ </br>
-L wordlist </br>

--password </br>
-p รหัสหนึ่งรหัส </br>
-P wordlist </br>

-V โฃว์ รหัส พาส ระหว่างเดา </br>

path:parameters:F </br>
ในส่วนนี้ใช้ burb suit ดูได้ </br>
"/PATH/login.php     :   username=^USER^&password=^PASS^    :      F=Invalid username" </br>

username, password มาจากเว็บ </br>

^USER^ --> username ที่ต้องการให้เดา </br>
^PASS^ --> password ที่ต้องการให้เดา
