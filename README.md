class Attributes(Programer12):
    def __init__(self) -> None:
        super().__init__()
        
    @staticmethod
    def contact() -> str:
        return "No contact information provided.
        

    @staticmethod
    def life() -> tuple:
        age = None
        langs = ['French', 'English']
        return langs, age

    @staticmethod
    def coding() -> tuple:
        learning = "python"
        specialities = 'automation'
        environment = 'vscode'
        return learning, specialities, environment
