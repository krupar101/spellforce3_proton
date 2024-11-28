Proton that fixes the Spellforce 3 font rendering.

Place the spellforce3_fix folder from the zip file into:
$HOME/.steam/steam/compatibilitytools.d

Select that proton to run the game in steam. 
![image](https://github.com/user-attachments/assets/881ed2a6-4401-4b33-9dfe-559ace0f36d5)

### Installation Command

To install the custom Proton version automatically, run the following command in your terminal:

```bash
curl -L "https://github.com/krupar101/spellforce3_proton/releases/download/sf3proton/spellforce3_fix.zip" -o /tmp/spellforce3_fix.zip && mkdir -p "$HOME/.steam/steam/compatibilitytools.d/" && unzip -q /tmp/spellforce3_fix.zip -d "$HOME/.steam/steam/compatibilitytools.d/" && rm /tmp/spellforce3_fix.zip
