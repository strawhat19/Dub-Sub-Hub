# Dub Sub Hub logo concepts — v6

These concepts refine the [wide](../v5/01-orange-relay-wordmark.svg) and [stacked](../v5/02-stacked-relay-pill.svg) orange gradient pills. All retain the left dialogue relay and a flat white Hub tile. Their palette contains only oranges and white: the original gradient `#FF8744` → `#FF5C35` → `#EF4530`, deeper orange `#D94B27`, Hub orange `#EE4C2C`, and white `#FFFFFF`.

| File | Spacing approach | Suggested use |
| --- | --- | --- |
| `01-even-wide-orange.svg` | Dub, Sub, and Hub each occupy a 205-unit text span, with an exact 75-unit horizontal gap between words. | Wide header or video slate. |
| `02-even-stacked-orange.svg` | All three words share a 230-unit width and align left; their baselines are exactly 134 units apart. | Compact launch screen or vertical badge. |
| `03-balanced-two-row-orange.svg` | Preserves the original Dub/Sub top row and centered Hub below. All words share a 220-unit width and 116-unit font size; horizontal and nominal vertical text-box gutters are 48 units. | A close refinement of the v5 compact layout. |

The word widths are set with SVG `textLength` to control layout spacing across font fallbacks. Font bearings can still affect optical spacing. The white Hub tiles have no shadow. All files remain editable SVGs.
