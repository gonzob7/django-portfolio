1. The Django structure is built to benefit larger projects. urls.py takes care of all the urls in the project, think of it as a table of contents. Views.py is in charge of displaying information on the front-end

2. We use separate urls files, one is for the project directory, and all the other for each app we create within the project.

3. It is desirable to split into different apps when the features are large and in their own category, for organizing/refactoring purposes.
