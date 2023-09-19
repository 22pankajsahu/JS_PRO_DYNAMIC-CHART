# JS_PRO_DYNAMIC-CHART


# Real-Time Chart

A simple web application that displays a real-time chart using Chart.js. The chart updates with random data at regular intervals.

## Table of Contents

- [Demo](#demo)
- [Screenshots](#screenshots)
- [Features](#features)
- [How it Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Demo

You can check out the live demo of the Real-Time Chart [here](https://22pankajsahu.github.io/JS_PRO_DYNAMIC-CHART/).

## Screenshots
![Screenshot 1](https://github.com/22pankajsahu/JS_PRO_DYNAMIC-CHART/assets/135128502/6fbae8f8-40ff-43d4-91a2-1cf6c89d4964)
![Screenshot 2](https://github.com/22pankajsahu/JS_PRO_DYNAMIC-CHART/assets/135128502/24001bc1-db63-4d6e-b184-53e7ac907bf6)

## Features

- Displays a real-time line chart.
- Updates the chart with random data every second.
- Easy-to-use and visually appealing.

## How it Works

The Real-Time Chart web application is built using HTML, CSS, and Chart.js. Here's how it works:

### HTML Structure

The HTML structure defines the elements that make up the Real-Time Chart:

- A `canvas` element with the ID `realTimeChart` to render the chart.

### CSS Styling

The CSS styles define the appearance of the chart and ensure it is responsive:

- The `canvas` element is styled to be responsive and fit within its container.

### JavaScript Functionality

The JavaScript code initializes Chart.js, creates an empty chart, and updates it with random data at regular intervals. Here's a brief overview:

- The `ctx` variable gets the 2D rendering context of the `realTimeChart` canvas.
- Initial data for the chart is defined with empty labels and a dataset.
- The chart's configuration is specified, including the type (line chart) and options.
- The chart is created using `new Chart(ctx, chartConfig)`.
- The `addData` function generates random data and updates the chart.
- Data is added to the chart at regular intervals using `setInterval`.

## Installation

To run the Real-Time Chart web application locally, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone [https://github.com/22pankajsahu/JS_PRO_DYNAMIC-CHART.git]
```

2. Open the project folder in your code editor.

## Usage

1. Open the `index.html` file in a web browser.

2. You will see a real-time line chart that updates every second with random data.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository to your own GitHub account.

2. Create a new branch for your feature:

```bash
git checkout -b feature/new-feature
```

3. Make your changes and commit them:

```bash
git commit -m "Add new feature"
```

4. Push your changes to your forked repository:

```bash
git push origin feature/new-feature
```

5. Open a pull request to the original repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

- Name: [PANKAJ SAHU](https://linkedin.com/in/22pankajsahu-)
- Email: [22pankajsahu@gmail.com](mailto:22pankajsahu@gmail.com)
- GitHub: [22pankajsahu](https://github.com/22pankajsahu)
