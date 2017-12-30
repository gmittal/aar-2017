# AAR 2016-2017
Training deep LSTM neural networks to model conversations as a part of the [PAUSD Advanced Authentic Research (AAR) Program](https://aar.pausd.org/) for the 2016-17 academic year. I've chosen to focus on computer-generated responses within spam email chains for my project, partially inspired by [James Veitch's TED talk](http://bit.ly/1PTmSxS).

Project by [Gautam Mittal](http://www.gautam.cc)<br />
Mentor: [Melanie Tory](https://research.tableau.com/user/melanie-tory)

Update (December 30, 2017): [Spamnesty](https://spa.mnesty.com/) does exactly what this project explores. It looks awesome, plus it has been deployed and is doing some real good.

### Installation
The following dependencies are required:
- Python 3.5+
- tensorflow v1.0
- numpy
- CUDA (if you have an NVIDIA GPU you want to use)
- nltk
- tqdm

You'll need to run the following to download additional NLTK dependencies:
```
$ python3 -m nltk.downloader punkt
```

To talk with the trained model (trained on an NVIDIA Tesla K80 for ~15 hours), simply run:
```
$ python3 main.py --test interactive
```

That will result in something like this.

![I am cynthia bishop](https://puu.sh/uZkIL/609adf255f.png)



### License ([TL;DR](https://tldrlegal.com/license/mit-license))
The MIT License (MIT)

Copyright (c) 2017 Gautam Mittal

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
