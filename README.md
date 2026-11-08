# Ride City

**Ride City** is a small 3D open-world city game by Niyal Rahaman. Start at home, explore the streets on foot, and drive or ride around the city. The game includes traffic, pedestrians, day and night lighting, and keyboard and touch controls.

## Play

- **Live game:** [ridecity.netlify.app](https://ridecity.netlify.app/)
- **GitHub repository:** [Niyal779/Ride-City](https://github.com/Niyal779/Ride-City)
- **Developer:** [Niyal](https://niyal.netlify.app/)

## Features

- 3D city with roads, buildings, parks, trees, street lamps, and traffic lights
- Walk around and explore on foot
- Ride motorcycles and drive cars and buses
- Spawn and drive a tank or helicopter
- Pedestrians walking around the city
- On-foot shooting and tank shells, with hit reactions for pedestrians and vehicles
- Day/night lighting and city ambience
- Responsive layout with mobile touch controls

## Controls

### On foot

| Key | Action |
| --- | --- |
| `W` / `A` / `S` / `D` | Move and turn |
| `Shift` | Run |
| `Space` | Jump |
| `P` | Fire |
| `Enter` | Close melee hit |
| `E` | Enter a nearby vehicle or use the home door |
| `F` | Enter a nearby vehicle |
| `B` | Call your bike |
| `H` | Spawn a helicopter |
| `T` | Spawn a tank |
| `C` | Change camera |

### Vehicles

- Use `W` / `S` to move and `A` / `D` to steer.
- Press `E` or `F` to exit.
- On a bike, `Shift` boosts and `Space` is the handbrake.
- In the helicopter, hold `W` to climb and fly forward; use `S` to descend and `A` / `D` to turn. `Shift` adds speed.
- In the tank, hold `Space` to fire shells.
- Tank shells can destroy cars, bikes, and buses. Vehicle impacts remove the whole vehicle and its collision entry so leftover wheels do not block the road.

### Mobile

Use the on-screen movement stick to walk or steer, and drag the camera area to look around. Tap the action controls for riding, boosting, camera, and other available actions.

## Run locally

The game is a static web project and does not need a build step. With XAMPP, place or clone the repository inside `htdocs`, start Apache, then open the project folder through `http://localhost/` in a browser. The project also uses a local `three.min.js` file.

## Deploy

The included `netlify.toml` sets `netlify-site` as the Netlify publish directory. Deploy the repository to Netlify with this configuration, or connect the GitHub repository to a Netlify site.

## Tech

- HTML
- CSS
- JavaScript
- Three.js

---

Made by **Niyal Rahaman** · [niyal.netlify.app](https://niyal.netlify.app/)
