
# Порівняння відповідей

## 📝 Запит: Що таке згорткові нейронні мережі?

## 🔍 Відповіді моделей

### Без використання RAG

Згорткові нейронні мережі (CNN, Convolutional Neural Networks) — це тип глибоких нейронних мереж, які спеціально розроблені для обробки даних з сітковою структурою, таких як зображення. Вони використовують згорткові шари для автоматичного виділення ознак, що дозволяє ефективно розпізнавати об'єкти, текстури та інші елементи в зображеннях. CNN зазвичай складаються з кількох згорткових шарів, шарів підвибірки (пулінгу) та повнозв'язних шарів, що робить їх потужними для задач комп'ютерного зору, таких як класифікація зображень, детекція об'єктів та сегментація.

### З використанням RAG

Згорткові нейронні мережі (CNN) — це тип нейронних мереж, які спеціально розроблені для обробки даних з решітковою структурою, таких як зображення. Вони використовують згорткові шари для автоматичного виділення ознак з вхідних даних, що дозволяє ефективно виконувати завдання, пов'язані з класифікацією, розпізнаванням об'єктів та іншими задачами комп'ютерного зору. Згорткові мережі здатні виявляти складні патерни та структури в даних, що робить їх потужним інструментом у сфері штучного інтелекту.

## 📚 Знайдені фрагменти тексту


### Фрагмент 1 (відстань: 0.9587)

**Шлях**: data/own_framework.md

# Introduction to Neural Networks. Multi-Layered Perceptron In the previous section, you learned about the simplest neural network model - one-layered perceptron, a linear two-class classification model. In this section we will extend this model into a more flexible framework, allowing us to: * perform


### Фрагмент 2 (відстань: 0.9745)

**Шлях**: data/perceptron.md

array, so the neural network had 400 inputs and one binary output. A simple network contained one neuron, also called a **threshold logic unit**. Neural network weights acted like potentiometers that required manual adjustment during the training phase. > ✅ A potentiometer is a device that allows the


### Фрагмент 3 (відстань: 0.9998)

**Шлях**: data/own_framework.md

**multi-class classification** in addition to two-class * solve **regression problems** in addition to classification * separate classes that are not linearly separable We will also develop our own modular framework in Python that will allow us to construct different neural network architectures. ## Formalization


### Фрагмент 4 (відстань: 1.0301)

**Шлях**: data/own_framework.md

data. Because subset is taken randomly each time, such method is called **stochastic gradient descent** (SGD). ## Multi-Layered Perceptrons and Backpropagation One-layer network, as we have seen above, is capable of classifying linearly separable classes. To build a richer model, we can combine several


### Фрагмент 5 (відстань: 1.0328)

**Шлях**: data/perceptron.md

# Introduction to Neural Networks: Perceptron One of the first attempts to implement something similar to a modern neural network was done by Frank Rosenblatt from Cornell Aeronautical Laboratory in 1957. It was a hardware implementation called "Mark-1", designed to recognize primitive geometric figures,

