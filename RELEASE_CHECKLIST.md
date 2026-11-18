# Hardware release checklist

- [ ] Replace archived native design files with the actual latest Altium revision.
- [ ] Rebuild the project with relative paths to its six schematic sheets and one PCB.
- [ ] Add the relevant `.SchLib`, `.PcbLib` and manufacturer STEP sources with portable references; respect redistributable licenses.
- [ ] Export high-resolution real Altium PCB top, bottom, 3D, layer stack and ground-plane images.
- [ ] Export `06_System_Overview` schematic and replace low-resolution previews if desired.
- [ ] Rerun project validation and reconcile electrical warnings.
- [ ] Run fresh DRC on the exact committed PCB and upload the matching report.
- [ ] Check BLE antenna keepout, buck-boost loop and LDO voltage headroom.
- [ ] Verify patient interface, current limiting, protection and isolation plan before human contact.
- [ ] Open a fresh clone on another machine and verify PCB 3D geometry and all library dependencies.
- [ ] Verify document labels / component values and DNP population.
- [ ] Never claim fabrication, testing, firmware or medical certification without evidence.
