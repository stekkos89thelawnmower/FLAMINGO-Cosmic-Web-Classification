# FLAMINGO-Cosmic-Web-Classification
Cosmic-web classification (V-web/T-web) and environment decomposition of Buchert's kinematical backreaction QD in FLAMINGO simulations.

QD Cosmic-Web Classification in FLAMINGO

Overview

This repository contains the analysis pipeline used to classify the FLAMINGO simulation volume into cosmic-web environments (Void, Sheet, Filament, Knot) and study the decomposition of Buchert's kinematical backreaction term \(Q_D\).

The project investigates:

validation of the IDW velocity-field reconstruction method;

testing of local velocity-gradient estimators;

V-web classification based on the velocity shear tensor;

independent T-web validation;

exact environment decomposition of \(Q_D\);

differential comparison between FLAMINGO Fiducial and NoCooling runs.


Main Results

Local gradient estimation at tracer positions introduces a systematic physical bias and is not adopted.

The IDW pipeline remains the reference reconstruction method.

V-web and T-web classifications show significant agreement.

An exact decomposition identity


\[Q_D = \sum_i f_i Q_{D,i} + Q_{inter}\]

is verified to machine precision.

Environment-dependent signals detected at z=1 are not reproducible at later epochs.


Repository Contents

notebooks/

figures/

tables/

report/

data_products/


Reference

Boi, S. (2026). Cosmic-Web Environment Classification for Kinematical Backreaction (Q_D) Estimation in FLAMINGO. 
