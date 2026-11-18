SETUP (phone only)
1. console.firebase.google.com > Add project > Build > Realtime Database > Create (test mode).
2. Rules tab: {"rules":{".read":true,".write":true}} > Publish.
3. Project settings > Add web app > copy the config into CFG at top of index.html (include databaseURL).
4. Upload index.html + movies.json to a GitHub repo > Settings > Pages > deploy from main.
