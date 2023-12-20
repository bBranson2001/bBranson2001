- 👋 Hi, I’m @bBranson2001
-  I like to tinker with tech, and break things alike.
-  Wannbe IT guy
- 📫 Drop me a message at this Email js snippet  ((crypt) => {
    const rot13 = c => {
        c = c.codePointAt(0);
        let d = c + 13;
        if (d > (c <= 90 ? 90 : 122)) {
            d -= 26;
        }
        return String.fromCodePoint(d);
    }
    const backwards = s => s.split("").reverse().join("");
    return backwards(crypt.replace(/[a-z]/gi, rot13));
})("zbp.xbbyghb@eruphbo.abfaneo ");
    

<!---
bBranson2001/bBranson2001 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
