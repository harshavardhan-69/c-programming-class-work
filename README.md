#include <stdio.h>

//Define the "student" structure
struct student {
  char name[50];
  int id;
  float gpa;
};

int main() {
  // Declare a "student" variable
  struct student my_student;

  // Set the fields of the "student" variable
1  printf("Enter student name: ");
  scanf("%s", my_student.name);

  printf("Enter student ID: ");
  scanf("%d", &my_student.id);

  printf("Enter student GPA: ");
  scanf("%f", &my_student.gpa);

  // Print out the fields of the "student" variable
  printf("\nStudent name: %s\n", my_student.name);
  printf("Student ID: %d\n", my_student.id);
  printf("Student GPA: %f\n", my_student.gpa);

  return 0;
}
