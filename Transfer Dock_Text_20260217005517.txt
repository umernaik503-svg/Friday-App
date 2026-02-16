from kivy.app import App
from kivy.uix.label import Label

class FridayApp(App):
    def build(self):
        return Label(text='Friday AI is Online, Boss!')

if __name__ == '__main__':
    FridayApp().run()