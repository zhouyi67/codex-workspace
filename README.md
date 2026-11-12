# 分镜 Skill 库

- [导演分镜 Skill](导演分镜-SKILL-2.0.md)：日常分镜入口，采用前置人物初始站位、p编号与自然段正文。
- [真人写实打斗参考库](skills/real-combat-director/SKILL.md)：现实格斗、兵器、防守闪避和多人调度的按需参考，沿用导演分镜的格式和用户要求。
- [玄幻打斗参考库](skills/xuanhuan-combat-director/SKILL.md)：写到近身攻防、武器、法术或大场面时按需取用，沿用导演分镜的格式和用户要求。

参考包完整性检查：

```bash
python3 skills/xuanhuan-combat-director/scripts/check_package.py
```

该脚本检查入口与8份参考文件是否存在，不验证平台能力、招式参数或实际生成效果。
