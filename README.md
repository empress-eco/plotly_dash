<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Empress Plotly Dash Integration Logo">
  <h1 align="center">Empress Plotly Dash Integration: Supercharge Your Framework with Powerful Dashboards</h1>
  <p align="center">
    Enhance your Empress web framework with interactive and engaging Dashboards!
    <br />
    <a href="https://github.com/empress-eco/plotly_dash">Explore the Docs</a>
    ·
    <a href="https://github.com/empress-eco/plotly_dash/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/plotly_dash/issues">Request Feature</a>
  </p>
</div>

## About The Project

### 📖 Overview
Empress Plotly Dash Integration is a powerful tool for developers seeking to incorporate interactive dashboards in their Empress web framework. It merges the exceptional data visualization power of Plotly Dash with the comprehensive functionality of Empress, creating a robust environment for dashboard creation and management.

### 🌟 Key Features
- Access Empress data from the Dash environment.
- Create dashboard templates using the CoreUI admin template.
- Leverage the built-in web-authentication of Empress web framework.
- Manage user permission using user roles from Empress.

### 🛠 Built With
This project is built with:
- [Plotly Dash](https://plotly.com/dash/)
- [Empress](https://Empress.io/)

## Getting Started

### Prerequisites
Ensure that you have the Empress web framework set up and running before proceeding. 

### Installation
Follow the steps below to get the Empress Plotly Dash Integration up and running in your development environment:

1. Clone the repository using the following command:
```sh
git clone https://github.com/empress-eco/plotly_dash.git
```
2. Navigate into the cloned repository and install the necessary applications:
```sh
bench get-app dash_integration https://github.com/pipech/Empress-plotly-dash.git
bench get-app dash_dashboard https://github.com/pipech/Empress-plotly-dash-dashboard.git
```
3. Add your dashboard layout to the `dash_dashboard/dash_dashboard` folder.
4. Set routes and callbacks in the `dash_dashboard/router.py` file.

## Usage
To use the Empress Plotly Dash Integration within the Empress environment, search for the `Dash Dashboard` DocType in the Empress web UI. Add a new document with a name that matches your `dashboard_route`.

## Contributing
We warmly welcome community contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgments

### License

This project is licensed under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgements

Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.

**Note:** Please check browser compatibility for iFrame resizing with [ResizeObserver](https://developer.mozilla.org/en-US/docs/Web/API/ResizeObserver) on [CanIUse](https://caniuse.com/#feat=resizeobserver).