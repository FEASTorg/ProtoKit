# ProtoKit

ProtoKit is an open-source collection of protoboards, stripboards, expansion boards, and layout boards with configured footprints and trace routing. Designed in KiCad to support rapid electronics prototyping and customization.

## Ordering Resources

- [JLC - The Ultimate Guide to PCB Panelization: Tools and Techniques](https://jlcpcb.com/blog/the-ultimate-guide-to-pcb-panelization:-tools-and-techniques)
- [JLC - Technical Guidance: V-Cut Panelization Standards](https://jlcpcb.com/blog/technical-guidance-v-cut-panelization-standards)

## Footprints

This repository includes standalone KiCad footprint libraries used throughout the ProtoKit boards. You can either:

- Reference them directly by adding your local copy of this repository to your global KiCad footprint library table
- Or copy the `.pretty` folders into your local KiCad library directory (note: copied versions will not receive updates unless you manually sync or re-clone the repository)

### Libraries

- `Proto.pretty` – Core library for general protoboard and stripboard footprints
- `Proto-Matrix.pretty` – Specialized footprints for designing matrix-style pad-per-hole protoboards

These libraries are intended to be reusable for your own prototyping PCB designs.

## References & Acknowledgements

- [github.com/mikespook/KiCAD-prototype-boards](https://github.com/mikespook/KiCAD-prototype-boards)
