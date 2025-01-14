# Smart Treadmill Project

## Overview

The Smart Treadmill project is designed to provide real-time analysis and post-workout statistics for treadmill workouts. It includes hardware integration, data processing, and a user interface for monitoring and visualizing workout data.

## Project Structure

smart_treadmill/
│
├── requirements.txt
├── config/
│   └── settings.py
├── data/
│   └── treadmill_training_data.csv
├── src/
│   ├── _init_.py
│   ├── hardware/
│   │   ├── _init_.py
│   │   ├── treadmill_controller.py
│   │   └── heart_rate_monitor.py
│   ├── analysis/
│   │   ├── _init_.py
│   │   ├── threshold_calculator.py
│   │   └── data_processor.py
│   ├── models/
│   │   ├── _init_.py
│   │   ├── user.py
│   │   └── workout_session.py
│   └── ui/
│       ├── _init_.py
│       ├── main_window.py
│       └── widgets/

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/smart_treadmill.git
    cd smart_treadmill
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Configure the settings in [settings.py](http://_vscodecontentref_/1) as needed.

2. Run the application:
    ```sh
    python main.py
    ```

3. Use the command-line arguments for additional options:
    ```sh
    python main.py --config path/to/config.json --debug --simulate
    ```

## Features

- Real-time workout data analysis
- Post-workout statistics and summaries
- Hardware integration with treadmill and heart rate monitor
- User interface for monitoring and visualizing workout data
- Data export to CSV

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

### Steps to Contribute

1. Fork the repository:
    ```sh
    git fork https://github.com/yourusername/smart_treadmill.git
    ```

2. Clone your forked repository:
    ```sh
    git clone https://github.com/yourusername/smart_treadmill.git
    cd smart_treadmill
    ```

3. Create a new branch for your feature or bugfix:
    ```sh
    git checkout -b feature-or-bugfix-name
    ```

4. Make your changes and commit them:
    ```sh
    git add .
    git commit -m "Description of the feature or bugfix"
    ```

5. Push your changes to your forked repository:
    ```sh
    git push origin feature-or-bugfix-name
    ```

6. Open a pull request on the original repository.

### Abstract

Using treadmill and cycle ergometers are the best methods of endurance training and choosing best training intensity is very crucial in endurance exercise training. According to more than one decade of our research experiences, it is possible to determine optimum personal training intensity based on estimation of person's anaerobic threshold. A hardware and software has been developed to monitor the heart rate and control the treadmill speed and slope. Software provided utilities to record the individual information (e.g. name, age, gender, weight and maximum and resting heart rate) and graphical curves of treadmill (speed, slope, work, power) and real-time heart rate. In this method, heart rate was used to draw the heart rate-time curve during an exhaustive graded maximal intensity exercise to find the best treadmill speed and slope in his/her anaerobic threshold. In this study, ten male athletes (19.3±1.7 years; 88.50±4.43 kg; 182.0±3.7 cm) recruited. Validity and reliability of this method have been evaluated by gas analysis every 5 seconds to determine anaerobic...