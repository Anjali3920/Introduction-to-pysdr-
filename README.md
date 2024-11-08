
# 2 Introduction-to-pysdr-
# SDR ( Software - Defined Radio)
It refers to a device that you can plug an antenna into and receive RF signals , with the digitalized RF samples being sent to a computer for processing or recording .many SDR also have transmit capabilities .
# DSP (Digital Signal Processing)
It refers to various techniques for improving the accuracy and reliability of digital communications.
# Frequency domain 
The frequency domain refers to an analysis or representation of data, signals, or functions in terms of frequency rather than time. This concept is crucial in many fields, including signal processing, image processing, and communications.
# Fourier Series
When we break signal down into it's composite sine waves,we call it a Fourier series. 
To understand how we can break down a signal into sine waves,we need to know about:
1.Amplitude: strength of wave
2.Frequency: no.of waves per second.
3.Phase:phase representation how the sine wave is shifted in time , anywhere from 0 to 360 degrees.
# Time- Frequency Pairs
Signals can be represented as sine waves, which have several attributes. Now, let’s learn to plot signals in the frequency domain. While the time domain demonstrates how a signal changes over time, the frequency domain displays how much of a signal rests in which frequencies.
https://github.com/user-attachments/assets/438c1bd9-92a6-4832-8ae6-5d59fc2c2e62
# Fourier Transformation 
The Fourier Transform is a mathematical technique that transforms a time-domain signal into its corresponding frequency-domain representation. It decomposes a function or signal into its constituent frequencies, showing how much of each frequency is present. This is especially useful in analyzing periodic signals, filtering, and signal processing.The inverse Fourier Transform can be used to convert the frequency-domain signal back to the time-domain.
# Fast Fourier Transform (FFT)
The Fast Fourier Transform  is simply an algorithm to compute the discrete Fourier Transform . The FFT is a function with one input and one output .It converts a signal from time to frequency:
(https://github.com/user-attachments/assets/fceb5b15-5c59-4803-aee1-21fb7349d680)
# FFT in python 
Now that we have learned about what an FFT is and how the output is represented, let’s actually look at some Python code and use Numpy’s FFT function, np.fft.fft(). It is recommended that you use a full Python console/IDE on your computer, but in a pinch you can use the online web-based Python console linked at the bottom of the navigation bar on the left.

import numpy as np
t = np.arange(100)
s = np.sin(0.15*2*np.pi*t)
hello world



# NETWORKING VIRTUALIZATION 
Networking virtualization is the process of creating multiple virtual networks on top of a physical network infrastructure. This allows for the efficient allocation of network resources, enabling multiple isolated networks to run on the same physical hardware. 

Networking Virtualization

1. Introduction to Networking Virtualization

Definition: Networking virtualization refers to the abstraction of network resources, enabling them to be decoupled from physical devices and operated through software.

# Purpose: 
It aims to improve the flexibility, scalability, and efficiency of network resources in an organization, especially in data centers and cloud environments.

# Types of Network Virtualization: 
Explain types, including Virtual LAN (VLAN), Virtual Private Network (VPN), and Software-Defined Networking (SDN), as each plays a role in creating virtualized networks.


# 2. Key Components of Networking Virtualization

Virtual Network Interface Cards (vNICs): vNICs allow virtual machines (VMs) to connect to virtual networks, creating a seamless interface between VMs and the physical network.

Network Function Virtualization (NFV): NFV replaces physical network devices, like routers, with virtual instances, enabling efficient and flexible management.

Software-Defined Networking (SDN): SDN separates the control plane from the data plane, allowing centralized management of network traffic through software.


# 3. Advantages of Networking Virtualization

Resource Efficiency: Virtualization helps in utilizing the full capacity of physical resources, reducing waste and operating costs.

Scalability: Virtual networks can be scaled up or down without the need for significant hardware changes.

Isolation and Security: Virtual networks provide isolated environments, enhancing security by preventing cross-network access unless explicitly allowed.


# 4. Use Cases of Networking Virtualization

Data Centers: Virtualized networks are essential in large data centers for managing complex environments with numerous VMs and containers.

Cloud Computing: In public and private clouds, networking virtualization is critical for enabling multi-tenant environments where each user has their isolated network.

Enterprise Networks: Corporations use virtualization to create segmented networks for different departments or applications, enhancing performance and security.


5. Challenges of Networking Virtualization

Complexity: Setting up virtualized networks requires specialized knowledge and can add complexity to network management.

Performance Overheads: Virtualization may introduce latency or bandwidth overhead due to additional layers of abstraction.

Security Vulnerabilities: Virtual networks, if not properly configured, can be susceptible to attacks that exploit the underlying infrastructure.


# 6. Future of Networking Virtualization

Advancements in SDN and NFV: Emerging technologies in SDN and NFV



# OOPS IN PYTHON 
Object-Oriented Programming (OOP) is a programming paradigm based on the concept of objects, which can contain data and methods. OOP aims to organize code in a way that is easy to manage, scale, and reuse.

# Key Concepts of OOP

# 1. Class:

A class is a blueprint for creating objects. It defines the properties (attributes) and behaviors (methods) that the objects created from it can have.

Think of a class as a template — for example, a "Car" class defines what attributes (like brand, model, and year) and methods (like start, stop) every car object will have.



# 2. Object:

An object is an instance of a class. It represents a specific entity created using the class blueprint.

For example, if "Car" is the class, then a specific car (like a Toyota Corolla) is an object of that class.



# 3. Attributes:

Attributes are variables that hold data associated with an object. They represent the characteristics of the object.

For example, a car object may have attributes like brand, model, color, and year.



# 4. Methods:

Methods are functions defined inside a class that describe the behaviors of an object.

For example, a car object may have methods like drive, brake, and honk.




# Principles of OOP

OOP is based on four main principles:

## 1. Encapsulation:

Encapsulation is the practice of bundling data (attributes) and methods (functions) that manipulate the data into a single unit (class).

It restricts access to certain components, making it easier to maintain and protect the data. This is often achieved using private attributes, which cannot be directly accessed from outside the class.

Encapsulation ensures that the internal state of an object is hidden from the outside world and can only be modified through defined methods.



## 2. Inheritance:

Inheritance is a mechanism that allows a class to inherit attributes and methods from another class. It helps promote code reusability and establishes a relationship between classes.

The parent class (or superclass) passes its properties and behaviors to the child class (or subclass).

For example, if "Vehicle" is a parent class, then "Car" and "Motorcycle" can be subclasses that inherit common features like speed and color while having their unique features.



## 3. Polymorphism:

Polymorphism means "many shapes." It allows objects of different classes to be treated as objects of a common superclass. It enables the same method to behave differently based on the object calling it.

For instance, a method called fly may behave differently when called by a "Bird" class object compared to when it is called by a "Plane" class object, even though both classes may have a fly method.



## 4. Abstraction:

Abstraction is the process of hiding complex implementation details and showing only the essential features of an object.

It helps reduce complexity by allowing the user to interact with an object at a high level without needing to understand the inner workings.

For example, when using a smartphone, the user does not need to know the intricate hardware details; they only interact with the interface.




# Advantages of OOP

### 1. Modularity:
Code is organized into classes and objects, making it easier to understand and maintain.


### 2. Reusability: 
Inheritance allows the reuse of existing code, reducing redundancy.


### 3. Scalability: 
OOP makes it easier to add new features and functionality as the program grows.


### 4. Security: 
Encapsulation helps protect the internal state of objects by restricting direct access to their attributes.



# Special (Magic) Methods in Python

In Python, classes can have special methods (often called magic methods) that provide additional functionality. These methods are denoted with double underscores (e.g., __init__, __str__, __len__). They allow objects to interact with Python’s built-in functions and operators in intuitive ways.

__init__: Initializes the object when it is created.

__str__: Defines the string representation of an object.

__len__: Defines the behavior of the len() function when called on an object.


These methods make classes behave more like built-in types, enhancing the usability of custom objects.


