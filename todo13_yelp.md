# To-do 13: Poking at Big Data (Yelp)

## Na-Rae the fake student:
- My 5-year-old ThinkPad laptop did ok! It has ... RAM, which worked ok with this much data, etc. Grepping through the whole of xxx json file took...

## Dastan
- I have a 7 year old custom built computer with 32GB of RAM and a AMD 2700x processor
- Grepping through the file was relatively quick, only taking a few seconds at most
- I was able to go up to 1,000,000 which took about 38 seconds real time, I tried 5,000,000 and 10,000,000 but they all caused MemoryErrors in the program. Everything below 1,000,000 took less than 10 seconds for me.
- When running the 5,000,000 and the 10,000,000 my activity monitor was off the charts, almost 99% memory utilization at the peak, having chrome opened also played a role in that percentage but it was marginal compared to the python script

## Maddy
- I have a 3ish year-old Dell XPS 13 with 16GB of RAM and a mid range intel i7 processor
- Grepping through the file was relatively quick, only taking a few seconds
- Everything below 1,000,000 was relatively quick (< 1 minute), but that and above took several minutes and used all of my computer's memory
- I also tried the full file and gave up because it was taking too long and my computer was getting very hot

## Maya
- I have a 2021 MacBook Pro with 16 GB of RAM and an Apple M1 Pro chip.
- Grepping through the file wasn't instaneous but was still quick.
- My computer was able to handle 1,000,000, but 10,000,000 proved to be too much for it because it ran for a long time until I finally gave up and terminated it. I was streaming music on my computer at the same time and the audio started cutting out, and the activity monitor was showing large readings, so my poor computer was hard at work. 

## Riley
- I have a 4-year-old MacBook Pro with 16 GB of RAM and an Intel Core i5 processor
- grepping only took a few seconds max
- 100000 or less was under 10 seconds, but 1 million took just under a minute
- When I tried the full file, I waited about 10 minutes and it hadn't finished and my fan was working overtime so I stopped

## Teresa
- I Have a 4-year-old MacBook Pro with 16 GB of RAM and an Intel core i5 processor
- The grepping took a little while to get the line count and the tail, but definitely less than a minute
- Up to 1 million the python script took just a few seconds to run but then it slowed down significantly.
