# starbucks_capstone

### Table of Contents

1. [Installation](#installation)
2. [Project Overview](#motivation)
3. [Project Aim](#aim)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

- Anaconda needed
- Python v3.* needed
- libraries numpy, pandas, seaborn, matplotlib needed

## Project Overview <a name="motivation"></a>

This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. Not all users receive the same offer, and that is the challenge to solve with this data set. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products. Every offer has a validity period before the offer expires. As an example, a BOGO offer might be valid for only 5 days. You'll see in the data set that informational offers have a validity period even though these ads are merely providing information about a product; for example, if an informational offer has 7 days of validity, you can assume the customer is feeling the influence of the offer for 7 days after receiving the advertisement.

## Project Aim <a name="aim"></a>

The aim is to combine transactional, demographic and offer data to determine which demographic groups respond best to which type of offer. Heuristics should be developed to indicate which offer is best sent to a customer.


## File Descriptions <a name="files"></a>

- 1 notebook
- 1 Readme file
- 1 data folder containing:
  - portfolio.json (describes the offer types)
  - profile.json (describes the demographic data on customers)
  - transcript.json (describes the transactions)

## Results<a name="results"></a>

I have written an article containig the [main results](https://medium.com/@martin.senser/starbucks-capstone-the-best-offer-for-every-customer-b4e1711a91d8).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
