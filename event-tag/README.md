# Interactive 3D Event Tag

An interactive 3D event tag/name badge created with React, Three.js, and React Three Fiber. The tag features realistic physics using Rapier physics engine. This project is based on the Vercel 3D event tag design and implementation.

## Features

- 3D interactive name badge with realistic physics
- Grab and drag interaction with natural movement
- Realistic band simulation using rope joints
- Physical properties including gravity, damping, and collisions
- Beautiful lighting and environment mapping

## Technologies Used

- React
- Three.js
- React Three Fiber (@react-three/fiber)
- Drei helpers (@react-three/drei)
- Rapier physics engine (@react-three/rapier)
- MeshLine for the band rendering

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone this repository
   ```bash
   git clone <repository-url>
   cd event-tag
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn
   ```

3. Start the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Usage

- **Drag the tag**: Click and drag to move the name tag around
- **Physics interaction**: The tag will swing naturally when dragged and released
- **Debug mode**: Toggle the debug option in the controls panel to visualize physics bodies

## Customization

You can customize the appearance by:

1. Replacing the texture image for the card
2. Adjusting physics parameters in the `Band` component
3. Modifying lighting in the `Environment` component
4. Changing the band properties in the `MeshLineMaterial`

## Credits

Based on the Vercel 3D event tag implementation. Created using models and textures from Vercel. Physics simulation powered by Rapier.
