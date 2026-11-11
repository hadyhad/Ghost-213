# Suspect Dossier

- **Alias:** The Recipe Locker
- **Skill:** Amateur to intermediate
- **Motive:** Financial extortion

## Modus Operandi

The attacker distributed a malicious archive named `Grand_Mother_Secret_Recipes_Pack.zip` through an unverified public forum. The archive contained an executable disguised with a double extension as `Secret_Almond_Baklava.pdf.exe`. After execution, the ransomware encrypted the bakery's workstation and connected backup drive, renaming files with the `.LOCKED_BAKERY` extension. The attacker then displayed a ransom demand requesting 0.1 BTC and 500 baguettes.

## Adversary Mistake

The attacker left several identifiable clues: the archive came from an unverified public forum, the executable used the suspicious `.pdf.exe` double extension, and the ransomware used the distinctive `.LOCKED_BAKERY` file extension. The continuously connected USB backup also showed that the encryption affected both the workstation and backup drive.
