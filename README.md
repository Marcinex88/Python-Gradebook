# Python-Gradebook

last_semester_gradebook = [("politics", 80), ("latin", 96), ("dance", 97), ("architecture", 65)]
subjects = ["physics","calculus","poetry","history"]
grades = [98, 97, 85, 88]
subjects.append("computer_science")
grades.append(100)
subjects.append("visual_arts")
grades.append(93)
gradebook = zip(subjects, grades)
print(gradebook)
print(list(gradebook))
full_gradebook = list(gradebook) + last_semester_gradebook
