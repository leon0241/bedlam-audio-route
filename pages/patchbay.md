## Various Set-ups for the Patch Bay

### Prerequisite info:
- [Equipment List](equipment-list.md)
- Model of the PatchBay is the Neutrik NYS-SPP-L1

### How To Read the diagrams
- **Patch In** Refers to the top row (A), and is where the inputs are sent in
- **Patch Out** Refers to the bottom Row (B), and is what output an input gets routed to
- **Use** columns are purely referential, if you want to set up stuff then just connect input - output in each row and it should work out of the box

[Image of the Patchbay](../images/patchbay-image.jpg)

### X32 with individually controlled channels

How to set up:
| Use | Input | Output | Use |
| - | - | - | - |
| X32 XLR Out 16 | 16 | 10 | Speaker Router R | 
| X32 XLR Out 15 | 15 | 9 | Speaker Router L |
| X32 XLR Out 14 | 14 | 8 | Tech Box R |
| X32 XLR Out 13 | 13 | 7 | Tech Box L |
| X32 XLR Out 12 | 12 | 6 | Subwoofer R |
| X32 XLR Out 11 | 11 | 5 | Subwoofer L |
| X32 XLR Out 10 | 10 | 4 | Near Speaker R |
| X32 XLR Out 9 | 9 | 3 | Near Speaker L |
| Speaker Router Out 1 | 2 | 2 | Far Speaker R |
| Speaker Router Out 2 | 1 | 1 | Far Speaker L |

![Patchbay - X32 with individual channels](../images/patchbay-1.svg)

### X32 with a combined mix sent to all speakers

How to set up:
| Use | Input | Output | Use |
| - | - | - | - |
| X32 XLR Out 16 | 16 | 10 | Speaker Router R | 
| X32 XLR Out 15 | 15 | 9 | Speaker Router L |
| X32 XLR Out 14 | 14 | 8 | Tech Box R |
| X32 XLR Out 13 | 13 | 7 | Tech Box L |
| Speaker Router Out 6 | 6 | 6 | Subwoofer R |
| Speaker Router Out 5 | 5 | 5 | Subwoofer L |
| Speaker Router Out 4 | 4 | 4 | Near Speaker R |
| Speaker Router Out 3 | 3 | 3 | Near Speaker L |
| Speaker Router Out 2 | 2 | 2 | Far Speaker R |
| Speaker Router Out 1 | 1 | 1 | Far Speaker L |

![Patchbay - X32 with combined channels](../images/patchbay-2.svg)

### Combined mix sent to all speakers - Any mixer

How to set up:
| Use | Input | Output | Use |
| - | - | - | - |
| Output R | 16 | 10 | Speaker Router R | 
| Output L | 15 | 9 | Speaker Router L |
| (Optional) Mini Mixer R | 14 | 8 | Tech Box R |
| (Optional) Mini Mixer L | 13 | 7 | Tech Box L |
| Speaker Router Out 6 | 6 | 6 | Subwoofer R |
| Speaker Router Out 5 | 5 | 5 | Subwoofer L |
| Speaker Router Out 4 | 4 | 4 | Near Speaker R |
| Speaker Router Out 3 | 3 | 3 | Near Speaker L |
| Speaker Router Out 2 | 2 | 2 | Far Speaker R |
| Speaker Router Out 1 | 1 | 1 | Far Speaker L |

Note: Mini mixernot required, but if you want tech box speakers to be in use, then use it exclusively for setting up the L/R relay microphones, optionally route aux to mini mixer to get it in the tech box as well

![Patchbay - mixer with combined channels](../images/patchbay-3.svg)
### Individually controlled channels using the Motu 828mkii

How to set up:
| Use | Input | Output | Use |
| - | - | - | - |
| (Optional) Mini Mixer R | 14 | 8 | Tech Box R |
| (Optional) Mini Mixer L | 13 | 7 | Tech Box L |
| Motu 828mkii Out 6 | 22 | 6 | Subwoofer R |
| Motu 828mkii Out 5 | 21 | 5 | Subwoofer L |
| Motu 828mkii Out 4 | 20 | 4 | Near Speaker R |
| Motu 828mkii Out 3 | 19 | 3 | Near Speaker L |
| Motu 828mkii Out 2 | 18 | 2 | Far Speaker R |
| Motu 828mkii Out 1 | 17 | 1 | Far Speaker L |

Note: mini mixer not required, but if you want tech box speakers to be in use, then use it exclusively for setting up the L/R relay microphones, optionally route aux to mini mixer to get it in the tech box as well

![Patchbay - Motu 828mkii with individual channels](../images/patchbay-4.svg)

