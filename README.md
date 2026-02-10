```python
class SoftwareDeveloper:
    def __init__(self):
        self.name = "Radomir"
        self.age = 19
        self.location = "Russia"
        self.passion = "Game Dev"
        
    @property
    def skills(self):
        return {
            'Programming Languages': ['C#', 'Python', 'JS'],
            'Instruments': ['Unity', 'Aseprite', 'Github', 'Figma', 'Photoshop']
            'Languages': ['Russian (Native)', 'English (B2)', 'Japanese (N5)'],
        }

me = SoftwareDeveloper()
