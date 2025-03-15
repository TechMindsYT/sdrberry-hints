
# sdrberry hints

These notes are to assist any users wishing to follow along with my sdrberry pi installation video which is found on YouTube.

SOAPY should be already installed with the sdrberry installation, below are other SOAPY modules which can be used.

## SOAPY RTL-SDR.
```
sudo apt-get install rtl-sdr librtlsdr-dev

git clone https://github.com/pothosware/SoapyRTLSDR.git
cd SoapyRTLSDR
mkdir build
cd build
cmake ..
make
sudo make install
sudo ldconfig 

```

## SOAPY SDRPlay.
```
Install SDRPlay API first:

wget https://www.sdrplay.com/software/SDRplay_RSP_API-Linux-3.15.2.run
chmod 755 SDRplay_RSP_API-Linux-3.15.2.run
./SDRplay_RSP_API-Linux-3.15.2.run

Now install the SDRPlay SOAPY module.

git clone https://github.com/SDRplay/SoapySDRPlay
cd SoapySDRPlay
mkdir build
cd build
cmake ..
make
sudo make install
sudo ldconfig 

```

<iframe width="560" height="315" src="https://www.youtube.com/embed/Y5Jd29SA8go?si=Xvib-G1wfSQSm6-k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

