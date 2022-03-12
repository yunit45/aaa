# aaa
ah npc bazzar most npc secreat
source code
public Setting(SettingID settingID, boolean def) {
    this.settingID = settingID;
    Tuple<String, String> t = SettingsManager.getNameAndDesc(this.settingID);
    this.name = (String)t.func_76341_a();
    this.description = (String)t.func_76340_b();
    this.enabled = def;
