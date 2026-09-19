# photorestor

- Changes resistance based on light level

## schema

       +5V
        │
        │
      ┌─┴─┐
      │ Ф │   фоторезистор
      │ о │
      │ т │
      └─┬─┘
        │
        ├──────────► A0 (вход АЦП, почти не потребляет ток) (analog read)
        │
      ┌─┴─┐
      │10к│   резистор
      └─┬─┘
        │
       GND