# # Flashy - French Vocabulary Flashcards App
An interactive **Flashcard Learning App** built with Python and Tkinter.  
It helps you memorize French vocabulary by flipping cards - if you know a word, it’s removed from your learning list automatically!

## ✨ Features
- 🧠 **Flashcard Learning** - displays a random French word and flips to show the English translation after a few seconds  
- ⏱️ **Automatic Flip Timer** - card flips every 3 seconds for quick recall training  
- 💾 **Progress Tracking** - words you already know are removed and saved to a `words_to_learn.csv` file  
- 🔄 **Persistent Data** - next time you open the app, it continues from where you left off  
- 🎨 **Beautiful UI** - smooth card animations, clean interface, and easy navigation  

## 🧰 Technologies Used
- **Python 3**
- **Tkinter** - for the GUI  
- **Pandas** - for reading and writing CSV data  
- **Random** - for selecting words randomly  

## 🚀 How It Works

1. When you start the app, a **French word** appears on a flashcard.  
2. After 3 seconds, the card flips to show the **English translation**.  
3. If you know the word, click ✅ - it’s removed from your learning list.  
4. If not, click ❌ - it stays in the rotation.  
5. Your progress is saved automatically in `data_files/words_to_learn.csv`.

⚙️ Installation & Usage
1. Clone this repository:
git clone https://github.com/<your-username>/flashy.git
cd flashy
2. Install required package:
pip install pandas
3. Make sure you have the images and data_files folders in the same directory as main.py.
4. Run the program:
python main.py

## 💡 Future Improvements
- 🎧 Add text-to-speech for pronunciation
- 🌐 Add multiple languages (Spanish, German, etc.)
- 📊 Add statistics tracking (progress over time)
- 💾 Add backup/sync support

