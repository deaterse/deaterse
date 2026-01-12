<h1 align="center">
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28">
  Hey, I'm Radomir! 
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28">
</h1>

```python
class SoftwareDeveloper:
    def __init__(self):
        self.name = "Radomir"
        self.age = 19
        self.location = "Russia"
        self.passion = "Game Development & Web3"
        
    @property
    def skills(self):
        return {
            '🎮 Game Dev': ['Unity', 'C#', 'Blender', 'Aseprite'],
            '🌐 Web Dev': ['React', 'Bootstrap', 'Flask', 'Python'],
            '🗣️ Languages': ['Russian (Native)', 'English (B2)', 'Japanese (N5)'],
            '🚀 Currently Learning': ['Multiplayer', 'Procedural Generation']
        }
    
    def say_hi(self):
        return "Passionate about creating immersive games and scalable systems!"

me = SoftwareDeveloper()
print(me.say_hi())
