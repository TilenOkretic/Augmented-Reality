# Augmented reality - 07.03.2022

## Introduction to Android development

* Android:
  
  * we say it is **Linux based** because Linux karnel is used in Android
  
  * **open source system**
  
  * softwere stack
  
  * Android SDK ~ development tools 
  
  * why Android:
    
    * large market
    
    * low costs
    
    * google play store
  
  * fetures:
    
    * UI
    
    * Connectivity
      
      * GSM, IDEN
    
    * Storage
      
      * SQLite
    
    * Media support
    
    * Messaging
      
      * SMS, MMS
    
    * Web browser
    
    * Multi-touch
      
      * Handsets
    
    * Multitasking
    
    * Resizable widgets
    
    * Multi-language
      
      * sturtured language support
      
      * XML file
    
    * GCM
    
    * Wi-Fi direct
    
    * Android beam



## Android applications

* Java

* Kotlin is taking over

* **App stores**

## Android versions

* every 6 months

* Problem: **fragmentation** ~ apps compatible over multiple devices

## Android architecture

* LOW level to HIGH level:
  
  1. Linux kernel
  
  2. Hardware abstraction layer ~ **HAB**
  
  3. Native C/C++ libraries // Android runtime
  
  4. Java API framework
  
  5. System apps
     
     * holds applications

* When anything comes to screen it is essentialy an **activity**!!

## Android runtime

* For running your applications

* **ART** is a kind of java virtual machine for android

* Multi threading and a lot of optimizations are handled "automatically"

## How does ART work

* Write in java lang

* compile to java bytecode

* java bytecode to DEX bytecode

* DEX is packaged with other application resources

## Application components

* Acitivities
  
  * This is where the app starts
  
  * Things that become visible on screen
  
  * It is a **fullscreen UI component**
  
  * Apps stack ~ multiple layers one over the other
  
  * Lifecycles
  
  * Events

* Services
  
  * Background tasks

* Broadcast recievers
  
  * Share "messages" with other apps on the phone
  
  * Multi apllication integration
  
  * examples: 
    
    * Send an SMS with the use of an app
    
    * App opens phones camera

* Content providers
  
  * Data stored on the system

* Fragments
  
  * app controlls only a part of a screen

* Views

* Layouts
  
  * addapting to chaanges in orientation

* Intents
  
  * whet do you want your app to do

* Resources
  
  * External things
  
  * strings
  
  * constants

* Manifest
  
  * info about the app
  
  * version
  
  * configuration file



## Android studio - introduction


