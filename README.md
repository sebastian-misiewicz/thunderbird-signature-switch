# thunderbird-signature-switch

This is a modified code of https://addons.mozilla.org/pl/thunderbird/addon/signature-switch/. The aim was to move the signature from the bottom of the message to the top. I have removed the `--` as well.

## Building

1. Pack the contents of the `chrome/signatureswitch` into `chrome/signatureswitch.jar`.
2. Pack everything into a file with `.xpi` extension (eg. `signature-switch.xpi`).

## Installation

Drag&drop the XPI file into the Thunderbird.
