---
layout: post
title:  "MIDI to Sync ConverterはSEQTRAKでは使用できません"
date:   2024-08-21 00:00:00 +0900
categories: blog MIDItoSync
---
MIDI to Sync ConverterがYAMAHA SEQTRAKで使用出来ないという報告あり。

使えない機器があることは想定内であったものの、気になったので購入して[検証](https://x.com/YuuichiAkagawa/status/1826213530653360605)したところSEQTRAKのMIDIはGNDが接続されておらず電源を取ることができない。  
付属ケーブルは結線されているので、本体で接続されていない模様([参考](https://x.com/YuuichiAkagawa/status/1826266103087251830))。

本来はグランドループ防止のためMIDI IN側はGNDに接続してはいけないので、MIDIから電源を取るのはダメなんだけど利便性のために利用している。
