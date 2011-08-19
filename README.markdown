# ScreenCalculator

![](Screenshot.png)

## Introduction

A simple HTML5 webpage I use to get a sense for different screen and pixel dimensions and densities when designing and developing mobile operating systems and applications.

It (1) **calculates screen dimensions** (physcial width and height) based on the diagonal commonly referenced in promotional material and manuals. Once the dimensions are established, it also (2) allows you to **calculate the pixel pitch** (ppi: pixel per inch). If you configure the size of your computer screen, it also (3) shows you a **realistic size reference**.

## Dependencies

* [fraction.js](https://github.com/ekg/fraction.js)

## Known issues

* No support Internet Explore prior to version 9.
* On multi-display setups, only the main-monitor is used to calibrate the screen PPI.

## Usage

Simply enter the desired values for screen diagonal (in inch) and screen resolution. The html5 canvas graph updates as you enter your data.

In order to get an accurate size reference, you need to click the "default: 96ppi" button, and enter the diagonal of the screen you are looking at.



