# Semenuk Andrey Nikolaevich

**Contact Information:**

- Phone: +375 29 2534534
- E-mail: asemenuk100@gmail.com
- Telegram: @semenukan

**Briefly About Myself:**
I am driven to create innovative solutions and continuously pursue personal development. My goals include not only achieving success in the professional sphere but also creating something new and valuable for society.

**Goals and Priorities:**
My drive to create something new inspires me to seek creative solutions and innovations. I aspire to contribute to areas where communication and perseverance play a key role. My goal is to develop and refine my skills to interact effectively with colleagues and overcome any professional challenges.

**Strong Points:**
One of my strengths is a high level of communicability. I can establish common ground with different people, facilitating successful teamwork. My experience in learning and developing personal skills demonstrates my readiness for continuous self-improvement.

**Experience:**
Currently, my work experience is limited to the absence of formal experience. However, I am ready to contribute my knowledge and enthusiasm to a new field. My experience in education and self-learning, as well, as the ability to quickly absorb new information, makes me adaptive and prepared for any professional tasks.

I am confident that my qualities and commitment to development can significantly enrich your team. I am ready to start my professional journey and invest all my energy in achieving common goals.

## Skills and Proficiency:

- HTML, CSS, JS
- Python, Django, Django Rest Framework
- Java Basics
- C# Basics
- Git, GitHub
- Sublime, Visual Studio, VS Code, PyCharm, Eclipse IDE

## Code Example:

_Write a Python program to solve the traveling salesman problem. Given a set of cities with known distances between them, find the shortest path that passes through each city exactly once and returns to the starting city._

```python
from itertools import permutations

def calculate_total_distance(path, distances):
    total_distance = 0
    for i in range(len(path) - 1):
        total_distance += distances[path[i]][path[i + 1]]
    total_distance += distances[path[-1]][path[0]]
    return total_distance

def traveling_salesman_bruteforce(distances):
    num_cities = len(distances)
    all_paths = permutations(range(num_cities))

    shortest_path = None
    shortest_distance = float('inf')

    for path in all_paths:
        current_distance = calculate_total_distance(path, distances)
        if current_distance < shortest_distance:
            shortest_distance = current_distance
            shortest_path = path

    return shortest_path, shortest_distance

distances = [
    [0, 10, 15, 20],
    [10, 0, 35, 25],
    [15, 35, 0, 30],
    [20, 25, 30, 0]
]

shortest_path, shortest_distance = traveling_salesman_bruteforce(distances)

print(f"Shortest path: {shortest_path}")
print(f"Path length: {shortest_distance}")
```

**Courses**

- Путь в IT Python PRO (in progress)
- JavaScript/Front-end 2023Q4\*\* (in progress)

**Languages:**

- Russian - Native
- English - Intermediate/Upper-intermediate (according to the online test at [www.efset.org](www.efset.org))
