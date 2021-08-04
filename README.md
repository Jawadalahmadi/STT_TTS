# STT_TTS
One single code where we convert speech to text &amp; text to speech and make them convert to .txt file and mp3 respectfully 


# Transcribe
Taking the code from the watson-straeming-stt file, what we did was add our own APIKEY and URL for both STT and TTS services to it.
Then i went to the on_message method part of the file and i edited with adding variable "p" which includes the message spoken while recording, then using the "with open" command we created out txt file name output.txt which will turn the speech to text  in it, then using the same command we created a MP3 file named speech.mp3( both txt and mp3 files are included in the watson-streaming-stt file) to save the output "p" and turn the text to speech which you can listen to after running the program.

NOTE: "This program was working fine and fast with only the txt file command included but after adding the mp3 file command there is a little delay in hearing your voice and it may not register the right words that you utter so you may have to run the program for a little longer like 20 sec.
