+++
title = "MIDI"
outputs = ["Reveal"]
[reveal_hugo]
theme = "solarized"
# show_notes = "separate-page"
+++

![](MIDI_LOGO.svg)

{{% note %}}
* musical instrument digital interface
* connects devices together to exchange information like pitch and volume 
* allows for keyboards and controllers to manipulate a DAWs faders and knobs
* allows for a DAW to control hardware audio processors and synthesizers 
* MIDI spec - describes hardware and messages
* hardware
    * cables, ports, computer interfaces, and various electrical details that allow for the communication of musical data between synthesizers, computers, and various other electronic musical devices. 
* messages
    * what information can be communicated between such connected devices and what form the messages take.ß

---

# MIDI Hardware

## A brief history of MIDI

---

## Analog Days: Synthesizers in the 1960s and 1970s

* Robert Moog, Donald Buchla, and others  
    * analog
    * modular 
    * voltage controlled

{{% note %}}
* analog
    * electrical signals in the synths consisted of continuous changes in electrical voltage rather than a discrete series of numbers as in modern digital synthesizers.
* modular 
    * the task of generating sound was distributed among separate hardware units called modules.
    * oscillators, filters, and amplifiers were separate modules. 
* voltage controlled
    * keyboards, joysticks, and ribbon controllers were used to send control voltages to the modules to change their settings.

---

## Moog - show by Wendy Carlos

<iframe width="560" height="315" src="https://www.youtube.com/embed/4SBDH5uhs4Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## Buchla 200e

<iframe width="560" height="315" src="https://www.youtube.com/embed/Y7nxZdkqWpk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## Digital Control, Digital Memory, and Digital Synthesis

<img src="sequential-circuits-model-800-cv-gate-sequencer-1741124.jpg" width="60%">

{{% note %}}
* in the 1970s digital control in the form of sequencers was added to analog synthesizers to allow for more precise control.
* they also added the ability to save settings, the original presets 
* this is a Sequential Circuits Model 800 that could hook up to any synthesizer through voltage control 
* Eventually all digital synthesizers were developed

---

## Yamaha DX7

<iframe width="560" height="315" src="https://www.youtube.com/embed/Q1Ha0MMT0aA?start=165" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

{{% note %}}
Yamaha DX7, an early all-digital, MIDI-compatible keyboard synthesizer (1983). At about $2,000, the DX7 was relatively inexpensive by early 1980s’ standards.

---

## MIDI 1.0 Specification

* synth manufacturers wanted to create a communications standard
* MIDI 1.0 Specification - published in 1983
* first connections at NAMM - Sequential Circuits Prophet 600 and a Roland JP-6.



---

## Controllers

[Various controllers](https://duckduckgo.com/?q=midi+controllers&t=newext&atb=v265-1&iax=images&ia=images&iai=https%3A%2F%2Fwww.bhphotovideo.com%2Fimages%2Fimages2500x2500%2Flivid_instruments_lvbase02_multipurpose_performance_controler_for_1054583.jpg)

{{% note %}}
* only sends MIDI messages
* doesn't generate sound on its own 
* before personal computers it would send messages to a hardware synth but now we connect them to computers

---

## Modules - Roland Fantom-XR

<img src="roland-fantom-xr.jpg" width="60%">

{{% note %}}
A module is a device that can generate sound when it receives MIDI messages but has no keys to play, and hence can’t output MIDI messages. 
 

---

## Workstations - Akai MPC

<iframe width="560" height="315" src="https://www.youtube.com/embed/SENzTt3ftiU?start=165" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## Alternate controllers - AKA NIMES

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZRHLtkeWwwA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>





