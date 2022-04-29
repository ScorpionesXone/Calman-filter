
J/A+A/469/807       Catalogue of Galactic low-mass X-ray binaries  (Liu+, 2007)
================================================================================
Catalogue of low-mass X-ray binaries in the Galaxy (4th edition).
    Liu Q.Z., van Paradijs J., van den Heuvel E.P.J.
   
   =2007A&A...469..807L
================================================================================
ADC_Keywords: Binaries, X-ray ; Photometry, UBV ; Cross identifications

Keywords: stars: low-mass star - stars: X-ray - stars: binaries - catalogue


Abstract:
    We present a new edition of the catalogue of the low-mass X-ray
    binaries in the Galaxy and the Magellanic Clouds. The catalogue
    contains source name(s), coordinates, finding chart, X-ray luminosity,
    system parameters, and stellar parameters of the components and other
    characteristic properties of 187 low-mass X-ray binaries, together
    with a comprehensive selection of the relevant literature. The aim of
    this catalogue is to provide the reader with some basic information on
    the X-ray sources and their counterparts in other wavelength ranges
    ({gamma}-rays, UV, optical, IR, and radio). Some sources, however, are
    only tentatively identifed as low-mass X-ray binaries on the basis of
    their X-ray properties similar to the known low-mass X-ray binaries.
    Further identification in other wavelength bands is needed to finally
    determine the nature of these sources. In cases where there is some
    doubt about the low-mass nature of the X-ray binary this is mentioned.
    Literature published before 1 October 2006 has, as far as possible,
    been taken into account.

File Summary:
--------------------------------------------------------------------------------
 FileName      Lrecl  Records   Explanations
--------------------------------------------------------------------------------
ReadMe            80        .   This file
lmxb.dat         287      187   LMXB catalogue
lmxbnote.dat      80     1160   Individual notes
refs.dat         140     1782   References
--------------------------------------------------------------------------------

See also:
        B/cb : Cataclysmic Binaries, LMXBs, and related objects (Ritter+, 2007)
        : Catalogue of X-ray binaries (Liu+ 2001)
  : High-mass X-ray binaries in the Magellanic Clouds (Liu+, 2005)
  : Catalogue of Galactic high-mass X-ray binaries (Liu+, 2006)


Byte-by-byte Description of file:lmxb.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1- 24  A24   ---     Name      Source name
  26- 42  A17   ---     Type      [ABDEGMPRTUZ ?,()] X-ray type (1)
  44- 45  I2    h       RAh       Right ascension (J2000)
  47- 48  I2    min     RAm       Right ascension (J2000)
  50- 55  F6.3  s       RAs       Right ascension (J2000)
      57  A1    ---     DE-       Declination sign (J2000)
  58- 59  I2    deg     DEd       Declination (J2000)
  61- 62  I2    arcmin  DEm       Declination (J2000)
  64- 68  F5.2  arcsec  DEs       ? Declination (J2000)
  70- 75  F6.2  deg     GLON      Galactic longitude
      76  A1    ---     ---       [,]
  78- 84  F7.3  deg     GLAT      Galactic latitude
  87- 88  A2    ---     Pos       Type of observation from which the source
                                   position has been derived (2)
  91-100  A10   ---     Opt       Optical counterpart
     102  A1    ---     ---       ([)
 103-117  A15   ---     r_Opt     Reference for Optical counterpart
                                  (finding charts)
     118  A1    ---     ---       (])
 120-124  F5.2  mag     Vmag      ? V magnitude
     125  A1    ---     ---       [-]
 126-130  F5.2  mag     Vmag2     ? Lower value of V magnitude when interval
     131  A1    ---     n_Vmag    [*] Individual note on photometry, see notes
 132-136  F5.2  mag     B-V       ? B-V colour index
     137  A1    ---     u_B-V     Uncertainty flag on B-V
 139-143  F5.2  mag     U-B       ? U-B colour index
     145  A1    ---     l_E(B-V)  [~>< ] Limit flag on E(B-V)
 146-151  F6.3  mag     E(B-V)    ? Interstellar redenning
     152  A1    ---     u_E(B-V)  Uncertainty flag on E(B-V)
     153  A1    ---     ---       [-]
 154-157  F4.2  mag     E(B-V)2   ? Lower value of interstellar redenning
                                    when interval
     159  A1    ---     ---       ([)
 160-174  A15   ---     r_Vmag    Reference for UBV photometry
     175  A1    ---     ---       (])
     177  A1    ---     l_FX      Limit flag on FX
 178-185  F8.2  uJy     FX        ? Maximun X-ray flux in (2-10keV) unless
                                    otherwise indicated in Range
     186  A1    ---     ---       [-]
 187-191  I5    uJy     FX2       ? Upper value of X-ray flux when interval
 193-205  A13   ---     Range     Energy range for X-ray flux if not (2-10keV)
     207  A1    ---     ---       ([)
 208-217  A10   ---     r_FX      Reference for X-ray flux
     218  A1    ---     ---       (])
 220-230  F11.6 h       Porb      ? Orbital period
     231  A1    ---     u_Porb    [:?] Uncertainty flag on Porb
     232  A1    ---     x_Porb    [d] d when Period in days
 234-240  F7.5  s       Ppulse    ? Pulsational period
     242  A1    ---     ---       ([)
 243-252  A10   ---     r_Porb    Reference for orbital and/or pulse period
     253  A1    ---     ---       (])
 255-276  A22   ---     Name2     Other name
 278-287  A10   ---     Name3     Other name
--------------------------------------------------------------------------------
Note (1): Type of sources as follows:
      A = known atoll source
      B = X-ray burst source
      D = "dipping" low-mass X-ray binary
      E = eclipsing or partially eclipsing low-mass X-ray binary
      G = globular cluster X-ray source
      M = micropulsar
      P = X-ray pulsar
      R = radio loud X-ray binary
      T = transient X-ray source
      U = ultrasoft X-ray spectrum
      Z = Z-type source
Note (2): Type of observation is
      o = optical ; x = X-ray ; r = radio ; IR = infrared
--------------------------------------------------------------------------------

Byte-by-byte Description of file:lmxbnote.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1- 24  A24   ---     Name      Source Name
  26- 80  A55   ---     Note      Text of the note (1)
--------------------------------------------------------------------------------
Note (1): Abbreviations used:
          o = optical; x = X-ray; r = radio; IR = infrared.
     A reference on the source position is given under 'pos.'.
--------------------------------------------------------------------------------

Byte-by-byte Description of file:refs.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1-  4  I4    ---     Ref       Reference number
   6- 24  A19   ---     BibCode   BibCode
  26- 61  A36   ---     Aut       Author's name
  63-140  A78   ---     Com       Comments
--------------------------------------------------------------------------------

Acknowledgements:
    Q.Z. Liu, qzliu(at)pmo.ac.cn
================================================================================
(End)                                      Patricia Vannier [CDS]    22-Jun-2007
