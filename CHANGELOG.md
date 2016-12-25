# Changelog

## 1.5.0 - 2016-12-25

- Add bboxToCenter & hash function
- Enforce strict [number, number] instead of number[]

## 1.4.0 - 2016-12-4

- Replace test tools for Jest
- Added Circle CI testing

## 1.3.5 - 2016-10-25

Reduce library size by 430% (350KB to 80KB)

## 1.3.1 - 2016-10-14

- Update typings to allow `number[]`
- Enforcing validation with `validateLngLat`, `validateMeters` & `validateTile`
- Reviewed entire documentation
- Dropped zoom `@param` from functions with only LatLng & Meters.

```javascript
lngLatToMeters([lng, lat, zoom])
// Changed to
lngLatToMeters([lng, lat])

metersToLngLat([x, y, zoom])
// Changed to
metersToLngLat([x, y])
```

## 1.2.0 - 2016-10-13

Added new features:

- `grid` - Creates an Iterator of Tiles from a given BBox
- `gridBulk` - Creates a bulk Iterator of Tiles from a given BBox
- `gridLevels` - Creates a grid level pattern of arrays
- `gridCount` - Counts the total amount of tiles from a given BBox

## 1.1.0 - 2016-10-03

- Remove Default export
- Modules compiles only to ES6

## 1.0.0 - 2016-10-01

First Stable release was created