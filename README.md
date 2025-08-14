I built a movie search app using React.js and the TMDb API to let users quickly find and explore movies. 

I used a debounce feature with react-use so the app waits 500ms after typing before searching, which reduces unnecessary API calls. 

I integrated Appwrite to track trending movies. each search updates or creates a record in the database, and the top results are shown in a trending section. The app includes a loader for smooth UX, error handling for failed requests, and a clean, responsive design with Tailwind CSS.

Tech Stack: React.js | TMDb API | react-use (debounce) | Appwrite | Tailwind CSS
