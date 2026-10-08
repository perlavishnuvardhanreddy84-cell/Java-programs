public class UniversityStudentRecordSystem {

    static class Student {
        int id = 101;
        String name = "VISHNU";
        int age = 19;
        double marks = 90;
        double attendance = 90;

        void display() {
            System.out.println("===== UNIVERSITY STUDENT RECORD SYSTEM =====");
            System.out.println("Student ID : " + id);
            System.out.println("Name       : " + name);
            System.out.println("Age        : " + age);
            System.out.println("Marks      : " + marks);
            System.out.println("Attendance : " + attendance + "%");

            if (marks >= 90)
                System.out.println("Grade      : A+");
            else if (marks >= 80)
                System.out.println("Grade      : A");
            else if (marks >= 70)
                System.out.println("Grade      : B");
            else if (marks >= 60)
                System.out.println("Grade      : C");
            else
                System.out.println("Grade      : F");

            if (attendance >= 75)
                System.out.println("Status     : Eligible");
            else
                System.out.println("Status     : Not Eligible");
        }
    }

    public static void main(String[] args) {

        Student s = new Student();

        s.display();
    }
}
