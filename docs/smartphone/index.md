# mCerebrum
**An Open Source Software Suite for Mobile Sensor Data**


<center><iframe src="https://www.youtube.com/embed/g_WC0vpn5rU" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen"></iframe></center>

## mCerebrum Overview

**mCerebrum is a configurable smartphone software platform for mobile and wearable sensors.** mCerebrum is open-source and provides support for reliable real-time data collection. The software is fully configurable and can be used with multiple sensors simultaneously to collect a wide variety of data at hundreds of data points per second.

![mCerebrum Home Screen](../img/mCerebrumOnPhone.png)

Even at this high frequency, our software continuously takes steps to evaluate data quality and maintain the integrity of sensor data by using advanced analytics to convert streaming sensor data into markers of health, behavior, and risk factors (such as stress, smoking, eating and activity).

With mCerebrum, these markers obtained from sensor data can be used to trigger mobile interventions or to solicit self-reports. To fulfill the vision of precision medicine, mCerebrum facilitates novel ways to return health data back to the user to improve their engagement, bringing a modern approach to preventative medicine that stays one step ahead in today’s rapidly changing world.

## Adopting mCerebrum

The MD2K software platform is **fully configurable and open-source**. We invite you to use our software and we welcome contributions from anyone who is interested in improving mobile health. Please visit our [MD2K GitHub organization](https://www.github.com/MD2Korg/) and [Adopt MD2K pages](http://howto.md2k.org/adopt/) for more information.

## List of mCerebrum Apps

| Applications                                                                          | Download                                                                                   |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| [mCerebrum (Study)](https://github.com/MD2Korg/mCerebrum-Study)                       | [latest release](https://github.com/MD2Korg/mCerebrum-Study/releases/latest) |
| [AutoSense](https://github.com/MD2Korg/mCerebrum-AutoSense)                           | [latest release](https://github.com/MD2Korg/mCerebrum-AutoSense/releases/latest) |
| [Microsoft Band](https://github.com/MD2Korg/mCerebrum-MicrosoftBand)                  | [latest release](https://github.com/MD2Korg/mCerebrum-MicrosoftBand/releases/latest) |
| [Phone Sensor](https://github.com/MD2Korg/mCerebrum-PhoneSensor)                      | [latest release](https://github.com/MD2Korg/mCerebrum-PhoneSensor/releases/latest) |
| [Stream Processor](https://github.com/MD2Korg/mCerebrum-StreamProcessor)              | [latest release](https://github.com/MD2Korg/mCerebrum-StreamProcessor/releases/latest) |
| [Mood Surfing](https://github.com/MD2Korg/mCerebrum-MoodSurfing)                      | [latest release](https://github.com/MD2Korg/mCerebrum-MoodSurfing/releases/latest) |
| [Thought Shakeup](https://github.com/MD2Korg/mCerebrum-ThoughtShakeup)                | [latest release](https://github.com/MD2Korg/mCerebrum-ThoughtShakeup/releases/latest) |
| [Ecological Momentary Assessment (EMA)](https://github.com/MD2Korg/mCerebrum-EMA)     | [latest release](https://github.com/MD2Korg/mCerebrum-EMA/releases/latest) |
| [EMA Scheduler](https://github.com/MD2Korg/mCerebrum-EMAScheduler)                    | [latest release](https://github.com/MD2Korg/mCerebrum-EMAScheduler/releases/latest) |
| [Notification Manager](https://github.com/MD2Korg/mCerebrum-NotificationManager)      | [latest release](https://github.com/MD2Korg/mCerebrum-NotificationManager/releases/latest) |
| [Data stream plotter](https://github.com/MD2Korg/mCerebrum-Plotter)                   | [latest release](https://github.com/MD2Korg/mCerebrum-Plotter/releases/latest) |
| [DataKit](https://github.com/MD2Korg/mCerebrum-DataKit)                               | [latest release](https://github.com/MD2Korg/mCerebrum-DataKit/releases/latest) |

## Background
mCerebrum is backed by 9 years of software development on the [Fieldstream](http://www.fieldstream.org/) and [AutoSense](https://sites.google.com/site/autosenseproject/) projects which yielded in excess of 20,000 hours of wearable sensor data from a variety of lab and field studies with hundreds of participants. Over 27 research articles (with over 400 citations) have been published using analysis of these data. mCerebrum is based on these extensive experiences with real-life high-frequency sensor data and its analysis for both technology and health research.

The signal processing for Fieldstream and AutoSense were on a Matlab batch-processing codebase that operates on data after a participant has returned the data collection device to the lab. Therefore, no real-time sensor-triggered notifications or interventions were possible with the existing framework and furthermore, the codebase does not lend itself well to distributed processing for scalable application performance.

## Novelty
mCerebrum is designed to be compatible with mobile platforms so as to support **real-time signal processing of high-frequency data streams** in excess of 800 hertz, while meeting quality of service requirements for the mobile platform. In addition, mCerebrum is designed as an **open-source project** so that it can be easily used by the community and modified to suit specific research needs.

## Software Release Schedule
- Major `X.0.0` software updates will occur approximately once per year
- Minor/Feature `0.X.0` updates will occur on the third Wednesday of each month
- Critical bug fixes `0.0.X` will be released as needed

| Year |    Month   | Release Day       |
|------|------------|-------------------|
| 2017 | May        | 05/17/2017  (Wed) |
| 2017 | June       | 06/21/2017  (Wed) |
| 2017 | July       | 07/18/2017  (Wed) |
| 2017 | August     | 08/16/2017  (Wed) |
| 2017 | September  | 09/20/2017  (Wed) |
| 2017 | October    | 10/18/2017  (Wed) |
| 2017 | November   | 11/15/2017  (Wed) |
| 2017 | December   | 12/20/2017  (Wed) |
