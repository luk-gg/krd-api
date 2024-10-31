API for kart.cafe (discontinued) with slight modifications. Output not tested. Requires supplying game data in `/game/client`.

TODO:
- All Entries DB (`KtItemTable.uasset`, combine with `KtItemPartsSetDef.uasset` for sets)
- Character DB
    - Skills (`/Content/DataTable/Skill` and `CharacterSkillDef.uasset` thumbnail ref `CharacterToSkillThumbnail.uasset`)
    - Cosmetics
    - Emotes
- Kart DB (stats `KtKartGearSetDef.uasset` and `KtKartUpgradeCustomSetDef.uasset`)
- Misc DB (balloons, wheels, stickers, etc.)
- Track DB (`KtTrackListDef.uasset` theme list `KtTrackThemeListDef.uasset`)
- Models (`/Content/ART`)
- Item mode item rates (`/Content/DataTable/Spitem` or `/Content/DataTable/Ingame`--might be ranked mode/grand prix)
- Textures (`/Content/UI` & `/Content/UI_Common`)
- Racing Pass DB (`/Content/DataTable/RacingPass`)

`/Content/DataTable/StringTable` for list of KR strings.
`/Content/Dev/DriftExperimental` has drift torque curves (not sure if useful).