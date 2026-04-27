# ICU-Vital-Signs-Processing-Pipeline
## ICU Vital Signs Visualizer

Interactive visualization of ICU patient vital signals recorded in `.vital` format (VitalDB).

## Tracks

| Type | Signals | Sample Rate |
|------|---------|-------------|
| Waveform | ECG_II | 500 Hz |
| Waveform | ABP, CVP, PLETH | 125 Hz |
| Numeric | ABP, NIBP, HR, SpO2, CVP, RR, ST | 1 Hz |

## Interactive Preview

### Waveform Signals (ABP, CVP, PLETH)
[📈 Interactive View](https://SEOL8.github.io/ICU-Vital-Signs-Processing-Pipeline/html/waveform.html)

### Numeric Parameters (HR, BP, SpO2, RR ...)
[📈 Interactive View](https://SEOL8.github.io/ICU-Vital-Signs-Processing-Pipeline/html/numeric.html)

## Requirements
```bash
pip install vitaldb plotly numpy matplotlib
```

## Usage
1. `.vital` 파일을 `ICU.vital`로 이름 변경 후 notebook과 같은 디렉토리에 위치
2. Jupyter에서 `vital_load.ipynb` 실행

## Data
Data files are not included in this repository.  
Compatible with `.vital` files exported from Philips IntelliVue monitors via [VitalDB](https://vitaldb.net).
