# Packed Circles

ES6 d3.js packed circles visualization.


## Style

Style is expected to be addressed via css. The top-level svg is assigned a class `lgv-packed-circles`. Any style not met by the visualization module is expected to be added by the importing component.

## Environment Variables

The following values can be set via environment or passed into the class for a given visualization.

| Name | Type | Description |
| :-- | :-- | :-- |
| `DIMENSION_HEIGHT` | integer | height of artboard |
| `DIMENSION_WIDTH` | integer | width of artboard |
| `LAYOUT_PADDING_CIRCLES` | integer | space between circles |
| `PARSE_DELIMETER` | string | separator on source data hierarchy path value |

## Install

```bash
# install package
npm install @lgv/visualization
```

## PackedCircles

### Data Format

The following values are the expected input data structure for a given visualization.

### Quickstart

```bash
// initialize
const pc = new PackedCircles(data);

// render visualization
pc.render(document.body);
```
