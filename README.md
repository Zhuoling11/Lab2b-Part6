# Lab2b-Part6
## Todo
- modify the PIO/DMA logic analyzer example to record a timestamped trace of an RP2040-ADPS9960 exchange while the BOOT button is pressed(WORK)
- with a partner, connect a second Qt Py to the Stemma Qt bus of an ADPS9960 that's attached to a first Qt Py running the Lab 1 Python code(WORK)
- record a trace of this exchange(WORK)
<img width="1110" alt="Part6screenshot" src="https://user-images.githubusercontent.com/114199800/202325604-0ba4a8df-e78f-4289-808f-e5ee0e98c8d4.png">
## Some usful Notes

https://github.com/PZZ97/ese5190-2022-lab2b-esp/blob/main/lab/06_pioscope/useful_notes/Note.md
The sampleing rate is 8 times of i2c rate
5ms pre packet interval is about 0.005 * 1600 *8000 = 64000 cycle. so the the PIO scope work crrectly
