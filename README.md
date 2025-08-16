# 🎧 FM Receiver with GNU Radio and RTL-SDR

Este projeto implementa um **receptor de rádio FM** utilizando o **GNU Radio** e o **dongle RTL-SDR**.

## 🚀 Funcionalidades
- Ajuste de **frequência** (sintonia de estações)
- Controle de **ganho de RF**
- Controle de **volume**
- Visualização em tempo real do espectro do sinal

## 📂 Estrutura do Projeto
- `fm_receiver.grc` → flowgraph do GNU Radio
- `fm_receiver.py` → código gerado (Python)
- `docs/` → prints de execução

## 🛠️ Requisitos
- GNU Radio >= 3.8
- SoapySDR
- RTL-SDR driver (`rtl-sdr` package)
  
Instalação no Ubuntu:
```bash
sudo apt-get install gnuradio rtl-sdr soapysdr-module-rtlsdr
