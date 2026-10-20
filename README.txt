HOSPITAL QUEUE MANAGEMENT SYSTEM
=================================

Project overview
----------------
This is a simple hospital reception queue management application built with
HTML, CSS, and JavaScript. It demonstrates the FIFO (First In, First Out)
principle using a JavaScript array.

How to run
----------
1. Extract the ZIP file.
2. Open the Hospital-Queue-System folder.
3. Double-click index.html to open it in a web browser.
   Alternatively, open the folder in VS Code and run index.html with Live Server.

How to use
----------
1. Enter a patient's name.
2. Click "Add Patient" to add them to the end of the queue.
3. Click "Call Next Patient" to serve the first patient.
4. The waiting list, number of waiting patients, and number served will update.
5. "Clear Queue" clears the waiting list.

Queue operations
----------------
- patientQueue.push(name): adds a patient to the end of the queue.
- patientQueue.shift(): removes the first patient from the queue.
- patientQueue.length: counts the patients currently waiting.
- patientQueue.forEach(...): displays each waiting patient.

Important note
--------------
This is an educational demonstration. The queue is held in browser memory, so
refreshing the page resets it. It is not intended for real patient records.
