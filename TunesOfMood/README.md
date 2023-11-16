# TunesOfMood
Song Recommendation based on expression / gestures

😀 Smile -> happy

🤘(Rock on (hand sign)) -> energetic

👌(ok hand)-> calm

👎(thumbs down): -> sad

# Opening View
<img width="1438" alt="Screenshot 2023-07-06 at 7 35 26 PM" src="https://github.com/anusha-adhikari/TunesOfMood/assets/74814765/294ca075-6c61-4232-aef2-b387db7711d0">

# Recognizing Expression/Gestures
<img width="1440" alt="Screenshot 2023-07-06 at 7 37 19 PM" src="https://github.com/anusha-adhikari/TunesOfMood/assets/74814765/31d4945b-1359-41da-b4be-85e6c6fe4104">

<img width="1439" alt="Screenshot 2023-07-06 at 7 37 36 PM" src="https://github.com/anusha-adhikari/TunesOfMood/assets/74814765/974cf28f-7beb-4aa8-9497-8aa275d99008">

<img width="1440" alt="Screenshot 2023-07-06 at 7 37 51 PM" src="https://github.com/anusha-adhikari/TunesOfMood/assets/74814765/7f6034fe-6583-44b0-bb31-ad388c160726">

<img width="1440" alt="Screenshot 2023-07-06 at 7 38 08 PM" src="https://github.com/anusha-adhikari/TunesOfMood/assets/74814765/c58b6753-62e6-402e-bc1d-a05c2fdd05c7">

# List of songs collected for “energetic”:
<img width="1438" alt="Screenshot 2023-07-06 at 7 44 53 PM" src="https://github.com/anusha-adhikari/TunesOfMood/assets/74814765/085f5efb-1c62-46ed-8862-54e47d4579c9">

# Files Explained :
1) dataCollection.py - To collect the moods/gestures (data) using mediapipe framework with corresponding labels.
2) dataTraining.py - To train the model with moods/gestures and corresponding labels using keras’ models.Model, compile, fit, layers.Input, layers.Dense
3) recommend.py - Using Streamlit to create a user interface (local) and to recommend songs depending on the mood/gesture detected. Songs were recommended using conditions for different moods.
4) .npy - dataset for each expression/gesture (400 images)

# Challenges faced (ML background) :
1)  Forced to establish a user interface within a night, due to unforseen circumstances.
2)  Unstable server connection on streamlit
3)  Adapted to situation quickly and was able to create a local interface.

