SDSS M Dwarf Template Spectra from [Bochanski et al. (2007)](http://adsabs.harvard.edu/abs/2007AJ....133..531B)
==============



The templates are listed as follows:

type.activity.lines.fits

The type variable runs from M0 - L0, one for each spectral subclass.

The activity variable is either active (for active stars), nactive
(for inactive stars) or all (for the combined dataset).

The lines variable describes the lines measured for the RV determinations.
This will either be Halpha, Na and K (for active stars) or just Na and K
(for inactive stars or the combined templates).

The highest quality data will be the combined (or 'all' template set).



The header for each template is as follows:

    SIMPLE  =                    T / Written by IDL:  Thu Sep  7 11:50:33 2006
    WAT1_001= 'wtype=linear label=Wavelength units=angstroms' /
    CTYPE1  = 'LINEAR  '           /
    CRVAL1  =              3825.00 /
    CRPIX1  =              1.00000 /
    CD1_1   =             0.100000 /
    DC-FLAG =              0.00000 /
    VHELIO  =              0.00000 /
    DATE-OBS= '1993-03-17T04:56:38.0' /
    RA      = '12:00:00'           /
    DEC     = '12:00:00'           /
    EPOCH   =              1993.00 /
    OBSERVAT= 'KPNO    '           /
    NUMOFFIL=                   67 /
    NAXIS   =                    2 /
    NAXIS1  =                53750 /Number of positions along axis 1
    NAXIS2  =                    4 /Number of positions along axis 2
    SIMPLE  =                    T /
    BITPIX  =                  -64 / IEEE double precision floating point
    END

Most of the information is to ensure IRAF does not introduce a heliocentric
velocity correction for cross-correllation RV work.  The one flag of interest
would be `NUMOFFIL`, which is the number of SDSS spectra that went into a given
template spectrum.

There are 4 fits extensions of each template.  They are:<br>
1 - Mean Normalized Coadded Flux<br>
2 - Median Normalized Coadded Flux<br>
3 - Coadded Signal to Noise<br>
4 - Standard Deviation of Individual Spectra




I've tarred up the active, inactive and combined sets, as well as all three
for easy downloading.


If you have any questions, please feel free to contact me at bochanski@gmail.com

**For the new SDSS L dwarf Templates, see Sarah Schmidt's repository [here](https://github.com/adleorocks/SDSS-L-dwarf-templates)**
