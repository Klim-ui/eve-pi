# EVE Online - Gallente Control Tower Small Assembly Project

## 🎯 Project Goal
Assemble **Gallente Control Tower Small** by manufacturing all required components via Planetary Interaction.

## 📦 Final Product
- **Gallente Control Tower Small**
  - Base Price: ~125M ISK
  - Assembly Time: 6:50:00
  - Command Center Level Required: 5

## 📋 Required Components (8 types)

### Planetary Materials (T3)
1. **4x Broadcast Node** - Core processing unit
2. **9x Integrity Response Drones** - Defense system
3. **7x Nano-Factory** - Advanced factory blueprint
4. **7x Organic Mortar Applicators** - Structural component
5. **4x Recursive Computing Module** - Processing logic
6. **4x Self-Harmonizing Power Core** - Power system
7. **7x Sterile Conduits** - Data transfer
8. **4x Wetware Mainframe** - Main processor

### Capital Components
- **2x Capital Construction Parts** - Heavy structural elements

## 🪐 Planet Types Needed

### Lava Planets
- **Raw Materials**: Silicon, Fernite Alloy, Super Conductors
- **Advantage**: Multiple valuable minerals on same planet type
- **Setup**: 1-2 Lava planets for maximum efficiency

### Barren/Temperate Planets
- **Raw Materials**: Carbon Compounds, Reactive Metals, Biofuels
- **Setup**: 1-2 planets for T1 components

### Storm Planets
- **Raw Materials**: Electrolytes, Plasmoids
- **Optional**: Can substitute with Lava if needed

## 🏭 Production Infrastructure

### Per Planet Setup
```
Command Center (Level 5)
├─ 4x Extractors (16-hour cycle) → Raw Materials
├─ 1x Basic Industry Facility → P1 Components
├─ 1x Advanced Industry Facility → P2 Components
└─ 1x Launchpad → Storage/Export
```

### Timeline
- **Setup Time**: 2-3 days (building infrastructure)
- **Production Cycles**: 3-4 weeks (depending on volume)
- **Per Component**: ~8-16 hours per cycle

## 📊 Resource Flow

```
RAW MATERIALS (T0)
↓
BASIC INDUSTRY (T1 Components)
├─ Silicon → Silicon Wafers
├─ Carbon Compounds + Reactive Metals → Polyaramids
├─ Fernite Alloy + Super Conductors → Metallic Alloys
└─ [Other raw materials]
↓
ADVANCED INDUSTRY (T2/T3 Components)
├─ T1 Materials → T2 Components
│  ├─ Nanotransistors
│  ├─ Plasmonic Circuits
│  └─ [Other T2]
└─ T2 Materials → T3 Components (8 types listed above)
↓
BROADCAST NODE & OTHER T3 COMPONENTS (Ready for Assembly)
↓
MANUFACTURING STATION (6:50:00)
↓
GALLENTE CONTROL TOWER SMALL ✅
```

## 💰 Budget Estimate

| Item | Quantity | Est. Cost/Unit | Total |
|------|----------|----------------|-------|
| Command Centers | 2 | 5M | 10M |
| Extractors | 8 | 1M | 8M |
| Industry Facilities | 4 | 3M | 12M |
| Launchpads | 2 | 2M | 4M |
| **Infrastructure Total** | | | **34M** |
| T1 Materials Purchase | Various | Varies | ~20M |
| T2 Components (if buying) | Various | Varies | ~30M |
| **Operating Total** | | | **80M+** |

## 📝 Next Steps

1. ✅ **Resource Mapping** - See `resources_required.csv`
2. ✅ **Production Chains** - See `production_chains.md`
3. 🔄 **Planet Selection** - Choose 2-4 planets
4. 🔨 **Infrastructure Build** - Deploy facilities
5. ⚙️ **Route Setup** - Configure extraction → processing → storage
6. 🎯 **Production Start** - Begin material processing
7. 📦 **Component Assembly** - Combine T1 → T2 → T3
8. 🚀 **Tower Assembly** - Final manufacturing at station

## 📂 File Structure

```
eve-pi/
├── README.md (this file)
├── control_tower_blueprint.json
├── resources_required.csv
├── production_chains.md
└── planet_setups/
    ├── lava_planet_setup.json
    ├── barren_planet_setup.json
    └── temperate_planet_setup.json
```

## 🎮 Game Notes

- **Campaign**: ~3-4 weeks of active PI management
- **Skill Requirements**: Industry V, appropriate Production skills
- **Location**: Jita region (The Forge)
- **Final Deployment**: Low-Sec (0.7 or lower required for tower placement)

---

**Last Updated**: 2026-05-04
**Author**: Klim-ui
**Status**: 🚀 Ready to Deploy
