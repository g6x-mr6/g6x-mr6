# Hello everyone, im GHOS6T
class Student:
    def __init__(self):
        self.name = "GHOS6T"
        self.country = "Jordan 🇯🇴"
        self.status = "Future University Student 🎓"
        self.major = "Computer Science 💻"
        self.interests = [
            "Programming",
            "Technology",
            "Problem Solving",
            "Learning"
        ]
        self.goal = "Become a Software Developer 🚀"

    def introduce(self):
        print("Hi, I'm GHOS6T 👋")
        print("I'm from Jordan 🇯🇴")
        print("I'm a Future University Student 🎓")
        print("I want to study Computer Science 💻")
        print("I'm interested in:")
        
        for interest in self.interests:
            print(f"- {interest}")
        
        print("My goal is to become a Software Developer 🚀")


me = Student()
me.introduce()
