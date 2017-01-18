forsyde-haskell-demonstrators
===============================

Demonstrators implemented with the ForSyDe-Haskell Shallow modeling library. 

----

Installation and usage
----------------------
Most of the demos are intedended to be executed directly in `ghci`. 

Use `cabal` to compile the documentation:

	cabal configure
	cabal haddock --hyperlink-source
	

List of demos
-------------

#### 1. Synchronous MoC

  1. TrafficLight: Models a FSM for a traffic light controller.
  1. PitchControl: TODO 
  1. FibonacciRabbits: Models to Fibonacci rabbits reproduction system.
  1. FibonacciRabbitsDeath: Models the Fibonacci reproduction system considering rabbits death rate.
  1. RCFilter: Models a first order low pass RC filter.

#### 2. Untimed MoC

  1. AdaptiveAmp: Models an adaptive amplifier.
  1. Ascii2Bin: Models two processes to convert between ASCII characters and their binary representations.

#### 3. Synchronous DataFlow MoC
  
  No demos available at the moment.

#### 4. Continuous Time MoC

  No demos available at the moment.


#### 5. Heterogeneous Models
  
  These are demos that show how to use more than one MoC to model a system.

  1. ASKTransceiver: TODO
