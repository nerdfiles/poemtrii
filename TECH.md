# TECH

## Client-side Speech Collection

Collect MP3 Audio Data from Browser via https://github.com/zzarcon/microm.

## Speech Format Conversion

Use ``pip install pydub`` to convert audio data to WAV format:

    from pydub import AudioSegment
    sound = AudioSegment.from_mp3("/path/to/file.mp3")
    sound.export("/output/path", format="wav")

## Speech-based Token Assessment

Use ``pip install SpeechRecognition`` to convert to text, mapping to tokens of text 
rendered to the user for matching.

## Speech-based Navigation

Use SpeechRecognition to map to canonical links and link relationships.
Use SpeechRecognition for non-normative assistive link menus.
Use SpeechRecognition for inline taxonomic navigational menus.
Use SpeechRecognition for inline model navigation properties, complex properties, 
queries, property paths, metadata storage changes, model notification updates.
