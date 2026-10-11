# મફતમાં APK બનાવવાની સરળ રીત (Android Studio વગર)

આ પ્રોજેક્ટમાં GitHub Actions build workflow ઉમેર્યું છે. GitHub પર પ્રોજેક્ટ અપલોડ કર્યા પછી GitHub પોતે APK બનાવશે. આ ZIP હજી APK નથી.

## પગલાં
1. GitHub.com ખોલીને સાઇન ઇન કરો.
2. `New repository` બનાવો. નામ `handball-scoreboard-android` રાખી શકો છો. `Public` અથવા `Private` પસંદ કરો.
3. `Add file` → `Upload files` પસંદ કરો. આ ZIP ને પહેલા Extract કરો, પછી તેની અંદરના પ્રોજેક્ટના બધા ફોલ્ડર/ફાઇલો અપલોડ કરો. `.github` ફોલ્ડર પણ અપલોડ થવો જરૂરી છે.
4. `Commit changes` કરો.
5. Repository માં `Actions` ટેબ ખોલો.
6. `Build Handball Scoreboard APK` workflow પસંદ કરો અને `Run workflow` દબાવો. જો આપમેળે ચાલે તો ચાલવા દો.
7. Build પૂરું થયા પછી તે run ખોલો. નીચે `Artifacts` માં `Handball-Scoreboard-APK` ડાઉનલોડ કરો.
8. ZIP ખોલો; તેમાં `app-debug.apk` મળશે. APK Android ફોનમાં મોકલીને ઇન્સ્ટોલ કરો.

## ધ્યાનમાં રાખો
- આ રીત GitHub account અને થોડા upload/click પગલાં માગે છે; હું આ પર્યાવરણમાંથી તમારા GitHub accountમાં અપલોડ કરી શકતો નથી.
- GitHub Actions build નિષ્ફળ જાય તો `Actions` run નો error screenshot મોકલો.
- એપ હાલની ઓનલાઇન scoreboard વેબસાઇટ ખોલે છે, તેથી ઇન્ટરનેટ જરૂરી છે.
