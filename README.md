class MonjimaDey:
    def __init__(self):
        self.name = "Monjima Dey"
        self.education = "B.Tech in Computer Science and Engineering at Narula Institute of Technology"
        self.cgpa = 9.19
        self.skills = [
            "Java", "Python", "C", "C++", "SQL",
            "Spring Boot", "MongoDB", "MySQL", "Git", "Postman"
        ]
        self.interests = [
            "Machine Learning", "Software Development", "IoT Systems", "Generative AI"
        ]
        self.projects = [
            "EcoBazarX – Carbon Footprint Aware Shopping Assistant",
            "Sports Car Price Prediction Model",
            "Netflix-style Content Recommendation Engine",
            "IoT-based Product Counting System"
        ]
        self.achievements = {
            "HackerRank": "5⭐ in C and Java",
            "Hackforge Hackathon (JU)": "Second Runner-Up",
            "Smart India Hackathon": "Participant (2023, 2024)",
            "NPTEL": ["Soft Computing (Topper)", "IoT (Elite)", "Computer Networks"]
        }
        self.current_learning = ["Spring Boot", "Generative AI", "Advanced Problem Solving"]
        self.fun_fact = "I love solving complex problems and building impactful, intelligent systems!"

    def introduce(self):
        print(f"Hi there! 👋 I'm {self.name}, a passionate developer and tech enthusiast.")
        print("I enjoy blending creativity and logic to build real-world solutions.")

# Create an instance
me = MonjimaDey()
me.introduce()
