# Learning-Option-Pricing

Welcome to the **Learning Option Pricing** repository! This repository is dedicated to providing you with a comprehensive collection of code and resources to help you understand and implement option pricing models. Whether you're new to options or looking to deepen your knowledge, this repository has something for everyone.

## Table of Contents

- [Introduction](#introduction)
- [Option Basics](#option-basics)
- [Implemented Models](#implemented-models)
- [Usage](#usage)
- [Contributing](#contributing)
- [Resources](#resources)

## Introduction

Understanding option pricing is crucial in the world of finance and investing. Options are derivatives that give you the right, but not the obligation, to buy or sell an underlying asset at a predetermined price within a specified timeframe. Option pricing models help estimate the fair value of these options, enabling investors to make informed decisions.

This repository aims to provide a practical and hands-on approach to learning option pricing. It contains code implementations of various option pricing models, along with explanations and resources to help you grasp the underlying concepts.

## Option Basics

If you're new to options, it's essential to understand the basic terminology and concepts. Here are a few key terms:

- **Call Option:** This gives the holder the right to buy the underlying asset at a specified price before the expiration date.
- **Put Option:** This gives the holder the right to sell the underlying asset at a specified price before the expiration date.
- **Strike Price (Exercise Price):** The price at which the underlying asset can be bought or sold when exercising an option.
- **Expiration Date:** The date when the option contract expires and becomes invalid.
- **Premium:** The price paid for the option.

## Implemented Models

In this repository, you'll find implementations of various option pricing models, including but not limited to:

- [Black-Scholes Model](tutorial_notebooks/Black-Scholes-Analysis.ipynb)
- [Binomial Model](tutorial_notebooks/Black-Scholes-Analysis.ipynb)
- [Monte Carlo Simulation](tutorial_notebooks/MonteCarlo.ipynb)

and some implementations of stochastic processes that I borrowed from QuantGirl:

 - [Brownian Motion](tutorial_notebooks/QuantGirl/brownian_motion.ipynb)
 - [Geometric Brownian Motion](tutorial_notebooks/QuantGirl/geometric_brownian_motion.ipynb)
 - [Vasicek Process](tutorial_notebooks/QuantGirl/vasicek.ipynb)
 - [CIR Process](tutorial_notebooks/QuantGirl/cir_process.ipynb)

Each model comes with its own set of code files, along with explanations of how the model works and how to use the code effectively.

## Usage

To make the most of this repository, follow these steps:

1. **Clone the Repository:** Start by cloning this repository to your local machine using the `git clone` command.

2. **Explore the Models:** Browse through the directories for the specific option pricing models you're interested in. Each directory contains the necessary code files and a README explaining the model's theory.

3. **Run the Code:** Open the code files using your preferred programming environment. Install the dependencies in [requirements.txt](requirements.txt)

4. **Experiment and Learn:** Tweak the parameters, try different scenarios, and observe how changing inputs affects option prices. This hands-on experimentation will deepen your understanding.

## Contributing

Contributions to this repository are welcome! If you've implemented an additional option pricing model, optimized existing code, or have insightful explanations to add, feel free to create a pull request. Make sure to follow the repository's guidelines for contributing.

## Resources

Check out these additional resources to enhance your understanding of option pricing:

### Recommended Books
- **The Concepts and Practice of Mathematical Finance** by Mark S. Joshi ([Amazon link](https://www.amazon.in/Concepts-Practice-Mathematical-Finance-Mathematics/dp/0521514088))
- **An Elementary Introduction to Mathematical Finance** by Sheldon M. Ross ([Amazon link](https://www.amazon.in/Elementary-Introduction-Mathematical-Finance/dp/0521192536))
- **Quantitative Finance For Dummies** by Steve Bell ([Amazon link](https://www.amazon.in/Quantitative-Finance-Dummies-Steve-Bell/dp/1118769465))

### Online Tutorials and Courses
- [QuantGirl](https://quantgirl.blog/)
- [Investopedia](https://www.investopedia.com/)

Please note that while this repository provides code implementations, it's important to have a solid grasp of the underlying mathematical concepts for effective utilization.

Start exploring the fascinating world of option pricing and take your knowledge of finance to the next level. Happy coding!

*Disclaimer: This repository is for educational purposes only and does not provide financial advice. Always do your own research before making any investment decisions.*
