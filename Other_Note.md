

#### mac related
```
application directories
/Library/Preferences/
~/Library/Preferences
/Library/Application Support/
~/Library/Application Support/
/Library/Caches/
~/Library/Caches/
```

#### mvn related
```
mvn clean install -f pom_ck.xml
```

#### shell related
```
nohup node wdserver.js > server.log 2>&1 &
echo xx.txt | xargs awk '{print $4}' | awk '{sum += $1} END{print sum}'
awk '{sum += $1} END{print sum}' temp1.txt
```

#### git related
```
git submodule update --init --recursive

// rm from repo but keep local
git rm --cached -r dirName
```

#### adb related
```
adb shell;run-as com.ck.android
adb uninstall com.ck.android
adb shell am force-stop com.ck.android
adb shell pm clear com.ck.android
adb shell am start -a android.intent.action.VIEW -d 'ck://openpage'
adb shell am start -n com.ck.android/.Login
```

#### ssl
```
check ssl certificate:
openssl s_client -showcerts -connect some_server:server_port 
```

#### others
```
PoC: Proof of Concept  
Vul: Vulnerability  
Exp: Exploit  
```
