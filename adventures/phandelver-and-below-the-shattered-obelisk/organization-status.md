# Phandelver and Below: The Shattered Obelisk - Organization Status

## Completed Files ✅

### Main Adventure
- `/adventure-overview.md` - Complete campaign overview and chapter summaries

### Chapters  
- `/chapters/chapter-01-dangerous-journey.md` - Complete Chapter 1 content
- `/chapters/chapter-02-trouble-in-phandalin.md` - Complete Chapter 2 content

## Remaining Chapters to Create 📝

Based on the dump file structure, the following chapters need to be extracted and organized:

### Chapter 3: The Snake's Web (Lines ~1225-1804)
- **Content**: Wilderness exploration around Phandalin
- **Locations**: Conyberry/Agatha's Lair, Old Owl Well, Thundertree, Wyvern Tor, Cragmaw Castle
- **Level**: 3rd level characters
- **Goal**: Find Wave Echo Cave location

### Chapter 4: Wave Echo Cave (Lines ~1804-2179) 
- **Content**: The lost mine dungeon
- **Enemies**: Undead, monsters, Nezznar the Snake
- **Level**: 4th level characters  
- **Goal**: Clear the mine, defeat the Snake

### Chapter 5: Paths of Peril (Lines ~2179-2974)
- **Content**: Return to Phandalin, psionic goblins, Zorzula's Rest
- **Enemies**: Sawplee goblins, Ruxithid the Chosen
- **Level**: 5th level characters
- **Goal**: Discover mind flayer fanatic plot

### Chapter 6: The Shattered Obelisk (Lines ~2974-4105)
- **Content**: Race for obelisk pieces in Underdark
- **Locations**: Talhundereth, Crypt of Talhund, Gibbet Crossing
- **Enemies**: Mind flayer Qunbraxel
- **Level**: 6th-8th level characters

### Chapter 7: Rifts in Reality (Lines ~4105-4970)
- **Content**: Illithinoch, ceremorphosis ritual
- **Enemies**: Mind flayer fanatics, Far Realm corruption
- **Level**: 9th-11th level characters
- **Goal**: Stop ritual, follow fanatics to Far Realm

### Chapter 8: Beyond a Lightless Star (Lines ~4970+)
- **Content**: Far Realm, Briny Maze, final confrontation
- **Enemies**: Ilvaash refraction, mind flayer fanatics  
- **Level**: 12th level characters
- **Goal**: Final ritual disruption, defeat godlet refraction

## Additional Content to Extract

### NPCs Directory
Create individual NPC files in `/npcs/` folder:
- Major NPCs (Gundren, Sildar, Glasstaff, Nezznar, etc.)
- Phandalin NPCs (organized by location/faction)
- Chapter-specific NPCs

### Encounters Directory  
Create encounter files in `/encounters/` folder:
- Organized by CR level
- Include stat blocks, tactics, scaling options
- Cross-reference with chapters

### Locations Directory
Create location files in `/locations/` folder:
- Phandalin (detailed town guide)
- Cragmaw Hideout
- Wave Echo Cave
- Underdark locations
- Far Realm locations

### Factions & Organizations
Create files in `/organizations/` folder:
- Lords' Alliance
- Order of the Gauntlet  
- Harpers
- Zhentarim
- Emerald Enclave
- Cragmaw Tribe
- Mind Flayer Fanatics

### Magic Items & Artifacts
Create files in `/magic-items/` folder:
- Shattered Obelisk pieces
- Adventure-specific items
- Faction rewards

## Repository Structure Recommendations

```
/adventures/phandelver-and-below-the-shattered-obelisk/
├── adventure-overview.md
├── chapters/
│   ├── chapter-01-dangerous-journey.md ✅
│   ├── chapter-02-trouble-in-phandalin.md ✅ 
│   ├── chapter-03-snakes-web.md
│   ├── chapter-04-wave-echo-cave.md
│   ├── chapter-05-paths-of-peril.md
│   ├── chapter-06-shattered-obelisk.md
│   ├── chapter-07-rifts-in-reality.md
│   └── chapter-08-beyond-lightless-star.md
├── locations/
│   ├── phandalin/
│   ├── cragmaw-hideout.md
│   ├── wave-echo-cave.md
│   ├── underdark/
│   └── far-realm/
├── npcs/
│   ├── major/
│   ├── phandalin/
│   ├── cragmaw/
│   └── mind-flayer-fanatics/
├── encounters/
│   ├── cr-1-2/
│   ├── cr-3-5/
│   ├── cr-6-10/
│   └── cr-11-15/
├── organizations/
├── magic-items/
└── reference/
    ├── timeline.md
    ├── far-realm-corruption.md
    └── faction-relationships.md
```

## Next Steps

1. **Continue Chapter Extraction**: Process remaining chapters 3-8 from dump file
2. **Create Location Files**: Extract detailed location descriptions
3. **Build NPC Database**: Organize all NPCs with stats and roleplay notes  
4. **Encounter Library**: Separate encounters with scaling options
5. **Cross-Reference System**: Link between chapters, NPCs, locations
6. **Session Tracking**: Templates for session notes and player handouts

## Tools for Continuation

To continue this organization process:
1. Use `read_file` with appropriate line ranges for each chapter
2. Follow the established markdown structure and frontmatter format
3. Maintain consistency with repository conventions from copilot instructions
4. Create cross-references between related files
5. Include quick reference sections for DM use at table
