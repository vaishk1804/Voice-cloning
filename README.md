# Voice-cloning

An implementation of cloning a person's voice from Hindi to English , while mantaining pitch and audio tone.

After cloning the tortoise repository:

- Save the audio file you want clone from hindi to english into the tortoise-tts folder as "test.wav"
- Save samples of the speaker's audio in a new folder in tortoise-tts/tortoise/voices
- Use the name of the audio sample folder as VOICE_NAME while generating the cloned voice.


Input provided:
- Shahrukh voice samples ( present in the shahrukh folder, folder saved to tortoise-tts/tortoise/voices for running the model)
- test.wav ( saved to tortoise-tts folder , contains audio to be cloned)

Output: 
- generated-shahrukhclone.wav file
