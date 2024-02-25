# 3850-Project-4
Used to re-create DS-3850 python coding projects using AI (ChatGPT 3.5)

def introduce_projects():
    # Display introduction
    print("Welcome to Braden Pickell's GitHub Repository!")
    print("Here, you can find a collection of projects completed during the DS 3850 programming class at Tennessee Tech University.")
    print("Let's explore some of the projects!")

    # List of project names and descriptions
    projects = [
        {"name": "Quiz Bowl", "description": "A trivia game where players answer questions on various topics."},
        {"name": "MadLib", "description": "A fun game where users fill in the blanks to create humorous stories."},
        {"name": "Powerball", "description": "A random number generator for generating Powerball numbers."},
        # Add more projects as needed
    ]

    # Display projects and descriptions
    print("\nProjects:")
    for idx, project in enumerate(projects, start=1):
        print(f"{idx}. {project['name']}: {project['description']}")

if __name__ == "__main__":
    introduce_projects()
