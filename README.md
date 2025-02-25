# ADS
This project was developed for the Architecture and Software Development course as part of our Master's program. The goal was to create a solution for a common problem we face daily: attendance tracking in university classes and the inefficient use of classroom space due to the lack of real-time student occupancy data.

Our proposed solution leverages QR codes to identify classrooms. Each student can scan the QR code with their mobile device to mark their attendance. We developed a system that scans the QR code and redirects the user to an HTML page where their presence is recorded. Additionally, we implemented methods to collect and analyze the attendance data efficiently.

To ensure the usability and adoption of the solution, we focused on making the technology accessible and user-friendly. Data integrity was also a key concern, so attendance validation includes an IP address check to prevent multiple submissions from the same device for a specific class. Future improvements could include geolocation verification and biometric data hashing to further enhance security, though these were not implemented in this version as they were outside the scope of the course.

This project provides a foundation for a more efficient and reliable attendance tracking system, with the potential for further expansion and real-world application.
</br>
# Testes-afk.github.io
frontend.py -> pede o num de aluno e escaneia o QR code com a sala <br/>
landingpage -> inicia com os dados do py e confirma<br/>
confirmacao -> o utilizador é redirecionado pra essa pg dps de confirmar<br/>
index -> lista de presenças 
