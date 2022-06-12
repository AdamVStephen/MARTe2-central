# MARTe2 Cheat Sheet : Types

*A quick overview of data types and supported techniques for managing them.*

## References

1. [MARTe2_RealTimeApplicationsII.pdf](https://drive.google.com/file/d/1RZTB_YCU6zYuXkwyxIyaxofopUq3H_Gz/view)

## Overview

The essence of many software systems follows the ETL pattern (*Extract, Transform, Load*).
In the context of MARTe2, an application consists of several parallel data pipelines.
An equivalent concept in Matlab/Simulink is that model blocks are interconnected by
*buses* over which data flows.

In almost all cases, managing the complexity of the world comes down to packaging data
for both ease of conceptual management, to ensure egress/ingress compatibility, and
to optimise performance.

Loosely, a *type* is a digital data format which defines an encoding/decoding
for mapping values to and from memory.  From a low level point of view, this
encoding/decoding must be implemented.  The implementation may add details that
are uninteresting for the interface/semantic view.  From this high level
interface/semantic view, the importance of the encoding is the way in which
values are defined (governs representation ability), organised (describes
relationships between consituent parts) and named (implying semantics). 

MARTe2 supports the following conceptual aspects of *type* management.

## Fundamental Platform Types

## Core BaseLib Types

## User Defined Types

## Compile Time Types

## Run Time Defined Types

## Type Conversion

## Scatter/Gather Data Flow

## Composite / Elementwise Access

## Aliasing or Name Rebinding
