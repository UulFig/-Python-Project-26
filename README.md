# -Python-Project-26
#26 Simple grade score

student_scores = {
    "Harry": 81,
    "Ron": 78,
    "Hermione": 99,
    "Draco": 74,
    "Neville": 62,
}
student_grade = {}

for score in student_scores:
    scores = student_scores[score]
    if scores > 91:
        student_grade[score] = "Outstanding"
    elif scores > 81:
        student_grade[score] = "Exceeds Expectation"
    elif scores > 71:
        student_grade[score] = "Acceptable"
    else:
        student_grade[score] = "Fail"

print(student_grade)
