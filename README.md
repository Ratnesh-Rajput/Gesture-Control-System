# Gesture controller:

This project uses the Python OpenCV module to detect hand gestures. By using computer vision techniques, the program captures the movements of the user's hand (& ***proposed:*** translates them into corresponding actions in the game), after that it translates those actions to direction keys(***WASD***). 



## Installation

Run the following command:
```sh
pip install -r requirements.txt
```
If a error involving mediapipes pops, solve it via running this command:
```
py -m pip install mediapipe
```

## Usage

#### Using PC camera:
- Run `python main-pc-cam.py`


And put your hand in front of the Camera to provide directions (previewed in the console), which when integrated can be used to control motion virtually! 🚗

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
