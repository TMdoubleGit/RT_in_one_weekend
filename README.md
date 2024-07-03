# Ray Tracing in One Weekend

Welcome to the "Ray Tracing in One Weekend" project! This project is an implementation of the basic ray tracer described in the book ["Ray Tracing in One Weekend" by Peter Shirley](https://raytracing.github.io/books/RayTracingInOneWeekend.html). The goal of this project is to build a simple yet functional ray tracer from scratch, providing a solid foundation for understanding the principles of ray tracing.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

Ray tracing is a technique for generating images by simulating the way light interacts with objects. It produces highly realistic images by tracing the path of light rays as they travel through a scene. This project implements a basic ray tracer that can render simple scenes with spheres and planes, including basic lighting and shading effects.

## Features

- Basic ray-sphere and ray-plane intersection
- Diffuse and specular shading
- Simple camera model
- Antialiasing for smoother images
- Multithreading for faster rendering

## Getting Started

### Prerequisites

To build and run this project, you will need:

- A C++ compiler (supporting C++11 or later)
- CMake (version 3.10 or later)
- Git (for cloning the repository)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/ray-tracing-in-one-weekend.git
    cd ray-tracing-in-one-weekend
    ```

2. Create a build directory and navigate to it:
    ```sh
    mkdir build
    cd build
    ```

3. Configure the project with CMake:
    ```sh
    cmake ..
    ```

4. Build the project:
    ```sh
    make
    ```

## Usage

After building the project, you can run the ray tracer to generate an image. The output will be saved to a file named `output.ppm` in the build directory.

```sh
./raytracer
