---
layout: post
title: Texting and Driving Simulator
description: Demonstrate risks of driving while texting. Evaluates how reaction times suffer when using a mobile device.
image: assets/images/driving_simulator/simulator_screens_6.jpg
---

### What is this?

This project was built using several technologies: **UDK**, **Unrealscript**, **Unreal Kismet**, a C++ DLL, Flash, Scaleform, 3ds Max, Photoshop, **Android Studio** and WiiYourself.

This driving simulator was built to illustrate the risks of driving while texting. The idea behind it is to quantify and evaluate if/how the attention levels and reaction times of a driver suffer when using a mobile device. To achieve this, the simulator does three short tests.

<div class="row">
	<div class="4u 12u$(medium)">
		<span class="image fit">
            <img src="{% link assets/images/driving_simulator/simulator_test_1.jpg %}" alt="" />
            <br>
            <p>First, a <strong>Baseline reaction test</strong> where three random text messages are sent to the user's mobile phone. The user must reply to these messages, and the simulator records a baseline.</p>
        </span>
    </div>
    <div class="4u 12u$(medium)">
		<span class="image fit">
            <img src="{% link assets/images/driving_simulator/simulator_test_2.jpg %}" alt="" />
            <br>
            <p>Second, a <strong>Driving test</strong>. Here, the user only needs to complete the circuit.</p>
        </span>
	</div>
    <div class="4u 12u$(medium)">
		<span class="image fit">
            <img src="{% link assets/images/driving_simulator/simulator_test_3.jpg %}" alt="" />
            <br>
            <p>Third, a <strong>Texting and Driving test</strong>. In here, the user must both drive the vehicle correctly and reply to SMS messages in time.</p>
        </span>
	</div>
</div>


### What do we do with this data?

Once done with the tests, the simulator will display a set of results. These will graphically and quantitatively show changes in reaction time between the last two tests. See the results below:

<div class="row">
	<div class="4u 12u$(medium)">
		<span class="image fit">
            <img src="{% link assets/images/driving_simulator/simulator_results_1.jpg %}" alt="" />
            <br>
            <p align="middle">Results page - Path comparison.</p>
        </span>
    </div>
    <div class="4u 12u$(medium)">
		<span class="image fit">
            <img src="{% link assets/images/driving_simulator/simulator_results_2.jpg %}" alt="" />
            <br>
            <p align="middle">Results page - Text message data.</p>
        </span>
	</div>
    <div class="4u 12u$(medium)">
		<span class="image fit">
            <img src="{% link assets/images/driving_simulator/simulator_results_3.jpg %}" alt="" />
            <br>
            <p align="middle">Results page - Speed comparison.</p>
        </span>
	</div>
</div>

There are three difficulty levels, these modify things such as: 

- The amount of text messages the driver has to respond
- The maximum time the user has to respond to messages. 
- The difficulty of the track and terrain.
- Harder levels force a minimum vehicle speed.
- The visibility of the track. Below is an example of how the difficulty affects visibility.

<div class="row">
	<div class="4u 12u$(medium)">
		<span class="image fit">
            <img src="{% link assets/images/driving_simulator/simulator_difficulty_day.jpg %}" alt="" />
            <br>
            <p align="middle">High visibiliy - Daytime.</p>
        </span>
    </div>
    <div class="4u 12u$(medium)">
		<span class="image fit">
            <img src="{% link assets/images/driving_simulator/simulator_difficulty_afternoon.jpg %}" alt="" />
            <br>
            <p align="middle">Medium visibiliy - Afternoon.</p>
        </span>
	</div>
    <div class="4u 12u$(medium)">
		<span class="image fit">
            <img src="{% link assets/images/driving_simulator/simulator_difficulty_night.jpg %}" alt="" />
            <br>
            <p align="middle">Low visibiliy - Night.</p>
        </span>
	</div>
</div>

The result is a simulator that reflects the consequences of driving a vehicle while interacting with a mobile device.

<hr class="major" />

### Gallery

<div>
    <div class="row">
        <div class="4u"><span class="image fit"><img src="{% link assets/images/driving_simulator/simulator_screens_1.jpg %}" alt="" /></span></div>
        <div class="4u"><span class="image fit"><img src="{% link assets/images/driving_simulator/simulator_screens_2.jpg %}" alt="" /></span></div>
        <div class="4u"><span class="image fit"><img src="{% link assets/images/driving_simulator/simulator_screens_3.jpg %}" alt="" /></span></div>
        <!-- Break -->
        <div class="4u"><span class="image fit"><img src="{% link assets/images/driving_simulator/simulator_screens_4.jpg %}" alt="" /></span></div>
        <div class="4u"><span class="image fit"><img src="{% link assets/images/driving_simulator/simulator_screens_5.jpg %}" alt="" /></span></div>
        <div class="4u"><span class="image fit"><img src="{% link assets/images/driving_simulator/simulator_featured.jpg %}" alt="" /></span></div>
</div>


