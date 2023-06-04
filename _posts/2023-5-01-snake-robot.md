---
layout: post
title: Remotely Operated Snake Robot
description: Remotely controlled robot that moves using friction.
image: assets/images/snake_robot/snake_featured.jpg
---

### What is this thing?

This snake-like robot moves using friction ...by dragging itself just like a snake! It can be remotely controlled via an Android application that allows the “driver” of the snake to move it forwards, backwards, left and right. A real-time 720p video feed from the nose of the snake is streamed to the client app at all times. 

The robot's head contains an array of high-brightness LEDs that can be toggled on in low-light environments.

### Design

A computer generated 3D model of the robot was created before the mechanical model was constructed. This model was used to simulate the movements of the snake before its construction. Below is a 3D model of the final design. 

<div class="row">
    <span class="image fit">
        <img src="{% link assets/images/snake_robot/snake_model_complete.jpg %}" alt="" />
        <p align="middle">A mechanical 3D model of the snake, head at the far right.</p>
    </span>
</div>

The snake has seven modules, each module has its own servo motor which allows a module to move with respect to adjacent modules. Each module has one degree of freedom which allows vertical -perpendicular to the floor- or horizontal -parallel to the floor- movement. A clever arrangement of modules allows the robot to move in straight  sinusoidal fashion.

### Sensors

Various sensors report the environmental conditions where the robot is:

- An MQ3 gas sensor.
- A DHT11 Humiture sensor.
- An infrared obstacle sensor.
- A microphone (Will stream sound to client app).
- A digital temperature sensor.

The robot uses Wi-Fi to communicate to the Android app, several ports are used for communicatting commands and streaming real-time status (video and sensor) data.

<hr class="major" />

### Gallery

<div>
    <div class="row">
        <div class="4u">
            <span class="image fit">
                <img src="{% link assets/images/snake_robot/snake_1.jpg %}" alt="" />
                <p align="middle">Inside the Snake Head</p>
            </span>
        </div>
        <div class="4u">
            <span class="image fit">
                <img src="{% link assets/images/snake_robot/snake_2.jpg %}" alt="" />
                <p align="middle">Android app beta build</p>
            </span>
        </div>
        <div class="4u$">
            <span class="image fit">
                <img src="{% link assets/images/snake_robot/snake_3.jpg %}" alt="" />
                <p align="middle">Assembled Head</p>
            </span>
        </div>
        <!-- Break -->
        <div class="4u">
            <span class="image fit">
                <img src="{% link assets/images/snake_robot/snake_4.jpg %}" alt="" />
                <p align="middle">Robot module</p>
            </span>
        </div>
        <div class="4u">
            <span class="image fit">
                <img src="{% link assets/images/snake_robot/snake_5.jpg %}" alt="" />
                <p align="middle">Raspberry PI + Camera</p>
            </span>
        </div>
        <div class="4u$">
            <span class="image fit">
                <img src="{% link assets/images/snake_robot/snake_6.jpg %}" alt="" />
                <p align="middle">Head with Sensors</p>
            </span>
        </div>
    </div>
</div>