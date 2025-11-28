# Using Imperatives, Should in IT- 5°

To ensure that the Course Management project runs correctly after every update, it is essential to install and keep all frontend dependencies up to date. 
Whenever you pull from the repository, you must install the core libraries such as React and React-DOM along with their corresponding type definitions, 
and run a general npm install to synchronize all required packages. It is also necessary to install tools used for generating documents, such as xlsx and 
file-saver for data exports, and jspdf with jspdf-autotable for creating PDF reports; in some cases, if an issue appears, reinstalling jspdf individually
is recommended. To handle communication with the backend, installing axios and its type definitions is indispensable, ensuring stable and consistent 
integration with server-side services. Once all dependencies are properly configured, the project should be launched using npm run dev, which starts 
the development environment and allows you to view and test all course-related functionalities.

From a practical perspective, these actions reflect the logic of Imperatives and Should. Imperatively, you are required to install dependencies,
run the correct commands, and configure the environment so the project works. From the Should perspective, you are encouraged to keep packages updated,
verify installations after each pull, check the console for errors, and ensure that all tools for data processing and report generation are working as expected.
Together, these practices help the course management platform operate smoothly, efficiently, and professionally, providing a solid experience both for developers and for end users.


















IMPERATIVES vs SHOULD – Gestión de Cursos
Imperative | Should
Instala las dependencias ahora
- You should install the required dependencies after every pull.
(npm install xlsx file-saver jspdf jspdf-autotable axios)

Ejecuta el proyecto
- You should run the project with npm run dev to start the frontend.

Configura Axios correctamente
- You should ensure Axios is installed or add @types/axios if needed.

Mantén tu entorno actualizado
- You should reinstall dependencies whenever package.json changes.

No ignores los errores de consola
- You should check the console logs to prevent issues during course management.
