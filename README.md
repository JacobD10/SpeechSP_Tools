# Sound Zone Tools
Sound Zone Tools is a collection of auxiliary MATLAB tools for soundfield reproduction and other signal processing tasks. The tools have been written by myself or collected from other open sources. If a file is missing and there is no download link in the parent file's header, please open an issue to request the link.

Don't forget to give appropriate reference to the code used, author details are usually found in the file's header.
Enjoy!
[![license](https://img.shields.io/github/license/JacobD10/SoundZone_Tools.svg?style=flat-square)](https://github.com/JacobD10/SoundZone_Tools/blob/master/LICENSE)

File name | Description
:--------:|------------
_addNoise.m_ | Adds a given level and type of noise to a signal
_ALcons2STI.m_ | Converts Articulation Loss of Consonants (ALcons) to the Speech Transmission Index (STI)
_ArbitraryOctaveFilt.m_ | Filters a signal with any arbitrary spectrum smoothed with any fractional octave band average
_buildDocumentation.m_ | Generates documentation HTML and builds MATLAB search database for dependencies of a main file
_buildReleaseZIP.m_ | Creates a ZIP file of all release dependencies for a main file
_ConcatTIMITtalkers.m_ | Concatenates all the talkers from the TIMIT corpus into individual speech files 
_confidence_intervals.m_ | Find the confidence intervals for a set of data for use with the errorbar function in MATLAB
_Correlated_Normalisation.m_ | Matches the amplitude of X using cross-correlation
_COSHdist.m_ | Finds the symmetric Itakura-Saito distance using the hyperbolic cosine function
_Dropbox.m_ | Function to start and kill dropbox from MATLAB
_estoi.m_ | Implementation of the Extended Short-Time Objective Intelligibility (ESTOI) predictor
_extractIR.m_ | Extract impulse response from swept-sine response.
_fconv.m_ | Fast Parallelised Convolution
_fdeconv.m_ | Fast Parallelised Deconvolution
_generateNoise.m_ | Generates basic noise at a given level with the option to be additive
_getAllFiles.m_ | Retrieves a list of all files within a directory
_interpFromVal_2D.m_ | This function will interpolate from desired z-axis values and return the interpolation indices for them in the y-axis
_interpVal.m_ | This function will interpolate from desired arbitrarily spaced index values
_interpVal_2D.m_ | This function will interpolate from desired abitrarily spaced index values in a 2D array
_invFIR.m_ | Design inverse filter (FIR) from mono or stereo impulse response
_invimplms.m_ | Inverse impulse using the Levinson-Durbin algorithm
_invSweepFFT.m_ | Obtain the FFT of an inverted exponentional sine sweep
_IRcompactingKirkebyFilter.m_ | Compacting Kirkeby Filter
_keepFilesFromFolder.m_ | Keeps files and file paths in a cell array if the file names in a given folder are found in the path string
_LTASS.m_ | Computes the Long-Term Average Speech Spectrum from a folder of speech files or vector of speech samples
_MiKTeX_FNDB_Refresh.m_ | Function to refresh the File Name DataBase in MiKTeX
_octaveBandMean.m_ | Given a magnitude spectrum this function will calculate the average (single, third, nth) octave band magnitude
_pesq2.m_ | Objective speech quality measure
_pesq3.m_ | A wrapper for the objective Perceptual Evaluation of Speech Quality measure
_pesq_mex_vec.m_ | Accepts vectors for a mex compiled version of the objective Perceptual Evaluation of Speech Quality measure
_printHyperlink.m_ | Prints a hyperlink to the command window
_shapeSpectrum.m_ | This function will shape an input signal to the given spectrum (simple, unregulated spectral shaping)
_showTimeToCompletion.m_ | Prints the time to completion and expected finish of a looped simulation based on linear extrapolation.
_simpleWarning.m_ | Prints a coloured warning without the location information
_sineSweepLin.m_ | Synthesize a linear sine sweep
_STI.m_ | Calculation of the Speech Transmission Index (STI)
_STI_BandFilters.m_ | Calculation of the Speech Transmission Index (STI) Band Filters
_stoi.m_ | The Short-Time Objective Intelligibility measure 
_stoi_d2percCorr.m_ | Converts the stoi measure, d, to percent words correct unit
_synthSweep.m_ | Synthesize a logarithmic sine sweep
_wait_for_file.m_ | A forceful method to wait for a file to finish being written to
