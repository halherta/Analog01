# Lesson 02 - Basic Concepts

In this chapter the basic quantities and circuit elements used in
resistive circuits are introduced.

## Basic quantities

### Charge

The concept of electricity arises from an observation of nature. We
observe a force between objects, that, like gravity, acts at a distance.
The source of this force has been given the name charge. A very
noticeable thing about electric force is that it is large, far greater
than the force of gravity. Unlike gravity, however, there are two types
of electric charge; positive (protons) and negative (electrons).

Opposite types of charge attract, and like types of charge repel.
Gravity has only one type: it only attracts, never repels. The SI
derived symbol for charge is Q, and its SI unit is the **coulomb (C)**.

### Current

Current (I) is the rate of flow of charge.

$$i(t) = \frac{dq}{dt}$$

Current is reported as the number of charges per unit time passing
through a boundary. Visualize placing a boundary all the way through a
wire. Station yourself near the boundary and count the number of charges
passing by. Report how much charge passed through the boundary in one
second.

A positive charge will move from a positive terminal of a battery, to
its negative terminal (conventional flow). Whereas a negative charge
will move from a negative terminal of a battery, to its positive
terminal (electron flow). Current is measured in **Amperes (A)**.

### Voltage

Electric voltage is a **difference of potential** between two places
with different charges. Voltage provides the ability to move charges and
hence do a work, and therefore voltage is also sometimes called
electromotive force (EMF). The symbol for voltage is V or sometimes U,
and the SI measurement unit of is **volt (V)**. The SI definition is:

> \"The volt is the potential difference between two points of a
> conducting wire carrying a constant current of 1 ampere, when the
> power dissipated between these points is equal to 1 watt.\"

Voltage in an electric circuit is analogous to the product of the
acceleration due to gravity and the change of height. A ball at the top
of the hill rolls down. When it is halfway down, it has given up half of
its potential energy. An electron at the top of a voltage \"hill\"
travels \"downhill\" through wires and elements of a circuit. It gives
up its potential energy, doing work along the way. When the electron is
halfway down the hill, it has given up, or \"dropped\", half of its
potential energy.

<figure>
<img src="../../_static/images/basic_concepts/voltageanalogy.svg"
class="align-center" style="width:75.0%"
alt="../../_static/images/basic_concepts/voltageanalogy.svg" />
<figcaption>Voltage is analogous to gravity</figcaption>
</figure>

For both the ball and the electron, the trip down the hill happens
spontaneously. The ball and electron move towards a lower energy state
all by themselves. On the trip down, there can be things in the way of
the ball, like trees or bears to bounce off. For electrons, we can guide
electrons using wires and make them flow through electronic components
and do interesting things along the way.

### Power

Power (P) is defined as the rate energy E is transformed or transferred
over time. We measure power in units of joules/second, also known as
**watts (W)**.

$$P =\frac{dE}{dt}$$

An electric circuit is capable of transferring power. Current is the
rate of flow of charge, and voltage measures the energy transferred per
unit of charge. We can insert these definitions into the equation for
power:

$$P =\frac{dE}{dt}=\frac{dU}{dq}\cdot\frac{dq}{dt} = v(t) \cdot i(t)$$

Since in this course we are dealing with static DC circuits whose
quantities do not vary with time we can rewrite power as:

$$P = V \cdot I$$

Electrical power is the product of voltage times current. And is
measured in units of watts.

### Resistance and Conductance

Resistance (R) is a electrical quantity that indicates how much voltage
is necessary to create a certain amount of current in a component. The
relation among voltage, current and resistance is given by the Ohm\'s
law:

$$V = I \cdot R$$

Resistance is measured in **ohms (Ω)**. The SI definition of ohm is:

> \"The ohm is the electric resistance between two points of a conductor
> when a constant potential difference of 1 volt, applied to these
> points, produces in the conductor a current of 1 ampere, the conductor
> not being the seat of any electromotive force.\"

Conductance (G) is an measure of how conductive a material or object is.
Conductance is inversely proportional to resistance and its measurement
unit is **mhos (Ʊ) or siemens(S)**.

$$G = \frac{1}{R}$$

## Conventional flow vs Electrical flow

In 1752, prior to electricity being identified with the electron,
Benjamin Franklin chose a convention regarding the direction of current
flow. Franklin assumed that positive charge carriers flowed from
positive to negative terminals. We now know this is incorrect. In
metals, the charge carrier is the electron whose charge is negative by
definition (note negative sign): ($−1.6×10−19C$)

The flow of electrons is termed **electron current**. Electrons flow
from the negative terminal to the positive. Conventional current or
simply current, behaves as if positive charge carriers cause current
flow. Conventional current flows from the positive terminal to the
negative. Perhaps the clearest way to think about this is to pretend as
if movement of positive charge carriers constituted current flow.

<figure>
<img
src="../../_static/images/basic_concepts/conventionalvselectron.png"
class="align-center" style="width:50.0%"
alt="../../_static/images/basic_concepts/conventionalvselectron.png" />
<figcaption>Conventional flow vs Electron flow</figcaption>
</figure>

It is important to realize that the difference between conventional
current flow and electron flow in no way effects any real-world behavior
or computational results. In general, analyzing an electrical circuit
yields results that are independent of the assumed direction of current
flow. Conventional current flow is the standard that most follow,
despite it being strictly incorrect.

::: note
::: title
Note
:::

In this and all other courses in the program, conventional flow will be
strictly followed !!!
:::

## AC Current vs DC Current

<figure>
<img src="../../_static/images/basic_concepts/acdc.jpg"
class="align-center" style="width:90.0%"
alt="../../_static/images/basic_concepts/acdc.jpg" />
<figcaption>AC vs DC currents (Source: <a
href="https://i2.wp.com/www.freeingenergy.com/wp-content/uploads/2018/05/AC-vs-DC-1.jpg?w=680&amp;ssl=1">The
Freeing Energy Project</a>)</figcaption>
</figure>

Two types of current exist.

-   Alternating current (AC): This type of current is time varying, i.e.
    the current changes direction periodically. Currents and voltages in
    AC circuits typically vary with time in a sinusoidal fashion. AC
    current can be found in electrical grids. The current coming out of
    any electrical socket is AC. AC circuits will be covered in much
    more detail in Analog Circuits II.
-   Direct Current (DC): This type of current is static and non-time
    varying. This is the type of current that comes out of a DC power
    adapter or a battery. We will be primarily focused on DC based
    circuits in this course.
