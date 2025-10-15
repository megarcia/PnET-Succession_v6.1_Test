## PnET-Succession_v6.1_Test

Test suite for use with Landis-II PnET-Succession v6.1 as modified by Matthew Garcia up to October 14, 2025.

There is one single-cell test available thus far.

The test uses Landis-II v8 (Landis Core v3.0.1) with:
- PnET-Cohort Library v3 
- PnET-Succession Extension v6.1
- PnET-Biomass-Output Extension

A Dockerfile is included to build Landis-II with these specific libraries and extensions on Linux.

Additional unmodified Landis-II components are used via pre-compiled DLLs:
- Climate Library v5
- Succession Library v9
- Initial Community Library v1.1
- Universal Cohorts Library v1
- Metadata Library v2
- Parameters Library v2

Additional notes and instructions for running the test are in README.txt.
