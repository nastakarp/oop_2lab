Данное консольное приложение работает с 2 файлами: address.xml и address.csv. Это - файлы-справочники, в которых хранится информация об этажности домов, находящихся в разных городах. Программа выводит дублирующиеся записи, статистику этажности по городам, время обработки файла. В ходе работы задание было разбито на 5 файлов с разными классами. Каждый файл содержит код, предназначенный для выполнения определенных действий:

- класс Java CsvParser предназначен для чтения данных из CSV-файла и преобразования их в удобный для работы формат.
- класс Java XmlParser предназначен для чтения данных из XML-файла и преобразования их в удобный для работы формат.
- класс FileProcessor выполняет роль универсального обработчика файлов разных форматов (в данном случае CSV и XML).
- класс Statistics предназначен для анализа данных о записях, таких как дублирующиеся адреса и статистика этажей зданий по городам.
- класс DirectoryProcessorApp представляет собой основное приложение, которое позволяет запустить программы из 4 других файлов.

Программа была разработана Ксенией Шинкарь и Анастасией Карпенко
