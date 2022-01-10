# haiiku
This project is an attempt to use deep learning to generate haikus that conform to the 5-7-5 syllable pattern. Much previous research into generating haikus doesn't enforce syllable counts, largely because modern English haikus often don't strictly conform to that pattern either. This makes finding training data difficult. I get around this problem by providing the syllable count of each line as an input to the network along with the text at training time. Then, at generation time, I can choose how many syllables I want for each line. This project is still early, but so far I've gotten some promising results.

Here an examples of 5-7-5 syllable output:

early morning sun

from the carried garden fate

stars at the sunset


And if I use the same network to get a 10-10-10 poem:

just as the street lamp spake the sun is bright

and the soul and the spring are blowing

with every beat of my heart i will love you
