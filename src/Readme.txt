!*** Copyright Notice ***
!
!"IMPACT-T" Copyright (c) 2016, The Regents of the University of California,
!through Lawrence Berkeley National Laboratory (subject to receipt of any
!required approvals from the U.S. Dept. of Energy).  All rights reserved.
!
!If you have questions about your rights to use or distribute this software,
!please contact Berkeley Lab's Innovation & Partnerships Office at IPO@lbl.gov.
!
!NOTICE.  This Software was developed under funding from the U.S. Department of
!Energy and the U.S. Government consequently retains certain rights. As such,
!the U.S. Government has been granted for itself and others acting on its behalf
!a paid-up, nonexclusive, irrevocable, worldwide license in the Software to reproduce,
!distribute copies to the public, prepare derivative works, and perform publicly
!and display publicly, and to permit other to do so.
!
!****************************
!V2.0
!
Note: 
1) The current version of the code is for serial single processor computer
with Fortran90 compiler.
To run the code on a parallel computer with MPI, the user has to
specify the flag "-DUSE_MPI=ON" when invoking cmake.
2) The phaseOpt.py is used to find the driven phase of a RF cavity with initial 
design phase. This code needs to be modified for each input ImpactT.in file
in order to use it correctly.
3)The subroutines in FFT.f90: realft, four1, and sinft,
can be replaced with functions from the Numerical Recipe or some 
equavilent 1D FFT functions.
