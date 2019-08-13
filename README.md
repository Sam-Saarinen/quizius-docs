# quizius-docs
Documentation for the quizius quiz-generation platform.

## For Students:
Just follow the instructions upon first logging in (and create an account/register if you have not logged in). You may need to register for the course using the system (registration is as simple as finding the course listing on the courses page and adding yourself to it). You will then be able to see a list of quizzes that are active for that class.

## For Instructors:
Setup is simple; there are only 5 steps.

1. Set up an instructor account. This will likely require an administrator (sam_saarinen@brown.edu) to create an account for you or change the permissions on your existing account.
2. Create a course in quizius. You will need to specify the course title and course id. The admin can also help you with this. You will also need to identify start and end dates. Note that this determines when the course will be available in the enrollments page, and should not necessarily reflect the actual start and end dates of the course.
3. Create a quiz. This will require several pieces of information
  * Parent Course - If you are running multiple courses, you will have to select which one the course belongs to.
  * Quiz Title - Give an informative title for the quiz to help students understand the scope.
  * Start and End Dates, and Late Days Allowance - Allow students to submit the quiz with up to n late days, for courses with late day grading policies.
  * is filtered and subset id - EXPERIMENTAL! This is used for running multiple forms of quiz for the purpose of A/B testing. To run quizzes using this feature, please contact the admin for support. Otherwise, leave the default (blank) settings.
  * uses dynamic - leave this checked to allow student-authored questions to be shown to other students, and to filter based on response statistics. Uncheck this to serve a static quiz using only questions authored (by the instructor) before the start date.
  * num q and max q - what are the minimum and maximum numbers of questions students can write in order to complete the assignment. If writing a question is required, "num q" should be set to a number 1 or greater.
  * Q Prompt - This is the text students will see when prompted to write a question.
  * Extra Details - This is hide-able information available while the students are writing and answering questions. Common uses include displaying pre-made classes that can be referenced, tables, definitions, or meta-information.
  * Q input type - changes syntax highlighting and formatting settings for question authoring. E.g. if students are supposed to write short Java programs, this can be set to Java Input for appropriate formatting.
  * num a - the minimum number of questions a student has to answer in order to complete the quiz. If no more questions are available, the student's quizzed will be marked complete. However, all students are able to go back and answer extra questions if they are available.
  * A prompt - the prompt that the student will see (in addition to the question text) when answering questions in quizius. This should include any extra information that applies to all questions, such as what to do if the question is ill-posed or causes errors.
  * A Input Type - Formatting rules for the answers students write. For most situations, this should be Plaintext.
4. (Optional) Contribute Initial Questions to the Quiz. This can be done by going through Quizzes->Show->Write Question (at the bottom of the page)
5. Have students login to the system, enroll in the course, and complete the quiz. If you launch multiple quizzes in one course, they will be able to see upcoming quiz dates as well. Results can be seen by following the links from the quizzes page, to see completion records or to see the contributed questions and variety of responses.

