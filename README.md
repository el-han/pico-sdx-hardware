# Pico SDX

Pico SDX is a Software Defined HF Transceiver.

## Related Projects

- [uSDX](https://github.com/threeme3/usdx): ATmega 328P based SSB Transceiver. Large Arduino source file, no hardware sources, only schematics
- [(tr)uSDX](https://dl2man.de/): Implementation of uSDX by DL2MAN. No hardware sources, only schematics
- [uSDX-x](https://github.com/KD9PDP/uSDX-x): uSDX implementation with KiCAD hardware sources and JLCPCB friendly manufacturing data. ATmega328P based and compatible to uSDX. **Looks like a good starting point**
- [uSDR-pico](https://github.com/ArjanteMarvelde/uSDR-pico): RP2040 based SSB Transceiver. Highly experimental according to author. Pico SDK based Firmware, Eagle hardware sources. **Looks like a good starting point**
- [Blueberry SDR](http://www.andreadrian.de/sdr/Blueberry_SDR_schematics.html) experiments with different designs and components
- [YU1MLs SDRs](https://web.archive.org/web/20200227193146/http://yu1lm.qrpradio.com/sdr%20rx%20yu1lm.htm) many RX, TX and TRX designs
- [Teensy SDR](https://www.pjrc.com/convolution-software-defined-radio/) Teensy based sdr with waterfall diagram

## Related resources

- [Barbaros Aşuroğlu](https://antrak.org.tr/author/barbarosasuroglu/) has built an own uSDX implementation and many other projects.
- [QRP labs](https://www.qrp-labs.com/lpfkit.html) sells low pass and band pass filter modules for all HF bands
- [QRP labs](https://www.qrp-labs.com/synth/ms5351m.html) comparison between the clock generators Si5351A (Silicon labs) and MS5351M (Relmon) regarding usage in SDRs
- [Calculate your locator](https://dxcluster.ha8tks.hu/hamgeocoding/)

## technical background

- [Dan Tayloe](https://www.norcalqrp.org/files/Tayloe_mixer_x3a.pdf) brief description of the operation of quadratur mixers
- Gerald Youngbloods QEX articles [1](https://www.arrl.org/files/file/Technology/tis/info/pdf/020708qex013.pdf), [2](https://www.arrl.org/files/file/Technology/tis/info/pdf/020910qex010.pdf), [3](https://www.arrl.org/files/file/Technology/tis/info/pdf/021112qex027.pdf) and [4](http://www.arrl.org/files/file/Technology/tis/info/pdf/030304qex020.pdf) very good, detailed and comprehensive description of SDR projects for ham radio operators and additional [ARRL SDR](http://www.arrl.org/software-defined-radio) resources
- Walla Walla University projects: [Paper](http://fweb.wallawalla.edu/~frohro/ClassHandouts/Electronics/A%20Comparison%20of%20Affordable,%20Self-Assembled%20%20Software-Defined%20Radio%20Receivers%20Using%20Quadrature%20Sampling%20Down-Conversion.pdf), [Talk](https://www.youtube.com/watch?v=UoL1Qzaw2H0&t=217s),[Jordyn Watkins Wiki](https://github.com/greenjacketgirl/SDR_Receiver/wiki), [Caleb Froelichs Wiki](https://github.com/froeca/Software-Defined-Radio/), [Konrad MacClure](https://github.com/KonradMcClure/SDR_Receiver) and [SMD Version by Caleb Nelson](https://github.com/Dizzerin/Software-Defined-Radio)with detailed explanations, simulations, design decisions and tests
- [Burkhard Kainkas](https://www.b-kainka.de/iqrx.htm) experiments with iq mixers
- [devttys0](https://www.youtube.com/watch?v=JuuKF1RFvBM) video on explanations of the function of the tayloe mixer
- [w2aew](https://www.youtube.com/watch?v=Mm7WfVzr1ao) video on RF-mixer basics
- [BPF design for HF-Tranceiver](https://www.arrl.org/files/file/Technology/tis/info/pdf/8809017.pdf)
- [devttys0](https://www.youtube.com/watch?v=1sq8Cvju2Oo) video on practical filter design and construction
