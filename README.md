# YourEyez: An AI-powered vision aid

YourEyez is a groundbreaking project designed to empower the visually impaired with an intuitive and intelligent understanding of their surroundings. By leveraging cutting-edge AI technologies such as object detection and advanced computer vision, we aim to provide real-time audio feedback that paints a vivid picture of the environment.

## Core Technologies

- **Object detection with YOLOv7**: Accurately identifies and tracks objects in real-time, providing crucial information about obstacles and points of interest.
- **Computer vision with GPT-4 Vision**: Delivers insightful and contextual descriptions of the scene, capturing details that go beyond simple object recognition.
- **Audio generation with Deepgram**: Converts text into natural-sounding speech using advanced text-to-speech technology.

## Local Development Setup

**1. Clone the repository:**

```bash
git clone https://github.com/abdularif0705/youreyez.git
```

**2. Install dependencies:**

```bash
pnpm install
```

**3. Set up environment variables:**

Create a .env.local file in the root directory and add the following variables:

```
OPENAI_API_KEY=your_openai_api_key
DEEPGRAM_API_KEY=your_deepgram_api_key
CLERK_API_KEY=your_clerk_api_key
CLERK_FRONTEND_API=your_clerk_frontend_api
```

**4. Run the development server:**

```bash
pnpm dev
```

**5. Access the application:**

Open http://localhost:3000 in your browser.

## Usage

**1. Sign in/Sign up:** Users need to authenticate with Clerk to access the application.

**2. Start the app:** Press the "Start" button to initiate object detection and scene description.

**3. Audio feedback:** The app will announce detected objects and provide contextual descriptions of the scene.

**4. Manual trigger:** Swipe up to manually request a scene description.

**5. Mute irrelevant phrases:** Swipe down to mute audio feedback for specific phrases.

## Features

- **Real-time object detection**: Identifies and announces objects like people, furniture, vehicles, and potential hazards.
- **Contextual scene descriptions**: Provides rich narratives about the surrounding environment, including details such as the layout, atmosphere, and activities taking place.
- **Customizable audio feedback**: Users can adjust the volume, voice, and frequency of audio cues to personalize their experience.
- **Intuitive interface**: Easy-to-use gestures allow for seamless interaction and control over the app's functionalities.

## Benefits

- **Enhanced independence and mobility**: Enables users to navigate their environment with greater confidence and safety.
- **Improved situational awareness**: Provides a deeper understanding of the surroundings, fostering a sense of connection and engagement with the world.
- **Greater accessibility**: Opens up new possibilities for visually impaired individuals to participate in activities and experiences they may have previously found challenging.

## Future Development

- **Integration with other sensors**: Incorporate data from additional sensors like LiDAR or depth cameras to create a more comprehensive understanding of the environment.
- **Offline capabilities**: Enable users to access core features even without an internet connection.
- **Multilingual support**: Expand language options for audio feedback to cater to a wider audience.
- **Open-source development**: Foster community involvement and collaboration to further enhance the app's capabilities.

We are excited about the possibilities that YourEyez holds and are committed to its continued development and improvement.

Join us in building a future where everyone can see the world YourEyez.
