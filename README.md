# BeatKenja
Beat Saber automapping tools:
1. timing creation
2. fix timings
3. convert any map into a timings map:
   1. without stacks
   2. with stacks
4. read and write v2.2.0 maps
5. create a really simple linear two handed pattern

#Setup
1. install aubio:

    either:
   1. download precompiled version & extract it to the folder "aubio/". The auboonset.exe should be in ./aubio/bin/aubioonset.exe
   2. or install it so that "aubioonset song.wav" is possible.
2. Put the gson.jar into "libs/"

#How to use
1. create the onsets with and write it into timings.txt "aubioonset song.wav > timings.txt"
2. (more will be added here)

#TODOs:
1. creating new pattern types:
   1. one handed
   2. doubles
   3. more variation
2. Better music onsets