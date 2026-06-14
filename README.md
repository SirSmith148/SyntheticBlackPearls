# SyntheticBlackPearls
Repository for my Ark Ascended Mod Synthetic Black Pearls


Craft Your Own Black Pearls!
==========================================

This mod allows you to craft synthetically made black pearls.


Adds in a new item engram for synthetic black pearls, unlocked at level 84 alongside the absorbent substrate and made withing the chemistry bench.

Default Recipe (Chemistry Bench):
10x Silica Pearls
5x Obsidian
2x Oil
= 1x Synthetic Black Pearl

To customize the recipe add this to your Game.ini:
==========================================

[/Script/ShooterGame.ShooterGameMode]
ConfigOverrideItemCraftingCosts=(ItemClassString="PrimalItemResource_SyntheticBlackPearl_C",BaseCraftingResourceRequirements=((ResourceItemTypeString="PrimalItemResource_Silica_C",BaseResourceRequirement=10.0,bCraftingRequireExactResourceType=False),(ResourceItemTypeString="PrimalItemResource_Obsidian_C",BaseResourceRequirement=5.0,bCraftingRequireExactResourceType=False),(ResourceItemTypeString="PrimalItemResource_Oil_C",BaseResourceRequirement=2.0,bCraftingRequireExactResourceType=False)))

Curse Forge [ID] 1574735
==========================================
