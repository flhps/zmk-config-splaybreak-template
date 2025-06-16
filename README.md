# ZMK Firmware Template for the SplayBreak Split Keyboard

You can find the keyboard files [here](https://github.com/flhps/splaybreak-keyboard).

## Layout Language

This comes pre-loaded with my personal long-term layout. Out of habit I configured it to output keycodes for a German keyboard layout. If you want to change the output language to the default American English, remove the `config/keys_de.h` file and remove its import at the top of `config/splaybreak.keymap`. Then replace the keycodes to ones without the `DE_` prefix. You can do that last step with the recommended setup below.

## Recommended Setup

1. Create your own repository based on this template.
2. Use this [online keymap editor](https://nickcoutsos.github.io/keymap-editor/) and give it access to your firmware repository.
3. Adjust the keymap to your liking and press "Save" to have the editor commit to your repo.
4. After a minute, the GitHub action has rebuilt the firmware which can also be downloaded with the blue button in the editor.
5. Connect each keyboard side to your computer, double-press the reset button, and move the corresponding `utf2` file to the controller, which appears as a storage medium.
