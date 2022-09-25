# Синопсис

Эксперимент по подделке отпечатков камеры с помощью генеративных нейросетей (GAN)

# Содержание

Проект содержит следующие папки:

Images - Изображения, предоставленные вместе со сборкой алгоритма снятия отпечатка камер, используются для экспериментов с алгоритмом в одном из файлов
Img_postcompress - Изначальная выборка изображений с камеры телефона, сжатая до приемлемого масштаба
Img_train - датасет изображений, используемый в обучении нейросети
generated images - папка, в которую сохраняются образцы изображений, сгенерированных в процессе обучения нейросети
models - папка, в которую сохраняются модели на разных этапах обучения
archive - Папка, в которой хранятся модели и изображения самой последней версии нейросети, приложенной в проекте
algo_test - выборка изображений из датасета для обучения и изображений, сгенерированных нейросетью, используется для финального сравнения отпечатков сгенерированных изображений с отпечатком камеры
src - Папка с файлами алгоритма снятия отпечатка камер (camera fingerprinting)

Проект содержит следующие блокноты:

Fingerprint experiments - серия экспериментов с алгоритмом снятия отпечатка камер, приведена в удобный для чтения вид
picGAN - финальная версия генеративной нейросети, генерирующей изображения
Final Testing - итоговый тест схожести отпечатка сгенерированных изображений и отпечатка фотографий с камеры телефона