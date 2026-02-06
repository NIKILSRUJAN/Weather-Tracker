# Go Weather Tracker

A command-line interface (CLI) tool written in Go that fetches real-time weather data using the OpenWeatherMap API.

## Features
* **Real-time Data:** Fetches current weather conditions for specified locations.
* **API Integration:** Demonstrates how to consume RESTful APIs in Go.
* **Secure Configuration:** Keeps API keys separate from the codebase.

## Getting Started

### Prerequisites
* [Go](https://go.dev/dl/) installed on your machine.
* An API Key from [OpenWeatherMap](https://openweathermap.org/api).

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YOUR-USERNAME/weather-project.git](https://github.com/YOUR-USERNAME/weather-project.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd weather-project
    ```

### Configuration (Important!)

Since API keys should never be shared, the configuration file is not included in the repository. You must create it manually.

1.  Create a file named `.apiConfig` in the root directory.
2.  Add your OpenWeatherMap API key in JSON format:

    ```json
    {
      "OpenWeatherMapApiKey": "YOUR_API_KEY_HERE"
    }
    ```
    *(Note: Ensure the JSON key matches what is expected in `main.go`)*

### Usage

Run the program using:

```bash
go run main.go
