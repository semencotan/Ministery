class Ministry:
    def __init__(self, name, budget):
        self.name = name
        self.budget = budget

    def get_info(self):
        return f"Ministry: {self.name}, Budget: {self.budget}"

# Пример использования класса Ministry
ministry_of_education = Ministry("Ministry of Education", 1000000)
print(ministry_of_education.get_info())

ministry_of_health = Ministry("Ministry of Health", 1500000)
print(ministry_of_health.get_info())
