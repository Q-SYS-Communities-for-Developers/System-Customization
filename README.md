# System Customization Tutorial File

This tutorial demonstrates methods for creating a set of controls that can be adjusted in the field to account for minor room variations. A room controls script handles system automation. The user selects which components should be controlled and makes per-room adjustments (motion sensor timeout, etc). A UCI text helper script takes in a .json string and populates panel text. Using a combo box, anyone using the room can switch the panel to their preferred language.

There are 3 UCIs in this file. The layouts are identical, but the underlying controls vary. The first UCI uses control pins for nearly everything ("no code"). The other two UCIs use scripting for controls. The second UCI uses component controls for room and text controls. The third UCI takes it a step further and incorporates script notifications.

## Getting Started

- See the "01 - Instructions" schematic pages of the design files for instructions on how to use this file
- Schematic Page "02 - Room Controls" has a helper script that manages system automations. Buttons for power on, power off privacy, etc can be placed on a UCI. Select which components to be controlled using drop down menus.
- Schematic Page "03 - System Components" contains basic components to be controlled by the room controller.
- Schematic Page "04 - UCI Text" has a helper script that updates panel text using a .JSON string to populate all values.
- Schematic Page "05 - UCI Controls" has the logic blocks for the "no code" UCI as well as controls to automate the notification subscriptions for UCI three.
- Schematic Page "06 - Programming Challenge" has a four-step programming challenge.

### Dependencies

- [Q-SYS Designer](https://www.qsys.com/resources/software-and-firmware/q-sys-designer-software/) version 9.12 or greater

## Help

If you have any questions or comments about this file, please go to [developers.qsc.com](https://developers.qsc.com)

## Author(s)

- Hope Roth [@qsc-hoperoth](https://github.com/qsc-hoperoth)

## Version History

- 1.0
  - Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

- Thank you Eugene Dunn III [@qsc-eugene](https://github.com/qsc-eugene) as always, for the QA support!
- Thank you to Jonathan Moore [@qsc-jonathanmoore](https://github.com/qsc-jonathanmoore) for the user testing and feedback
- Thank you to Curtis Harnish for the user testing and feedback
- Thank you to Thomas Bauer [@qsc-thomasbauer](https://github.com/qsc-thomasbauer) for the user testing and feedback, plus German translation
- Thank you to Luis Pena [@qsc-luispena](https://github.com/qsc-luispena) for Spanish and Portugese translation
- Thank you to Sam Zhao [@qsc-samzhao](https://github.com/qsc-samzhao)for the Chinese translation
- Thank you to Adrien Avellan [@qsc-adrienavellan](https://github.com/qsc-adrienavellan)for fixing my terrible French grammar
