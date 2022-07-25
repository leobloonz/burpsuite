# burpsuite
pass: 311138

download latest version and do the magic trick

## create launcher
touch burpsuite && chmod +x burpsuite

echo "java -javaagent:BurpSuiteLoader_v2022.7.jar -noverify -jar burpsuite_pro_v2022.7.jar" > burpsuite

## add certificate
open firefox

enable foxyproxy

http://burp

download cert

firefox settings -> view certificates

import -> tick option 1
