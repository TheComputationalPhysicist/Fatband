# Fatband
This repository provides all the necessary files, scripts, and instructions for generating fatbands with orbital and sub-orbital contributions in the SIESTA code. These resources will help you visualize orbital contributions in band structures efficiently, with automated plotting scripts.
Bash Scripts for streamlined fatband generation:
e_ef.sh: Adjusts Fermi energy.
eps_jpg.sh: Converts EPS files to JPEG.
fatband.sh: Main script for running fatband plotting.
fatband.in: Configuration file for orbital-specific plotting.
Utilities & Executables:
COOP/fat, COOP/mprop, Bands/eigfat2plot, Bands/gnubands
Setup Instructions:
Commands to install necessary libraries (Gnuplot, Python 3.0)
Setup for copying scripts and executables to /usr/local/bin
Sample input.fdf tags for enabling COOP and orbital analysis
How to Use:
Install Required Libraries: Ensure Gnuplot and Python 3.0 are installed.
Run the Setup: Copy all executable files and scripts to /usr/local/bin and set execute permissions.
Edit fatband.in: Customize for specific orbital and sub-orbital contributions.
Execute fatband.sh: Run the main script to automatically generate fatband plots.
Contact & Support:
If you have any questions or need specific files, feel free to reach out at himalaykolavada642@gmail.com.

Related Videos:
SIESTA Installation with Parallel Processing (https://youtu.be/Zq3Y4RjPqp8)
Band Structure, DOS, and PDOS Plotting in Xmgrace (https://youtu.be/gghbO03kWCQ)
