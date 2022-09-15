## CapRover-nginx

**Using nginx on CapRover (minimal configuration)**

You can publish static files using nginx.
CapRover uses nginx, but don't edit its Configfile. Because it destroys the CapRover! (Unfortunately that is the report seen in the CapRover discussion) Add this app instead.

- [CapRover](https://caprover.com/)
- [nginx](https://nginx.org/)

## Usage

1. Open your CapRover website and create an App with Create A New App.
2. Clone this repository.
3. Edit `index.html` in `public/`. Add other files if needed.
4. Run `caprover deploy`. Please follow the display.
