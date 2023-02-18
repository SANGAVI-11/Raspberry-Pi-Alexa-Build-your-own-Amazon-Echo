# Raspberry-Pi-Alexa-Build-your-own-Amazon-Echo

## Abstract:

In this project we have tried to design a voice assistant with few functions like playing music, giving information on wiki search and providing us with the information like day, date, time, weather and temperature.

## Introduction: 

A voice assistant, also called an intelligent personal assistant or a connected speaker, are new types of products marketed by Apple, Amazon and Google and are based on natural language speech recognition. Automating repeated tasks to a voice-activated personal assistant frees up the human time and resources. Also, it can efficiently perform these mundane tasks with no errors, which often leads to an improvement in customer satisfaction. Today, voice assistants are 
integrated into many of the devices we use on a daily basis, such as cell phones, computers, and smart speakers. Because of their wide array of integrations, 
there are several voice assistants who offer a very specific feature set, while some choose to be open ended to help with almost any situation at hand.

## Theory:

### Socket programming:

Socket is an interface between application process and end to end transport protocol. Socket programming is the communication between the client and server applications using sockets.

Socket programming is a way of connecting two nodes on a network to communicate with each other. One socket(node) listens on a particular port at an IP, while the other socket reaches out to the other to form a connection.Stream sockets: This is the most common type. The two communicating parties first establish a socket connection, after which any data passed through that connection is guaranteed to arrive in the same order in which it was sent 

### Datagram sockets: 

Offer connection-less semantics. Either party sends datagrams as needed and waits for the other to respond. Messages can be lost in transmission or received out of order Libraries that implement sockets for internet protocol use TCP for streams, UDP for datagrams. 

Transmission Control Protocol (TCP) is connection-oriented, meaning once a connection has been established, data can be transmitted in two directions. TCP has built-in systems to check for errors and to guarantee data will be delivered in the order it was sent, making it the perfect protocol for transferring information like still images, data files, and web pages.

User Datagram Protocol (UDP) is a simpler, connectionless Internet protocol 
wherein error-checking and recovery services are not required. With UDP, there 
is no overhead for opening a connection, maintaining a connection, or 
terminating a connection; data is continuously sent to the recipient, whether or 
not they receive it.

### Threading:

Threading is the process of implementing parallelism of processes or functions. 
By the concept of threading, we achieve it, by creating a separate thread for a 
specific function and run it parallelly.

## Packages used:

### 1) Speech recognition

a) Speech_recognition: Speech recognition in Python is used to convert the 
spoken words into text, make a query or give a reply.

b) Pyaudio and portaudio: PyAudio provides Python bindings for 
PortAudio, it is a cross-platform audio I/O library. With PyAudio, you 
can easily use Python to play and record audio on a variety of platforms, 
such as GNU/Linux, Microsoft Windows, and Apple Mac OS X / macOS.

c) Pyttsx3: pyttsx3 is a text-to-speech conversion library in Python.

### 2) Socket 

a) Socket: The socket module provides various objects, constants, functions 
and related exceptions for building full-fledged network applications 
including client and server programs.

b) Json: JavaScript Object Notation (JSON) is a standardized format 
commonly used to transfer data as text that can be sent over a network.

### 3) Playing music 

a) Youtube-dl: youtube-dl is a command-line program to download videos 
from YouTube.com.

b) Pafy: Pafy is a Python library to download YouTube content and retrieve 
metadata.

c) Python-vlc: This is used to play the audio in python using VLC media 
player.

### 4) Other packages:

a) Wikipedia : Wikipedia is a python package which allows us to access 
data from Wikipedia and extract the required amount of data. 

b) Random : Random is a python built in package, which allows us to 
randomize replies.

c) Datetime : Datetime package allows us to access and process the date and 
time values.

d) Urllib : Urllib package is the URL handling module for python. It is used 
to fetch the song URL form youtube.

e) Threading : This package is used for using the concepts of parallelization 
of processes.

f) Requests : This package can be used to make HTTP requests such as 
GET, POST, PUT

## Overview:

We will be performing functions like getting time, date, day, weather, 
music(audio) and Wikipedia search.
There are 3 modules used here are:

• smallFunctions.py: This contains the functions getTime, getDate, 
getDay, getWiki, getWeather.

• playMusic.py: This contains the function required for getting the 
information of the audio requested by the user to play the music.

• tara.py: This is the driver module which incorporates all the other 
modules and gives the desired output.

• server.py: In the server, we will be running this, this collects the log 
from the raspberry pi and send to our django server for storing and 
visualizing

## Advantages:

• It is very effective as an end product

• It can perform multiple functions

• It is very time efficient

## Disadvantages:

• We are not in the control of the data that is being collected by it

• It is not secure and safe 

• There are possibilities of data breach

## Conclusion:

So in this project, we have created out own Alexa/Echo with some basic 
functionality and also have implemented the concepts of server-client and cloud 
architecture.




