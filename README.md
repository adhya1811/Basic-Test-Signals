# Basic-Test-Signals 
## Aim
To generate continuous and discrete waveforms for the following :
1. unit impulse signal
2. unit step signal
3. ramp signal
4. sine signal
5. cosine wave
6. bipolar pulse signal
7. unipolar pulse signal
8. triangular signal
9. exponential signal
## Theory
A digital signal can be either a deterministic signal that can be predicted with certainity, or a
random signal that is unpredictable. Due to ease in signal generation and need for predictability,
deterministic signal can be used for system simulation studies. A continuous time signal is
defined for all values of time t.
1. Unit impulse signal:
The simplest signal is the unit impulse signal which is defined as,
δ(t) =∞;𝒕=𝟎
 =𝟎;𝒕 ≠�
2. Unit step signal:
A signal that is zero for all negative time values and one for positive time values.It is
defined as,
u (t) = 1 for t ≥ 0
 = 0 for t< 0
3. Ramp signal:
A signal that increases linearly with time. This signal is given by,
r (n) = n for n ≥ 0
 = 0 for n < 0
4. Sine signal :
A continuous periodic signal. It oscillates smoothly between -1 and 1.It is defined as,
y(t)=Asin(2πft)
5. Cosine wave :
A continuous periodic signal like the sine wave but phase-shifted by π\2.It is defined
as,
y(t)=Acos(2πft)
6. Bipolar pulse signal :
A pulse signal that alternates between positive and negative values, usually rectangular
in shape. It switches between two constant levels (e.g., -1 and 1) for a defined duration.It
is given by,
 p(t) = A for |t| ≤ τ/2,
 = 0 otherwise
7. Unipolar pulse signal:
A pulse signal that alternates between zero and a positive value. It remains at zero for
a specified duration and then jumps to a positive constant level (e.g., 0 and 1). It is given
by,
p(t) = A for |t| ≤ τ/2,
 = 0 otherwise (assuming A is positive)
8. Triangular signal :
A periodic signal that forms a triangle shape, linearly increasing and decreasing with
time, typically between a positive and negative peak. It is given by,
Λ(t) = 1 - |t| for |t| ≤ 1,
 = 0 otherwise
9. Exponential signal:
A signal that increases or decreases exponentially with time. The rate of growth or
decay is determined by the constant a . It’s general form is,
x (n) = an
for all n.
