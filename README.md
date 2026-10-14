# Ride Camera
Ride Camera is a client-side Minecraft Forge mod that automatically points your view in the direction of travel on custom roller coasters and vehicles. It provides smooth rotation, independent mouse look, automatic ride detection, and configurable camera behavior without moving the player or sending custom network data. Designed for Minecraft Java Edition 1.12.2.

## Controls

- `V`: manually enable or disable Ride Camera.
- Mouse: look freely relative to the ride's direction, including backward-facing seats.
- `B`: recenter the mouse-look offset.
- `O`: open quick settings and detailed tuning controls.
- `N`: show or hide diagnostic information.

All keys can be reassigned through Minecraft's Controls screen.

## Default behavior

- Automatically enables after mounting a detected armor-stand ride vehicle.
- Waits through brief vehicle swaps before automatically disabling.
- Follows horizontal turns, climbs, and drops.
- Holds the last known camera direction during missing movement updates.
- Uses unrestricted horizontal mouse look.
- Changes only camera rotation and never moves the player or camera position.
- Hides diagnostics until requested.

## Limitations

- Server or network pauses can still freeze the actual ride vehicle.
- Automatic activation currently detects armor-stand vehicles. Use `V` on unsupported vehicles.
- Trackless Rides do not produce good smooth motion due to position not matching vehicle orientation.
  A future fix is being investigated. For now, it is recommended to turn the ride camera off (v).
- Camera roll and true inversion through coaster loops are not supported.

Check a server's rules before using client-side mods there.

## Release 0.4.0

This is the first public Ride Camera release for Minecraft 1.12.2.                                                   
