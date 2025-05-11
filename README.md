class Weather:
    def __init__(self, date, humidity, night_weather, day_weather):
        self.date = date
        self.humidity = humidity
        self.night_weather = night_weather
        self.day_weather = day_weather

    def __str__(self):
        return f"Дата: {self.date}\nВлажность: {self.humidity}%\nПогода ночью: {self.night_weather}\nПогода днем: {self.day_weather}"

# Пример создания объектов класса
weather1 = Weather("2025-05-10", 75, "Облачно", "Солнечно")
weather2 = Weather("2025-05-11", 80, "Дождливо", "Облачно")

# Вывод информации о погоде
print(weather1)
print()
print(weather2)
