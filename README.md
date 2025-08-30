from googletrans import Translator

# Initialize the Translator
translator = Translator()

# Input Hindi text
text_hindi = "Mere liye Safar Safar Jaisi game Jaisi"

# Translate Hindi text to English
translation = translator.translate(text_hindi, src='hi', dest='en')

# Print the translated text
print("Translated Text:", translation.text)

pip install googletrans==4.0.0-rc1
