<div align="center">
  <h1>🌌 Quantum Computing Simulator</h1>
  <h3>Квантовый симулятор на Python</h3>
  
  [![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)]()
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()
</div>

## 🇬🇧 English Version

### 🚀 Features
- Full-featured quantum computer simulator
- Supports up to 10 qubits
- Includes basic gates (X, Y, Z, H, S, T, CNOT)
- Grover's and Shor's algorithms implementation
- Interactive GUI with visualization
- Educational purpose - great for learning QC basics

### 💻 Installation
```bash
git clone https://github.com/Nuxora/Quantum-Simulator-Repository-Setup-English-.git
cd quantum-simulator
pip install -r requirements.txt
```

### 🏃‍♂️ Quick Start
```python
from src.simulator import QuantumSimulator

qs = QuantumSimulator(2)  # Create 2-qubit system
qs.apply_gate('H', 0)    # Apply Hadamard to qubit 0
qs.cnot(0, 1)            # Entangle qubits
print(qs.measure(0))      # Measure qubit 0
```

### 📊 Visualization Example
![Q-Sphere Visualization](https://github.com/Nuxoraa/Quantum-Simulator-Repository-Setup-English-/blob/main/qsphere.png)

## 🇷🇺 Русская Версия

### 🌟 Возможности
- Полнофункциональный симулятор квантового компьютера
- Поддержка до 10 кубитов
- Все базовые гейты (X, Y, Z, H, S, T, CNOT)
- Реализация алгоритмов Гровера и Шора
- Графический интерфейс с визуализацией
- Отлично подходит для изучения основ КК

### ⚙️ Установка
```bash
git clone https://github.com/Nuxora/Quantum-Simulator-Repository-Setup-English-.git
cd quantum-simulator
pip install -r requirements.txt
```

### 🏁 Быстрый Старт
```python
from src.simulator import QuantumSimulator

qs = QuantumSimulator(2)  # Создаём систему из 2 кубитов
qs.apply_gate('H', 0)     # Применяем Адамара к 0-кубиту
qs.cnot(0, 1)            # Запутываем кубиты
print(qs.measure(0))      # Измеряем 0-кубит
```

### 📈 Пример Визуализации
![Визуализация Q-Sphere](https://github.com/Nuxoraa/Quantum-Simulator-Repository-Setup-English-/blob/main/qsphere.png)

## 👨‍💻 Development / Разработка

### 🇬🇧 Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

### 🇷🇺 Участие в разработке
Приветствуются pull requests! Алгоритм:
1. Форкните репозиторий
2. Создайте ветку для своей фичи
3. Закоммитьте изменения
4. Запушьте в ветку
5. Создайте Pull Request

## 📜 License / Лицензия
MIT License - see [LICENSE](LICENSE) file for details  
Лицензия MIT - подробности в файле [LICENSE](LICENSE)








ENG:
(attention, perhaps in the process of promoting and
updating the project, the components of the repository
may become inoperative, for example, links, etc., so please, 
if you see this, then perhaps I will fix it soon, thank you for
understanding, for me it is difficult since I work solo and I am only 
14, thank you for understanding again :)


RUS:
(внимание возможно в процессе продвижения
и обновления проекта компоненты 
репозитория могут стать не рабочими на пример ссылки 
и тд так что просьба если видите такое то возможно в скоре я это 
исправлю спасибо за понимание для меня это тяжело так как я работаю 
соло и мне всего 14 спасибо за понимание еще раз :)
