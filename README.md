# Define a function to create a CV form
def create_cv_form(name, email, phone, education, experience, skills):
    print("-------------------------------------------------")
    print("            Curriculum Vitae Form")
    print("-------------------------------------------------")
    print("Name:", name)
    print("Email:", email)
    print("Phone:", phone)
    print("\nEducation:")
    for edu in education:
        print("-", edu)
    print("\nExperience:")
    for exp in experience:
        print("-", exp)
    print("\nSkills:")
    for skill in skills:
        print("-", skill)
    # Inserting an image using Markdown syntax
    print("\n![Profile Picture](https://cdn-icons-png.flaticon.com/512/3001/3001764.png)") 

# Define CV data
name = "Ahmer "
email = "ahmer@example.com"
phone = "+1234567890"
education = [
    "Bachelor of Science in Computer Science, Punjab University , 2026",
    "Master of Science in Computer Science, Punjab University, 2028"
]
experience = [
    "Data Analyst, Company A, 2028",
    "Software Engineer, Company B, 2027"
]
skills = ["Python", "Data Analysis", "Machine Learning"]

# Call the function to create the CV form
create_cv_form(name, email, phone, education, experience, skills)
