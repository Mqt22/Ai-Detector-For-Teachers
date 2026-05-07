# Ai-Detector-For-Teachers
1. The Trigger (Webhook)
The process starts when an external app (like a form or a website) sends data to this workflow. Think of this as the "Incoming Mail" box.

2. The Filter (If)
The workflow checks a specific condition. For example, it might be asking: "Does this message contain a PDF?" * If Yes (True): It moves forward.

If No (False): The process stops.

3. The Reader (Extract from File)
The system "reads" the PDF document and turns the visual text into data that a computer can easily understand.

4. The Brain (AI Agent)
This is where the magic happens. An AI (powered by Groq) looks at the text from the PDF. You’ve likely programmed it to do something specific, like: "Find the total price and the vendor name from this invoice."

5. The Organizer (Edit Fields & Append Row)
Edit Fields: The workflow cleans up the AI's answer so it fits perfectly into a table.

Append row in sheet: Finally, it automatically types that information into a Google Sheet, creating a new row so you have a clean, organized log of all your documents.
