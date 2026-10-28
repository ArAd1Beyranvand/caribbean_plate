FREE PALESTINE 🇮🇷🇵🇸 پاینده ایران

GO VEGAN 🌱

==================================

# caribbean_plate

Licence plates for caribbean members, for the plate_core library.

## Install

```yaml
dependencies:
  plate_core: ^0.12.0
  caribbean_plate: ^0.1.0
```

## Use

```dart
import 'package:plate_core/plate_core.dart';
import 'package:caribbean_plate/caribbean_plate.dart';

PlateCanvas(
  spec: AnguillaPlates.private,
  theme: AnguillaThemes.standard,
  validator: const AnguillaValidator(),
  autoValidate: true,
  onChooseCharacter: noCharacterChooser,
);
```

## Contains

- `AnguillaPlates` — 1 plate spec: `private`.
- `BermudaPlates` — 3 plate specs: `private`, `prefixed`, `suffixed`.
- `BonairePlates` — 4 plate specs: `bonaire`, `blue`, `statia`, `saba`.
- `BritishVirginIslandsPlates` — 4 plate specs: `private`, `government`, `commercial`, `taxi`.
- `CaymanIslandsPlates` — 3 plate specs: `pair`, `taxi`, `single`.
- `CollectivityOfSaintMartinPlates` — 1 plate spec: `private`.
- `MontserratPlates` — 1 plate spec: `private`.
- `SabaIslandPlates` — 2 plate specs: `current`, `classic1978`.
- `SintEustatiusPlates` — 2 plate specs: `statia`, `bicentennial`.
- `SintMaartenPlates` — 1 plate spec: `private`.
- `TurksAndCaicosIslandsPlates` — 3 plate specs: `modern`, `prefixed`, `selfDrive`.
- 2 bundled assets (``, ``).

Each also ships its `…Country` panel, `…Themes` and, where one exists, an advisory `…Validator`.

## Part of plate

Painted by [`plate_core`](https://pub.dev/packages/plate_core); alphabets shared through [`plate_alphabet`](https://pub.dev/packages/plate_alphabet); optional character picker in [`plate_keypad`](https://pub.dev/packages/plate_keypad).

