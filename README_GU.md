SGFI Handball Scoreboard — Android APK project (મફત)

આ પ્રોજેક્ટ તમારા હાલના scoreboard ને Android એપમાં ખોલે છે:
https://ptejash58-netizen.github.io/handball-scoreboard/

મહત્વનું:
- આ APK ફાઇલ પોતે નથી; આ Android Studio project/source છે, જેમાંથી મફતમાં APK બનાવી શકાય.
- હાલનો Firebase live scoreboard અને તેનો ડેટાબેઝ જ વપરાય છે. ફોનમાં ઇન્ટરનેટ જરૂરી છે.
- જો વેબસાઇટનો URL બદલાય અથવા સાઇટ બંધ હોય તો એપમાં પણ સ્કોરબોર્ડ નહીં ખુલે.
- Camera permission માટે Android wrapper તૈયાર છે, પરંતુ અપલોડ કરેલી HTML ફાઇલમાં camera-streaming code દેખાતો નથી. એટલે એપ wrapper એકલું કેમેરા લાઇવ સ્ટ્રીમ ઉમેરતું નથી.

APK બનાવવાની રીત (Windows, મફતમાં):
1. Android Studio ને official Android Developers website પરથી install કરો.
2. ZIP extract કરો.
3. Android Studio > Open > extracted HandballScoreboard folder પસંદ કરો.
4. Gradle sync પૂરો થવા દો અને SDK 35 install કરવા કહે તો સ્વીકારો.
5. Build > Build Bundle(s) / APK(s) > Build APK(s) પસંદ કરો.
6. APK સામાન્ય રીતે app/build/outputs/apk/debug/app-debug.apk માં મળશે.
7. APK ફોનમાં મોકલી install કરો. ફોનમાં પૂછે તો આ સ્ત્રોતથી install કરવાની મંજૂરી આપો.

Play Store પર publish કરવું જરૂરી નથી; વ્યક્તિગત ઉપયોગ માટે debug APK બનાવી શકાય છે.
