# Gesture Glasses

Runs on the MicroLumin M6 glasses only. The glasses camera watches the hands of the person
in front of you and shows the meaning in big green text (and speaks it, if the glasses have a voice).

- Change what each gesture says: `phrases` at the top of `app/src/main/java/com/worn/gestureglasses/MainActivity.kt`
- Your own signs: train with `train_signs.ipynb` in Google Colab, then put the downloaded
  `gesture_recognizer.task` in `app/src/main/assets/` (replace the old one) and press Run again.
- Status line (bottom-left of the display): camera, model, frames per second, voice.
- Logs: `adb logcat -s Gesture`

Built-in gestures: Thumb_Up=Yes, Thumb_Down=No, Open_Palm=Hello, Closed_Fist=Stop,
Pointing_Up=Wait, Victory=Peace, ILoveYou=I love you.
